# Warframe arbitration

Is there anything to write here?  
Come on, I think everyone has known about this for a long time.

## Original:
https://data.source.wf/arbys.txt
```
1718031600,SolNode412
1718035200,SolNode100
1718038800,ClanNode23
...
```

## Digested:
https://raw.githubusercontent.com/ix1le/warframe-arbitrations/main/arbys.json
```
[
    {
        "start": 1718031600,
        "node": "SolNode412",
        "name": "Mithra",
        "planet": "Void",
        "enemy": "Orokin",
        "missionType": "Interception",
        "bonus": null
    },
    {
        "start": 1718035200,
        "node": "SolNode100",
        "name": "Elara",
        "planet": "Jupiter",
        "enemy": "Grineer",
        "missionType": "Survival",
        "bonus": null
    },
    {
        "start": 1718038800,
        "node": "ClanNode23",
        "name": "Gabii",
        "planet": "Ceres",
        "enemy": "Infestation",
        "missionType": "Survival",
        "bonus": {
            "resourceBonus": 0.35,
            "xpBonus": 0.26,
            "weaponXpBonusFor": "Melee",
            "weaponXpBonusVal": 0.21
        }
    },
    ...
]
```