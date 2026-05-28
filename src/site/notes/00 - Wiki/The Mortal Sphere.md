---
{"dg-publish":true,"dg-home":true,"created":"2025-05-31T11:34:13.504-05:00","permalink":"/00-wiki/the-mortal-sphere/","tags":["gardenEntry"],"dgPassFrontmatter":true,"updated":"2026-05-27T20:40:01.986-05:00","dg-note-properties":{"created":"2025-05-31"}}
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


## Most Recent Pages

```base
formulas:
  created: file.ctime.format('"YYYY-MM-DD"').toString()
properties:
  note.created:
    displayName: Created Date
  formula.created:
    displayName: date
  file.ctime:
    displayName: Created
views:
  - type: table
    name: Table
    filters:
      and:
        - file.ext == "md"
    order:
      - file.name
      - created
      - file.ctime
    sort:
      - property: created
        direction: DESC
      - property: file.ctime
        direction: DESC
    limit: 10

```


```base
formulas:
  john:): file.ctime.format("yyyy-MM-D").toString()
properties:
  file.ctime:
    displayName: Created
views:
  - type: table
    name: Recent Notes
    filters:
      and:
        - file.ext == "md"
    order:
      - file.name
      - file.ctime
      - formula.john:)
      - updated
    sort:
      - property: formula.john:)
        direction: DESC
      - property: file.ctime
        direction: DESC
    limit: 10

```
