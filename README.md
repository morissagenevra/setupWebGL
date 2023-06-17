# setupWebGL
How to set up WebGL spoofing in Kameleo?
WebGL spoofing settings in Kameleo
You have three options to set the WebGL in Kameleo.

You can turn off the WebGL spoofing. In this case, the browser will see your original device’s values. If you manage several accounts, they will have the same WebGL hash.

kameleo-webgl-off.png
You can set it to Block. It will completely disable the WebGL functions. It can be suspicious because most internet users are not blocking it.

kameleo-webgl-block.png
You can set it to Noise. In this case, every profile will have different hashes.

kameleo-webgl-noise.png
WebGL metadata settings in Kameleo
If you click on More on the Device panel, then you can set the WebGL metadata manually.

kameleo-webgl-settings.png
Here you can set up the Unmasked Vendor and Unmasked Renderer based on your interest.

kameleo-webgl-metadata.png
It can make your overall fingerprint a bit inconsistent if you choose it carelessly. If you leave on Automatic, then the metadata comes from the Basic profile, which is recommended.

WebGL spoofing in global settings
You can also set up a default WebGL spoofing value and WebGL metadata in the global settings. These values will be applied automatically when a new profile is created.

kameleo-webgl-global-settings.png
