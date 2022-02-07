# db_str

!!! info
	This page was last generated 2022.01.01

db_str.txt is a client side file that is used to convey information that otherwise would show up incorrectly to players. Things such as defining spells so they show up in the correct spell categories when searching via right-clicking spell slots (type 5), or providing a description of your custom spells (type 6)

## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| id | int | Unique Database String Identifier |
| type | int | Type |
| value | text | Value |

## Type Field

| Type | Description |
| :--- | :--- |
| 0 | Time Messages, Banners, Campsites |
| 1 | AA names, a few spell names |
| 2 | Spell Types, Line 1 |
| 3 | Spell Types, Line 2 |
| 4 | AA descriptions |
| 5 | Spell Gem Categories |
| 6 | Spell Descriptions |
| 7 | Lore Groups |
| 8 | Character Creation Race Descriptions |
| 9 | Character Creation Class Descriptions |
| 10 | Character Creation Stat Descriptions |
| 11 | Race Names |
| 12 | Race Names (Pluralized) |
| 13 | Class Names (Pluralized) |
| 14 | Character Creation Deity Descriptions |
| 15 | Character Creation Starting City Descriptions |
| 16 | Augmentation Slot Names |
| 17 | Currencies |
| 18 | Currencies (Pluralized) |
| 19 | AA Types (Non-Expansion) |
| 20 | Expansion Names (with funny Easter eggs past RoF) |
| 21 | Mercenary Types, Prefix |
| 22 | Mercenary Types, Suffix (Tier I-V) |
| 23 | Mercenary Types, Descriptions | 
| 24 | Mercenary Stances |
| 25 | Mercenary Stance Descriptions |
| 26 | Mercenary Stance Tooltips |
| 28 | Unknown / Possible quest scripting
| 31 | Free-to-Play ads for Silver/Gold Membership |
| 32 | Upgrade button label for 31 |
| 33 | Join, Gold, Tip Buttons for 31 ("Tip"?) |
| 34 | Achievement Descriptions |
| 35 | Achievement Descriptions |
| 36 | Mercenary Groups |
| 71 | Currency "Brellium Token" |


