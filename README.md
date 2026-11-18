# Buffs-Fix-DBOClassic
Correction of the dialogue for Shenron’s wishes (Strength, Constitution, Focus, Dexterity, Energy)
## What was fixed?
In the original English localization, the Shenron wish menu texts and resulting buff descriptions did not match the actual stat bonus granted by the server:

| Wish / Skill ID Block | Old (Incorrect) Text | Actual Server Bonus | Fixed Text |
| :--- | :--- | :--- | :--- |
| `262xxxx` / `9910xx` | Dragon King's Focus | +20% Strength | **Dragon King's Strength** |
| `263xxxx` / `9911xx` | Dragon King's Energy | +20% Constitution | **Dragon King's Constitution** |
| `264xxxx` / `9912xx` | Dragon King's Constitution | +20% Focus | **Dragon King's Focus** |
| `265xxxx` / `9913xx` | Dragon King's Strengh *(typo)* | +20% Dexterity | **Dragon King's Dexterity** |
| `266xxxx` / `9914xx` | Dragon King's Soul | +20% Soul | **Dragon King's Soul** *(Unchanged)* |
| `267xxxx` / `9915xx` | Dragon King's Dexterity | +20% Energy | **Dragon King's Energy** |

How to Install
Go to your DBO Classic client folder: `...\DragonBall\localize\TAIWAN\pack\
Paste the downloaded files and replace the originals.
