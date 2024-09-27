# Star System Generator

A simple browser-based application for generating random star systems using the my interpretation of the procedures and formats presented in *The World Builder's Handbook* by Mongoose Publishing.

This is just a tool - you can and should change or ignore any result that does not match your vision for a system.

## Requirements

The application can run in any modern browser (e.g. Firefox), no internet or local server required.

## Installation

1. Download the `star_gen.html` file to somewhere on your computer.

2. Double-click it and your preferred browser should open it automatically. If not, right-click the file and select the "Open with" option in the context menu, then choose your preferred browser.

3. You should now see the application running in your browser, just like any other web page, no interent required!

## Continuation Method

**Star Profile(s)** Accepts standard profiles, separated by colons. E.g. "M0 V" for a single star or "M0 V:BD" for a binary (but not necessarily Companion) star system.

**Check for Secondaries** When only a single Star Profile is provided, this option enables checking for additional Secondary Stars using the normal procedures.

**System Planetary Profile** Optionally enter the number of each type of planetary body, System Baseline Number, and/or System Spread; any left blank will be determined using the normal procedures.

**Main World**

Worlds with an Atmosphere code of 4-9 will be placed around an HZCO if possible. Worlds with any other atmosphere type will be placed at random.

- UWP: Supports SAH, ?SAHPGL (? = optional Starport rating), and standard full UWP ESAHGPL-T.

- Temperature: Adjusts placement of worlds around the HZCO based on an estimated Raw Temperature Roll; final temperature may differ due to actual 2D+DMs roll.

- Satellite of: Selecting Gas Giant or Terrestrial will place the main world as a satellite around that type of planet. The default "Auto" option places the main world as its own body; Planetary Rings are placed preferentially around Gas Giants.

## Standard Options

### Star / System Options

**Star Type Distribution** Use "Traditional Traveller" for a more varied universe, or "Realistic" to include more Type M stars.

**Primary Star: Main-Sequence Only** Uncheck this to allow Brown Dwarfs and other **Unusual** or **Peculiar** results for the Primary Star.

**Primary Star: Peculiar Type** Options for resolving particularly **Peculiar** Primary Star results.

**Star Subtype: Flat Roll Method** Use a straight D10-1 to determine star subtype rather than the Star Subtype tables.

**Enable Variance** Adds some amount of variability to the results for each of the following:

- Diameter

- Luminosity: recommended to leave unchecked to calculate Luminosity based on the star's Diameter and Temperature.

- Mass

- Orbit#s: applies only to stars; planets always add a variable amount to their Orbit#.

- Temperature

**Enable Orbital Eccentricity** Unchecking this option results in every star (and planet) having a perfectly circular orbit.

**Age, Small Stars: Increase Precision** Determine the age of small stars to within 1/10 of a Gyr of precision instead of only whole Gyrs.

**Age, Large Stars: Use 1D100/100** Uncheck this to use the more cumbersome ((1D-1)+(1D/6))/6 roll to determine the portion of lifespan experienced using linear variance.

**Secondary Giant bigger than Primary Giant** Options for handling the rare cases when a Secondary Giant would become more massive than the Primary Giant when attempting to make it cooler.

- Use Twin Method: Change the Secondary to a Twin of the Primary

- Change to Class V: Change the Secondary to Class V

### Planet Options

**HZCO Fudge** Amount of leeway, in Orbit#s from 0.00 to 1.00, when determining if an HZCO is considered to be valid, i.e. within the Min and Max Allowed Orbit#s of a star.

**Main World Candidate Threshold** Value from 0 to 1, where any world scoring in the top n percent of will be flagged as a Main World Candidate. For example, for a value of 0.8, if the top-scoring world received 100 points, any world that received 81+ would be flagged as a potential main world.

**Cumulative Orbital Variance** If checked, each planetary orbit will be calculated from the previous orbit, rather than from a fixed value of one spread per planet.

**Per-Star Baseline Numbers** Determine the Baseline Number, Baseline Orbit#, and Spread for each star separately; the primary star groups (i.e. A, AB, ABC, and ABCD) always use the system-wide values.

**Per-Star Empty Orbits** Roll for empty orbits for each star separately instead of for the star system as a whole.

**Temperature: Basic Mean Only** Determine the Mean Temperature using only the basic formula, and do not calculate the High or Low Temperature.

**Temperature: Flat Roll Beyond HZCO** If checked, worlds outside the HZCO will use a flat 7 + DMs to determine their initial temperature range.

**Life: Check Every World** By default, only worlds within the HZCO or pre-determined Main Worlds are checked for native lifeforms. Enable this option to check every world.

### Main World Options

**Population A+ Variant** If checked, the Population A Variant rule will be used to determine P Value for worlds with Population A+.

## Notes

**Orbit#** Orbit#s are measured from the object being orbited. All Secondary stars and groups of stars orbit the Primary Star; Companions orbit their host; Planets may orbit an individual star or a group of stars.

**HZCO** Habitable zones in parentheses indicate the HZCO is outside of the allowed orbit#s; however, the actual habitable zone typically extends +/- 1 Orbit# in either direction, so some portion of it may extend into the allowed orbit#s.

**Allowed Orbit#s** Similar to Orbit#, but measured from the first listed Component in the entry. For example, orbits around Bab (B) are effectively measured from Ba, while those around ABC are measured from A.

**# Slots** Indicates this star's (or group of stars') weight when determining the number of planets that should orbit around it, if any.

**# Planets** Suggested number of planets that should orbit this star (or group of stars), assuming equal distribution based on the # Slots value.

**Baseline #** If using the Per-Star Baseline Numbers option, this indicates the star's Baseline Number.

**Base Orbit#** If using the Per-Star Baseline Numbers option, this indicates the star's Baseline Orbit#.

**Spread** If using the Per-Star Baseline Numbers option, this indicates the star's Spread.

## Disclaimer

This application is released as is with no guarantees, forever free of charge, and according to Mongoose Publishing's [**Fair Use Policy**](https://cdn.shopify.com/s/files/1/0609/6139/0839/files/Traveller_Fair_Use_Policy_2024.pdf?v=1725357857):

The Traveller game in all forms is owned by Mongoose Publishing. Copyright 1977 - 2024 Mongoose Publishing. Traveller is a registered trademark of Mongoose Publishing. Mongoose Publishing permits web sites and fanzines for this game, provided it contains this notice, that Mongoose Publishing is notified, and subject to a withdrawal of permission on 90 days notice. The contents of this site are for personal, non-commercial use only. Any use of Mongoose Publishing’s copyrighted material or trademarks anywhere on this web site and its files should not be viewed as a challenge to those copyrights or trademarks. In addition, any program/articles/file on this site cannot be republished or distributed without the consent of the author who contributed it.
