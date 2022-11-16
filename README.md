# Exam Timer
Exam Timer is a low frequency timer that aims to be simple and avoid distractions. 
The timer features a sound effect and visual effect once the exam is complete.
Disable the visual effect by turning on prefer reduce motion via browser settings or system settings.
## NOTE
Most modern browsers require the enablement of autoplay or sound for the timer sound effect to work. Firefox should show a permission popup. Set 'sound' to allow in Chromium browsers. Safari is unsupported.
## Usage
The timer will automatically use a 90 minute duration. 
To set a custom duration, use URL parameters. 
The default URL once fully loaded looks like so:
```
https://will-lol.github.io/examtimer/?minutes=90
```
The URL takes one parameter, minutes. It supports fractional amounts of minutes. For example, if you wanted to test the timer:
```
https://will-lol.github.io/examtimer/?minutes=0.1
```

There is no other configuration needed for this app. If you wish to customise the app, I suggest you look through the code, all contained in the single index.html file. 
## Configuring the timer to your liking
See the comments provided in the index.html file.

## Libraries used
canvas-confetti: https://www.npmjs.com/package/canvas-confetti 
