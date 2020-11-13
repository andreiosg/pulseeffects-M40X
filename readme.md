# Contents

Custom equalizer preference settings for the Audio Technica M40X headphones along with the daemon.conf, default.pa config files for Pulseeffects.

Custom equalizer settings which I find comfortable listening to are based on u/oratory1990's Harmann equalizer settings with slight deviations based on personal preference relative to the Harmann curve; lowered bass, thicker low mids, shouty upper mid frequencies and lower high frequencies.
Credit to u/oratory1990 for graphing the custom EQ settings.

Pulseeffects config files present:
- `/etc/pulse/default.pa`  
- `/etc/pulse/daemon.conf`  

# In app changes
Additionally a `niceness` level of -15 was set, along with disabled input and output processing.

The pulseeffects daemon was enabled.



