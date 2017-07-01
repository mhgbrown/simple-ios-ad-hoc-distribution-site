# Simple iOS Ad Hoc Distribution Site

A simple site for the ad doc distribution of an iOS app ready for deployment on Heroku. Based on this [Ad Hoc iOS distribution website starter](https://github.com/YouYue123/iOS-Adhoc-Distribution).

## Motivation

Distributing an iOS app is pretty painful in current world.

There are 3 ways to distibute your app.

  1. AppStore & TestFlight
  2. Ad Hoc
  3. Install directly with your Mac

Using [Appstore](https://developer.apple.com/library/content/documentation/IDEs/Conceptual/AppDistributionGuide/SubmittingYourApp/SubmittingYourApp.html#//apple_ref/doc/uid/TP40012582-CH9-SW1) to distribute your app is the most common and recommended way but also very painful to wait for the reviewing.

Sometimes we just want to show our app to friends and let them try first. You don't want to take your Macbook to visit every friend you want to impress with your new app.

Ad Hoc would be the best way for you to share your app with your friends.

## Prerequisites

For Ad Hoc distribution, you need to sign your app using one of the following way.
  1. Enterprise Distribution Certificates
  2. Developer Distribution Certificates with [adding your friends UDID](https://developer.apple.com/library/content/documentation/IDEs/Conceptual/AppDistributionGuide/MaintainingProfiles/MaintainingProfiles.html)

After signing your app, by following [this process](https://developer.apple.com/library/content/documentation/IDEs/Conceptual/AppDistributionGuide/TestingYouriOSApp/TestingYouriOSApp.html#//apple_ref/doc/uid/TP40012582-CH8-SW1), you will get an ipa file and a mainfest file.

## Usage
1. Download the starter code here
2. change config.js as yours
```javascript
const config = {
  APP_NAME: 'Accountability',
  WEB_URL: 'https://your-site.herokuapp.com'
}
```
3.replace the ipa and mainfest file in folder app/


