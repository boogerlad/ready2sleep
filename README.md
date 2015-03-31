timer and service go in `/etc/systemd/system`
the shell script goes in `/usr/local/bin`
`systemctl enable ready2sleep.timer`

you can change the frequency of polling by modifying the timer.
1st parameter * frequency = how long cpu should be idle before sleeping
ditto for 2nd and 3rd parameter
all conditions must be met before sleeping.




todo: change mouse pointer diff to screenshot diff.
