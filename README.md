# cordova-plugin-walkme

## Disclaimer

This is a public plugin that integrates with the WalkMe service. You must have an account set up with WalkMe for this to work.

This plugin is not maintained by WalkMe, so please do not contact them with any bugs. Use at your own risk!



## <a id="reference">Reference</a>
## Installation

Install with two variables per OS - **[OS]_APP_KEY** and **[OS]_APP_SECRET** available from the WalkMe Console. 

```javascript
cordova plugin add cordova-plugin-walkme 
--variable IOS_APP_KEY=LONGSTRINGFROMWALKME 
--variable IOS_APP_SECRET=EVENLONGERSTRINGFROMWALKME 
--variable ANDROID_APP_KEY=ANOTHERLONGSTRINGFROMWALKME 
--variable ANDROID_APP_SECRET=ANOTHEREVENLONGERSTRINGFROMWALKME
```

Once the plugin has been installed, you should be good to go! Configure all screens and modules from within WalkMe.

## window.plugins.WalkMe.sendGoals

goalName - Required Goal Name

properties - Optional Struct of key/value string pairs

```javascript
window.plugins.WalkMe.sendGoals("Viewed Items");

window.plugins.WalkMe.sendGoals("Purchased Item",{"Book":"Count of Monte Cristo","Book":"You Don't Know Js: Scope & Closures"});

```

## License

Copyright [2017] [Mad Mobile]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
