# Package Format

It's a zip file which contains a Icon. _file which is used as the logo/icon in the installer and an Assembly.xml which is where the details of the mod._\
_Everything else is copied to Gameroot/_

## Example of Assembly.xml:

```markup
<package version="BETA 1.0" name="Devils pit">
  <metadata>
    <author>
      <displayName>SkacikPL</displayName>
      <actionLink />
      <web />
      <facebook />
      <twitter />
      <youtube />
    </author>
    <description>Devil's Pit Mod offers you a chance to visit unused area of caverns located at the Devil's Pit quarry along with numerous enhancements to the area and additional content that can be enjoyed within the base game.</description>
    <largeDescription>FEATURES:
Over 19 new items, including but not limited to:
Alkaline bomb - Alkaline bomb capable of neutralizing most vicous acids, rendering enemies unable to use acid based attacks.
Battlemages essence - Potion enhancing stamina for caster builds.
Bear trap - Popular amongst hunters for hunting bears, can be used against other targets with great results.
Fine throwing knife - Well balanced throwing knife - lethal weapon if thrown by capable hand.
Fungi bomb - Bomb containing spores of fast growing fungus that blocks vocal chords of infected targets making them unable to use their voice.
Glue bomb - Bomb containing resin based compound that sticks to enemies, rendering them unable to fly or move.
Grappling bolt - Bolt with a hooked end, can be used for quick transportation - nearly useless in combat.
Invisibility charm - A magical charm which renders its wearer invisible as long as he moves slowly.
Mule essence - Powerful steroid which temporarily enhances maximum carry weight.
Plaguebearer - Cursed sword capable of turning fallen foes into undead servants of the wielder.
Salt bomb - Simple bomb containing salt, useful against spectral enemies, forcing them to take material form.
Shaving kit - An inexpensive portable shaving kit - handy for any man that spends most of his time on the road.
Shrapnel bomb - Crude bomb containing hundreds of miniature shrapnels capable of piercing wings of most flying enemies, forcing them to fight on ground. Whilst shrapnels are too small to cause any serious harm, they still can be used to stagger the target.
Spring trap - Simple explosive tripwire trap, deals damage within 8 metre radius - can trigger other nearby traps within 6 meters.
Sworddancers essence - Potion enhancing stamina for melee builds.
Throwing knife - A cheap throwing knife - probably the handle is more lethal than the blade.
Viper school hood - Article of clothing popular amongst witchers of the Viper school.
Viper school throwing knife - Throwing knives favored by witchers from the school of Viper - well balanced, sharp and poisonous.
Virus bomb - Bomb containing virus capable of crippling regenerative abilities of infected targets.</largeDescription>
    <license>GPL</license>
  </metadata>
  <colors>
    <headerBackground useBlackTextColor="false">Red</headerBackground>
    <iconBackground>Black</iconBackground>
  </colors>
  <content />
</package>
```

## Example file layout:

Icon.ico\
Assembly.xml\
Mods\modDevilsPitDLC\content\metadata.store\
Mods\modDevilsPitDLC\content\buffers0.bundle\
Mods\modDevilsPitDLC\content\blob0.bundle
