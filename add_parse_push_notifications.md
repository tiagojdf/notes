#Add parse push notifications

### How to generate the .certSigningRequest?

For push notifications you will need your csr. If you have erased the file a long time ago, have no fear, you can always generate a new one as follows:
http://stackoverflow.com/questions/12415801/osx-keychain-access-generate-csr-from-existing-private-key-for-apns-apple-push

After all is done, check if the provisioning profile is invalid or not. If so, go to Xcode, preferences account and refresh.

###How to add a framework to a plugin?



Backend
https://parse.com/docs/ios/guide#push-notifications
Check how to personalize push (title, alert, ...)
https://parse.com/questions/send-a-push-notification-to-one-installationid-from-javascript-sdk
Check what post to parse you need to do
https://parse.com/docs/rest/guide/#push-notifications-using-advanced-targeting

Guzzle
https://github.com/misd-service-development/guzzle-bundle/blob/master/Resources/doc/index.md
