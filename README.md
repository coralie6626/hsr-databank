# hsr-databank
Honkai Star Rail Game Data

## CharacterData Interface

The `CharacterData` interface represents the data structure for character information in the Honkai Star Rail game. It defines the following properties:

- **name**: A string representing the character's name.
- **faction**: A string indicating the faction to which the character belongs.
- **rarity**: A number representing the rarity level of the character.
- **path**: A string specifying the path or role of the character.
- **combatTypes**: A string representing the combat types associated with the character.
- **chineseName**: A string providing the voice actor's name in Chinese.
- **englishName**: A string providing the voice actor's name in English.
- **koreanName**: A string providing the voice actor's name in Korean.
- **japaneseName**: A string providing the voice actor's name in Japanese.
- **ascensionMaterials**: An array of `AscensionMaterial` objects representing materials required for character ascension.
- **traceMaterials**: An array of `AscensionMaterial` objects representing trace materials related to the character.
- **story**: A string containing the character's background story.
