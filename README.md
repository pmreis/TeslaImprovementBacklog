# Tesla Improvement Backlog

A repository containing a checklist of issues and features that would improve Product Quality or User Experience.

## Backlog

- [ ] Restore USB playback after sleep state if USB was the selected audio source before sleeping.
- [ ] Perform audio search on USB and not just on Spotify.
- [ ] When playing from USB, touching the music card should select the current track on the respective folder of the USB device.
- [ ] Implement gapless playback for USB audio [[1]](#note-1).
- [ ] Make speed-sensitive volume a configurable option again, or turn it off by default.
- [ ] Some vehicles don't have the option to select the temperature for activating Cabin Overheat Protection [[2]](#note-2).
- [ ] Navigation should zoom-in in places with lots of intersections and if the suggested path requires a turn on any of those intersections. Zoom level (or map scale) should be enough to make every intersection distinguishable on the screen. What is "a lot of intersections"? Let's assume any 10 meter stretch of road with more than one intersection [[3]](#note-3).
- [ ] Multi-language recognition on voice commands [[4]](#note-4).
- [ ] Reduce phantom braking in particular cases [[5]](#note-5).
- [ ] Fix wipers turning on for no apparent reason. Seems to be caused by sunlight coming through tree foliage and hitting the windscreen.
- [ ] Make Enhanced Autopilot and Full Self-Driving available as subscriptions.
- [ ] Support for voice commands should be equal on all supported languages [[6]](#note-6).
- [ ] Switch off the interior lights (both dome and ambient lights) if the car is locked, no one is sitting on the inside and dog/camp mode is inactive.
- [ ] Add fold/unfold mirrors to the shortcut list of the left scroll wheel.
- [ ] Fix navigation ignoring certain roads [[7]](#note-7).
- [ ] Allow turning off the wipers when on Autopilot [[8]](#note-8).
- [ ] Add option to turn off wireless phone charging.
- [ ] Allow turning off air flow for the passenger side alone.

# Notes

## Note 1
Not having gapless playback is like being dragged out of the zone everytime playback moves to the next track on the album.

## Note 2
Difference in software feature support. If these are caused by hardware changes then it should be made clear for owners through the manual or some other official documentation.

## Note 3
Here is an example of a main road (R. Direita) traversing a small village. Notice the 3 interceptions in just 10.62 meters stretch of the main road. In Europe, some roads were built by Romans who traveled using horses more than 2000 years ago. Roads that narrow are usually tightly packed in some areas.

![horseRoads](note-3.jpg)

## Note 4
Imagine having the infotainment set to Portuguese and then using the voice command "Ligar para Elon Musk", which means "Call Elon Musk", and instead of the desired outcome, the command "Ligar / Call" is recognized but the name is not, resulting in gibberish.
Conversely, assuming the infotainment is set to English and the vehicle is traveling in Portugal, when the voice command "Navigate to Ericeira" is issued, a similar gibberish result will happen.

This also happens with Google Maps, by the way!

- Interpretation failing (Ligar para Elon Musk): https://youtube.com/shorts/TKKCOxPPl0A
- Interpretation failing (Navigate to Ericeira): https://youtube.com/shorts/3dkkxvKyq8I
- Working correcly (Navegar para Ericeira): https://www.youtube.com/shorts/4RrTzKC0dNc

## Note 5
Phantom braking seems to be related to quickly passing from a bright area to a dark area. This is always the case with in this place: https://goo.gl/maps/UntGW1vgpS67g95L9 (Google Street View), https://goo.gl/maps/YtuBvAwzYKCu4791A (Pin / Placemark), or simply the coordinates 38.75756188349858, -9.171885145989462.

 Notice the reflective signs on the side of the bridge slightly facing downwards to the vehicles. Soon after, a very dark shadow cast by the bridge.

![horseRoads](note-5.jpg)

## Note 6
There are missing commands in Portuguese when compared with the available commands in English. For example, unfolding mirrors (abrir espelhos) is not supported, but folding mirrors (fechar espelhos) is supported. 
Another example: all the voice commands for showing a settings page, e.g. lights, locks, display, won't work in Portuguese.

## Note 7
Some roads on the map coverage are completly ignored by navigation. There is no clear pattern on why some roads are ignored, but I leave an example below for this road: https://goo.gl/maps/iC1AYiaTJsKaaXvu8.

> Already on the ignored road and navigation suggests turning back. This is an asphalt road.
![ignoredRoad1](note-7_1.jpg)

> More detailed location for Google Maps comparison.
 ![ignoredRoad2](note-7_2.jpg)

> Road is considered by Google Maps navigation.
 ![ignoredRoad2](note-7_3.jpg)

 ## Note 8
 When the windshield is dirty (specially with bugs), activating the Autopilot also activates the wipers on full speed. This behaviour does not contribute to safety and damages the wiper blades. Previous software versions allowed turning off the wipers with the Autopilot on. Also, this behaviour is inconsistent with auto high-beams, which can be turned off after being activated by Autopilot.