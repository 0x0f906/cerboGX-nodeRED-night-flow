<h1>cerboGX-nodeRED-night-flow</h1>
<img src="/cerboGX-nodeRED-night-flow1.png" alt="screenshot" title="screenshot">
<p>This flow is written to control the display on a CerboGX using Node-RED. It sets the display to turn on for 60 seconds at sunset and remain on full time at sunrise. If Node-RED is already installed locally on the device, the ssh module is not necessary.</p>
<p>Requirements:</p>
<ul>
  <li>node-red-contrib-cb-suncron</li>
  <li>node-red-contrib-ssh-v3</li>
  <li>signalk/node-red-embedded</li>
</ul>
