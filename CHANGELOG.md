## 2.1.4 - 2022-03-05
- Prevent melee usage of combination weapons consuming ammunition

## 2.1.3 - 2022-03-04
- Revert system change to disregard empty ammunition stacks
- Prevent unloading into stowed ammunition stacks

## 2.1.2 - 2022-02-26
- Add a dialog when first being unable to fire a weapon because of the module, linking to documentation

## 2.1.1 - 2022-02-20
- Fix issue with Hunted Prey effect not applying

## 2.1.0 - 2022-02-18
- Implement Advanced Ammunition System
- Add improved macro icons

## 2.0.2 - 2022-01-31
- Fix issue where the Loaded effect would be removed even if the attack roll was cancelled

## 2.0.1 - 2022-01-30
- Fix bug preventing NPCs from reloading
- Fix bug stopping the "Reload All" macro from working

## 2.0.0 - 2022-01-30
- Remove range increment calculation macros and effects (implemented in Pathfinder 2e system)
- Refactor macros into scripts - future updates will not require macro re-import
- Add useful chat messages for running macros
- Automatically remove "loaded" effect on firing a weapon
- (Optional) Prevent firing an unloaded weapon

## 1.2.1 - 2022-01-25
- Fix issue with Reload and Hunt Prey macros duplicating effects

## 1.2.0 - 2022-01-25
- Add to actions compendium with one- and two-action reload versions
- Add item-targeted effects for Crossbow Ace and Crossbow Crack Shot
- Improved Reload macro to apply Crossbow Ace and Crossbow Crack Shot effects, and check if weapon is already loaded
- Add Hunted Prey effect to track which target is hunted
- Add Hunt Prey macro which applies the Hunted Prey effect for selected target, and applies Crossbow Ace effect for equipped crossbows
- Automate enabling/disabling "Hunted Prey" toggle based on current hunted prey and targeted token

## 1.1.0 - 2022-01-24
- Add Reload macro to apply the "Loaded" effect for a particular weapon
- Add actions compendium with Reload action
- Update range calculation to take into account large and larger creatures

## 1.0.0 - 2022-01-14
- Add compendia for range penalty effects and macros to automatically calculate which to use
