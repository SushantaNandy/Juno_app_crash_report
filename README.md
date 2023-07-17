# Juno_app_crash_report
[info] [35m[Appium][39m Welcome to Appium v1.17.1
[info] [35m[Appium][39m Non-default server args:
[info] [35m[Appium][39m   allowInsecure: {
[info] [35m[Appium][39m   }
[info] [35m[Appium][39m   denyInsecure: {
[info] [35m[Appium][39m   }[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session[39m
[info] [35m[HTTP][39m [90m{"capabilities":{"firstMatch":[{}],"alwaysMatch":{"appium:devicename":"SM M515F","platformName":"Android","appium:appPackage":"com.capitalJ.onjunodev","appium:appActivity":"com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity"}}}[39m
[debug] [35m[W3C][39m Calling AppiumDriver.createSession() with args: [null,null,{"firstMatch":[{}],"alwaysMatch":{"appium:devicename":"SM M515F","platformName":"Android","appium:appPackage":"com.capitalJ.onjunodev","appium:appActivity":"com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity"}}]
[debug] [35m[BaseDriver][39m Event 'newSessionRequested' logged at 1689568839236 (10:10:39 GMT+0530 (India Standard Time))
[warn] [35m[Appium][39m 
[warn] [35m[Appium][39m ======================================================================
[warn] [35m[Appium][39m   DEPRECATION WARNING:
[warn] [35m[Appium][39m 
[warn] [35m[Appium][39m   The 'automationName' capability was not provided in the desired 
[warn] [35m[Appium][39m   capabilities for this Android session
[warn] [35m[Appium][39m 
[warn] [35m[Appium][39m   Setting 'automationName=UiAutomator2' by default and using the 
[warn] [35m[Appium][39m   UiAutomator2 Driver
[warn] [35m[Appium][39m 
[warn] [35m[Appium][39m   The next major version of Appium (2.x) will **require** the 
[warn] [35m[Appium][39m   'automationName' capability to be set for all sessions on all 
[warn] [35m[Appium][39m   platforms
[warn] [35m[Appium][39m 
[warn] [35m[Appium][39m   In previous versions (Appium <= 1.13.x), the default was 
[warn] [35m[Appium][39m   'automationName=UiAutomator1'
[warn] [35m[Appium][39m 
[warn] [35m[Appium][39m   If you wish to use that automation instead of UiAutomator2, please 
[warn] [35m[Appium][39m   add 'automationName=UiAutomator1' to your desired capabilities
[warn] [35m[Appium][39m 
[warn] [35m[Appium][39m   For more information about drivers, please visit 
[warn] [35m[Appium][39m   http://appium.io/docs/en/about-appium/intro/ and explore the 
[warn] [35m[Appium][39m   'Drivers' menu
[warn] [35m[Appium][39m 
[warn] [35m[Appium][39m ======================================================================
[warn] [35m[Appium][39m 
[info] [35m[Appium][39m Appium v1.17.1 creating new AndroidUiautomator2Driver (v1.44.2) session
[debug] [35m[BaseDriver][39m Creating session with W3C capabilities: {
[debug] [35m[BaseDriver][39m   "alwaysMatch": {
[debug] [35m[BaseDriver][39m     "platformName": "Android",
[debug] [35m[BaseDriver][39m     "appium:devicename": "SM M515F",
[debug] [35m[BaseDriver][39m     "appium:appPackage": "com.capitalJ.onjunodev",
[debug] [35m[BaseDriver][39m     "appium:appActivity": "com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity"
[debug] [35m[BaseDriver][39m   },
[debug] [35m[BaseDriver][39m   "firstMatch": [
[debug] [35m[BaseDriver][39m     {}
[debug] [35m[BaseDriver][39m   ]
[debug] [35m[BaseDriver][39m }
[warn] [35m[BaseDriver][39m The following capabilities were provided, but are not recognized by Appium:
[warn] [35m[BaseDriver][39m   devicename
[info] [35m[BaseDriver][39m Session created with session id: 84347594-b4dc-427f-97fd-0c9cdb48db67
[info] [35m[UiAutomator2][39m Starting 'com.capitalJ.onjunodev' directly on the device[debug] [35m[ADB][39m Connected devices: [{"udid":"RZ8TA00DGFT","state":"device"}]
[info] [35m[AndroidDriver][39m Using device: RZ8TA00DGFT
[info] [35m[ADB][39m Using 'adb.exe' from 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe'
[debug] [35m[ADB][39m Setting device id to RZ8TA00DGFT
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell getprop ro.build.version.sdk'[debug] [35m[ADB][39m Current device property 'ro.build.version.sdk': 33
[info] [35m[ADB][39m Getting device platform version
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell getprop ro.build.version.release'[debug] [35m[ADB][39m Current device property 'ro.build.version.release': 13
[debug] [35m[ADB][39m Device API level: 33
[warn] [35m[UiAutomator2][39m Relaxing hidden api policy
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell settings put global hidden_api_policy_pre_p_apps 1'[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell settings put global hidden_api_policy_p_apps 1'[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell settings put global hidden_api_policy 1'[warn] [35m[AndroidDriver][39m No app sent in, not parsing package/activity
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT wait-for-device'
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell echo ping'[debug] [35m[AndroidDriver][39m Pushing settings apk to device...
[debug] [35m[ADB][39m Getting install status for io.appium.settings
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell dumpsys package io.appium.settings'[debug] [35m[ADB][39m 'io.appium.settings' is installed
[debug] [35m[ADB][39m Getting package info for 'io.appium.settings'
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell dumpsys package io.appium.settings'[debug] [35m[ADB][39m The version name of the installed 'io.appium.settings' is greater or equal to the application version name ('3.1.0' >= '3.1.0')
[debug] [35m[ADB][39m There is no need to install/upgrade 'C:\Users\hp\AppData\Local\Programs\Appium\resources\app\node_modules\appium\node_modules\io.appium.settings\apks\settings_apk-debug.apk'
[debug] [35m[ADB][39m Getting IDs of all 'io.appium.settings' processes
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell 'pgrep --help; echo $?''[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell pgrep -f io\\.appium\\.settings'[debug] [35m[AndroidDriver][39m io.appium.settings is already running. There is no need to reset its permissions.
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell appops set io.appium.settings android\:mock_location allow'[debug] [35m[Logcat][39m Starting logcat capture[debug] [35m[UiAutomator2][39m Forwarding UiAutomator2 Server port 6790 to 8200
[debug] [35m[ADB][39m Forwarding system: 8200 to device: 6790
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT forward tcp\:8200 tcp\:6790'[debug] [35m[ADB][39m Getting install status for io.appium.uiautomator2.server
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell dumpsys package io.appium.uiautomator2.server'[debug] [35m[ADB][39m 'io.appium.uiautomator2.server' is installed
[debug] [35m[ADB][39m Getting package info for 'io.appium.uiautomator2.server'
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell dumpsys package io.appium.uiautomator2.server'[debug] [35m[ADB][39m The version name of the installed 'io.appium.uiautomator2.server' is greater or equal to the application version name ('4.5.5' >= '4.5.5')
[debug] [35m[UiAutomator2][39m io.appium.uiautomator2.server installation state: sameVersionInstalled
[debug] [35m[ADB][39m Checking app cert for C:\Users\hp\AppData\Local\Programs\Appium\resources\app\node_modules\appium\node_modules\appium-uiautomator2-server\apks\appium-uiautomator2-server-v4.5.5.apk[info] [35m[ADB][39m Using 'apksigner.jar' from 'C:\Users\hp\AppData\Local\Android\Sdk\build-tools\33.0.1\lib\apksigner.jar'
[debug] [35m[ADB][39m Starting apksigner: 'C:\\Program Files\\Java\\jdk-11.0.16.1\\bin\\java.exe' -Xmx1024M -Xss1m -jar C:\\Users\\hp\\AppData\\Local\\Android\\Sdk\\build-tools\\33.0.1\\lib\\apksigner.jar verify --print-certs C:\\Users\\hp\\AppData\\Local\\Programs\\Appium\\resources\\app\\node_modules\\appium\\node_modules\\appium-uiautomator2-server\\apks\\appium-uiautomator2-server-v4.5.5.apk[debug] [35m[ADB][39m apksigner stdout: Signer #1 certificate DN: EMAILADDRESS=android@android.com, CN=Android, OU=Android, O=Android, L=Mountain View, ST=California, C=US
[debug] [35m[ADB][39m Signer #1 certificate SHA-256 digest: a40da80a59d170caa950cf15c18c454d47a39b26989d8b640ecd745ba71bf5dc
[debug] [35m[ADB][39m Signer #1 certificate SHA-1 digest: 61ed377e85d386a8dfee6b864bd85b0bfaa5af81
[debug] [35m[ADB][39m Signer #1 certificate MD5 digest: e89b158e4bcf988ebd09eb83f5378e87
[debug] [35m[ADB][39m 
[debug] [35m[ADB][39m 'C:\Users\hp\AppData\Local\Programs\Appium\resources\app\node_modules\appium\node_modules\appium-uiautomator2-server\apks\appium-uiautomator2-server-v4.5.5.apk' is signed with the default certificate
[debug] [35m[ADB][39m Getting install status for io.appium.uiautomator2.server.test
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell dumpsys package io.appium.uiautomator2.server.test'[debug] [35m[ADB][39m 'io.appium.uiautomator2.server.test' is installed
[debug] [35m[ADB][39m Checking app cert for C:\Users\hp\AppData\Local\Programs\Appium\resources\app\node_modules\appium\node_modules\appium-uiautomator2-server\apks\appium-uiautomator2-server-debug-androidTest.apk
[debug] [35m[ADB][39m Starting apksigner: 'C:\\Program Files\\Java\\jdk-11.0.16.1\\bin\\java.exe' -Xmx1024M -Xss1m -jar C:\\Users\\hp\\AppData\\Local\\Android\\Sdk\\build-tools\\33.0.1\\lib\\apksigner.jar verify --print-certs C:\\Users\\hp\\AppData\\Local\\Programs\\Appium\\resources\\app\\node_modules\\appium\\node_modules\\appium-uiautomator2-server\\apks\\appium-uiautomator2-server-debug-androidTest.apk[debug] [35m[ADB][39m apksigner stdout: Signer #1 certificate DN: EMAILADDRESS=android@android.com, CN=Android, OU=Android, O=Android, L=Mountain View, ST=California, C=US
[debug] [35m[ADB][39m Signer #1 certificate SHA-256 digest: a40da80a59d170caa950cf15c18c454d47a39b26989d8b640ecd745ba71bf5dc
[debug] [35m[ADB][39m Signer #1 certificate SHA-1 digest: 61ed377e85d386a8dfee6b864bd85b0bfaa5af81
[debug] [35m[ADB][39m Signer #1 certificate MD5 digest: e89b158e4bcf988ebd09eb83f5378e87
[debug] [35m[ADB][39m 
[debug] [35m[ADB][39m 'C:\Users\hp\AppData\Local\Programs\Appium\resources\app\node_modules\appium\node_modules\appium-uiautomator2-server\apks\appium-uiautomator2-server-debug-androidTest.apk' is signed with the default certificate
[info] [35m[UiAutomator2][39m Server packages are not going to be (re)installed
[debug] [35m[UiAutomator2][39m Waiting up to 30000ms for services to be available
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell pm list instrumentation'[debug] [35m[UiAutomator2][39m Instrumentation target 'io.appium.uiautomator2.server.test/androidx.test.runner.AndroidJUnitRunner' is available
[debug] [35m[UiAutomator2][39m No app capability. Assuming it is already on the device
[debug] [35m[ADB][39m Getting install status for com.capitalJ.onjunodev
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell dumpsys package com.capitalJ.onjunodev'[debug] [35m[ADB][39m 'com.capitalJ.onjunodev' is installed
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell am force-stop com.capitalJ.onjunodev'[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell pm clear com.capitalJ.onjunodev'[debug] [35m[AndroidDriver][39m Performed fast reset on the installed 'com.capitalJ.onjunodev' application (stop and clear)
[debug] [35m[UiAutomator2][39m Performing shallow cleanup of automation leftovers
[debug] [35m[UiAutomator2][39m No obsolete sessions have been detected (Error: socket hang up)
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell am force-stop io.appium.uiautomator2.server.test'[info] [35m[UiAutomator2][39m Starting UIAutomator2 server 4.5.5
[info] [35m[UiAutomator2][39m Using UIAutomator2 server from 'C:\Users\hp\AppData\Local\Programs\Appium\resources\app\node_modules\appium\node_modules\appium-uiautomator2-server\apks\appium-uiautomator2-server-v4.5.5.apk' and test from 'C:\Users\hp\AppData\Local\Programs\Appium\resources\app\node_modules\appium\node_modules\appium-uiautomator2-server\apks\appium-uiautomator2-server-debug-androidTest.apk'
[info] [35m[UiAutomator2][39m Waiting up to 30000ms for UiAutomator2 to be online...
[debug] [35m[ADB][39m Creating ADB subprocess with args: ["-P",5037,"-s","RZ8TA00DGFT","shell","am","instrument","-w","io.appium.uiautomator2.server.test/androidx.test.runner.AndroidJUnitRunner"][debug] [35m[WD Proxy][39m Matched '/status' to command name 'getStatus'
[debug] [35m[WD Proxy][39m Proxying [GET /status] to [GET http://127.0.0.1:8200/wd/hub/status] with no body
[info] [35m[WD Proxy][39m Got response with unknown status: {"code":"ECONNRESET"}[debug] [35m[WD Proxy][39m Matched '/status' to command name 'getStatus'
[debug] [35m[WD Proxy][39m Proxying [GET /status] to [GET http://127.0.0.1:8200/wd/hub/status] with no body[debug] [35m[WD Proxy][39m Matched '/status' to command name 'getStatus'
[debug] [35m[WD Proxy][39m Proxying [GET /status] to [GET http://127.0.0.1:8200/wd/hub/status] with no body
[info] [35m[WD Proxy][39m Got response with unknown status: {"code":"ECONNRESET"}
[debug] [35m[Instrumentation][39m io.appium.uiautomator2.server.test.AppiumUiAutomator2Server:[debug] [35m[WD Proxy][39m Matched '/status' to command name 'getStatus'
[debug] [35m[WD Proxy][39m Proxying [GET /status] to [GET http://127.0.0.1:8200/wd/hub/status] with no body
[info] [35m[WD Proxy][39m Got response with unknown status: {"code":"ECONNRESET"}[debug] [35m[WD Proxy][39m Matched '/status' to command name 'getStatus'
[debug] [35m[WD Proxy][39m Proxying [GET /status] to [GET http://127.0.0.1:8200/wd/hub/status] with no body
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"None","value":{"ready":true,"message":"UiAutomator2 Server is ready to accept commands"}}
[debug] [35m[UiAutomator2][39m The initialization of the instrumentation process took 5334ms
[debug] [35m[WD Proxy][39m Matched '/session' to command name 'createSession'
[debug] [35m[WD Proxy][39m Proxying [POST /session] to [POST http://127.0.0.1:8200/wd/hub/session] with body: {"capabilities":{"firstMatch":[{"platform":"LINUX","webStorageEnabled":false,"takesScreenshot":true,"javascriptEnabled":true,"databaseEnabled":false,"networkConnectionEnabled":true,"locationContextEnabled":false,"warnings":{},"desired":{"platformName":"Android","devicename":"SM M515F","appPackage":"com.capitalJ.onjunodev","appActivity":"com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity"},"platformName":"Android","devicename":"SM M515F","appPackage":"com.capitalJ.onjunodev","appActivity":"com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity","deviceName":"RZ8TA00DGFT","deviceUDID":"RZ8TA00DGFT"}],"alwaysMatch":{}}}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":{"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","capabilities":{"firstMatch":[{"platform":"LINUX","webStorageEnabled":false,"takesScreenshot":true,"javascriptEnabled":true,"databaseEnabled":false,"networkConnectionEnabled":true,"locationContextEnabled":false,"warnings":{},"desired":{"platformName":"Android","devicename":"SM M515F","appPackage":"com.capitalJ.onjunodev","appActivity":"com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity"},"platformName":"Android","devicename":"SM M515F","appPackage":"com.capitalJ.onjunodev","appActivity":"com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity","deviceName":"RZ8TA00DGFT","deviceUDID":"RZ8TA00DGFT"}],"alwaysMatch":{}}}}
[info] [35m[WD Proxy][39m Determined the downstream protocol as 'W3C'
[debug] [35m[WD Proxy][39m Proxying [GET /appium/device/info] to [GET http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/appium/device/info] with no body
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":{"androidId":"d6922bb2e1d52389","manufacturer":"samsung","model":"SM-E135F","brand":"samsung","apiVersion":"33","platformVersion":"13","carrierName":"STAY AT HOME","realDisplaySize":"1080x2408","displayDensity":450,"networks":[{"type":0,"typeName":"MOBILE","subtype":13,"subtypeName":"LTE","isConnected":true,"detailedState":"CONNECTED","state":"CONNECTED","extraInfo":"ims","isAvailable":true,"isFailover":false,"isRoaming":false,"capabilities":{"transportTypes":"TRANSPORT_CELLULAR","networkCapabilities":"NET_CAPABILITY_IMS,NET_CAPABILITY_NOT_METERED,NET_CAPABILITY_TRUSTED,NET_CAPABILITY_NOT_VPN,NET_CAPABILITY_VALIDATED,NET_CAPABILITY_NOT_ROAMING,NET_CAPABILITY_FOREGROUND,NET_CAPABILITY_NOT_CONGESTED,NET_CAPABILITY_NOT_SUSPENDED","linkUpstreamBandwidthKbps":5474,"linkDownBandwidthKbps":5474,"signalStrength":-2147483648,"networkSpecifier":"TelephonyNetworkSpecifier [mSubId = 1]","SSID":null}},{"type":0,"typeName":"MOBILE","subtype":13,"subtypeName":"L...
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell dumpsys window'[info] [35m[AndroidDriver][39m Screen already unlocked, doing nothing
[info] [35m[UiAutomator2][39m Starting 'com.capitalJ.onjunodev/com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity and waiting for 'com.capitalJ.onjunodev/com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity'
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell am start -W -n com.capitalJ.onjunodev/com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity -S'[debug] [35m[WD Proxy][39m Proxying [GET /appium/device/pixel_ratio] to [GET http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/appium/device/pixel_ratio] with body: {}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":2.8125}
[debug] [35m[WD Proxy][39m Matched '/appium/device/system_bars' to command name 'getSystemBars'
[debug] [35m[WD Proxy][39m Proxying [GET /appium/device/system_bars] to [GET http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/appium/device/system_bars] with body: {}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":{"statusBar":66}}
[debug] [35m[WD Proxy][39m Matched '/window/current/size' to command name 'getWindowSize'
[debug] [35m[WD Proxy][39m Proxying [GET /window/current/size] to [GET http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/window/current/size] with body: {}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":{"height":2207,"width":1080}}
[info] [35m[Appium][39m New AndroidUiautomator2Driver session created successfully, session 84347594-b4dc-427f-97fd-0c9cdb48db67 added to master session list
[debug] [35m[BaseDriver][39m Event 'newSessionStarted' logged at 1689568873961 (10:11:13 GMT+0530 (India Standard Time))
[debug] [35m[W3C (84347594)][39m Cached the protocol value 'W3C' for the new session 84347594-b4dc-427f-97fd-0c9cdb48db67
[debug] [35m[W3C (84347594)][39m Responding to client with driver.createSession() result: {"capabilities":{"platform":"LINUX","webStorageEnabled":false,"takesScreenshot":true,"javascriptEnabled":true,"databaseEnabled":false,"networkConnectionEnabled":true,"locationContextEnabled":false,"warnings":{},"desired":{"platformName":"Android","devicename":"SM M515F","appPackage":"com.capitalJ.onjunodev","appActivity":"com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity"},"platformName":"Android","devicename":"SM M515F","appPackage":"com.capitalJ.onjunodev","appActivity":"com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity","deviceName":"RZ8TA00DGFT","deviceUDID":"RZ8TA00DGFT","deviceApiLevel":33,"platformVersion":"13","deviceScreenSize":"1080x2408","deviceScreenDensity":450,"deviceModel":"SM-E135F","deviceManufacturer":"samsung","pixelRatio":2.8125,"statBarHeight":66,"viewportRect":{"left":0,"top":66,"width":1080,"height":2141}}}
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session [39m[32m200[39m [90m34770 ms - 930[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m730 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m1069 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m142 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m780 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m90 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m77 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m78 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m69 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m60 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m73 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m80 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m92 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m94 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m84 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m80 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m67 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m65 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m467 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m75 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m62 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m78 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m87 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m79 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m76 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m70 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m84 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m200 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m52 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m83 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m614 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m112 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m68 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m79 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m83 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m65 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m90 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m59 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m53 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m110 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m80 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m74 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m79 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m75 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m56 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m68 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m53 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m3733 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m80 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m71 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m81 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m67 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m71 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m65 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m90 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m58 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m47 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m62 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m75 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m73 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m78 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m430 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m304 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m54 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m56 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m67 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m68 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m81 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m73 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m69 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m70 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m70 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m66 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m71 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m82 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m92 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m752 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m63 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mGET[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/source[39m
[info] [35m[HTTP][39m [90m{}[39m
[info] [35m[W3C (84347594)][39m Driver proxy active, passing request on via HTTP proxy
[debug] [35m[WD Proxy][39m Matched '/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/source' to command name 'getPageSource'
[debug] [35m[WD Proxy][39m Proxying [GET /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/source] to [GET http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/source] with body: {}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":"<?xml version='1.0' encoding='UTF-8' standalone='yes' ?>\r\n<hierarchy index=\"0\" class=\"hierarchy\" rotation=\"0\" width=\"1080\" height=\"2207\">\r\n  <android.widget.FrameLayout index=\"0\" package=\"com.capitalJ.onjunodev\" class=\"android.widget.FrameLayout\" text=\"\" checkable=\"false\" checked=\"false\" clickable=\"false\" enabled=\"true\" focusable=\"false\" focused=\"false\" long-clickable=\"false\" password=\"false\" scrollable=\"false\" selected=\"false\" bounds=\"[0,0][1080,2207]\" displayed=\"true\">\r\n    <android.widget.LinearLayout index=\"0\" package=\"com.capitalJ.onjunodev\" class=\"android.widget.LinearLayout\" text=\"\" checkable=\"false\" checked=\"false\" clickable=\"false\" enabled=\"true\" focusable=\"false\" focused=\"false\" long-clickable=\"false\" password=\"false\" scrollable=\"false\" selected=\"false\" bounds=\"[0,0][1080,2207]\" displayed=\"true\">\r\n      <android.widget.FrameLayout index=\"0\" package=\"com...
[info] [35m[WD Proxy][39m Replacing sessionId 951cf2ed-2a66-45ab-b068-1c3dff21ef0b with 84347594-b4dc-427f-97fd-0c9cdb48db67
[info] [35m[HTTP][39m [37m<-- GET /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/source [39m[32m200[39m [90m637 ms - 6231[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mGET[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/screenshot[39m
[info] [35m[HTTP][39m [90m{}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.getScreenshot() with args: ["84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[WD Proxy][39m Matched '/screenshot' to command name 'getScreenshot'
[debug] [35m[WD Proxy][39m Proxying [GET /screenshot] to [GET http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/screenshot] with no body[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":"iVBORw0KGgoAAAANSUhEUgAABDgAAAloCAYAAACBSQW4AAAAAXNSR0IArs4c6QAAAARzQklUCAgI\nCHwIZIgAACAASURBVHic7N17dJXlnejx384N5H4pmIBKFSEVa1XiCKOoqbVaWtQ6nVrFSjsdi45O\nPSquc9rxVOnyME7PeKszXW1pp7bMKF3WtlPBS0URceoNQY61HQj1gpYEQblIuIUk+\/wRs5uYQEiy\nAz7w+azV1ezsnXe\/+0XIfr\/7eZ8nc3RpZAMAAAAgYQX7ewcAAAAAukvgAAAAAJIncAAAAADJEzgA\nAACA5AkcAAAAQPIEDgAAACB5AgcAAACQPIEDAAAASJ7AAQAAACRP4AAAAACSJ3AAAAAAyRM4AAAA\ngOQJHAAAAEDyBA4AAAAgeQIHAAAAkDyBAwAAAEiewAEAAAAkT+AAAAAAkidwAAAAAMkTOAAAAIDk\nFe3vHThYFBUVxYgRI6KhoSHWrFmzv3fngFdUVBQjR46MY445JsaOHRvDhg2LXr16xfbt26O6ujpW\nrlwZK1eujHXr1kVDQ8P+3t2cUaNGRUVFRRx\/\/PHRu3fvuO+++2Lp0qW5+z\/96U\/HmWeeGRs2bIgX\nX3wxli1bFm+99dZ+3OPWUj3uALA3+vfvH2eccUaUlZW1e\/+WLVviwQcfjC1btuzjPesZ5eXlMWbM\nmJg\/f\/7+3pU9OvTQQyMiPlDvidqTyvE85JBDIiJi+\/bt+3lP9r8BAwZEWVlZbN68OdauXbtf92Xw\n4MExZMiQ3d6\/fv36ePfdd\/fhHn0wCRy7cdppp8XkyZPjiCOOiC9+8Ytd2sbIkSPj0ksvjZNOOikO\nP\/zwKCwsjIiIXbt2xeuvvx7PP\/dc\/HTOnNiwYUM+d3238vGa9uV2u6KgoCA+PGpUXPBXfxWVlZVR\nWloamUym...
[debug] [35m[W3C (84347594)][39m Responding to client with driver.getScreenshot() result: "iVBORw0KGgoAAAANSUhEUgAABDgAAAloCAYAAACBSQW4AAAAAXNSR0IArs4c6QAAAARzQklUCAgI\nCHwIZIgAACAASURBVHic7N17dJXlnejx384N5H4pmIBKFSEVa1XiCKOoqbVaWtQ6nVrFSjsdi45O\nPSquc9rxVOnyME7PeKszXW1pp7bMKF3WtlPBS0URceoNQY61HQj1gpYEQblIuIUk+/wRs5uYQEiy\nAz7w+azV1ezsnXe/+0XIfr/7eZ8nc3RpZAMAAAAgYQX7ewcAAAAAukvgAAAAAJIncAAAAADJEzgA\nAACA5AkcAAAAQPIEDgAAACB5AgcAAACQPIEDAAAASJ7AAQAAACRP4AAAAACSJ3AAAAAAyRM4AAAA\ngOQJHAAAAEDyBA4AAAAgeQIHAAAAkDyBAwAAAEiewAEAAAAkT+AAAAAAkidwAAAAAMkTOAAAAIDk\nFe3vHThYFBUVxYgRI6KhoSHWrFmzv3fngFdUVBQjR46MY445JsaOHRvDhg2LXr16xfbt26O6ujpW\nrlwZK1eujHXr1kVDQ8P+3t2cUaNGRUVFRRx//PHRu3fvuO+++2Lp0qW5+z/96U/HmWeeGRs2bIgX\nX3wxli1bFm+99dZ+3OPWUj3uALA3+vfvH2eccUaUlZW1e/+WLVviwQcfjC1btuzjPesZ5eXlMWbM\nmJg/f/7+3pU9OvTQQyMiPlDvidqTyvE85JBDIiJi+/bt+3lP9r8BAwZEWVlZbN68OdauXbtf92Xw\n4MExZMiQ3d6/fv36ePfdd/fhHn0wCRy7cdppp8XkyZPjiCOOiC9+8Ytd2sbIkSPj0ksvjZNOOikO\nP/zwKCwsjIiIXbt2xeuvvx7PP/dc/HTOnNiwYUM+d3238vGa9uV2u6KgoCA+PGpUXPBXfxWVlZVR\nWloamUymzeMaGxvjtddei0ceeSQefPDBWLdu3X7Y2z874YQT4vzzz4+PfexjMXDgwOjdu3esWbMm\nevXq1e...
[info] [35m[HTTP][39m [37m<-- GET /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/screenshot [39m[32m200[39m [90m2293 ms - 176194[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m2592 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m2441 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m1521 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m246 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m698 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m1408 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m58 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m862 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m73 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m166 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m726 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m60 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m102 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m71 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m41 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m46 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m56 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m45 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m42 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m43 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m53 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m48 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m119 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m86 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m632 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m158 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m76 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m475 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m262 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m870 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m127 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m74 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m44 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m928 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m106 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m70 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m93 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m2144 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m1121 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":[]}
[debug] [35m[W3C (84347594)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/elements [39m[32m200[39m [90m2806 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mGET[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/source[39m
[info] [35m[HTTP][39m [90m{}[39m
[info] [35m[W3C (84347594)][39m Driver proxy active, passing request on via HTTP proxy
[debug] [35m[WD Proxy][39m Matched '/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/source' to command name 'getPageSource'
[debug] [35m[WD Proxy][39m Proxying [GET /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/source] to [GET http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/source] with body: {}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":"<?xml version='1.0' encoding='UTF-8' standalone='yes' ?>\r\n<hierarchy index=\"0\" class=\"hierarchy\" rotation=\"0\" width=\"1080\" height=\"2207\">\r\n  <android.widget.FrameLayout index=\"0\" package=\"com.capitalJ.onjunodev\" class=\"android.widget.FrameLayout\" text=\"\" checkable=\"false\" checked=\"false\" clickable=\"false\" enabled=\"true\" focusable=\"false\" focused=\"false\" long-clickable=\"false\" password=\"false\" scrollable=\"false\" selected=\"false\" bounds=\"[0,0][1080,2207]\" displayed=\"true\">\r\n    <android.widget.LinearLayout index=\"0\" package=\"com.capitalJ.onjunodev\" class=\"android.widget.LinearLayout\" text=\"\" checkable=\"false\" checked=\"false\" clickable=\"false\" enabled=\"true\" focusable=\"false\" focused=\"false\" long-clickable=\"false\" password=\"false\" scrollable=\"false\" selected=\"false\" bounds=\"[0,0][1080,2207]\" displayed=\"true\">\r\n      <android.widget.FrameLayout index=\"0\" package=\"com...
[info] [35m[WD Proxy][39m Replacing sessionId 951cf2ed-2a66-45ab-b068-1c3dff21ef0b with 84347594-b4dc-427f-97fd-0c9cdb48db67
[info] [35m[HTTP][39m [37m<-- GET /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/source [39m[32m200[39m [90m362 ms - 8851[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mGET[39m [37m/wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/screenshot[39m
[info] [35m[HTTP][39m [90m{}[39m
[debug] [35m[W3C (84347594)][39m Calling AppiumDriver.getScreenshot() with args: ["84347594-b4dc-427f-97fd-0c9cdb48db67"]
[debug] [35m[WD Proxy][39m Matched '/screenshot' to command name 'getScreenshot'
[debug] [35m[WD Proxy][39m Proxying [GET /screenshot] to [GET http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b/screenshot] with no body[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":"iVBORw0KGgoAAAANSUhEUgAABDgAAAloCAYAAACBSQW4AAAAAXNSR0IArs4c6QAAAARzQklUCAgI\nCHwIZIgAACAASURBVHic7J15fBRF2sd\/1TMJV8KRgDJRQY4k4IoKcYVVBFQQEARdPAARdOUSEDn1\n9QYVXQW81gPBVVfAsB67igQPbnBVlIRLVBJQASVc4UoMkGS63j+6q7r6mumZTAgD9f18lEwfVU9V\n1\/HUU1VPkcw0UEgkEolEIpFIJBKJRCKRxDFKdQsgkUgkEolEIpFIJBKJRFJZpIFDIpFIJBKJRCKR\nSCQSSdwjDRwSiUQikUgkEolEIpFI4h5p4JBIJBKJRCKRSCQSiUQS90gDh0QikUgkEolEIpFIJJK4\nRxo4JBKJRCKRSCQSiUQikcQ90sAhkUgkEolEIpFIJBKJJO6RBg6JRCKRSCQSiUQikUgkcY80cEgk\nEolEIpFIJBKJRCKJe6SBQyKRSCQSiUQikUgkEkncIw0cEolEIpFIJBKJRCKRSOIeaeCQSCQSiUQi\nkUgkEolEEvdIA4dEIpFIJBKJRCKRSCSSuEcaOCQSiUQikUgkEolEIpHEPdLAIZFIJBKJRCKRSCQS\niSTukQYOiUQikUgkEolEIpFIJHGPNHBIJBKJRCKRSCQSiUQiiXv81S2ARBJLFMWHQKAx\/vSnC3HR\nxRejRYsWOO\/c81C7Th3UqFEDx48fR3FxMXbu3Int27dh86ZN+P77zThwoAiqGpSyR4nf70eDBg1w\nXpOmaHPhhbiwTRs0b9Yc9Rs0QM2aNVFaWoqDRUUo2FaATRs34ceffsBvu3bh6NGjCAarV3aJRCKR\nSCQSiURyekAy00CrWwiJpFIQgtSUVPTr1w9XXXU1mjVvDkKI59dVVcXWrT\/hs08\/xWeffYrDhw9X\nobAW4ll2aIaNlunpGD...
[debug] [35m[W3C (84347594)][39m Responding to client with driver.getScreenshot() result: "iVBORw0KGgoAAAANSUhEUgAABDgAAAloCAYAAACBSQW4AAAAAXNSR0IArs4c6QAAAARzQklUCAgI\nCHwIZIgAACAASURBVHic7J15fBRF2sd/1TMJV8KRgDJRQY4k4IoKcYVVBFQQEARdPAARdOUSEDn1\n9QYVXQW81gPBVVfAsB67igQPbnBVlIRLVBJQASVc4UoMkGS63j+6q7r6mumZTAgD9f18lEwfVU9V\n1/HUU1VPkcw0UEgkEolEIpFIJBKJRCKRxDFKdQsgkUgkEolEIpFIJBKJRFJZpIFDIpFIJBKJRCKR\nSCQSSdwjDRwSiUQikUgkEolEIpFI4h5p4JBIJBKJRCKRSCQSiUQS90gDh0QikUgkEolEIpFIJJK4\nRxo4JBKJRCKRSCQSiUQikcQ90sAhkUgkEolEIpFIJBKJJO6RBg6JRCKRSCQSiUQikUgkcY80cEgk\nEolEIpFIJBKJRCKJe6SBQyKRSCQSiUQikUgkEkncIw0cEolEIpFIJBKJRCKRSOIeaeCQSCQSiUQi\nkUgkEolEEvdIA4dEIpFIJBKJRCKRSCSSuEcaOCQSiUQikUgkEolEIpHEPdLAIZFIJBKJRCKRSCQS\niSTukQYOiUQikUgkEolEIpFIJHGPNHBIJBKJRCKRSCQSiUQiiXv81S2ARBJLFMWHQKAx/vSnC3HR\nxRejRYsWOO/c81C7Th3UqFEDx48fR3FxMXbu3Int27dh86ZN+P77zThwoAiqGpSyR4nf70eDBg1w\nXpOmaHPhhbiwTRs0b9Yc9Rs0QM2aNVFaWoqDRUUo2FaATRs34ceffsBvu3bh6NGjCAarV3aJRCKR\nSCQSiURyekAy00CrWwiJpFIQgtSUVPTr1w9XXXU1mjVvDkKI59dVVcXWrT/hs08/xWeffYrDhw9X\nobAW4ll2aIaNlunpGDx4CK6++pqIZD9x4gQWLvwY77/3b+za9Vu1G2kkEolEIpFIJBJJfCMNHJK4\npkGDBh...
[info] [35m[HTTP][39m [37m<-- GET /wd/hub/session/84347594-b4dc-427f-97fd-0c9cdb48db67/screenshot [39m[32m200[39m [90m5606 ms - 2030394[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session[39m
[info] [35m[HTTP][39m [90m{"capabilities":{"firstMatch":[{}],"alwaysMatch":{"appium:devicename":"SM M515F","platformName":"Android","appium:appPackage":"com.capitalJ.onjunodev","appium:appActivity":"com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity"}}}[39m
[debug] [35m[W3C][39m Calling AppiumDriver.createSession() with args: [null,null,{"firstMatch":[{}],"alwaysMatch":{"appium:devicename":"SM M515F","platformName":"Android","appium:appPackage":"com.capitalJ.onjunodev","appium:appActivity":"com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity"}}]
[debug] [35m[BaseDriver][39m Event 'newSessionRequested' logged at 1689568957493 (10:12:37 GMT+0530 (India Standard Time))
[warn] [35m[Appium][39m 
[warn] [35m[Appium][39m ======================================================================
[warn] [35m[Appium][39m   DEPRECATION WARNING:
[warn] [35m[Appium][39m 
[warn] [35m[Appium][39m   The 'automationName' capability was not provided in the desired 
[warn] [35m[Appium][39m   capabilities for this Android session
[warn] [35m[Appium][39m 
[warn] [35m[Appium][39m   Setting 'automationName=UiAutomator2' by default and using the 
[warn] [35m[Appium][39m   UiAutomator2 Driver
[warn] [35m[Appium][39m 
[warn] [35m[Appium][39m   The next major version of Appium (2.x) will **require** the 
[warn] [35m[Appium][39m   'automationName' capability to be set for all sessions on all 
[warn] [35m[Appium][39m   platforms
[warn] [35m[Appium][39m 
[warn] [35m[Appium][39m   In previous versions (Appium <= 1.13.x), the default was 
[warn] [35m[Appium][39m   'automationName=UiAutomator1'
[warn] [35m[Appium][39m 
[warn] [35m[Appium][39m   If you wish to use that automation instead of UiAutomator2, please 
[warn] [35m[Appium][39m   add 'automationName=UiAutomator1' to your desired capabilities
[warn] [35m[Appium][39m 
[warn] [35m[Appium][39m   For more information about drivers, please visit 
[warn] [35m[Appium][39m   http://appium.io/docs/en/about-appium/intro/ and explore the 
[warn] [35m[Appium][39m   'Drivers' menu
[warn] [35m[Appium][39m 
[warn] [35m[Appium][39m ======================================================================
[warn] [35m[Appium][39m 
[info] [35m[Appium][39m Appium v1.17.1 creating new AndroidUiautomator2Driver (v1.44.2) session
[debug] [35m[BaseDriver][39m Creating session with W3C capabilities: {
[debug] [35m[BaseDriver][39m   "alwaysMatch": {
[debug] [35m[BaseDriver][39m     "platformName": "Android",
[debug] [35m[BaseDriver][39m     "appium:devicename": "SM M515F",
[debug] [35m[BaseDriver][39m     "appium:appPackage": "com.capitalJ.onjunodev",
[debug] [35m[BaseDriver][39m     "appium:appActivity": "com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity"
[debug] [35m[BaseDriver][39m   },
[debug] [35m[BaseDriver][39m   "firstMatch": [
[debug] [35m[BaseDriver][39m     {}
[debug] [35m[BaseDriver][39m   ]
[debug] [35m[BaseDriver][39m }
[warn] [35m[BaseDriver][39m The following capabilities were provided, but are not recognized by Appium:
[warn] [35m[BaseDriver][39m   devicename
[info] [35m[BaseDriver][39m Session created with session id: 0701d36d-05f1-44bf-8eb0-adab9d153f07
[info] [35m[UiAutomator2][39m Starting 'com.capitalJ.onjunodev' directly on the device
[info] [35m[ADB][39m Using 'adb.exe' from 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe'
[info] [35m[AndroidDriver][39m Retrieving device list
[debug] [35m[ADB][39m Trying to find a connected android device
[debug] [35m[ADB][39m Getting connected devices...[debug] [35m[ADB][39m Connected devices: [{"udid":"RZ8TA00DGFT","state":"device"}]
[info] [35m[AndroidDriver][39m Using device: RZ8TA00DGFT
[info] [35m[ADB][39m Using 'adb.exe' from 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe'
[debug] [35m[ADB][39m Setting device id to RZ8TA00DGFT
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell getprop ro.build.version.sdk'
[debug] [35m[ADB][39m Current device property 'ro.build.version.sdk': 33
[info] [35m[ADB][39m Getting device platform version
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell getprop ro.build.version.release'[debug] [35m[ADB][39m Current device property 'ro.build.version.release': 13
[debug] [35m[ADB][39m Device API level: 33
[warn] [35m[UiAutomator2][39m Relaxing hidden api policy
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell settings put global hidden_api_policy_pre_p_apps 1'[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell settings put global hidden_api_policy_p_apps 1'[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell settings put global hidden_api_policy 1'[warn] [35m[AndroidDriver][39m No app sent in, not parsing package/activity
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT wait-for-device'
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell echo ping'[debug] [35m[AndroidDriver][39m Pushing settings apk to device...
[debug] [35m[ADB][39m Getting install status for io.appium.settings
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell dumpsys package io.appium.settings'[debug] [35m[ADB][39m 'io.appium.settings' is installed
[debug] [35m[ADB][39m Getting package info for 'io.appium.settings'
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell dumpsys package io.appium.settings'[debug] [35m[ADB][39m The version name of the installed 'io.appium.settings' is greater or equal to the application version name ('3.1.0' >= '3.1.0')
[debug] [35m[ADB][39m There is no need to install/upgrade 'C:\Users\hp\AppData\Local\Programs\Appium\resources\app\node_modules\appium\node_modules\io.appium.settings\apks\settings_apk-debug.apk'
[debug] [35m[ADB][39m Getting IDs of all 'io.appium.settings' processes
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell 'pgrep --help; echo $?''[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell pgrep -f io\\.appium\\.settings'[debug] [35m[AndroidDriver][39m io.appium.settings is already running. There is no need to reset its permissions.
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell appops set io.appium.settings android\:mock_location allow'[debug] [35m[Logcat][39m Starting logcat capture[debug] [35m[UiAutomator2][39m Forwarding UiAutomator2 Server port 6790 to 8201
[debug] [35m[ADB][39m Forwarding system: 8201 to device: 6790
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT forward tcp\:8201 tcp\:6790'[debug] [35m[ADB][39m Getting install status for io.appium.uiautomator2.server
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell dumpsys package io.appium.uiautomator2.server'[debug] [35m[ADB][39m 'io.appium.uiautomator2.server' is installed
[debug] [35m[ADB][39m Getting package info for 'io.appium.uiautomator2.server'
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell dumpsys package io.appium.uiautomator2.server'[debug] [35m[ADB][39m The version name of the installed 'io.appium.uiautomator2.server' is greater or equal to the application version name ('4.5.5' >= '4.5.5')
[debug] [35m[UiAutomator2][39m io.appium.uiautomator2.server installation state: sameVersionInstalled
[debug] [35m[ADB][39m Checking app cert for C:\Users\hp\AppData\Local\Programs\Appium\resources\app\node_modules\appium\node_modules\appium-uiautomator2-server\apks\appium-uiautomator2-server-v4.5.5.apk
[info] [35m[ADB][39m Using 'apksigner.jar' from 'C:\Users\hp\AppData\Local\Android\Sdk\build-tools\33.0.1\lib\apksigner.jar'
[debug] [35m[ADB][39m Starting apksigner: 'C:\\Program Files\\Java\\jdk-11.0.16.1\\bin\\java.exe' -Xmx1024M -Xss1m -jar C:\\Users\\hp\\AppData\\Local\\Android\\Sdk\\build-tools\\33.0.1\\lib\\apksigner.jar verify --print-certs C:\\Users\\hp\\AppData\\Local\\Programs\\Appium\\resources\\app\\node_modules\\appium\\node_modules\\appium-uiautomator2-server\\apks\\appium-uiautomator2-server-v4.5.5.apk[debug] [35m[ADB][39m apksigner stdout: Signer #1 certificate DN: EMAILADDRESS=android@android.com, CN=Android, OU=Android, O=Android, L=Mountain View, ST=California, C=US
[debug] [35m[ADB][39m Signer #1 certificate SHA-256 digest: a40da80a59d170caa950cf15c18c454d47a39b26989d8b640ecd745ba71bf5dc
[debug] [35m[ADB][39m Signer #1 certificate SHA-1 digest: 61ed377e85d386a8dfee6b864bd85b0bfaa5af81
[debug] [35m[ADB][39m Signer #1 certificate MD5 digest: e89b158e4bcf988ebd09eb83f5378e87
[debug] [35m[ADB][39m 
[debug] [35m[ADB][39m 'C:\Users\hp\AppData\Local\Programs\Appium\resources\app\node_modules\appium\node_modules\appium-uiautomator2-server\apks\appium-uiautomator2-server-v4.5.5.apk' is signed with the default certificate
[debug] [35m[ADB][39m Getting install status for io.appium.uiautomator2.server.test
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell dumpsys package io.appium.uiautomator2.server.test'[debug] [35m[ADB][39m 'io.appium.uiautomator2.server.test' is installed
[debug] [35m[ADB][39m Checking app cert for C:\Users\hp\AppData\Local\Programs\Appium\resources\app\node_modules\appium\node_modules\appium-uiautomator2-server\apks\appium-uiautomator2-server-debug-androidTest.apk
[debug] [35m[ADB][39m Starting apksigner: 'C:\\Program Files\\Java\\jdk-11.0.16.1\\bin\\java.exe' -Xmx1024M -Xss1m -jar C:\\Users\\hp\\AppData\\Local\\Android\\Sdk\\build-tools\\33.0.1\\lib\\apksigner.jar verify --print-certs C:\\Users\\hp\\AppData\\Local\\Programs\\Appium\\resources\\app\\node_modules\\appium\\node_modules\\appium-uiautomator2-server\\apks\\appium-uiautomator2-server-debug-androidTest.apk[debug] [35m[ADB][39m apksigner stdout: Signer #1 certificate DN: EMAILADDRESS=android@android.com, CN=Android, OU=Android, O=Android, L=Mountain View, ST=California, C=US
[debug] [35m[ADB][39m Signer #1 certificate SHA-256 digest: a40da80a59d170caa950cf15c18c454d47a39b26989d8b640ecd745ba71bf5dc
[debug] [35m[ADB][39m Signer #1 certificate SHA-1 digest: 61ed377e85d386a8dfee6b864bd85b0bfaa5af81
[debug] [35m[ADB][39m Signer #1 certificate MD5 digest: e89b158e4bcf988ebd09eb83f5378e87
[debug] [35m[ADB][39m 
[debug] [35m[ADB][39m 'C:\Users\hp\AppData\Local\Programs\Appium\resources\app\node_modules\appium\node_modules\appium-uiautomator2-server\apks\appium-uiautomator2-server-debug-androidTest.apk' is signed with the default certificate
[info] [35m[UiAutomator2][39m Server packages are not going to be (re)installed
[debug] [35m[UiAutomator2][39m Waiting up to 30000ms for services to be available
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell pm list instrumentation'[debug] [35m[UiAutomator2][39m Instrumentation target 'io.appium.uiautomator2.server.test/androidx.test.runner.AndroidJUnitRunner' is available
[debug] [35m[UiAutomator2][39m No app capability. Assuming it is already on the device
[debug] [35m[ADB][39m Getting install status for com.capitalJ.onjunodev
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell dumpsys package com.capitalJ.onjunodev'[debug] [35m[ADB][39m 'com.capitalJ.onjunodev' is installed
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell am force-stop com.capitalJ.onjunodev'[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell pm clear com.capitalJ.onjunodev'[debug] [35m[AndroidDriver][39m Performed fast reset on the installed 'com.capitalJ.onjunodev' application (stop and clear)
[debug] [35m[UiAutomator2][39m Performing shallow cleanup of automation leftovers
[debug] [35m[UiAutomator2][39m The following obsolete sessions are still running: ["951cf2ed-2a66-45ab-b068-1c3dff21ef0b"]
[debug] [35m[UiAutomator2][39m Cleaning up the obsolete sessions[debug] [35m[Instrumentation][39m .[debug] [35m[Instrumentation][39m Time: 105.104
[debug] [35m[Instrumentation][39m 
[debug] [35m[Instrumentation][39m OK (1 test)
[debug] [35m[Instrumentation][39m The process has exited with code 0[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell am force-stop io.appium.uiautomator2.server.test'[info] [35m[UiAutomator2][39m Starting UIAutomator2 server 4.5.5
[info] [35m[UiAutomator2][39m Using UIAutomator2 server from 'C:\Users\hp\AppData\Local\Programs\Appium\resources\app\node_modules\appium\node_modules\appium-uiautomator2-server\apks\appium-uiautomator2-server-v4.5.5.apk' and test from 'C:\Users\hp\AppData\Local\Programs\Appium\resources\app\node_modules\appium\node_modules\appium-uiautomator2-server\apks\appium-uiautomator2-server-debug-androidTest.apk'
[info] [35m[UiAutomator2][39m Waiting up to 30000ms for UiAutomator2 to be online...
[debug] [35m[ADB][39m Creating ADB subprocess with args: ["-P",5037,"-s","RZ8TA00DGFT","shell","am","instrument","-w","io.appium.uiautomator2.server.test/androidx.test.runner.AndroidJUnitRunner"][debug] [35m[WD Proxy][39m Matched '/status' to command name 'getStatus'
[debug] [35m[WD Proxy][39m Proxying [GET /status] to [GET http://127.0.0.1:8201/wd/hub/status] with no body
[info] [35m[WD Proxy][39m Got response with unknown status: {"code":"ECONNRESET"}[debug] [35m[WD Proxy][39m Matched '/status' to command name 'getStatus'
[debug] [35m[WD Proxy][39m Proxying [GET /status] to [GET http://127.0.0.1:8201/wd/hub/status] with no body
[info] [35m[WD Proxy][39m Got response with unknown status: {"code":"ECONNRESET"}[debug] [35m[WD Proxy][39m Matched '/status' to command name 'getStatus'
[debug] [35m[WD Proxy][39m Proxying [GET /status] to [GET http://127.0.0.1:8201/wd/hub/status] with no body
[info] [35m[WD Proxy][39m Got response with unknown status: {"code":"ECONNRESET"}[debug] [35m[Instrumentation][39m io.appium.uiautomator2.server.test.AppiumUiAutomator2Server:[debug] [35m[WD Proxy][39m Matched '/status' to command name 'getStatus'
[debug] [35m[WD Proxy][39m Proxying [GET /status] to [GET http://127.0.0.1:8201/wd/hub/status] with no body
[info] [35m[WD Proxy][39m Got response with unknown status: {"code":"ECONNRESET"}[debug] [35m[WD Proxy][39m Matched '/status' to command name 'getStatus'
[debug] [35m[WD Proxy][39m Proxying [GET /status] to [GET http://127.0.0.1:8201/wd/hub/status] with no body
[info] [35m[WD Proxy][39m Got response with unknown status: {"code":"ECONNRESET"}[debug] [35m[WD Proxy][39m Matched '/status' to command name 'getStatus'
[debug] [35m[WD Proxy][39m Proxying [GET /status] to [GET http://127.0.0.1:8201/wd/hub/status] with no body[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"None","value":{"ready":true,"message":"UiAutomator2 Server is ready to accept commands"}}
[debug] [35m[UiAutomator2][39m The initialization of the instrumentation process took 6280ms
[debug] [35m[WD Proxy][39m Matched '/session' to command name 'createSession'
[debug] [35m[WD Proxy][39m Proxying [POST /session] to [POST http://127.0.0.1:8201/wd/hub/session] with body: {"capabilities":{"firstMatch":[{"platform":"LINUX","webStorageEnabled":false,"takesScreenshot":true,"javascriptEnabled":true,"databaseEnabled":false,"networkConnectionEnabled":true,"locationContextEnabled":false,"warnings":{},"desired":{"platformName":"Android","devicename":"SM M515F","appPackage":"com.capitalJ.onjunodev","appActivity":"com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity"},"platformName":"Android","devicename":"SM M515F","appPackage":"com.capitalJ.onjunodev","appActivity":"com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity","deviceName":"RZ8TA00DGFT","deviceUDID":"RZ8TA00DGFT"}],"alwaysMatch":{}}}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":{"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","capabilities":{"firstMatch":[{"platform":"LINUX","webStorageEnabled":false,"takesScreenshot":true,"javascriptEnabled":true,"databaseEnabled":false,"networkConnectionEnabled":true,"locationContextEnabled":false,"warnings":{},"desired":{"platformName":"Android","devicename":"SM M515F","appPackage":"com.capitalJ.onjunodev","appActivity":"com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity"},"platformName":"Android","devicename":"SM M515F","appPackage":"com.capitalJ.onjunodev","appActivity":"com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity","deviceName":"RZ8TA00DGFT","deviceUDID":"RZ8TA00DGFT"}],"alwaysMatch":{}}}}
[info] [35m[WD Proxy][39m Determined the downstream protocol as 'W3C'
[debug] [35m[WD Proxy][39m Proxying [GET /appium/device/info] to [GET http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/appium/device/info] with no body[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":{"androidId":"d6922bb2e1d52389","manufacturer":"samsung","model":"SM-E135F","brand":"samsung","apiVersion":"33","platformVersion":"13","carrierName":"STAY AT HOME","realDisplaySize":"1080x2408","displayDensity":450,"networks":[{"type":0,"typeName":"MOBILE","subtype":13,"subtypeName":"LTE","isConnected":true,"detailedState":"CONNECTED","state":"CONNECTED","extraInfo":"ims","isAvailable":true,"isFailover":false,"isRoaming":false,"capabilities":{"transportTypes":"TRANSPORT_CELLULAR","networkCapabilities":"NET_CAPABILITY_IMS,NET_CAPABILITY_NOT_METERED,NET_CAPABILITY_TRUSTED,NET_CAPABILITY_NOT_VPN,NET_CAPABILITY_VALIDATED,NET_CAPABILITY_NOT_ROAMING,NET_CAPABILITY_FOREGROUND,NET_CAPABILITY_NOT_CONGESTED,NET_CAPABILITY_NOT_SUSPENDED","linkUpstreamBandwidthKbps":5474,"linkDownBandwidthKbps":5474,"signalStrength":-2147483648,"networkSpecifier":"TelephonyNetworkSpecifier [mSubId = 1]","SSID":null}},{"type":0,"typeName":"MOBILE","subtype":13,"subtypeName":"L...
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell dumpsys window'[info] [35m[AndroidDriver][39m Screen already unlocked, doing nothing
[info] [35m[UiAutomator2][39m Starting 'com.capitalJ.onjunodev/com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity and waiting for 'com.capitalJ.onjunodev/com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity'
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell am start -W -n com.capitalJ.onjunodev/com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity -S'[debug] [35m[WD Proxy][39m Proxying [GET /appium/device/pixel_ratio] to [GET http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/appium/device/pixel_ratio] with body: {}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":2.8125}
[debug] [35m[WD Proxy][39m Matched '/appium/device/system_bars' to command name 'getSystemBars'
[debug] [35m[WD Proxy][39m Proxying [GET /appium/device/system_bars] to [GET http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/appium/device/system_bars] with body: {}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":{"statusBar":66}}
[debug] [35m[WD Proxy][39m Matched '/window/current/size' to command name 'getWindowSize'
[debug] [35m[WD Proxy][39m Proxying [GET /window/current/size] to [GET http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/window/current/size] with body: {}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":{"height":2207,"width":1080}}
[info] [35m[Appium][39m New AndroidUiautomator2Driver session created successfully, session 0701d36d-05f1-44bf-8eb0-adab9d153f07 added to master session list
[debug] [35m[BaseDriver][39m Event 'newSessionStarted' logged at 1689568983185 (10:13:03 GMT+0530 (India Standard Time))
[debug] [35m[W3C (0701d36d)][39m Cached the protocol value 'W3C' for the new session 0701d36d-05f1-44bf-8eb0-adab9d153f07
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.createSession() result: {"capabilities":{"platform":"LINUX","webStorageEnabled":false,"takesScreenshot":true,"javascriptEnabled":true,"databaseEnabled":false,"networkConnectionEnabled":true,"locationContextEnabled":false,"warnings":{},"desired":{"platformName":"Android","devicename":"SM M515F","appPackage":"com.capitalJ.onjunodev","appActivity":"com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity"},"platformName":"Android","devicename":"SM M515F","appPackage":"com.capitalJ.onjunodev","appActivity":"com.bankonjuno.juno.juno_main_app.views.activities.HomeActivity","deviceName":"RZ8TA00DGFT","deviceUDID":"RZ8TA00DGFT","deviceApiLevel":33,"platformVersion":"13","deviceScreenSize":"1080x2408","deviceScreenDensity":450,"deviceModel":"SM-E135F","deviceManufacturer":"samsung","pixelRatio":2.8125,"statBarHeight":66,"viewportRect":{"left":0,"top":66,"width":1080,"height":2141}}}
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session [39m[32m200[39m [90m25717 ms - 930[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":[]}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements [39m[32m200[39m [90m1034 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":[]}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements [39m[32m200[39m [90m531 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":[]}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.findElements() result: []
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements [39m[32m200[39m [90m161 ms - 12[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":[{"ELEMENT":"d9db9842-4741-4659-a45e-8a4e6b80a582","element-6066-11e4-a52e-4f735466cecf":"d9db9842-4741-4659-a45e-8a4e6b80a582"}]}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.findElements() result: [{"element-6066-11e4-a52e-4f735466cecf":"d9db9842-4741-4659-a45e-8a4e6b80a582","ELEMENT":"d9db9842-4741-4659-a45e-8a4e6b80a582"}]
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements [39m[32m200[39m [90m1146 ms - 139[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mGET[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/element/d9db9842-4741-4659-a45e-8a4e6b80a582/displayed[39m
[info] [35m[HTTP][39m [90m{}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.elementDisplayed() with args: ["d9db9842-4741-4659-a45e-8a4e6b80a582","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[WD Proxy][39m Matched '/element/d9db9842-4741-4659-a45e-8a4e6b80a582/attribute/displayed' to command name 'getAttribute'
[debug] [35m[WD Proxy][39m Proxying [GET /element/d9db9842-4741-4659-a45e-8a4e6b80a582/attribute/displayed] to [GET http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/element/d9db9842-4741-4659-a45e-8a4e6b80a582/attribute/displayed] with body: {}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":"true"}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.elementDisplayed() result: true
[info] [35m[HTTP][39m [37m<-- GET /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/element/d9db9842-4741-4659-a45e-8a4e6b80a582/displayed [39m[32m200[39m [90m186 ms - 14[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/sign_in_btn"}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/sign_in_btn","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/sign_in_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":[{"ELEMENT":"be3b8d13-0b75-42c8-8557-5d8fe400f0a0","element-6066-11e4-a52e-4f735466cecf":"be3b8d13-0b75-42c8-8557-5d8fe400f0a0"}]}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.findElements() result: [{"element-6066-11e4-a52e-4f735466cecf":"be3b8d13-0b75-42c8-8557-5d8fe400f0a0","ELEMENT":"be3b8d13-0b75-42c8-8557-5d8fe400f0a0"}]
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements [39m[32m200[39m [90m107 ms - 139[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/element/be3b8d13-0b75-42c8-8557-5d8fe400f0a0/click[39m
[info] [35m[HTTP][39m [90m{"id":"be3b8d13-0b75-42c8-8557-5d8fe400f0a0"}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.click() with args: ["be3b8d13-0b75-42c8-8557-5d8fe400f0a0","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[WD Proxy][39m Matched '/element/be3b8d13-0b75-42c8-8557-5d8fe400f0a0/click' to command name 'click'
[debug] [35m[WD Proxy][39m Proxying [POST /element/be3b8d13-0b75-42c8-8557-5d8fe400f0a0/click] to [POST http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/element/be3b8d13-0b75-42c8-8557-5d8fe400f0a0/click] with body: {"element":"be3b8d13-0b75-42c8-8557-5d8fe400f0a0"}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":null}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.click() result: null
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/element/be3b8d13-0b75-42c8-8557-5d8fe400f0a0/click [39m[32m200[39m [90m146 ms - 14[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mGET[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/source[39m
[info] [35m[HTTP][39m [90m{}[39m
[info] [35m[W3C (0701d36d)][39m Driver proxy active, passing request on via HTTP proxy
[debug] [35m[WD Proxy][39m Matched '/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/source' to command name 'getPageSource'
[debug] [35m[WD Proxy][39m Proxying [GET /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/source] to [GET http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/source] with body: {}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":"<?xml version='1.0' encoding='UTF-8' standalone='yes' ?>\r\n<hierarchy index=\"0\" class=\"hierarchy\" rotation=\"0\" width=\"1080\" height=\"2207\">\r\n  <android.widget.FrameLayout index=\"0\" package=\"com.capitalJ.onjunodev\" class=\"android.widget.FrameLayout\" text=\"\" checkable=\"false\" checked=\"false\" clickable=\"false\" enabled=\"true\" focusable=\"false\" focused=\"false\" long-clickable=\"false\" password=\"false\" scrollable=\"false\" selected=\"false\" bounds=\"[0,0][1080,2207]\" displayed=\"true\">\r\n    <android.widget.LinearLayout index=\"0\" package=\"com.capitalJ.onjunodev\" class=\"android.widget.LinearLayout\" text=\"\" checkable=\"false\" checked=\"false\" clickable=\"false\" enabled=\"true\" focusable=\"false\" focused=\"false\" long-clickable=\"false\" password=\"false\" scrollable=\"false\" selected=\"false\" bounds=\"[0,0][1080,2207]\" displayed=\"true\">\r\n      <android.widget.FrameLayout index=\"0\" package=\"com...
[info] [35m[WD Proxy][39m Replacing sessionId 3f7225d7-46e3-437c-b85a-91c1579c1842 with 0701d36d-05f1-44bf-8eb0-adab9d153f07
[info] [35m[HTTP][39m [37m<-- GET /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/source [39m[32m200[39m [90m1136 ms - 12075[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/auth_edit_text"}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/auth_edit_text","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/auth_edit_text","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":[{"ELEMENT":"199a7a90-879c-49b6-bef7-77bb50a06935","element-6066-11e4-a52e-4f735466cecf":"199a7a90-879c-49b6-bef7-77bb50a06935"}]}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.findElements() result: [{"element-6066-11e4-a52e-4f735466cecf":"199a7a90-879c-49b6-bef7-77bb50a06935","ELEMENT":"199a7a90-879c-49b6-bef7-77bb50a06935"}]
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements [39m[32m200[39m [90m257 ms - 139[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mGET[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/element/199a7a90-879c-49b6-bef7-77bb50a06935/displayed[39m
[info] [35m[HTTP][39m [90m{}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.elementDisplayed() with args: ["199a7a90-879c-49b6-bef7-77bb50a06935","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[WD Proxy][39m Matched '/element/199a7a90-879c-49b6-bef7-77bb50a06935/attribute/displayed' to command name 'getAttribute'
[debug] [35m[WD Proxy][39m Proxying [GET /element/199a7a90-879c-49b6-bef7-77bb50a06935/attribute/displayed] to [GET http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/element/199a7a90-879c-49b6-bef7-77bb50a06935/attribute/displayed] with body: {}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":"true"}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.elementDisplayed() result: true
[info] [35m[HTTP][39m [37m<-- GET /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/element/199a7a90-879c-49b6-bef7-77bb50a06935/displayed [39m[32m200[39m [90m38 ms - 14[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/auth_edit_text"}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/auth_edit_text","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/auth_edit_text","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":[{"ELEMENT":"4c52f316-1ee6-4398-8c8e-78621c9632a0","element-6066-11e4-a52e-4f735466cecf":"4c52f316-1ee6-4398-8c8e-78621c9632a0"}]}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.findElements() result: [{"element-6066-11e4-a52e-4f735466cecf":"4c52f316-1ee6-4398-8c8e-78621c9632a0","ELEMENT":"4c52f316-1ee6-4398-8c8e-78621c9632a0"}]
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements [39m[32m200[39m [90m142 ms - 139[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/element/4c52f316-1ee6-4398-8c8e-78621c9632a0/click[39m
[info] [35m[HTTP][39m [90m{"id":"4c52f316-1ee6-4398-8c8e-78621c9632a0"}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.click() with args: ["4c52f316-1ee6-4398-8c8e-78621c9632a0","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[WD Proxy][39m Matched '/element/4c52f316-1ee6-4398-8c8e-78621c9632a0/click' to command name 'click'
[debug] [35m[WD Proxy][39m Proxying [POST /element/4c52f316-1ee6-4398-8c8e-78621c9632a0/click] to [POST http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/element/4c52f316-1ee6-4398-8c8e-78621c9632a0/click] with body: {"element":"4c52f316-1ee6-4398-8c8e-78621c9632a0"}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":null}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.click() result: null
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/element/4c52f316-1ee6-4398-8c8e-78621c9632a0/click [39m[32m200[39m [90m203 ms - 14[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/auth_edit_text"}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/auth_edit_text","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/auth_edit_text","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":[{"ELEMENT":"8a4174a3-d2f3-45c3-b228-0a18ba777e80","element-6066-11e4-a52e-4f735466cecf":"8a4174a3-d2f3-45c3-b228-0a18ba777e80"}]}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.findElements() result: [{"element-6066-11e4-a52e-4f735466cecf":"8a4174a3-d2f3-45c3-b228-0a18ba777e80","ELEMENT":"8a4174a3-d2f3-45c3-b228-0a18ba777e80"}]
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements [39m[32m200[39m [90m509 ms - 139[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/element/8a4174a3-d2f3-45c3-b228-0a18ba777e80/value[39m
[info] [35m[HTTP][39m [90m{"text":"juno_moolya@mailinator.com","value":["j","u","n","o","_","m","o","o","l","y","a","@","m","a","i","l","i","n","a","t","o","r",".","c","o","m"],"id":"8a4174a3-d2f3-45c3-b228-0a18ba777e80"}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.setValue() with args: [["j","u","n","o","_","m","o","o","l","y","a","@","m","a","i","l","i","n","a","t","o","r",".","c","o","m"],"8a4174a3-d2f3-45c3-b228-0a18ba777e80","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[WD Proxy][39m Matched '/element/8a4174a3-d2f3-45c3-b228-0a18ba777e80/value' to command name 'setValue'
[debug] [35m[Protocol Converter][39m Added 'value' property ["j","u","n","o","_","m","o","o","l","y","a","@","m","a","i","l","i","n","a","t","o","r",".","c","o","m"] to 'setValue' request body
[debug] [35m[WD Proxy][39m Proxying [POST /element/8a4174a3-d2f3-45c3-b228-0a18ba777e80/value] to [POST http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/element/8a4174a3-d2f3-45c3-b228-0a18ba777e80/value] with body: {"elementId":"8a4174a3-d2f3-45c3-b228-0a18ba777e80","text":"juno_moolya@mailinator.com","replace":false,"value":["j","u","n","o","_","m","o","o","l","y","a","@","m","a","i","l","i","n","a","t","o","r",".","c","o","m"]}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":null}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.setValue() result: null
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/element/8a4174a3-d2f3-45c3-b228-0a18ba777e80/value [39m[32m200[39m [90m651 ms - 14[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/login_next_btn"}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/login_next_btn","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/login_next_btn","context":"","multiple":true}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":[{"ELEMENT":"bccfbd8d-5141-4b6a-8f4d-4b22e1d0fd1a","element-6066-11e4-a52e-4f735466cecf":"bccfbd8d-5141-4b6a-8f4d-4b22e1d0fd1a"}]}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.findElements() result: [{"element-6066-11e4-a52e-4f735466cecf":"bccfbd8d-5141-4b6a-8f4d-4b22e1d0fd1a","ELEMENT":"bccfbd8d-5141-4b6a-8f4d-4b22e1d0fd1a"}]
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements [39m[32m200[39m [90m160 ms - 139[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mGET[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/element/bccfbd8d-5141-4b6a-8f4d-4b22e1d0fd1a/displayed[39m
[info] [35m[HTTP][39m [90m{}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.elementDisplayed() with args: ["bccfbd8d-5141-4b6a-8f4d-4b22e1d0fd1a","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[WD Proxy][39m Matched '/element/bccfbd8d-5141-4b6a-8f4d-4b22e1d0fd1a/attribute/displayed' to command name 'getAttribute'
[debug] [35m[WD Proxy][39m Proxying [GET /element/bccfbd8d-5141-4b6a-8f4d-4b22e1d0fd1a/attribute/displayed] to [GET http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/element/bccfbd8d-5141-4b6a-8f4d-4b22e1d0fd1a/attribute/displayed] with body: {}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":"true"}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.elementDisplayed() result: true
[info] [35m[HTTP][39m [37m<-- GET /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/element/bccfbd8d-5141-4b6a-8f4d-4b22e1d0fd1a/displayed [39m[32m200[39m [90m49 ms - 14[39m
[info] [35m[HTTP][39m [90m[39m[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":[{"ELEMENT":"c87118e4-4292-4f93-bf1b-dcc0cd64e39e","element-6066-11e4-a52e-4f735466cecf":"c87118e4-4292-4f93-bf1b-dcc0cd64e39e"}]}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.findElements() result: [{"element-6066-11e4-a52e-4f735466cecf":"c87118e4-4292-4f93-bf1b-dcc0cd64e39e","ELEMENT":"c87118e4-4292-4f93-bf1b-dcc0cd64e39e"}]
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements [39m[32m200[39m [90m131 ms - 139[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/element/c87118e4-4292-4f93-bf1b-dcc0cd64e39e/click[39m
[info] [35m[HTTP][39m [90m{"id":"c87118e4-4292-4f93-bf1b-dcc0cd64e39e"}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.click() with args: ["c87118e4-4292-4f93-bf1b-dcc0cd64e39e","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[WD Proxy][39m Matched '/element/c87118e4-4292-4f93-bf1b-dcc0cd64e39e/click' to command name 'click'
[debug] [35m[WD Proxy][39m Proxying [POST /element/c87118e4-4292-4f93-bf1b-dcc0cd64e39e/click] to [POST http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/element/c87118e4-4292-4f93-bf1b-dcc0cd64e39e/click] with body: {"element":"c87118e4-4292-4f93-bf1b-dcc0cd64e39e"}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":null}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.click() result: null
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/element/c87118e4-4292-4f93-bf1b-dcc0cd64e39e/click [39m[32m200[39m [90m102 ms - 14[39m
[info] [35m[HTTP][39m [90m[39m[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/auth_edit_text"}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/auth_edit_text","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/auth_edit_text","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":[{"ELEMENT":"1dc2e4ec-15ac-4a42-b7ff-6f120c9645b2","element-6066-11e4-a52e-4f735466cecf":"1dc2e4ec-15ac-4a42-b7ff-6f120c9645b2"}]}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.findElements() result: [{"element-6066-11e4-a52e-4f735466cecf":"1dc2e4ec-15ac-4a42-b7ff-6f120c9645b2","ELEMENT":"1dc2e4ec-15ac-4a42-b7ff-6f120c9645b2"}]
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements [39m[32m200[39m [90m506 ms - 139[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mGET[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/element/1dc2e4ec-15ac-4a42-b7ff-6f120c9645b2/displayed[39m
[info] [35m[HTTP][39m [90m{}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.elementDisplayed() with args: ["1dc2e4ec-15ac-4a42-b7ff-6f120c9645b2","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[WD Proxy][39m Matched '/element/1dc2e4ec-15ac-4a42-b7ff-6f120c9645b2/attribute/displayed' to command name 'getAttribute'
[debug] [35m[WD Proxy][39m Proxying [GET /element/1dc2e4ec-15ac-4a42-b7ff-6f120c9645b2/attribute/displayed] to [GET http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/element/1dc2e4ec-15ac-4a42-b7ff-6f120c9645b2/attribute/displayed] with body: {}
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":"true"}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.elementDisplayed() result: true
[info] [35m[HTTP][39m [37m<-- GET /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/element/1dc2e4ec-15ac-4a42-b7ff-6f120c9645b2/displayed [39m[32m200[39m [90m52 ms - 14[39m
[info] [35m[HTTP][39m [90m[39m[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":[{"ELEMENT":"aad1a654-089b-4704-b890-9960dac9b7d8","element-6066-11e4-a52e-4f735466cecf":"aad1a654-089b-4704-b890-9960dac9b7d8"}]}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.findElements() result: [{"element-6066-11e4-a52e-4f735466cecf":"aad1a654-089b-4704-b890-9960dac9b7d8","ELEMENT":"aad1a654-089b-4704-b890-9960dac9b7d8"}]
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements [39m[32m200[39m [90m88 ms - 139[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/element/aad1a654-089b-4704-b890-9960dac9b7d8/click[39m
[info] [35m[HTTP][39m [90m{"id":"aad1a654-089b-4704-b890-9960dac9b7d8"}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.click() with args: ["aad1a654-089b-4704-b890-9960dac9b7d8","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[WD Proxy][39m Matched '/element/aad1a654-089b-4704-b890-9960dac9b7d8/click' to command name 'click'
[debug] [35m[WD Proxy][39m Proxying [POST /element/aad1a654-089b-4704-b890-9960dac9b7d8/click] to [POST http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/element/aad1a654-089b-4704-b890-9960dac9b7d8/click] with body: {"element":"aad1a654-089b-4704-b890-9960dac9b7d8"}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":null}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.click() result: null
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/element/aad1a654-089b-4704-b890-9960dac9b7d8/click [39m[32m200[39m [90m863 ms - 14[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/auth_edit_text"}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/auth_edit_text","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/auth_edit_text","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":[{"ELEMENT":"40492ff6-2ab5-4fd4-9893-5dbe372c9ad3","element-6066-11e4-a52e-4f735466cecf":"40492ff6-2ab5-4fd4-9893-5dbe372c9ad3"}]}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.findElements() result: [{"element-6066-11e4-a52e-4f735466cecf":"40492ff6-2ab5-4fd4-9893-5dbe372c9ad3","ELEMENT":"40492ff6-2ab5-4fd4-9893-5dbe372c9ad3"}]
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements [39m[32m200[39m [90m222 ms - 139[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/element/40492ff6-2ab5-4fd4-9893-5dbe372c9ad3/value[39m
[info] [35m[HTTP][39m [90m{"text":"Onjuno@123","value":["O","n","j","u","n","o","@","1","2","3"],"id":"40492ff6-2ab5-4fd4-9893-5dbe372c9ad3"}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.setValue() with args: [["O","n","j","u","n","o","@","1","2","3"],"40492ff6-2ab5-4fd4-9893-5dbe372c9ad3","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[WD Proxy][39m Matched '/element/40492ff6-2ab5-4fd4-9893-5dbe372c9ad3/value' to command name 'setValue'
[debug] [35m[Protocol Converter][39m Added 'value' property ["O","n","j","u","n","o","@","1","2","3"] to 'setValue' request body
[debug] [35m[WD Proxy][39m Proxying [POST /element/40492ff6-2ab5-4fd4-9893-5dbe372c9ad3/value] to [POST http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/element/40492ff6-2ab5-4fd4-9893-5dbe372c9ad3/value] with body: {"elementId":"40492ff6-2ab5-4fd4-9893-5dbe372c9ad3","text":"Onjuno@123","replace":false,"value":["O","n","j","u","n","o","@","1","2","3"]}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":null}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.setValue() result: null
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/element/40492ff6-2ab5-4fd4-9893-5dbe372c9ad3/value [39m[32m200[39m [90m1437 ms - 14[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/login_btn"}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/login_btn","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/login_btn","context":"","multiple":true}[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":[{"ELEMENT":"4c740823-b3c7-4717-a33b-dc1738b919d2","element-6066-11e4-a52e-4f735466cecf":"4c740823-b3c7-4717-a33b-dc1738b919d2"}]}
[debug] [35m[W3C (0701d36d)][39m Responding to client with driver.findElements() result: [{"element-6066-11e4-a52e-4f735466cecf":"4c740823-b3c7-4717-a33b-dc1738b919d2","ELEMENT":"4c740823-b3c7-4717-a33b-dc1738b919d2"}]
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements [39m[32m200[39m [90m824 ms - 139[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mGET[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/element/4c740823-b3c7-4717-a33b-dc1738b919d2/displayed[39m
[info] [35m[HTTP][39m [90m{}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.elementDisplayed() with args: ["4c740823-b3c7-4717-a33b-dc1738b919d2","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[WD Proxy][39m Matched '/element/4c740823-b3c7-4717-a33b-dc1738b919d2/attribute/displayed' to command name 'getAttribute'
[debug] [35m[WD Proxy][39m Proxying [GET /element/4c740823-b3c7-4717-a33b-dc1738b919d2/attribute/displayed] to [GET http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/element/4c740823-b3c7-4717-a33b-dc1738b919d2/attribute/displayed] with body: {}[warn] [35m[BaseDriver][39m Shutting down because we waited 60 seconds for a command
[warn] [35m[Appium][39m Closing session, cause was 'New Command Timeout of 60 seconds expired. Try customizing the timeout using the 'newCommandTimeout' desired capability'
[info] [35m[Appium][39m Removing session '84347594-b4dc-427f-97fd-0c9cdb48db67' from our master session list
[debug] [35m[UiAutomator2][39m Deleting UiAutomator2 session
[debug] [35m[UiAutomator2][39m Deleting UiAutomator2 server session
[debug] [35m[WD Proxy][39m Matched '/' to command name 'deleteSession'
[debug] [35m[WD Proxy][39m Proxying [DELETE /] to [DELETE http://127.0.0.1:8200/wd/hub/session/951cf2ed-2a66-45ab-b068-1c3dff21ef0b] with no body
[debug] [35m[WD Proxy][39m Got response with status 200: {"sessionId":"951cf2ed-2a66-45ab-b068-1c3dff21ef0b","value":null}
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell am force-stop com.capitalJ.onjunodev'[debug] [35m[Instrumentation][39m .
[debug] [35m[Logcat][39m Stopping logcat capture
[debug] [35m[ADB][39m Removing forwarded port socket connection: 8200 
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT forward --remove tcp\:8200'
[info] [35m[WD Proxy][39m Got response with status 404: {"sessionId":"3f7225d7-46e3-437c-b85a-91c1579c1842","value":{"error":"stale element reference","message":"Cached elements 'By.id: com.capitalJ.onjunodev:id\/login_btn' do not exist in DOM anymore","stacktrace":"io.appium.uiautomator2.common.exceptions.StaleElementReferenceException: Cached elements 'By.id: com.capitalJ.onjunodev:id\/login_btn' do not exist in DOM anymore\n\tat io.appium.uiautomator2.model.KnownElements.restoreCachedElement(KnownElements.java:59)\n\tat io.appium.uiautomator2.model.KnownElements.getElementFromCache(KnownElements.java:122)\n\tat io.appium.uiautomator2.handler.GetElementAttribute.safeHandle(GetElementAttribute.java:26)\n\tat io.appium.uiautomator2.handler.request.SafeRequestHandler.handle(SafeRequestHandler.java:38)\n\tat io.appium.uiautomator2.server.AppiumServlet.handleRequest(AppiumServlet.java:252)\n\tat io.appium.uiautomator2.server.AppiumServlet.handleHttpRequest(AppiumServlet.java:242)\n\tat io.appium.uiautomator2.http.ServerHandler.channelRead(ServerHandler.java:51)\n\...
[debug] [35m[W3C][39m Matched W3C error code 'stale element reference' to StaleElementReferenceError[info] [35m[WD Proxy][39m Got response with unknown status: {"code":"ECONNRESET"}
[debug] [35m[W3C (0701d36d)][39m Encountered internal error running command: UnknownError: An unknown server-side error occurred while processing the command. Original error: Could not proxy command to remote server. Original error: Error: socket hang up
[debug] [35m[W3C (0701d36d)][39m     at JWProxy.command (C:\Users\hp\AppData\Local\Programs\Appium\resources\app\node_modules\appium\node_modules\appium-base-driver\lib\jsonwp-proxy\proxy.js:266:13)
[info] [35m[HTTP][39m [37m<-- GET /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/screenshot [39m[31m500[39m [90m183 ms - 586[39m
[info] [35m[HTTP][39m [90m[39m
[debug] [35m[Instrumentation][39m Time: 31.091
[debug] [35m[Instrumentation][39m 
[debug] [35m[Instrumentation][39m OK (1 test)[debug] [35m[Instrumentation][39m The process has exited with code 0[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell settings delete global hidden_api_policy_p_apps'[info] [35m[HTTP][39m [37m-->[39m [37mPOST[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements[39m
[info] [35m[HTTP][39m [90m{"using":"id","value":"com.capitalJ.onjunodev:id/button_2_image"}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.findElements() with args: ["id","com.capitalJ.onjunodev:id/button_2_image","0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[BaseDriver][39m Valid locator strategies for this request: xpath, id, class name, accessibility id, -android uiautomator
[debug] [35m[BaseDriver][39m Waiting up to 0 ms for condition
[debug] [35m[WD Proxy][39m Matched '/elements' to command name 'findElements'
[debug] [35m[WD Proxy][39m Proxying [POST /elements] to [POST http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/elements] with body: {"strategy":"id","selector":"com.capitalJ.onjunodev:id/button_2_image","context":"","multiple":true}
[info] [35m[WD Proxy][39m Got response with unknown status: {"code":"ECONNRESET"}
[debug] [35m[W3C (0701d36d)][39m Encountered internal error running command: UnknownError: An unknown server-side error occurred while processing the command. Original error: Could not proxy command to remote server. Original error: Error: socket hang up
[debug] [35m[W3C (0701d36d)][39m     at JWProxy.command (C:\Users\hp\AppData\Local\Programs\Appium\resources\app\node_modules\appium\node_modules\appium-base-driver\lib\jsonwp-proxy\proxy.js:266:13)
[info] [35m[HTTP][39m [37m<-- POST /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/elements [39m[31m500[39m [90m59 ms - 586[39m
[info] [35m[HTTP][39m [90m[39m
[info] [35m[HTTP][39m [37m-->[39m [37mGET[39m [37m/wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/screenshot[39m
[info] [35m[HTTP][39m [90m{}[39m
[debug] [35m[W3C (0701d36d)][39m Calling AppiumDriver.getScreenshot() with args: ["0701d36d-05f1-44bf-8eb0-adab9d153f07"]
[debug] [35m[WD Proxy][39m Matched '/screenshot' to command name 'getScreenshot'
[debug] [35m[WD Proxy][39m Proxying [GET /screenshot] to [GET http://127.0.0.1:8201/wd/hub/session/3f7225d7-46e3-437c-b85a-91c1579c1842/screenshot] with no body[info] [35m[WD Proxy][39m Got response with unknown status: {"code":"ECONNRESET"}
[debug] [35m[W3C (0701d36d)][39m Encountered internal error running command: UnknownError: An unknown server-side error occurred while processing the command. Original error: Could not proxy command to remote server. Original error: Error: socket hang up
[debug] [35m[W3C (0701d36d)][39m     at JWProxy.command (C:\Users\hp\AppData\Local\Programs\Appium\resources\app\node_modules\appium\node_modules\appium-base-driver\lib\jsonwp-proxy\proxy.js:266:13)
[info] [35m[HTTP][39m [37m<-- GET /wd/hub/session/0701d36d-05f1-44bf-8eb0-adab9d153f07/screenshot [39m[31m500[39m [90m57 ms - 586[39m
[info] [35m[HTTP][39m [90m[39m
[debug] [35m[ADB][39m Running 'C:\Users\hp\AppData\Local\Android\Sdk\platform-tools\adb.exe -P 5037 -s RZ8TA00DGFT shell settings delete global hidden_api_policy'
