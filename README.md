# Continuous Prod
Mod for Civilization 6 that allows continuous production after certain turn to avoid mindless clicking.

## How does it work
Generally it does several action for you implicitly so you have less clicking.

### Civics and Research
With default configuration of the mod the `Future Civic` and `Future Tech` are being re-built for you automatically, starting at the turn 300.
- In your World View panel you see both completing in 999 turns as an indicator you no longer need to care, but both these will take their usual time to build.
- You won't see popups on completion, forcing you to click.
- You won't be asked to select new civic/tech.

### Production
The production of all of the below restarts automatically with no notifications or any action needed from you. Projects:
- Carbon Recapture,
- Theater Square Festival,
- Harbor Shipping,
- Encampment Training,
- Bread and Circuses,
- Commercial Hub.

This starts from turn 1, irrespective of the setting explained in configuration.

## Installation
Download zip file from Releases and extract into your DLC directory under the game directory. Then you only need to enable the mod in the game.

## Configuration
Optionally, edit the following line in `TechAndCivicSupport.lua` changing the value to whichever you want the continuous production to start working:
    
    IGNORE_POPUPS_TURN = 300;

## Compatibility
This was tested on `Gathering Storm v1.0.0.341` but is likely to work with previous expansions as well.
