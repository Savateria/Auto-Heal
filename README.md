# auto-heal
Skip lockons and instantly heals/cleanses party members.

## Info
- Skills will instantly lockon and heal/cleanse party members. Heals prioritize the lowest HP.
- Mystic's cleanse only works in parties of 5 members or less. Disabled in raids.
- Auto-casting can be disabled (Skills will pre-lockon onto targets and need to be manually pressed again to cast).

| Skills affected                 |
| ------------------------------- |
| Priest - Focus Heal             |
| Priest - Healing Immersion      |
| Mystic - Titanic Favor          |
| Mystic - Arun's Cleansing Touch |

## Usage
### `autoheal`
- Toggle on/off
- Default is on
### `autoheal [on/off]`
- Enables/disables auto-heals
### `autoheal [HP]`
- Set cutoff for healing. ('autoheal 50' = ignore members with >50% HP. Set to 100 to always heal)
- Default cutoff is 97%
### `autocleanse`
- Toggle on/off
- Default is on
### `autocleanse [on/off]`
- Enables/disables auto-cleansing
### `autocast`
- Toggle on/off
- Default is on
### `autocast [on/off]`
- Enables/disables auto-casting

## Issues
- Skills can ghost if proxy is also using Skill-Prediction (You see animation but nothing happens). Workaround is to disable the skills in SP. [Click here to see how](https://i.imgur.com/bS4VkbX.png)

---
"# Auto-Heal" 
