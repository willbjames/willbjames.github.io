---
layout: default
title: Home
---

# Will James

Musical experience designer in New York

# Music Enhancement Hardware Project

## Part 1: Iola Walker

[github.com/willjamescode/iolawalker](https://github.com/willjamescode/iolawalker)



In music, polyrhythms are propulsion-generating, overlaid figures prescribed according to principles of musical tension and release.  For example, in a jazz song with swung 4/4 time, a piano player might play a polyrhythmic figure of dotted quarter notes to induce excitement underneath an improvised solo. This two against three polyrhythm is a common one: a hemiola.

The 'iola' walker system is a medium for composing music to be played while the listener is walking. Musicians record songs with a walking listener in mind, imagining typical walking paces while playing improvised parts. Multiple versions of the same song are recorded with a variety of underlying polyrhythmic pulses.

 A listener goes for a walk, and the Iola Walker app detects their walking pace. Iola Walker picks up footfalls using a foot-mounted accelerometer, processing the signals in real time using a recurrent neural network in an android app. The android app outputs a midi event for each footfall. The iola walker player, which might be a VST running in a DAW, plays the version of the next music passage with underlying polyrhythms closest to the listener’s walking pace.
![Foot-mounted IMU for footfall detection](images/iolaShoe.png)

![VST3 plugin receiving MIDI messages](images/iolaApp.png)

---
