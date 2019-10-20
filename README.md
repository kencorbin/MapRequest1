# MapRequest1
Demonstrate problem with recent versions of Google Maps app

    Select "Display Treasure Location" from settings.
    This invokes the Google map app to display
    geo:0,0?q=34.99,-106.61(Treasure)
    request as documented in
    https://developer.android.com/guide/components/intents-common
    
    Works properly with Maps version 9.77.5.  Does not work with versions 10.16.7 and 10.27.2
    Instead of displaying the "Treasure" label it shows the GPS coordinates twice.

