---
{"dg-publish":true,"dg-home":true,"permalink":"/00-wiki/the-mortal-sphere/","tags":["gardenEntry"],"dgPassFrontmatter":true,"created":"2025-05-31T11:34:13.504-05:00","updated":"2026-05-27T21:05:41.216-05:00","dg-note-properties":{}}
---

# Welcome to  <span style="font-family: 'Cinzel Decorative';font-size: 24pt">The Mortal Sphere</span>
>
>"Nobody lives forever. Any who claim the contrary are not truly living."
>
 >— [[05 - Legendarium/05.1 - Characters/St. Zhefarah zi Nahri\|St. Zhefarah zi Nahri]], Pharaoh of [[01 - Geography/01.1 - Mord/Regions/The Holy Empire of Nahraam\|The Holy Empire of Nahraam]]
 >

Hello, and welcome to the Mortal Sphere! This website covers the ever-expanding knowledge base of worldbuilding material that I make for my homebrew universe made specially for Dungeons & Dragons 5th edition. If you are new to the campaign setting, I recommend you start with the [[00 - Wiki/Introduction\|Introduction]]! From there, feel free to branch out to any area of interest to you.
# Contents
This wiki is rich with information about a variety of topics throughout the Macrocosm, and with optional rules and content to use in your game.

```base
views:
  - type: cards
    name: Table of Contents
    filters:
      and:
        - '!file.folder.contains(".")'
        - file.ext == "md"
        - '!file.folder.contains("00 - Miscellaneous")'
        - '!file.folder.contains("00 - Wiki")'
    order:
      - file.name
      - file.folder
    sort:
      - property: file.folder
        direction: ASC

```


## Ten Most Recently Created Pages
```base
properties:
  file.ctime:
    displayName: Created
  file.name:
    displayName: Page
  note.created:
    displayName: Created
views:
  - type: table
    name: Recent Notes
    filters:
      and:
        - file.ext == "md"
    order:
      - file.name
      - created
    sort:
      - property: created
        direction: DESC
    limit: 10

```
