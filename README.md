# Electron + React Global Hotkeys POC

0. Clone this repository first and then enter the project folder in the terminal.

1. Install dependencies:
```
npm i
```

2. Run in `development` mode:

```
npm run dev
```


Now, with the app *on focus* or *out of focus*, press Ctrl (or Cmd on mac) + (up or down or left or right arrow).

And look at your terminal (ignore the actual app on the meantime, I need to pass the call into the UI so we can make it interact with `react`).

As you see the global hotkeys are registered and everytime the events are triggered, we need to pass that message to the frontend side of the app and "do something" with it.


# Build to target operating system

Right now, I only added the icon support for mac, in the future I will add support to multiple targets with icons and shit.