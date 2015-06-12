#Open native map application with itinerary


# To do
Allow intent for geo:
http://stackoverflow.com/questions/28913139/why-ng-href-behaving-weird-while-parsing-geo-string

When doing white-listing, take into account that you are replacing the whole regexp, so you need to add the multiple expressions in one, eg:
    $compileProvider.aHrefSanitizationWhitelist(/^\s*(geo|tel):/);
http://stackoverflow.com/questions/15637133/unsafe-link-in-angular

Use geo with query.
https://developers.google.com/maps/documentation/android/intents

Open google with following coordinates:
bar.coordinates.lat
bar.coordinates.lng

Get current coordinates

Plot itinerary

Others
http://stackoverflow.com/questions/15745096/android-phonegap-how-to-open-native-google-maps-application	