# F1LiveTimingDataGuide

A guide to the F1 Live Timing data via Multiviewer. 

## Clock
Accessible via `api/v2/live-timing/clock`

Example output:
```
{
    "paused": false,
    "liveTimingStartTime": 1656853260011,
    "systemTime": 1677376855446,
    "trackTime": 1656864738104
}
```
Paused indicates if the session timer has been paused or not; Possible outputs: `true, false`
liveTimingStartTime is the start time of the live timing in epoch.
systemTIme is 
