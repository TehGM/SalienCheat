# How to use this

## First steps

1. Download *cheat.py* and save it somewhere
2. Login to [Steam](https://steamcommunity.com/) on your borwser.
2. Go to [Token page](https://steamcommunity.com/saliengame/gettoken) and save it as *token.txt* in same folder as cheat.py
3. Install [Python3](https://www.python.org/downloads/)
4. Run `pip install requests tqdm` in Terminal/CMD.

## Setting up preferred planets

1. Simply edit line 18 to include IDs of preferred planets, for example `preferred_planets = [8, 10, 12]`. 
2. Save the file.

> First ID has priority over next, and so on. 
> If none of the preferred planets are available, script will automatically pick the latest one.

## Getting planet's ID

1. Open [Salien Game](https://steamcommunity.com/saliengame/) in browser.
2. Press *F12* to open debug console.
3. Go to *Network* tab.
4. (optional) Clear it for convenience.
5. Click on your planet. A request will appear in console, and one of them will have ID of the planet. For example, planet with ID will 10 display following request:
```/ITerritoryControlMinigameService/GetPlanet/v0001/?id=10&language=english```

## Run

Run the script: `python cheat.py`
