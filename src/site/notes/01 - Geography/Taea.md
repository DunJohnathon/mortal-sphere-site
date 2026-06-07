---
{"dg-publish":true,"permalink":"/01-geography/taea/","dgPassFrontmatter":true,"created":"2025-06-01T09:41:14.531-05:00","updated":"2026-06-06T19:00:37.684-05:00","dg-note-properties":{}}
---

# <span style="font-family: 'Cinzel Decorative';font-size: 36pt">Taea</span>
>
>"From the light of the Bright Star east I have wandered hither. Through the waste and fire from the black throne that was once my mother's, through the many lofts of the dragon lords, through the city-seas of the conqueror, through secret paths in mountain wounds, through the bloody fields of battle, I have arrived now to this Jewel of the Desert. I have seen much beauty, much pain, and many treasures. But in all my journeying, I thought only of home, of Taea."
>
 >— [[Ferron\|Ferron]], the last survivor of the [[House of the Fallen Star\|House of the Fallen Star]]
 >

Taea (pronounced: /TAY-ah/), the Mortal Sphere. The name, common of major landmarks, is of [[04 - Character Creation/04.1 - Ancestries/Elves\|Elvish]] origin, and might be literally translated to "This Place", or "The Place". Though it may seem lacking in spirit or character upon explanation, the significance of this translation is clear to Elvish speakers. In Elvish, such a name as Taea signifies intense gravity and magnitude of importance, and can be more generally understood to mean "the only place for us" or "the only place for me."
# Overview
Geography is an all-encompassing discipline that seeks an understanding of the lands, features, inhabitants, and phenomena of the Mortal Sphere. It would be easy to spend a lifetime detailing the idiosyncrasies and features of just one of the Mortal Spheres many realms or regions. In this content, information is often presented in the form of profiles that give you an immediate understanding of the place, its inhabitants, and perhaps most importantly, what makes it a cool location for adventure. It is important to remember that the Mortal Sphere is sort of structured like a university. Just like a university contains lots of different colleges under its umbrella, Taea contains many different settings: settings with different inspirations, settings with different tones or themes, and settings for many different types of campaigns. 
# Geography
```leaflet
id: atlas-map
image: Mortal Sphere Atlas v8.png
defaultZoom: -2
bounds: [[0,0], [2550,3300]]
lat: 1225
long: 1650
minZoom: -3
maxZoom: 1
height: 700px
width: 100%
```
*A Lorican map of the whole of the Mortal Sphere. Such maps attempt to visualize beyond the shores of Mord, Sannaea, or Volgaea, and are made using knowledge gained through communion with supernatural forces such as devils or spirits. The cartographers of such maps are, like Galileo, swiftly excommunicated from the church for their efforts.*

---
The surface of Taea has never been comprehensively surveyed in person, and does not have a single globalized culture in the current era. In addition, the nation-state has not yet emerged as the predominant method of classifying geographic areas as it has in the real world. Kingdoms and empires rise and fall, and their borders shift and migrate over time. Furthermore, the existence of creatures who live hundreds of years longer than others complicates the recognition of a valid political entity: does the [[Dwarvish\|Dwarvish]] geographer choose to even recognize an unstable human kingdom that may only last eighty years before collapse? The world is best understood as a loose collection of broad regions defined by shared geography, ecology, culture, or via self identification by the inhabitants therein. The most civilized, diverse, and populated regions are within the continents of [[01 - Geography/01.1 - Mord/Mord\|Mord]], [[01 - Geography/01.3 - Volgaea/Volgaea\|Volgaea]], and [[01 - Geography/01.2 - Sannaea/Sannaea\|Sannaea]]. The other three continents of Taea include [[01 - Geography/01.4 - Distant Lands/Bel\|Bel]], [[01 - Geography/01.4 - Distant Lands/Imir\|Imir]], and [[01 - Geography/01.4 - Distant Lands/Jotunheim\|Jotunheim]].

Notably, the [[Arbasmendi Mountain Range\|Arbasmendi Mountain Range]] is a geographical barrier to travel, trade, and large-scale cultural exchange. Functionally, the mountain range separates the east and west regions of Mord, Volgaea, and Sannaea. Though in the past the mountains were traversable thanks to the interconnected halls and tunnels maintained by the Dwarves of Az-Mundu, following the events of the [[The Lucernan Age\|The Lucernan Age]], a pilgrimage through the mountains is deadly even for natives familiar with its many trappings.

Taea also harbors four chief [[01 - Geography/01.4 - Distant Lands/The Oceans\|oceans]], including the [[The Bellatorian Ocean\|Bellatorian]], the [[The Conventaean Ocean\|Conventaean]], [[The Umbral Ocean\|the Umbral]], and the [[The Meridium Ocean\|Meridium]] Oceans. These oceans are each known for being particularly hazardous and difficult to traverse. Raging storms, fearsome oceanic monsters, and a [[particularly bellicose Storm Giant\|particularly bellicose Storm Giant]] make trans-continental sea voyages incredibly challenging. No entity has sailed successfully across these tempestuous waters in the current era without the aid of superior technology or a Vindman of the Vietor-Dych.

There also exists a subterranean network of caves, vaults, and chambers beneath the surface of Taea known as [[Karzauri\|Karzauri]] by the Dwarves, but more commonly throughout Taea as the Deep Dark, or the The World Below. The Dwarves of Az-Mundu once completed what was believed to be a comprehensive survey of the Mordo-Volgasannaean extents of these tunnels, but it was lost during the [[Second Hustea.\|Second Hustea.]]
## Continents
The surface continents are best broken up into two groups: the continents of Mord, Volgaea, and Sannaea, whom make up the super-continent of [[Mordo-Volgasannaea\|Mordo-Volgasannaea]] and contain most of the interconnected civilized world, and the distant lands of Bel, Imir, and Jotunheim.

```base
views:
  - type: table
    name: Major Geography
    filters:
      or:
        - geography == "continent"
        - geography == "major"
    groupBy:
      property: geography
      direction: ASC
    order:
      - file.name
      - tagline
      - description
      - geography
      - continent
    sort:
      - property: continent
        direction: DESC
      - property: file.name
        direction: ASC
    rowHeight: extra
    columnSize:
      note.geography: 107
      note.continent: 131

```
