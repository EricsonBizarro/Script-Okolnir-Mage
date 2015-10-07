# Script-Okolnir-Mage
Full refil


[Waypoints]
N 32225 31385 7 Start
N 32218 31401 7
N 32207 31429 6
N 32202 31429 6
N 32193 31429 5
N 32202 31429 5
N 32214 31431 6
N 32219 31430 5
N 32214 31431 5
N 32207 31417 6
N 32190 31421 6
N 32187 31430 7
N 32177 31441 8
N 32151 31435 8
N 32178 31457 8
N 32187 31430 8
S 32180 31446 7
N 32157 31432 7
N 32157 31430 6
N 32157 31432 6
N 32191 31451 7
N 32206 31421 7
N 32206 31434 7 subindo
N 32206 31433 7
A 32206 31433 7

isnotlocation gotolabel subindo

A 32206 31433 7

say 'exani hur "up'

N 32207 31425 6
N 32215 31418 6
N 32224 31428 6
N 32228 31415 6
N 32243 31410 6
N 32246 31405 6
N 32248 31397 5
N 32250 31392 5
N 32250 31395 6
N 32250 31392 6
N 32249 31389 5
N 32253 31401 5
N 32261 31383 5
N 32261 31371 5
N 32264 31350 4
N 32266 31344 4
N 32267 31352 5
N 32270 31354 6
N 32266 31360 7
N 32268 31364 6
N 32266 31361 6
N 32265 31343 7
N 32270 31362 8
N 32265 31343 8
N 32270 31353 7
N 32267 31352 6
N 32266 31344 5
N 32262 31371 4
N 32261 31387 5
N 32247 31403 5
N 32246 31405 5
N 32235 31409 6 subindoo
N 32235 31408 6
A 32235 31408 6

isnotlocation gotolabel subindoo

A 32235 31408 6

say 'exani hur "down'

N 32233 31400 7
N 32226 31385 7
A 32225 31384 7 Check

if [$itemcount.'sudden death runes' >= 150] { gotolabel 'Start' | end }
gotolabel 'Refill'

N 32225 31384 7 Refill
N 32225 31381 7
A 32225 31381 7

{ follow 'Buddel' | wait 600 | end }
{ npcsay 'hi' | npcsay 'Svargrond' | npcsay 'yes' | end }


N 32255 31187 7
N 32248 31158 7
N 32243 31142 7
N 32278 31140 7
N 32330 31117 7
N 32341 31112 7
L 32341 31112 7
N 32341 31108 6
N 32341 31107 6
A 32341 31107 6

{ follow 'Captain Breezelda' | wait 600 | end }
{ npcsay 'hi' | npcsay 'carlin' | npcsay 'yes' | end }

N 32387 31820 6
A 32387 31820 6

{ follow 'Captain Greyhound' | wait 600 | end }
{ npcsay 'hi' | npcsay 'yalahar' | npcsay 'yes' | end }

N 32811 31259 6
N 32803 31256 6
N 32802 31233 7
N 32818 31233 7
N 32829 31239 7
N 32824 31239 7
A 32824 31239 7

 countitems 3386 | if [$count==0]  | else npcsay 'hi' | npcsay 'trade' | sellitems 3386 $count
wait 1000


A 32824 31239 7

countitems 3392 | if [$count==0]  | else npcsay 'hi' | npcsay 'trade' | sellitems 3392 $count
wait 1000


N 32830 31233 7
N 32804 31233 7
N 32793 31233 7
N 32790 31239 7
N 32789 31239 6
A 32789 31238 5

{ follow 'Dark Rodo' | wait 600 | end }
{ npcsay 'hi' | npcsay 'trade' | wait 500 | end }
{ sellitems 284 100 | sellitems 284 100 | sellitems 284 25 | end }
{ useoncreatures 238 self | end } 
if [$itemcount.'great mana potion' <= 100] { buyitems 283 55 | wait 300 | end }
{ useoncreatures 238 self | end } 
if [$itemcount.'great mana potion' <= 100] { buyitems 283 55 | wait 300 | end }
if [$cap >= 200] { buyitems 3155 100 | wait 400 | end }
if [$cap >= 200] { buyitems 3155 100 | wait 400 | end }
if [$cap >= 200] { buyitems 3155 100 | wait 400 | end }
if [$cap >= 200] { buyitems 3155 100 | wait 400 | end }
if [$cap >= 200] { buyitems 3155 100 | wait 400 | end }
if [$cap >= 200] { buyitems 3155 100 | wait 400 | end }
if [$cap >= 200] { buyitems 3155 100 | wait 400 | end }
if [$cap >= 200] { buyitems 3155 100 | wait 400 | end }
if [$cap >= 200] { buyitems 3155 100 | wait 400 | end }
if [$cap >= 200] { buyitems 3155 100 | wait 400 | end }
if [$cap >= 200] { buyitems 3155 100 | wait 400 | end }
if [$cap >= 200] { buyitems 3155 100 | wait 400 | end }
if [$cap >= 200] { buyitems 3155 100 | wait 400 | end }
if [$cap >= 200] { buyitems 3155 100 | wait 400 | end }
if [$cap >= 200] { buyitems 3155 100 | wait 400 | end }
if [$cap >= 200] { buyitems 3155 100 | wait 400 | end }
if [$cap >= 200] { buyitems 3155 100 | wait 400 | end }
if [$cap >= 200] { buyitems 3155 100 | wait 400 | end }
if [$cap >= 200] { buyitems 3155 100 | wait 400 | end }
if [$cap >= 200] { buyitems 3155 100 | wait 400 | end }

N 32789 31239 5
N 32790 31239 6
N 32789 31232 7
N 32802 31232 7
N 32802 31253 7
N 32802 31256 7
N 32812 31272 6
N 32816 31272 6
A 32816 31272 6

{ follow 'Karith' | wait 600 | end }
{ npcsay 'hi' | npcsay 'Carlin' | npcsay 'yes' | end }


N 32387 31820 6
A 32387 31820 6

{ follow 'Captain Greyhound' | wait 600 | end }
{ npcsay 'hi' | npcsay 'Svargrond' | npcsay 'yes' | end }

N 32341 31112 6
N 32321 31117 7
N 32301 31128 7
N 32279 31142 7
N 32278 31155 7
N 32277 31162 7
N 32253 31160 7
N 32248 31171 7
N 32254 31180 7
N 32255 31196 7
A 32255 31196 7

{ follow 'Buddel' | wait 600 | end }
{ npcsay 'hi' | npcsay 'Okolnir' | npcsay 'yes' | end }

N 32225 31384 7

[Looting]
3386  e dragon scale mai
3392  e royal helmet

[CavebotOptions]
Rope: Rope
Shovel: Shovel
SkipNearbyNodes: 0
OpenNextBp: yes
LootNearbyTargets: yes
LootDistantTargets: yes

[Alerts]
PlayerOnScreen: 
GmDetected: 
PlayerAttacking: 
DefaultMessage: 
PrivateMessage: 
Disconnected: 
