# android-notifier
Automatically exported from code.google.com/p/android-notifier

<p>This project sends notifications to a desktop computer when certain events happen on an Android device, such as the phone ringing, an SMS being received, or the battery running low. The notifications can be sent over Wifi, Bluetooth, or (in the future) USB. </p><p>It runs as a service on android, consuming little resources while no events are happening, and the desktop application notifies the user about the event in some way (Growl on Mac, Gnome dbus notifications on Linux, Growl for Windows or System tray alert on Windows), including information such as the number that&#x27;s calling. </p><p>This is useful for people (like the developer) who wear noise-cancelling headphones, keep their cell phone in their bags, or don&#x27;t want to be interrupted to look at a vibrating cell phone in a meeting. </p><p>There are currently two different desktop applications - one called MacDroidNotifier for MacOS X, and another called android-notifier-desktop/MultiDroidNotifier which works on all operating systems. The former is in the process of being deprecated, so please download the later. </p><p>Please see the wiki for detailed setup instructions. </p><p>You can find the app on the android market easily by scanning this QR code: </p><p><img src="http://chart.apis.google.com/chart?cht=qr&amp;chs=350x350&amp;chl=market%3A%2F%2Fsearch%3Fq%3Dpname%3Aorg.damazio.notifier&amp;nonsense=something_that_ends_with.png" /> </p>