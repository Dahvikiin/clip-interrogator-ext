# CLIP Interrogator extension for Stable Diffusion WebUI
I made this fork just to solve a problem I had with my version of ‘transformers’ but then I added some buttons, maybe someone will find it useful.
This extension adds a tab for [CLIP Interrogator](https://github.com/pharmapsychotic/clip-interrogator)



![Interrogator tab screenshot](https://github.com/Dahvikiin/clip-interrogator-ext/blob/main/images/lebobo-screen.png)


## Installing

* Go to extensions tab
* Click "Install from URL" sub tab
* Paste `https://github.com/Dahvikiin/clip-interrogator-ext` and click Install
* Check in your terminal window if there are any errors (if so let me know!)
* Restart the Web UI and you should see a new **Interrogator** tab


## Changes

* Revert to CLIP Interrogator 0.6.0
* No more "The size of tensor a (8) must match the blablabla..." error
* Works with `transformers>=4.26.0,<=4.29.2`
* Added "send to..." buttons
* Added Test Setup details and information
