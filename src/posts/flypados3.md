---
title: 'The New flyPadOS 3 Released'
date: 'TBD'
authors:
  - 'Cdr_Maverick'
  - 'Valastiri'
  - 'DirtyFormal'
category: 'UPDATE'
metaImage: '/img/a32nxwing.png'
metaAlt: 'FlyByWire Simulations'
---
  
## Overview

We're happy to introduce the most feature rich update yet to our onboard Electronic Flight Bag (EFB) - flyPadOS 3. The user interface has been completely overhauled with 
FlyByWire's new branding scheme, to bring you the best user interface in flight simulation. Our flyPad is the first EFB to offer support for multiple languages, which would not have been possible without the kind support from our Community.

There are other goodies for our pilots to dive into as well, including updated Navigraph support, a new and improved pushback feature with onboard map, lighting presets, and in-flight checklists!

## New Features

### A Refreshing Unified User Experience

At FlyByWire, we believe in well-designed and integrated user interfaces that bring a great quality of life experience to our users. Since the introduction of our flyPad to MSFS, we've done away with copying real world operating systems - instead building a cohesive UI that easily integrates useful features at the tip of your cursor. Starting up the EFB requires a simple click on the screen, where you're greeted with our unique dashboard. From here, you can seamlessly download your simBrief OFP to display all the information required for 
your planned flight. Everything that's important for your flight is on the new dashboard:

- Shortcuts to take you to where you want to go.
- Flight status and general information including your planned route.
- METAR information - customizable with your choice of ICAO (displayed raw or with simple symbology).
- Active and upcoming checklists.
- Pinned Navigraph charts.
- Active failure management.

This user experience extends throughout our flyPadOS, enabling our pilots to quickly peruse their OFP, access calculations / charts, and integrate easily with online networks such as VATSIM or IVAO.

As you navigate throughout the EFB accessing different features and interacting with them, flyPadOS 3 now remembers the state you left it in. It remembers the pages or tabs with the associated data you have entered, so you can safely switch to a new screen without losing any data.

![Dashboard](/img/notam-images/flypados3/pinned-charts-widget.png)
![Weather Widget](/img/notam-images/flypados3/weather-widget-input.png)
![Fuel Dispatch](/img/notam-images/flypados3/flypad-dispatch-fuel.png)
![OFP Dispatch](/img/notam-images/flypados3/flypad-dispatch-ofp.png)

### Support for Over 30 Different Languages

We are extremely happy to offer support for over 30 languages onboard our EFB. A first in flight simulation, you can now access all the features mentioned above and interact with them in a language of your choice! This would not have been possible without the help of over 200 contributors, and those who have offered to review every corner of the EFB for accuracy. A huge benefit of an open source project is our unique position to have our community assist in endeavors such as this. We cannot stress enough how thankful we are.

[Pictures Here]

### Integrated Pushback

Our new pushback model is smoother with finer control for speed and direction. You can easily utilize your controller axes to steer the tug as you pushback. 
We've made it easier to see your turn radius and protected path with the new onboard map. This gives our pilots accurate and precise turns during pushback without having to 
switch to an external view.

![Pushback](/img/notam-images/flypados3/flypad-pushback.png)

### Performance Calculation

While we continue to work on providing accurate NEO performance calculations for takeoff, the rest of this module is tuned for precision with our flight model and braking simulation. Top of descent calculation, in tandem with various onboard A32NX systems, ensures you will always stay ahead of the aircraft and keep up with ATC instructions.

Our landing calculation page effortlessly pulls in information from your simBrief OFP to populate required fields. If you didn't generate an OFP you can simply choose the relevant ICAO for your landing. Our documentation provides all the information you need to accurately plan your stopping distances.  

[Landing Performance Calculator Documentation](https://docs.flybywiresim.com/fbw-a32nx/feature-guides/flypados3/performance/#ground-speed-and-wind).

![Landing OK](/img/notam-images/flypados3/performance-landing-ok.png)
![Landing MAX](/img/notam-images/flypados3/performance-landing-maxok.png)
![TOD Distance](/img/notam-images/flypados3/performance-tod-distance.png)

### Interactive "Smart" Checklists

We've included essential interactive checklists, accessible through its own tab in the left menu. The dashboard on the EFB also intelligently recommends the correct checklist based on the current phase of flight you are in. 

![Checklist 1](/img/notam-images/flypados3/flypad-checklist-page-partly-filled.png)
![Checklist 2](/img/notam-images/flypados3/flypad-checklist-page-section-filled.png)

The checklists page will also display what checklist you currently have active, and what checklists you are yet to complete. You can use your mouse to click on each line item, or simply use the "Mark item as complete" button at the bottom of the page. If you would like to utilize your hardware, we have some easy to use LVARs for those of you who can write to those.

### Onboard Navigraph Charts

Every flight requires meticulous planning. Keep your procedures close to hand, with our easily accessible Navigraph charts integration. This way there's no fumbling around with the MSFS toolbar and overlays - ruining your immersion.

Our new integration now supports the aircraft position symbol for better visualization of where your aircraft is on a particular chart. Our unified experience means that any chart you are viewing will remain active - even if you navigate away from the charts page. We've also included support for pinning relevant procedure maps, which are conveniently displayed on the flyPad's dashboard.

Something we also hope you can look forward to is our planned Local Files support. This will allow users load any image or PDF onboard EFB for effortless viewing.

![Navigraph Charts](/img/notam-images/flypados3/flypad-navigation.png)
![Pinned 1](/img/notam-images/flypados3/pinned-charts.png)

### Failure Simulation

We have improved the UI for our failure simulations, now grouping them under their respective ATA chapters. You can choose between two different views depending on how you want information to be displayed. While we continuously work on improving our failure simulations, this new method of displaying failures will mean a better, and easier, experience going forward.

![Failures Comfort](/img/notam-images/flypados3/flypad-failures.png)
![Failures Compact](/img/notam-images/flypados3/flypad-failures-compact-view.png)

### Online ATC

"Alt-tabbing"  to check the online ATC is not always the best when you're in command! The new online ATC page gives you a simplified overview of what frequencies are online and in range during your flight. Here you can also easily switch between active or standby frequencies.

We've also provided a text based output for ATIS, enabling our pilots to always have a quick reference to current ATIS information for departures and arrivals.

![Online ATC](/img/notam-images/flypados3/flypad-online-atc-vatsim.png)

### Presets

### Customizable Lighting Presets

Do you have that perfect cockpit lighting setup that you spend a few minutes on each flight getting just right? Well now you can save it! We know that starting a flight in a cold and dark state means you have a lot to do before you can get off the ground, so we hope this provides a nice little quality of life feature for our pilots.

Our new presets' page allows you to save up to 8 custom presets, name them, and load them up instantaneously at any point during your flight.

![Lighting Preset](/img/notam-images/flypados3/flypad-presets-lighting.png)

#### AI Co-Pilot

We heard you liked having an AI co-pilot. This new feature gives your co-pilot control over "on-the-ground" actions up to your takeoff roll. 

Our virtual co-pilot will sequentially perform the necessary setup tasks as in real life - from ADIRs alignment to engine starts. Do note that even this feature is realistically simulated, so the co-pilot will take the appropriate amount of time and steps to complete the procedures and actions. We would like to remind our pilots flying that it's still your responsibility to ensure the MCDU, FCU, transponder and radios are appropriately configured.

![Aircraft States](/img/notam-images/flypados3/flypad-presets-aircraft.png)

## Upcoming Features

At FlyByWire Simulations we are constantly coming up with new ideas and improvements. This means our pilots still have plenty of features to look forward to with future updates to flyPadOS 3 that we are working hard to deliver. Below is a short list of items we hope you will be excited for:

- FlyByWire SimBridge Integration for Local Files
  - Loading custom PDFs straight into the flyPad 
- Right to Left Writing
- Pushback Planning
- Improvements to Brightness Control
- Throttle Calibration Wizard
- W&B Loading Page
- Drawing on Charts

---

## General Information

Stay up to date with information from FlyByWire Simulations by following our social media!

- [Twitter](https://twitter.com/FlyByWireSim)
- [Facebook](https://www.facebook.com/FlyByWireSimulations/)

If you require support or would like to submit a bug report please see the links below:

- [Support Guide](https://docs.flybywiresim.com/fbw-a32nx/support/)
- [Discord Support](https://discord.gg/flybywire)
- [GitHub Issues](https://github.com/flybywiresim/a32nx/issues/new/choose)

When submitting an issue or asking for support to do the following:

- Visit our [Reported Issues Documentation](https://docs.flybywiresim.com/fbw-a32nx/support/reported-issues/) for common problems and workarounds.
- Ensure that your issue has not already been reported on our GitHub.

Download the latest version of the A32NX:

- [Installer](https://api.flybywiresim.com/installer)
- [Standalone Versions](https://flybywiresim.com/a32nx/#download)

---

Safe skies and happy flying!
