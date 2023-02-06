# cerboGX-nodeRED-night-flow

<img src="/cerboGX-nodeRED-night-flow1.png" alt="screenshot" title="screenshot">

This flow is written to control the display on a CerboGX using Node-RED. It sets the display to turn on for 60 seconds at sunset and remain on full time at sunrise. If Node-RED is already installed locally on the device, the ssh module is not necessary.

Requirements:

node-red-contrib-cb-suncron
node-red-contrib-ssh-v3
signalk/node-red-embedded
