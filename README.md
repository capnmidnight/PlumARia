# PlumARia
Augmented Audio Reality Device

# Description

PlumARia a wearable, hands-free, audio-only, augmented-reality computer system. Using environment, gesture, and speech recognition, PlumARia creates 3D, interactive objects around the user, sensed through touch and sound.

Through the combination of comfortable form-factor and the lack of energy-hungry display, PlumARia enables all-day use, to integrate seemlessly into your life.

# Notes

## Slack Log

**@Sean McBeth**
I've had this idea for a while, and I'm interested in collaborating on it. It's basically a wearable, audio-only computer system, with augmented reality features.

You'd have a hand gesture based interface, with large, virtual buttons around your body. A tracking camera on the back of your head would fix your position, and something like a Leap Motion on your chest would do the hand recognition.

Audio feedback cues would help anchor the position of the buttons in your body space.

Add a GPS system and you could do things like "follow the beep" for walking directions.

I've worked with speech recognition systems to make command menus before and they can be pretty good.

If you could learn how to use a screen reader like a blind person does, you could even browse the web

But I'm more interested in ideas of things you could do with such a system that wouldn't really be possible with a different UI. Like, it's ultimately a hands-free, eyes-free system, so things like automatic language translation are interesting to me, as are musical instruments and communication systems.

I think it'd be really cool to have voice turned to text, transmitted in real time between users, translated between languages, converted back to sppech, and then spatialized like the person is sitting next to you.

Or multiple people in a space (real or virtual), all playing virtual instruments in a band together, all able to hear each other in real time.

Maybe couple it with a simple, haptic feedback device on the wrist or finger tip to help with UI interactions

But ultimately, take the ideal of devices like the magic leap or HoloLens and get rid of all the visible parts of it, get the weight off the head, and add an all-day battery (which should be easy without needing a GPU)

I'm actually thinking I want to take a design-first approach to the project. Usually when I start a project, it's because I'm trying to figure out if it's even possible, but I already know the hardware and software are doable. So I'm thinking the first thing to do on this project is to come up with a set of designs in need of validation. Because it's the design part that needs the figuring out.

Primarily, I think interaction design is going to be the hardest, but I think product design is also a ripe field here. Because there is no display, it opens up a huge opportunity to incorporate the system into fashion wear, I think. I sort of imagining something like a cowl that people wear all year round, not just in the winter. It could be the primary structural component, where all the heavy battery and compute lives, keeping the weight off of the head, allowing for much longer term use.

One of the problems with current AR systems is that they are too invasive and burn too much battery to be usable all day. And because we don't use them all day, we never learn new modalities of use.

There's also room to eventually iterate to a hooded cowl, from which perhaps a proper wave guide display could be hung. Hooded cowl could also incorporate brain waves sensing devices, with the potential to develop biofeedback applications like anxiety and blood pressure warnings.

**@jackalope**
There's been some similar ui ideas with audio only based wearables; smart glasses they're usually called. Harry has some IBM glasses for prototyping.

They generally use voice instead of gesture. So hooking up a magic leap to that might work.

So the parameters of defining a proof of concept here for this product is:
Use audio cues in space to signal some kind of ui information which can be interacted with by gesture, right?
I think getting a button in space that one presses to launch an app would fit the bill there right?

**@Sean McBeth**
Maybe a really simple app would be a button to your periphery that punching or tapping or something would then give you the weather and any calendar entries you have for the next X hours.

As far as that proof of concept you mentioned, the hardware and software would be something I could put together in about a week or two.

**@jackalope**
Yeah I think getting the proof of concept working would be a good start.
What kind of deliverables were you hoping for from design on this?

**@Sean McBeth**
Short-term, a Website with concept description, a few design treatments for working up into tests, a project site for managing collaboration on the project. Longer term, a collection demos testing the designs, a start on a few apps, and maaaaaybe a Kickstarter?

**@lauren**
it would be fun to try that out as a drum circle type thing, maybe have a bongo or two you could play with your hand, with different percussion sounds to choose from. it could be really fun as more styles of gesture are picked up. i wonder how the abilities of using video recognition would compare to this type of tech https://mimugloves.com/#glover-feature

image recognition could also be fun - being able to link different objects you choose to specific sounds when they're touched, shaken or pointed at

**@Sean McBeth**
yeah, that'd be really cool. A combination of music performance and dance.

**@m-ezekiel**
I have long dreamed of using behavioral biometrics for activity recognition supporting creative and self-directed learning contexts.  This is what I did for undergraduate research. (link-to-pdf)

## Links

 - [Microsoft Soundscape](https://www.microsoft.com/en-us/research/product/soundscape/)
 - [Mimu Glove](https://mimugloves.com/)

## Parts

 - Compute: TBD
  - [CHUWI LarkBox](https://www.amazon.com/dp/B089QGYGP2)
  - [Gmk NucBox](https://www.amazon.com/dp/B08KZNSR74)
  - [Intel NUC 8](https://www.amazon.com/dp/B07GX67SBM?th=1)
  - [Beelink U57](https://www.amazon.com/dp/B0872S365N)
  - [LattePanda](https://www.amazon.com/dp/B01ID4HYE4)
  - Android phone?
  - iPhone?
 - Battery:
  - TBD (the specific choice of compute system will change the battery requirements).
 - Positional Tracking:
  - [Intel RealSense Tracking Camera T265](https://www.intelrealsense.com/tracking-camera-t265/).
  - ARKit/ARCore?
 - Gesture Tracking: 
  - [Leap Motion Controller](https://www.ultraleap.com/product/leap-motion-controller/)
  - [Ultraleap Stereo IR 170](https://www.ultraleap.com/product/stereo-ir-170/).
 - Audio Input/Output:
  - 3.5mm headset
  - Bluetooth headset
  	- [AfterShokz OpenComm](https://www.amazon.com/dp/B08DW2SJCQ)
 - GPS: 
  - [G72](https://www.amazon.com/dp/B07SMRXSC8)
  - [vk172](https://www.amazon.com/dp/B01MTU9KTF)
 - Modem:
  - [Verizon Wireless 4G LTE USB Modem](https://www.amazon.com/dp/B0069RXK9G)
  - [ZTE MF833V](https://www.amazon.com/dp/B07XXBQPZL)