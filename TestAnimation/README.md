Statue Scramble  
  
A simple 3rd Person game where as the Player you must scramble around to collect the statues that appear and disappear at ever increasing speeds.  
Are you quick enough to collect those pesky statues before the time runs out?  
  
A simple test game using the Unreal Engine 5.2 3rd Person Template as the base of this game.  
The requirements of this assignment are:    
1. The player must collect the small statues that appear on screen before time runs out.  
2. The initial time is set at 30 seconds.  
3. The game is over when there is no time remaining.  
4. There are three statues in the scenario that change position periodically.  
5. When the player gets a statue, another one is spawned.  
6. The score for a statue collected is determined by the expression “10 x Level” (ten multiplied by your current level).  
7. For every five statues collected, the Player Level increases and 15 seconds are added to the time.  
8. The player starts at Player Level 1, and the maximum Level a player can reach is Player Level 5.  
9. When a statue appears in a position, it will stay there for a period of time that depends on the current Player Level. The number of seconds it takes a statue to change position is the result of the expression “6 – Level” (six minus your current level).  
10. The time, score, and Player Level values will be drawn on the screen.  

Coded using Unreal Engine Blueprints.  

Screenshots:  
Go !
<img width="1010" alt="Go" src="https://github.com/forsbergsskola-se/301-ue-bp-gamerules-nice1stu/assets/112468923/2fdeed31-b104-4827-8450-296f06ff308e">  
  
You Win  
<img width="1013" alt="YouWin" src="https://github.com/forsbergsskola-se/301-ue-bp-gamerules-nice1stu/assets/112468923/0f4f3623-2655-4822-8ec3-369c1a768c83">  
  
You Lose  
<img width="1010" alt="YouLose" src="https://github.com/forsbergsskola-se/301-ue-bp-gamerules-nice1stu/assets/112468923/871eab4f-f428-42ff-8d1c-c8c874602c23">  
  
Link to the Youtube video:  
[![click to watch the video](https://img.youtube.com/vi/sJ3e3aEGPcI/maxresdefault.jpg)](https://youtu.be/sJ3e3aEGPcI)  
  
Link to the Github Repository:  
https://github.com/forsbergsskola-se/301-ue-bp-gamerules-nice1stu  

Technical Notes:  
1. Adding points at 10 x current level of player  
2. Player level is increased for every 5 statues colected (and statues collected reset on level on)  
3. on level up add 15 secs to remaining time  
<img width="1121" alt="OnStatueCollected" src="https://github.com/forsbergsskola-se/301-ue-bp-gamerules-nice1stu/assets/112468923/d3595db9-a08e-4f61-ade9-ce6a544fa56f">  
  
4. the staute duration is function of 6 - current player level  
<img width="1034" alt="StatueActiveDuration" src="https://github.com/forsbergsskola-se/301-ue-bp-gamerules-nice1stu/assets/112468923/a112f6cd-365e-4c27-a132-5c6d10dce049">  
  
5. Player wins when reaching level 5, loses when time runs out  
<img width="827" alt="WinLose" src="https://github.com/forsbergsskola-se/301-ue-bp-gamerules-nice1stu/assets/112468923/cf43ae2a-0279-4f15-bb3e-c949c8fd9725">  
