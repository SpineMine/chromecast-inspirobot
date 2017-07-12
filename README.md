# chromecast-inspirobot
Calls inspirobot every 20 seconds.  Nice background for your chromecast.

## Usage

Just open main.html with Chrome.

Click the cast button.

Choose your chromecast device.

## Change update time

To change the update time, change the 20000 in this line to the number of milliseconds between refreshes.

`setInterval(load_new_inspiration, 20000);`

Eg. if you want it to refresh every 60seconds

`setInterval(load_new_inspiration, 60000);`
