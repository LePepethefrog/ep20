# ep20

## Daily quest
The Daily quest NPC consists of 11 Daily quest, officially kro has 13 daily quests, 2 which requires npc, finding a spy, and another thats talk with a random npc, 2 quest dont give item rewards so ommited both NPC quest due to requiring story NPCs and move the reward of the spy one to the grey feather collecting so the amount of rewards remains the same  

## About instances
Sticky sea is pretty much 1:1 to kro
Rasgand was made with my best understanding of multiple sources, even some sources i could no longer find due to not speaking korean, it can be improved specially on the visual side, but functionality wise is pretty close ~90%+ to official

## About monsters
On kRO not a single monster drops etel dust, every etel dust is a map drop, used the server nif_dun01 rates for the drop, the field MVPs drop 3 etel dust at a 100%, it seems they may drop other stuff like treasure chest also as map drop but not enough footage as it will be explained below

## About the skills
When it comes to monster skills all come from my observation and understanding of the skills used on kro footage, i watched over 40 hours of kro footage to get a good look at the skills being used... 

HOWEVER the monsters dont like casting skills they could be hitting someone for over 30 seconds and cast nothing, on top of that players that post their gameplay oneshot the monsters without any effort (on top of ~40% of the monsters being passive due to lore reasons). 

Wandering Star was nice enough to let the instance boss hit him with his full rotation (there is also a video that goes in depth into the boss mechanics), however the only footage i found of the field MVPs is from Gunny and she 3 shot them when the monsters barely had casted 2 skills each, so some speculative skills were added to field bosses.

Some monsters cast a lot of skills and some dont cast any at all, thanks gravity, its highly likely that skills are missing.

## Emulator & Client

This was all coded on the latest version of rAthena, a Q1 client of 2022 was used, everything was tested to the best of my abilities

## Source modifications to the emulator?

None, but I would suggest checking if the src/map/npc.hpp is up to date

## Coding

Everything was coded by me, items were already on rAthena, cards were fixed since their scripts were wrong

NPCs and instances used both chat GPT and other instances/dailies, for example the snakeberry quest, I used a phantasmagorika daily as base for it, some 17.2 dailies like the boiler quest were used for coding some of the quest, the NPC has a lot of debugging lines because i would do 1 thing right and 5 would go wrong... Instances used HTF, OGH, OGH CM, EDDA Biolab, TODG, among others for mechanics and ideas on how to handle and produce certain stuff 

I had to make my own DPS calculation code at some point both to understand actual damage reductions and as a mechanic in Rasgand

First version of Rasgand had 175 lines of code (lots of stuff missing), at some point it had 1200 lines with all the debugging it was cleaned and optimized (is still a mess imo) to ~900 lines

## Sources (not limited to):
https://www.youtube.com/@ArtisticRovin

https://www.youtube.com/@%EB%82%98%EC%9D%B4%ED%8C%85%EA%B1%B4

https://www.youtube.com/@Ziu

https://www.youtube.com/@%EC%9C%A0%EB%9E%91%EB%B3%84t

https://www.inven.co.kr/board/ro/1952

https://www.divine-pride.net/



https://www.inven.co.kr/board/ro/1951/5442?name=nicname&keyword=%EC%A7%80%EB%83%89%EC%9D%B4

https://www.inven.co.kr/board/ro/1943/15544

https://www.inven.co.kr/board/ro/1946/2098

https://www.youtube.com/watch?v=VRfi8i5WEkk

https://www.youtube.com/watch?v=udJVX44vUBU

https://www.youtube.com/watch?v=EA5G3ZxTdO4

https://www.youtube.com/watch?v=pOq_qK3PY_U

https://www.youtube.com/watch?v=yLIEPRCl7V0

https://www.youtube.com/watch?v=Kms17HZWA0I

https://www.youtube.com/watch?v=v_QjGUBL0PE



