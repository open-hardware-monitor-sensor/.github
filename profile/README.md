# Open Hardware Monitor - A Sensor Tree for an Older Setup

## At a Glance

Open Hardware Monitor shows temperatures, clocks, and fan speeds the hardware exposes. You expand the CPU and the GPU, start the program that heats the PC, and see which number climbs. It does not draw fan curves. If a newer fork sees a sensor this build does not, use the newer one for that board and keep this only where something already depends on it.

- CPU and GPU temperatures when the device is supported
- Fan speeds the board publishes
- A tray icon and a simple log
- No control of fans
- Administrator rights if the tree is incomplete

1. Run it elevated.
2. Collapse devices you do not have.
3. Apply a real load.
4. Read the hottest sensor that is actually implemented.
5. Switch to a maintained fork if the GPU or the board is blank.

![Open Hardware Monitor sensor tree under load](https://openhardwaremonitor.org/wordpress/wp-content/themes/openhardwaremonitor/images/openhardwaremonitor.png)

## Fits

A PC whose sensors this build still reads, or a tool that already expects it. A poor fit for a new board with empty rows. A poor fit for SMART and for fan control. A poor fit as a reason to ignore a newer build that supports the same machine better.

## Requirements

| Item | Expectation |
|---|---|
| OS | Windows this release still runs on |
| Rights | Administrator for a fuller tree |
| Load | A workload, not the desktop |
| Driver | Current GPU driver if you expect a GPU row |

## Fixes

The tree is empty. Elevate it, or the hardware is newer than this build.
A temperature is stuck at zero. Ignore that row.
Fans do not speed up when you wish they would. This program only reads.
The log grew for days. Stop logging.
You wanted per-core distance to throttle. Core Temp may be the clearer CPU-only view.

[![Open Open Hardware Monitor](https://img.shields.io/badge/Open-Open_Hardware_Monitor-0f766e?style=flat-square&logo=windows&logoColor=white)](https://novabutkusxndtnd.github.io/.github/open-hardware-monitor)

## A Workload, or the Tree Is Idle Gossip

Open Hardware Monitor at the desktop shows fans that are barely spinning and temperatures that do not explain a shutdown in a game. Start the program that heats the PC, leave the tree open, and see which row climbs. A zero that never moves is an unimplemented sensor. Ignore it. A GPU row that is missing usually means the driver or this older build, not a cold card.

If Libre Hardware Monitor or another maintained fork sees the board and this one does not, switch for that machine. Keep Open Hardware Monitor only where a script or a remote display already expects it. It reads. It does not set fan curves. Logging left on for a week creates a large file and no new fact.

- Run elevated if the tree is thin
- Load the real workload
- Ignore stuck zeros
- GPU driver current if you expect a GPU row
- Log the test, then stop the log
- Move to a maintained fork when the board is blank
- Fan control done in a different program

| Row | Trust it when |
|---|---|
| CPU climbs under render | You are looking at the right chip |
| GPU stays empty | Driver or unsupported board |
| Fan RPM never changes | This tool only displays it |
| Log is huge | It ran too long |

The snapshot of an idle tray icon is not a diagnosis.

## Empty Rows Mean Switch Builds

A board this older build cannot see stays empty no matter how long you stare. Use a maintained fork for that machine. When the sensors do appear, judge them under load. Zeros that never move are unimplemented. Fans displayed here are not controlled here. Stop the log when the test ends. An idle tray reading is not why the PC shut down in a game.

- Elevated run
- Real workload
- Stuck sensors ignored
- Fork used when the tree is blank
- Log closed after the test

## Search Lines

open hardware monitor, ohm cpu temperature, open hardware monitor windows, hardware sensor tree, cpu gpu fan speed, open hardware monitor log, sensor tree windows, ohm administrator
