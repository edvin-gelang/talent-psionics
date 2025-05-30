# Changelog

## 2.0.2

- [WARNING] This module does not work on dnd5e 5.0 due to the sheet changes.
- Updated compatibility verification for v13/v4.4, set maximum compatibility to 4.5.

## 2.0.1

- Adjusted `sourceBooks` implementation to match new standards; 
    - The field should be "Talent", and in the Compendium Browser it will appear as "The Talent and Psionics"
    - Similarly it is "Flee, Mortals!" and "Flee, Mortals! The MCDM Monster Book"
- Updated verified compatibility to 4.1.2
- Added "None" manifest die option to fix select element
- Adjusted Time column to match new standards on sheet always abbreviating
- Fixed drag handling for powers

## 2.0.0

- Rewrite for dnd5e system 4.0.0
- Powers now use activities
- Powers now just use the normal Item sheet
- New custom Consumption type available for all item types: Manifest Die!
- Added compatibility with the Compendium Browser

## 1.1.2

- Added the `mgc` property to all powers
- Fixed an issue with the display of the Power tooltips
- Powers now correctly inherit their parent's proficiency bonus
- Added max compatibility of `dnd5e` 3.3.9 because of upcoming breaks in 4.0.

## 1.1.1

- Fixed formatting of the strain table. **by ceanec**
- Fixed dark theme formatting of strain lozenges. **by ceanec**

## 1.1 D&D 3.3

- Increased minimum version to 3.3
- Fixed compatibility issue with the new sheets due to 5e renaming their templates internally
- Added support for NPC Sheet V2

## 1.0.1

- Fixed NPC power duplicate display bug
- Fixed console error triggered by damage enricher rolls
- Strain Maximum now properly updates whenever a character's talent level updates
- Updated verified compatibility to D&D 3.2 and Foundry V12

## 1.0.0 Full Release

- Fixed several bugs that caused console errors
- Fixed possible bug from alternative localizations or nonstandard specializations
- Added "Flee, Mortals!" to the sourceBooks configuration
- Added translation to change the "Magical" item property to "Supernatural"

## 0.9.0 Beta Release

- Forked from ["Talent Character Sheet Support for D&D 5e" by ceane](https://github.com/CeaneC/FoundryVTT-Talent)
