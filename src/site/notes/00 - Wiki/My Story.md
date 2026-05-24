---
{"dg-publish":true,"created":"2025-06-23T17:51:30.826-05:00","permalink":"/00-wiki/my-story/","dgPassFrontmatter":true,"updated":"2026-05-24T16:46:32.194-05:00","dg-note-properties":{"created":"2025-06-23"}}
---

# My Story
I'm not really sure I can pin down when exactly I started "worldbuilding". What I do know is that I've had an active imagination for as long as I can remember. As a child growing up in rural America, I lived in a small neighborhood in the unincorporated areas of the county and attended a small school miles away from our house. I had to learn how to make my own fun very early. I was the type of kid who filled sketchbooks with drawings of monsters and characters. When I finished a novel, I was never satisfied with the ending. I would imagine the characters' lives after the story ended. I didn't even know that fan-fiction was a real hobby, I just thought that part of the normal fun of reading was creating my own fantasy about the book.

It wasn't until middle-school that I was first introduced to Advanced Dungeons and Dragons by my English teacher. During our small, four-person after-school D&D club, I discovered the powerful stories you can tell on the tabletop.

In early high-school, my older brother began to involve me (or maybe I involved myself) with his friend group. They were the cool kids, and they tolerated me enough to allow me to tag along with my brother. Eventually, a multitude of factors converged and my brother hit upon the idea of starting a D&D game with the new 5th edition books for all of his friends. Between many of them hitting the right age to start driving by themselves, getting absorbed into Magic the Gathering or Yugioh, and all of us having played a ton of video games or engaging with other fantasy media, we were in many ways the perfect group of young teens ready to dive into the game.

I was actually coerced into playing by my mom during their first meet, where we all made our characters. It wasn't long until I became interested in getting "behind the screen." I watched hours of D&D content on YouTube, I asked for the rule-books, minis, and dice for birthdays and Christmas, and I began drawing maps and making my first real worldbuilding notes.

I wish I could say that those same worldbuilding notes became the Mortal Sphere (how cool would that be!), but that would be a lie. I've made a few settings during my time playing D&D and other games, most of which never saw the light of a session zero. Most of them were little more than a few big ideas and a creation myth. Others have been iterated on and expanded over years of actual play. This setting was built from the outset to serve as my persistent, go-to D&D world. I began writing the foundations of the Mortal Sphere during my time in college, where I wasn't able to run the game for my friends as much as I wanted to. That dry spell lasted through my entire degree, and to some extent continued still after a big move that took me to a different city for my career.

Through it all, and still today (no matter when you are reading), I kept thinking about this setting; adding to it, editing it, subtracting from it. To this day, I am the same kid I was all the way back in the beginning; still doodling dragons in my notes while I should be paying attention. I draw inspiration from everything I can, whether its the tiny neighborhood I grew up in, the woods I got lost in, the games I've played, movies I've watched, or the stories that my friends and I have told each other since we were in middle school.

If you ever want to reach out to me with questions or to learn more about the Mortal Sphere, feel free to reach out on reddit where I can be found as u/AFumblingArchitect. 
I hope you enjoy The Mortal Sphere!


```base
formulas:
  created: file.ctime.format('"YYYY-MM-DD"').toString()
properties:
  note.created:
    displayName: Created Date
  formula.created:
    displayName: date
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
      - property: file.ctime
        direction: ASC
    limit: 10

```
