# This module is deprecated; for a V12+ replacement, try using [PF2e Dailies](https://github.com/reonZ/pf2e-dailies) instead.# PF2e Staves
 
This FoundryVTT module implements automations for Staves in the PF2e game system.

## Usage

When an item with the "magical" and "staff" traits are added to a character sheet, a corresponding spellcasting entry will be created.

![](/images/pf2e-staves-1.png)

Any spells linked in the text description will be automatically added to the spellcasting entry. This works for custom spells, as long as the spell exists in the item directory.

![](/images/pf2e-staves-2.png)

This spellcasting entry uses charges. The number of charges defaults to the highest level spell slot the character has. Casting spells in this spellcasting entry requires charges equal the level of the spell. If the character has Spontaneous spellcasting, the charge cost can be reduced by right clicking the Cast button. A spell slot of equal or higher level than the spell can be expended to reduce the charge cost to one charge.

![](/images/pf2e-staves-3.png)

When the character is ready to regain charges, the reset button next to the charge value will open a prompt to charge the stave. This will replenish the number of charges back to the default (equal to highest spell slot available). If the character has Prepared spellcasting, the player may choose a spell slot to expend to gain extra charges equal to the level of the spell slot.

![](/images/pf2e-staves-4.png)
