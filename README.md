# Background
This is my personal branch of klipper that I am using on my machines. It implements features that I find useful
for my workflow. The code may be janky at times. I'm not a programmer. I just figured this might be useful for 
some other people.

# Implemented Features

### Dimitry's Advanced Features
Adds the smoothed input shapers, the velocity dependent PA, as well as some of the nonlinear PA additions.

[Klipper Branch](https://github.com/dmbutyugin/klipper/tree/advanced-features)


### dans98 PID improvements
I've been using these for months now. Greatly improves PID stability and tunes much easier. 

[His branch](https://github.com/dans98/klipper/tree/Final-PID-Improvements)

[Discourse Discussion](https://klipper.discourse.group/t/experimental-pid-improvement-changes/3604)


### Reverse Temperature Fan
This has been helpful for me for regulating a chamber heater.

[Klipper Pull Request](https://github.com/Klipper3d/klipper/pull/6156)


### Increase Split Z Resolution
Might as well use the beacon resolution. 

### Add drop first probe
For the people who still use magprobes 

### Add Frequency Tester
Add the ability for holding a specific frequency to diagnose resonance issues. 

[Gist](https://gist.github.com/kmobs/f6def5db272ca5c1b81727482f53bed8)

### Add the Dockable Probe Module
This particular patch has been in limbo for quite a while from Mental. Added the updated version cloakedcode that is a bit simplied and targets fixed x/y and fixed z configurations. 

[Pull Request](https://github.com/Klipper3d/klipper/pull/6247)

# Standard Readme

Welcome to the Klipper project!

[![Klipper](docs/img/klipper-logo-small.png)](https://www.klipper3d.org/)

https://www.klipper3d.org/

Klipper is a 3d-Printer firmware. It combines the power of a general
purpose computer with one or more micro-controllers. See the
[features document](https://www.klipper3d.org/Features.html) for more
information on why you should use Klipper.

To begin using Klipper start by
[installing](https://www.klipper3d.org/Installation.html) it.

Klipper is Free Software. See the [license](COPYING) or read the
[documentation](https://www.klipper3d.org/Overview.html). We depend on
the generous support from our
[sponsors](https://www.klipper3d.org/Sponsors.html).
