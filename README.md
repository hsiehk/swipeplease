# swipeplease

This is a project to observe how swiping on handheld touchscreen devices affect your median nerve.
The website's purpose is to track the change of the user's thumb while performing a scroll motion on the screen.

Website opens in browser of touchscreen device (IOS/Android) and records finger placement relative to the bounding box and time from initial touch, continuous touch, to end touch.

Uses Google Sheets API to record and document each swipe location and time - info is then used to calculate swipe speed and swipe stroke.
Using video frame analysis, the change in grip strength can be calculated.
A decrease in swipe speed or swipe stroke would infer the cyclic loading of the muscles has caused fatigue.

More information on the study can be seen here:
https://kenthsieh.wixsite.com/website/smartphone-use-median-nerve
