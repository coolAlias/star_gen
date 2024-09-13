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

## Standard Options

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

**Secondary Giant: if > Primary Giant** Options for handling the rare cases when a Secondary Giant would become more massive than the Primary Giant when attempting to make it cooler.

- Use Twin Method: Change the Secondary to a Twin of the Primary

- Change to Class V: Change the Secondary to Class V

**HZCO Fudge** Amount of leeway, in Orbit#s from 0.00 to 1.00, when determining if an HZCO is considered to be valid, i.e. within the Min and Max Allowed Orbit#s of a star.

**Planets: Cumulative Orbital Variance** If checked, each planetary orbit will be calculated from the previous orbit, rather than from a fixed value of one spread per planet.

**Planets: Per-Star Baseline Numbers** Determine the Baseline Number, Baseline Orbit#, and Spread for each star separately; the primary star groups (i.e. A, AB, ABC, and ABCD) always use the system-wide values.

**Planets: Per-Star Empty Orbits** Roll for empty orbits for each star separately instead of for the star system as a whole.

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
