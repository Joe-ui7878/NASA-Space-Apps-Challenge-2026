# NASA-Space-Apps-Challenge-2026
Project Astroprep
🚀 Junior Astronaut Mission Trainer
An interactive browser game built for the NASA Space Apps Challenge ("Build a Junior Astronaut Mission Trainer"). Students run a Moon or Mars outpost for 20 days and balance power, oxygen, and radiation shielding while real NASA space weather tests their plans.
Play it: open index.html in a browser, or publish with GitHub Pages (below).
How to play
You get 3 crew hours a day. Every action has a real cost, so there is no free "safe" choice.
Check the Space weather ahead strip (3 days) and raise shielding before a flare hits.
Random crew events force trade-off decisions.
Earn score (with a balance streak) and science points. Spend points on upgrades.
Keys: 1-4 do actions, Enter ends the day.
When a mission fails, the game shows what hurt the crew most.
NASA data and honesty
On start, the game requests the last 30 days of solar flares from NASA DONKI (https://api.nasa.gov/DONKI/FLR) using the shared DEMO_KEY. M and X class flares become nightly events.
The in-game banner says LIVE when DONKI responded, or SNAPSHOT when it fell back to a saved list of real past events (2003 Halloween storms, 2017 X9.3 flare, May 2024 G5 storm, and others). Static data is never presented as live.
DEMO_KEY has low rate limits. Get a free key at https://api.nasa.gov/ and replace DEMO_KEY in index.html for heavier use. Please verify snapshot events against DONKI.
Hazard levels (1-5) and damage numbers are game simplifications, not measured radiation doses.
Sources: NASA DONKI (https://kauai.ccmc.gsfc.nasa.gov/DONKI/), NOAA Space Weather Scales (https://www.swpc.noaa.gov/noaa-scales-explanation).