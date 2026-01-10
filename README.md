# Paper-Mario-Feedback
Post issues/suggestions as they arise

Please try looking for the following things:
- Any partner animations where some meshes are showing which shouldn't be there (main ones to look out for would be Goombario speech bubbles)
- Any situations where the partners can be damaged and die (this should never happen!)
- Try breaking the partner abilities! Their implementations are complex, so they're bound to break, so let's do it now!
- Try messing up the constraints between Paper Mario and the partners by hitting Paper Mario during the abilities where they are connected and work together (like both Flurrie's abilities)
- Do the partners ever die if they're too far from Paper Mario from too long? There was a fix added for this, but is a little under tested

Known Bugs/issues:
- Mowz launch angle will be inconsistent due to it depending on which pikmin color she spawns as. This will be fixed once we figure out how to force the partners to a specific color
- Final Smash doesn't do anything
- Lots of missing sound effects
- D-Smash and Up-B cause the partner abilities to cancel if you are close enough to the partners. This shouldn't happen and will be fixed. If you run into this, it will mess up the ability count logic
