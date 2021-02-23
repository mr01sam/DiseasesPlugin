# Diseases Master List
 - Latest Plugin Version: v2.1.0
 - Last Updated: 2/23/2021
1. [Norovirus](####Norovirus by Mr01sam)
## Verified Disease Files
#### Norovirus by Mr01sam
```json
{
  "Disease name": "Norovirus",
  "Description": "Highly contagious disease that causes vomitting and is caused by eating rotten food. Can be treated with tea and cured with pills.",
  "Min time immune after recovery (seconds)": 180,
  "Max time immune after recovery (seconds)": 600,
  "Min time infected (seconds)": 180,
  "Max time infected (seconds)": 600,
  "Min time between symptoms (seconds)": 5,
  "Max time between symptoms (seconds)": 45,
  "Spread distance (4.0 = 1 foundation)": 2.0,
  "Spread chance with mask (0-100)": 0.0,
  "Spread chance without mask (0-100)": 85.0,
  "Symptom damage effects": [
    {
      "Stat name": "health",
      "Min damage": 1.0,
      "Max damage": 5.0
    },
    {
      "Stat name": "calories",
      "Min damage": 100.0,
      "Max damage": 125.0
    },
    {
      "Stat name": "hydration",
      "Min damage": 50.0,
      "Max damage": 85.0
    }
  ],
  "Items that cause infection on consumption": [
    {
      "Infection chance on consumption (0-100)": 10.0,
      "Short prefab name": "chicken.raw"
    },
    {
      "Infection chance on consumption (0-100)": 85.0,
      "Short prefab name": "chicken.spoiled"
    },
    {
      "Infection chance on consumption (0-100)": 10.0,
      "Short prefab name": "humanmeat.raw"
    },
    {
      "Infection chance on consumption (0-100)": 85.0,
      "Short prefab name": "humanmeat.spoiled"
    }
  ],
  "Items that cure on consumption": [
    {
      "Cure chance on consumption (0-100)": 50.0,
      "Short prefab name": "antiradpills"
    }
  ],
  "Items that reduce infection time on consumption": [
    {
      "Min infection time decreased (seconds)": 5,
      "Max infection time decreased (seconds)": 10,
      "Delay between reusing treament (seconds)": 10,
      "Short prefab name": "healingtea"
    },
    {
      "Min infection time decreased (seconds)": 10,
      "Max infection time decreased (seconds)": 40,
      "Delay between reusing treament (seconds)": 40,
      "Short prefab name": "healingtea.advanced"
    },
    {
      "Min infection time decreased (seconds)": 40,
      "Max infection time decreased (seconds)": 160,
      "Delay between reusing treament (seconds)": 160,
      "Short prefab name": "healingtea.pure"
    }
  ],
  "Entities that cause infection on hit": [
    {
      "Short prefab name": "boar",
      "Infection chance on hit (0-100)": 5.0
    }
  ],
  "Random outbreak settings": {
    "Outbreaks enabled": true,
    "Outbreak chance (0-100)": 25.0,
    "Time interval (seconds)": 300,
    "Only outbreak on players with the following stats": [
      {
        "Stat name": "health",
        "Min value": 0.0,
        "Max value": 50.0
      }
    ]
  },
  "Symptom effects": [
    {
      "Asset path": "assets/bundled/prefabs/fx/gestures/drink_vomit.prefab",
      "Local only": false
    },
    {
      "Asset path": "assets/bundled/prefabs/fx/water/midair_splash.prefab",
      "Local only": false
    },
    {
      "Asset path": "assets/prefabs/weapons/cake/effects/strike_screenshake.prefab",
      "Local only": true
    }
  ],
  "Symptom screen effects": [
    {
      "Sprite asset path": "assets/content/ui/overlay_poisoned.png",
      "Opacity (0-1.0)": 1.0,
      "Duration (seconds)": 1.0,
      "Fade out (seconds)": 1.0,
      "Material asset path (optional)": ""
    }
  ],
  "Version": {
    "Major": 2,
    "Minor": 1,
    "Patch": 0
  }
}
```
