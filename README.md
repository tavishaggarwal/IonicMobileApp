# IonicMobileApp

Starting with starter ionic app "ionic start conFusion sidemenu"

We can create mobile apps using four different ways:
- Native - C#, Swift and Java
- cross compiled - Xamirin C#
- Web Based - PhoneGAp, Cordova, Ionic, AngularJS
- Javascript runtime - ReactJS, NativeScript, Titanium

- To start with ionic choose any available template and start your ionic app.
Command: ionic start myapp [template]
Available templates: sidebar, tabs, blank

- Once the app is ready inorder to deploy it:
ON MAC:
We need xcode install, and then:
Commands: npm install -g ios-sim, ionic platform add ios, ionic build ios, ionic emulate ios

ON ANDROID:
Commands: ionic platform add android,  ionic build android, ionic emulate android, ionic run android

Cordovo provides various plugins to achieve native capabilities through JS API.