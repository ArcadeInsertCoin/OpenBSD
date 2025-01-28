# World of Warcraft Classic

#### show current speed
/script ChatFrame1:AddMessage(string.format("Player speed: %d%%", (GetUnitSpeed("Player") / 7) * 100))
#### Pet Training Points
##### Cat Broken Tooth PVP
Claw=8
Prowl=3
Dash=3
Greater Stamina=10
Natural Armor=3
Frost Resistance=2
Shadow Resistance=2

Solo = Growl, Bite, Dash

Raid/Dungeons = Bite, Claw, Dash
##### Wolf Bloodaxe Worg Raid
Dash=1
Furious Howl=4
Bite=8
Nature Resistance=3
Fire Resistance=1
Greater Stamina=10
##### Wind Serpent Son of Hakkar Raid
Dive=1
Lightning Breath=6
Bite=8
Nature Resistance=3
Fire Resistance=1
Greater Stamina=10
##### Bloodseeker Bat Raid
Dive=3
Screech=4
Bite=8
Growl=7
Greater Stamina=9
Natural Armor=4
Fire Resistance=2
Frost Resistance=3
#### Hunter Macros
```
#showtooltip
/cleartarget [dead][help]
/targetenemy [noexists]
/cast Aimed Shot
/cast !Auto Shot

#showtooltip
/cleartarget [dead][help]
/cast Arcane Shot
/cast !Auto Shot

#showtooltip
/cleartarget [dead]
/targetenemy [noharm]
/cast !Auto Shot
/stopattack
/cast Hunter's Mark
/petattack
/cast [pet:Cat,harm]Dash; [pet:Bat,harm]Dive

#showtooltip explosive trap
/petpassive
/petfollow
/stopattack
/cast [combat] Feign Death
/cast Explosive Trap

#showtooltip
/cast Feed Pet
/cast [pet] 0 1

#showtooltip freezing trap
/petpassive
/petfollow
/stopattack
/cast [combat] Feign Death
/cast Freezing Trap

#showtooltip frost trap
/petpassive
/petfollow
/stopattack
/cast [combat] Feign Death
/cast Frost Trap

/castsequence !Aspect of the Hawk, !Aspect of the Monkey, !Aspect of the Cheetah

#showtooltip
/cleartarget [dead][help]
/cast Multi-Shot
/cast !Auto Shot

#showtooltip Call Pet
/cast [nomod, nopet] Call Pet
/cast [mod:shift, @pet, dead][mod:shift, nopet] Revive Pet; [mod:shift, nochanneling] Mend Pet
/petpassive [nomod]
/petfollow [nomod]

#showtooltip
/cleartarget [dead][help]
/cast Arcane Shot(Rank 1)
/cast !Auto Shot

/startattack [dead]
/targetenemy [noharm]
/cast !Auto Shot
/startattack [harm,nodead]

#showtooltip Raptor Strike
/cleartarget [dead][help]
/cast Raptor Strike
/cast Mongoose Bite
/startattack

#showtooltip
/petpassive
/petfollow
/cast [@mouseover, harm][] Scatter Shot

#showtooltip
/cleartarget [dead][help]
/cast Scorpid Sting
/cast !Auto Shot

#showtooltip
/cleartarget [dead][help]
/cast Serpent Sting
/cast !Auto Shot

#showtooltip
/cleartarget [dead][help]
/cast Viper Sting
/cast !Auto Shot

#showtooltip
/cast [@cursor] Volley

#showtooltip Wing Clip
/cleartarget [dead][help]
/cast Raptor Strike
/cast Wing Clip
/startattack





