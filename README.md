# Speaker Keep-Alive

A free Windows app that keeps powered speakers awake, so sound starts the instant you press play.

**[Download the latest version](https://github.com/natepoehler-collab/speaker-keep-alive/releases/latest)**

## The problem

Many powered speakers and studio monitors switch themselves into standby after a few minutes of silence. When sound comes back they take a second or two to wake, so you lose the first note of a song, the first word of a video, or the notification you were waiting for.

## What it does

Speaker Keep-Alive plays a very short, very quiet tone on a timer. You set the tone low enough that you can't hear it, and the speakers still see a signal and stay awake.

- **You choose the tone.** Frequency from 20 Hz to 1 kHz, and a level you tune down until you can't hear it.
- **You choose the timing.** A pulse every 5 seconds up to every 2 hours. About half your speakers' standby timeout is a good place to start.
- **It stays out of the way.** It lives in the notification area by the clock. Closing the window hides it and the pulses keep going. Right-click the icon and choose Quit to stop it.
- **No clicks or pops.** Each pulse fades in and out, so there is nothing sharp to hear.
- **A built-in meter** shows when the app is producing sound, so you can see that it's working.

## What it will run on

| | |
|---|---|
| Runs on | Windows 10 and Windows 11, 64-bit |
| Does not run on | Mac, Linux, Windows 8.1 or older, 32-bit Windows |
| Download size | About 100 MB |
| Admin rights | Not needed. It installs for your user account only. |
| Internet | Not needed. It doesn't connect to anything. |

## Installing

1. Download `Speaker Keep-Alive Setup` from the [latest release](https://github.com/natepoehler-collab/speaker-keep-alive/releases/latest).
2. Run it. Windows will probably show a blue box that says "Windows protected your PC". That appears because this is a free app without a paid code-signing certificate. Click **More info**, then **Run anyway**.
3. Open Speaker Keep-Alive, set the tone and timing, and click **Start keep-alive**.

## Good to know

- It doesn't start by itself after a restart. Open it again when you want it.
- If the PC sleeps, the pulses stop, and the speakers can go to standby.
- The meter shows sound leaving the app. It can't tell whether Windows is muted or sending audio to a different device.

## Freeware

Speaker Keep-Alive is freeware. It's free to download and use, at home or at work, with no license fee and no sign-up. It's provided as-is, with no warranty.

Built by [Nate Poehler](https://n8poehler.com).
