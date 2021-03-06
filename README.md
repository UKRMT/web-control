# KATS OpenMCT Interface
This is the web interface used by the Kentucky AstroRobotic Terrain Systems Club at the University of Kentucky for the monitoring and controlling of our robot.

It is based on [NASA's OpenMCT](https://github.com/nasa/openmct-tutorial)

## Installing

```
git clone https://github.com/ukrmt/web-control.git
cd web-control
npm install
cd node_modules/openmct
npm install
npm run prepare
```

This will clone the site source and install the OpenMCT dependency. Then you must install and configure OpenMCT's dependencies with the past two commands.

## Note
The historical telemetry server currently depends on a working php installation to create example data to be plotted. 

The [TelemServer](https://github.com/UKRMT/MarsBotControl/tree/master/TelemServer) must be running on the server for realtime data to be available over websockets.
