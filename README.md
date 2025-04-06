# Bolt_OBC
Reverse Engineering of Chevrolet Bolt On Board Charger

This project seeks to document and develop methods of controlling the Chevrolet Bolt OBC for EV conversion projects.

At this time, control via 100Hz PWM is established.

Development thread on Open Inverter here: https://openinverter.org/forum/viewtopic.php?t=5484

the control pinout is:
1 - blank
2 - Ground/12V-
3 - DC Voltage Sense (PWM out from charger)
4 - Charging Control (PWM into charger)
5-8 - blank
9 - 12V+
10 - AC Voltage Sense (PWM out from charger)
11 - Enable (12V+)
12 - blank


Battery connection: TE 4-2103177-4
AC connection: Aptiv 35197127
Control connection: Same as Volt Gen 2, Molex MX150 33472-1201
