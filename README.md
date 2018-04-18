# Mario4k #

<img src="/screenshot.png" width="500" height="300">

My work here is a fork of https://github.com/klinker41/android-dreamscene by Klinker, but subsitutes Mario images.

Mario4k is a simple Android TV app that acts very similar to the default screensaver that displays nature images along with the clock and a Chromecast hint. The main difference being that this app uses 4k images targeted at Nvidia Shield on 4k displays.

## Setup ##

To enable the service, go into the Screen Saver section of settings and choose Mario4k instead of Backdrop.

## Adding More Wallpapers ##

Mario4k pulls all images from the JSONArray in ```backgrounds.json``` when it starts. This means that to add new images, you don't need to update the app since the values aren't hardcoded. Feel free to add more to the file and submit a pull request and I will check them out and approve them if I like them. Images must be 3840x2160 resolution.

---

## License

    Copyright (C) 2015 Jacob Klinker

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
