# elly-cam
Elly is a demon, and sometimes needs monitored if left home alone. Elly cam is a house-camera streaming service designed specifically around monitoring Elly.

My plan is to have multiple Raspberry Pis with cameras attached to them staged around the house. The Raspberry Pis will all be connected to the web server, which will also serve up a front end that can be accessed from any phone or computer. That front end will be locked behind username-and-password authentication, and gives the user a place to turn on and off the Elly cam, as well as watching the Elly cam. When the user turns on the Elly cam, the Raspberry Pis receive a signal to turn their webcams on and start streaming.
