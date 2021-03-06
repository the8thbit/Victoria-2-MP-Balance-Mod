# Victoria-2-MP-Balance-Mod (Checksum MHVE)

See changelog below:

- Increased the supply limit usage of frigates, man-o-wars, commerce raiders, ironclads, and monitors to better align with late-game ships
- Increased the minimum army and naval maintenance sliders to 50%
- Quadrupled the colonial maintenance goods required for overseas provinces
- Added "Paper" as a colonial maintenance good
- Tweaked output of some factories and increased bonuses from same state inputs (thanks Corn!)
- Reduced the effects of war exhaustion on factory and RGO output (max penalty now -80%, down from -100%)
- Slightly increased the buff to late-game infantry attack from "Stormtrooper Training" invention (+3 attack up from +1)
- Slightly increased the tank attack and siege values from "Human Wave vs Spearhead" invention (+4 attack up from +1, +2 siege up from +1)
- Balanced British army size by adding -3% mobilization size penalty from British Raj to reflect reliance on colonial troops
- Buffed stats on Dreadnoughts
- Increased Battleship and Dreadnought limits from 2 > 3 and 1 > 2 per appropriate level port, respectively
- Reduced the naval supply limit gained from naval bases in non-core provinces
- Slightly increased the naval supply limit gained from naval bases in core provinces
- Increased the factory savings cap from 3000 to 10000
- Reduced AI likilihood of investing in naval bases and forts so they don't go bankrupt
- Increased casaulty rate to soldier pops, people will actually die in Great Wars now...
- Increased dig-in time per level (10 days up from 5)
- Increased war subsidies amount (30% of military expenditures up from 20%)
- Changed Austria-Hungary's Reactionary party economic policy from "Interventionism" to "State Capitalism" because it was silly and they need the help
- Added a 0.1 research point bonus to the Dutch East India trigger modifier to better match the one for Britain

### Trade Good Rebalance ###

- Some RGOs in Scandinavia and Moravia will change to "Iron" after 1870 to help mitigate iron shortages
- Added "High-Quality Iron Ore" modifier to trigger in some provines in Luxembourg, Belgium, Norway, and Sweden after 1880
- Province 664 - Bucharest will now also spawn oil after 1885 to help mitigate oil shortages and to better reflect the importance of Romania in total European oil production
- Reduced Corn's buff to machine parts factory output from 2.5 down to 2.25 (original = 2.0).
- Reverted iron ore mine output to original value. (1.8 down from 2.0)
- Reverted cotton plantation output to original value. (1.8 down from 3.0)
- Slightly increased output from dye plantation (0.24 up from 0.22)
- Reduced fabric input of clipper shipyard's (80 down from 100)
- Increased base cotton price (2.2 up from 2.0)
- Increased base iron price (3.8 up from 3.5)
- Slightly increased iron output boost from "Puddling" tech (0.3 up from 0.25)
- Slightly increased iron output boost from "Hot Blast" tech (0.3 up from 0.25)
- Slightly increased coal and iron output boost from "Bessemer Process" tech (0.5 up from 0.4 for coal, 1.0 up from 0.9 for iron)
- Increased coal and iron output boost from "Advanced Metallurgy" tech (1.0 up from 0.9 for coal, 0.75 up from 0.5 for iron)
- Increased coal and iron output boost from "Electric Furnace" tech (1.2 up from 1.0 for both)
- Significantly increased the discovery chance of the "Synthetic Dye" invention (base chance +1 up from -4)
- Significantly increased the boost to cotton plantation output from the "Tractors" invention (0.15 up from 0.03)
- Increased the production boost from the "Mechanized Mining" province modifier (0.75 up from 0.5)
- Added cotton RGO change events to reflect historic shifts to African cotton production and to help balance out supply
- Added iron RGO output nerf event for eight provinces in China and Korea to last through about 1885 so that European iron miners don't immediately get unemployed and migrate away from iron provinces at the start of the game

### Dye Change Fix ###

- Doubled the unemployment required in dye RGOs before "End of Natural Dyes" decision can be taken.
- Limited decision availability to just those countries that have the synthetic dye invention, or to countries whose overlord or sphere leader has the invention

TBD

- Increase war exhaustion per casualties rate in lua
- Decrease war exhaustion reducation amount from the "Total War" triggered modifier
- Edit core warscore cost
- Edit "Cut Down" infamy
- Add social spending base or increased penalties
- Fix transfer CBs
- Rebalance infantry tech boosts to artillery, seems silly

- Messing with academia, to make penalties harsher, and bonuses better. This would prevent nations like britain being able to research every tech fast af.
- Adding in some conflict generators such as event driven brothers war, and not allowing formaton of germany until its been fought or something. (other nations apply.)
- adding in a conquest overseas rebellion penalty or something for like 5 years, makes conquered provinces less productive or whatever


### HPM Version 0.4.5 ###

Economic Observations
- Massive unemployment in certain RGOs around 1880 (tea, coal [could be related to Indian end of dye production event])
- Insufficient iron supply
