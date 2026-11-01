# مختار احمد صابری — نماز ٹائم ویجیٹ

Android home-screen widget with manually selected Pakistani city and daily prayer timings.

## Build
GitHub Actions builds a debug APK on each push to `main`. Open Actions and download the `Mukhtar-Prayer-Widget-APK` artifact from a successful run.

## Install and use
Install the APK, open the app, enter a city in English (for example Lahore or Mandi Bahauddin), save it, then add the widget from Home screen > Widgets.

## Prayer data
Timings are requested from the AlAdhan city-timings API (calculation method 1). Internet is needed for refresh. Local mosque timetables can differ; verify with your local mosque. The app asks only for internet permission and does not request precise location. Android may delay background refresh due to battery scheduling.
