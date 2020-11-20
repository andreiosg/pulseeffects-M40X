# Contents

Custom equalizer preference settings for the Audio Technica M40X headphones along with the daemon.conf, default.pa config files for Pulseeffects.

Custom equalizer settings which I find comfortable listening to are based on u/oratory1990's Harman equalizer settings with slight deviations based on personal preference relative to the Harman curve; lowered bass, thicker low mids, shouty upper mid frequencies and lower high frequencies.

Credit to u/oratory1990 for graphing the custom EQ settings.

Pulseeffects config files present:
- `/etc/pulse/default.pa`  
- `/etc/pulse/daemon.conf`  

# Pulseeffects <-> oratory1990 - naming differences
- Peak filter type = Bell
- Gain = slider (no input mode)
- Q-factor = Quality
- Preamp gain = Input 

# In app changes
Additionally a `niceness` level of -15 was set, along with disabled input and output processing.

Output: 
- Block size = 4096
- Latency = 4096 us
- Buffer = 300000 us

The pulseeffects daemon was enabled.

# Sound card
Due to my laptop's internal sound card issues the external *DELOCK, Sound Box 7.1* was used.




