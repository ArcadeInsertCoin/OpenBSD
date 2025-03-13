# World of Warcraft Classic

#### show current speed
/script ChatFrame1:AddMessage(string.format("Player speed: %d%%", (GetUnitSpeed("Player") / 7) * 100))
#### Pet Training Points
##### Broken Tooth PVP<br>

Prowl=3  <br>
Claw=8  <br>
Dash=3  <br>
Greater Stamina=10  <br>
Natural Armor=3  <br>
Frost Resistance=2  <br>
Shadow Resistance=2  <br>

Solo = Growl, Claw, Dash

Raid/Dungeons = Bite, Claw, Dash
##### Bloodaxe Worg Raid/Dungeons
Dash=1  <br>
Furious Howl=4  <br>
Bite=8  <br>
Nature Resistance=3  <br>
Fire Resistance=1  <br>
Greater Stamina=10  <br>
##### Wind Serpent Son of Hakkar Raid
Dive=1  <br>
Lightning Breath=6  <br>
Bite=8  <br>
Nature Resistance=3  <br>
Fire Resistance=1  <br>
Greater Stamina=10  <br>
##### Bloodseeker Bat Raid
Dive=3  <br>
Screech=4  <br>
Bite=8  <br>
Growl=7  <br>
Greater Stamina=9  <br>
Natural Armor=4  <br>
Fire Resistance=2  <br>
Frost Resistance=3  <br>
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





