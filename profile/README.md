# ParkControl - Turn Core Parking On or Off for a Plan

[![Open ParkControl](https://img.shields.io/badge/Open-ParkControl-334155?style=flat-square&logo=windows&logoColor=white)](https://novabutkusxndtnd.github.io/.github/parkcontrol-power)

## At a Glance

Core parking lets Windows leave some cores in a deeper idle state. That is reasonable on battery and sometimes noticeable in short tasks on a desktop. ParkControl makes the on/off choice visible per power plan. It does not overclock and it does not change the cooler. A plan set to High performance in Windows may still park until you look.

- The active power plan named on screen
- Parking enabled or disabled as a reversible switch
- A separate choice if you want Bitsum's higher-rate timer features, which you can leave off
- No effect on a GPU bottleneck
- A laptop that should usually keep parking on battery

1. Note the plan you are on.
2. Disable parking only for the plugged-in desktop plan you want to test.
3. Use the PC for the task that felt slow.
4. Watch temperatures.
5. Re-enable parking if the difference was heat.

## Fits

Desktops where you want a clear parking switch. A poor fit for chasing game FPS that a GPU graph already explains. A poor fit for a laptop on battery. A poor fit if several power utilities are installed. One of them should own the plan.

## Requirements

| Item | Expectation |
|---|---|
| OS | Windows Bitsum still supports |
| Plan | One you can identify |
| Test | A task you can repeat |
| Heat | Checked after the change |

![ParkControl showing core parking for the active power plan](https://bitsum.com/wp-content/uploads/parkcontrol_screenshot_dark.png)

## Fixes

The slider does nothing. You edited a plan you are not using.
The PC is louder. Parking was saving heat. Turn it back on.
Another tool resets it. Remove the duplicate power utility.
Games are unchanged. The limit was not parking.
You enabled extra timer features you do not understand. Turn those off and keep only the parking test.

## The Plan You Are Actually On

ParkControl edits parking for a power plan. If you change Balanced while the PC is on High performance, nothing you feel will match the slider. Read the active plan, disable parking only for the plugged-in desktop test, and repeat the task that felt slow. Watch heat. A laptop on battery should usually keep parking. A game that is GPU-bound will not gain frames because cores are unparked.

Bitsum's extra timer options can stay off. The test is parking, not a bundle of scheduler tweaks you cannot name. If another power utility is installed, it will overwrite this one. Keep a single owner of the plan.

- Active plan identified first
- One change, then the same task
- Parking restored if the result is only noise and heat
- Laptop battery left on the saving plan
- Extra timer features left off
- Duplicate power tools removed
- GPU-bound games not blamed on parking

| After the change | Meaning |
|---|---|
| Task feels the same, PC is louder | Turn parking back on |
| Desktop latency improves | Keep it on this plan only |
| Slider seems dead | You edited the wrong plan |
| Setting returns | Another utility rewrote it |

Parking was a power feature. Turning it off is allowed. It is not a free speed button.

## Heat Is Part of the Result

Unparking cores on a desktop can remove a little latency and add fan noise. If the task you timed did not improve, turn parking back on. Laptops on battery should keep it. GPU-bound games will not gain frames. Edit the plan that is actually active. Extra timer features stay off so the only change is parking. A second power utility will undo the slider. Remove that duplicate.

- Active plan read first
- One timed task
- Parking restored when the gain is noise
- Battery plan left alone
- One utility owns the plan

## Naming Notes

parkcontrol, bitsum parkcontrol, core parking windows, parkcontrol power, disable core parking, parkcontrol high performance, cpu parking desktop, parkcontrol windows
