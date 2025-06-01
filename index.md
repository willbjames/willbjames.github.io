---
layout: default
title: Home
---

# Hello from GitHub Pages!

Welcome to my first Jekyll-based GitHub Pages site. This page is generated from `index.md` and styled by the **minima** theme.

## About

- **Site title:** My GitHub Pages Site  
- **Description:** A simple Jekyll-powered GitHub Pages site  
- **Theme:** minima

Feel free to edit this file (`index.md`) or add new Markdown files to expand your site. Any changes pushed to the `main` branch will automatically rebuild and deploy at `https://<your-username>.github.io/`.

---

## Iola Walker Project

In music, hemiola rhythms are propulsion-generating rhythmic pulses that act as a mechanism of rhythmic tension. For example, when a song is in 4/4 time, a hemiola in dotted quarter notes might help generate excitement according to principles of musical tension and release. Often, a person will listen to music while walking purposefully to their next destination, or take a walk while listening to music in order to relax. Musicians record songs with an iola walking listener in mind, imagining typical walking paces when they play improvised parts and incorporating those pulses. Several versions of the same song are recorded with varying underlying hemiola pulses.

A person goes for a walk, and Iola Walker detects their walking pace. It then chooses, for the next section of a song, the version with hemiola rhythms closest to the listener’s walking pace. Iola Walker picks up footfalls using a foot-mounted IMU:

![Foot-mounted IMU for footfall detection](images/iolaShoe.png)

and outputs MIDI messages that can be consumed by a VST3 plugin:

![VST3 plugin receiving MIDI messages](images/iolaApp.png)

---

### Example Sections

#### Section One

You can write regular Markdown here:

- Bullet point 1  
- Bullet point 2  
- [Link to another page](/about)  

#### Section Two

```html
<!-- You can even include raw HTML -->
<p>This is a paragraph written in HTML inside the Markdown.</p>
