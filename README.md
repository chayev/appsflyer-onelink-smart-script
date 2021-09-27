## Overview

**At a glance:** Use OneLink Smart Script to generate URLs that get embedded behind a button on your mobile website.

![smart_script_flow](./images/Smart_Script_flow.png "OneLink Smart Script flow")

Users arrive at your mobile website before reaching your app store page, either organically, or via advertising campaigns. However, since there are two clicks (the first that directs to the web page and the second that directs from the web page to the app store), collecting click conversion metrics and deep linking is problematic.

OneLink Smart Script solves these problems. The script:

Uses the incoming URLs leading to the webpage to automatically generate unique outgoing OneLink URLs leading to the app store.
Provides accurate web-to-app metrics collection for all media sources, including ad networks, SRNs, Google clicks, and owned media.
Can be used for deep linking.
Runs seamlessly on any webpage or landing page.

Table of contents:

- [Script](scripts/onelink-smart-script.js)
- Sample use cases
  - [Basic URL](examples/basic_url.html?af_c=gogo&af_pid=email&af_custom_fruit=peaches&af_custom_amount=25)
  - [UTM Parameters](examples/utm_params.html?utm_source=email&utm_campaign=summer_sale&af_custom_fruit=peaches&af_custom_amount=25)
  - [Static PID and campaign values](examples/static_val.html?af_not_c=gogo&af_not_pid=email&af_custom_fruit=peaches&af_custom_amount=25)
  - [Override PID](examples/override_pid.html?af_pid=twitter&af_c=big_social&af_custom_fruit=peaches&af_custom_amount=25)
  - [Google Click ID](examples/gclid.html?af_pid=sms&af_c=candles&gclid=1a2b3c&af_custom_fruit=peaches&af_custom_amount=25)
  - [Set OneLink parameters](examples/setters.html?af_c=gogo&af_pid=email&af_custom_fruit=peaches&af_custom_amount=25)
  - [Skip List](examples/skip_list.html?original_campaign=origcamp&original_pid=origpid&af_custom_fruit=peaches&af_custom_amount=25)
