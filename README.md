Heartmonitor
============

A remote source that has a json file with heartrate data is read, and charted in a graph

Create a file called `remoteurl.js` in that file there should be the following line:

	var remoteurl = "https://api.spark.io/v1/devices/YOUR_DEVICE_ID_HERE/beatBuffer?access_token=YOUR_ACCESS_TOKEN_HERE"

where the the values YOUR_DEVICE_ID_HERE and YOUR_ACCESS_TOKEN_HERE should be replaced with your custom urls

This heartrate monitor script is a small project that was built as a demo at the "Social Support TAT: Theory, Applications, and Technology workshop" from 16 Mar 2015 through 20 Mar 2015.
(http://www.lorentzcenter.nl/lc/web/2015/688/info.php3?wsid=688&venue=Oort)

The script will monitor the heartrate on the [wristband heartrate monitors](http://shebsheb-experiments.de/2014/10/prototype-3-wristband-with-heart-rate-feedback/) built by Bernd Dudzik.

It is built with the following tools:
- [Foundation](http://foundation.zurb.com) for a quick layout
- [jQuery](http://www.jquery.com) for the javascript to tie it all together
- [Smoothie charts](http://smoothiecharts.org) for the charting

Licence
=======
Smoothie charts is licenced with MIT licence 
[Smoothie MIT licence](http://smoothiecharts.org/LICENSE.txt)

Foundation is licenced with MIT licence 
[Foundation MIT licence](https://github.com/zurb/foundation/blob/master/LICENSE)

The Heartrate monitor is MIT licenced 
[Licence](https://github.com/jadwigo/heartratemonitor/blob/master/LICENSE)


