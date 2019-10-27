
[![Build Status](https://travis-ci.com/TralahM/UberClone.svg?branch=master)](https://travis-ci.com/TralahM/UberClone)
[![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](https://opensource.org/licenses/MIT)
[![Organization](https://img.shields.io/badge/Org-TralahTek-blue.svg)](https://github.com/TralahTek)
[![made-with-java](https://img.shields.io/badge/Made%20with-JAVA-1f425f.svg)](https://www.java.com/)
[![HitCount](http://hits.dwyl.io/TralahM/UberClone.svg)](http://dwyl.io/TralahM/UberClone)
[![Inline Docs](http://inch-ci.org/github/TralahM/UberClone.svg?branch=master)](http://inch-ci.org/github/TralahM/UberClone)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/TralahM/pull/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/Naereen/StrapDown.js.svg)](https://gitHub.com/TralahM/UberClone/pull/)
[![GitHub version](https://badge.fury.io/gh/Naereen%2FStrapDown.js.svg)](https://github.com/TralahM/UberClone).

# UberClone.


[![TralahM](https://img.shields.io/badge/Architect-TralahM-blue.svg?style=for-the-badge)](https://github.com/TralahM)
[![TralahM](https://img.shields.io/badge/Maintainer-TralahM-green.svg?style=for-the-badge)](https://github.com/TralahM)

# Uber_android_app_clone

▷ Create an android app like uber
### Setup and Installation

```Bash
git clone https://github.com/TralahM/UberClone.git
cd UberClone
```


**▷ Download the app with the uber design here**: https://www.TralahM.com/product/uber-redesign/ <br />

▷ Full Video Tutorial Playlist here: https://www.youtube.com/playlist?list=PLxabZQCAe5fgXx8cn2iKOtt0VFJrf5bOd <br />
▷ Lesson on how to import this project here: https://www.youtube.com/watch?v=2TkNZ-Vael4 <br />
▷ Uber Functions for payouts and payments: https://github.com/TralahMYoutube/uberFirebaseFunctions

▷ Become a Patreon: https://www.patreon.com/TralahM<br />
▷ Donate with PayPal: https://www.paypal.me/TralahM<br />
▷ Twitter: https://twitter.com/TralahM<br />
▷ GitHub : https://github.com/TralahM<br />

▷ If you have any question please ask, I'll try to answer to every question and even look at your code if that is necessary.


**Important Links**

Project Download: https://goo.gl/imccvo<br />
FIrebase: https://goo.gl/9Wahb1<br />
geofire: https://goo.gl/SYXc2b<br />
Glide: https://github.com/bumptech/glide<br />
Place Autocomplete: https://developers.google.com/places/android-api/autocomplete<br />
Google-Directions-Android: :https://github.com/jd-alexander/google-directions-android<br />

P.S: If ou're going to download the full project please use your own firebase API, the one in the project will NOT be mantained and the app may not work.


# Implementation Guide
**1 - Project**
1 - Open the Project in your android studio;
2 - !!!!IMPORTANT!!!! Change the Package Name. You can check how to do that here (https://stackoverflow.com/questions/16804093/android-studio-rename-package)


**2 - Firebase Panel**
1 - Create Firebase Project (https://console.firebase.google.com/);
2 - import the file google-service.json into your project as the instructions say;
3 - Change Pay Plan to either Flame or Blaze;
4 - Go to Firebase -> Registration and activate Login/Registrtion with email
5 - Go to Firebase -> storage and activate it;

**3 - google maps**
1 - Add your project to the google API console (https://console.cloud.google.com/apis?pli=1)
2 - Activate google Maps API
3 - Activate google Places API
4 - Add google maps API key to the res/values/Strings.xml file in the string google_maps_key

**4 - PayPal**
1 - Install Node.js. Check my video to see how it is done (https://www.youtube.com/watch?v=nLxH15a4-6g&list=PLxabZQCAe5fgXx8cn2iKOtt0VFJrf5bOd&index=42);
2 - go to paypal developer and create an app;
3 - enable payouts in the app you've just created;
4 - Add the paypal credentials to the node.js project. Again follow the youtube video to see how it is done;
5 - Set the fee in your index.js file to the percentage that you want
6 - deploy the project;
7 - Go to the android studio -> java -> your package name -> PayPalConfig:
        a) add the PAYPAL_CLIENT_ID which you get from the paypal developer control Panel;
        b) add the PAYPAL_PAYOUT_URL which you get in the firebase control panel -> functions and the url that you want is the payouts;

[![TralahM](https://img.shields.io/badge/Developer-TralahM-blue.svg?style=for-the-badge)](https://github.com/TralahM)
