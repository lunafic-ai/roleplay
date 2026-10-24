---
title: "An App Where You Control Your Character and the AI Plays Everyone Else"
description: "How roleplay works when you control one character and the AI plays the rest: what the AI needs, how the cast list decides who is present, and a real example."
date: 2026-11-07
last_checked: 2026-10-25
---

> **Summary.** In this kind of roleplay app the player writes only their own character, and the AI writes the world and every other character, each from that character's own sheet. It works when the app keeps three things apart: the player's character, a separate profile for every other character, and a list of who is present in the scene, which Lunafic calls In this scene.

> Written by the Lunafic team. [Lunafic](https://lunafic.ai) is our AI roleplay app, and this guide describes it alongside the general method. Facts last checked October 25, 2026.

## Overview

"Everyone else" means more than one partner character. It covers the named cast, unnamed side characters such as a guard, and the world itself: weather, crowds, events. The player decides what one person says and does.

In a plain chat app built around one bot, this division tends to break once a second or third character joins:

- **Blended voices.** With one personality file for the whole chat, several characters drift toward the same tone.
- **Easy agreement.** One voice has one opinion, so the second character backs the first and the scene loses its friction.
- **No doors.** The app keeps no record of who is in the room, so a character mentioned in passing may answer from another city.
- **A lost seat.** Without a clear line around the player's character, the AI starts writing that character too.

## What the setup needs

Each failure has a matching part. On Lunafic they are:

1. **A fixed line around the player character.** In [MC Mode](https://lunafic.ai/features/mc-mode/), the default, the AI never writes the player character's dialogue, thoughts or actions. It writes what the others do and what the player character can see and hear, then stops where that character has to act, speak or decide.
2. **A sheet for every other character.** Each character has an entry in the [Wiki](https://lunafic.ai/features/world-bible/), the world bible, with panels such as Personality, Speech Style, Relationships, Knowledge and Secrets.
3. **A list of who is present.** The [In this scene](https://lunafic.ai/features/in-this-scene/) row above the reply line. The AI reads the full sheet of every character on stage and keeps the rest of the Wiki backstage.

## Who is on stage

A character in a Lunafic story is always in one of these states.

| State | How a character gets there | What the AI does |
|---|---|---|
| Player character | Chosen when the story starts | Never writes their lines, thoughts or actions |
| On stage | Ticked in In this scene | Reads their full sheet and writes them in the scene |
| Backstage | Not ticked, or taken off the list | Keeps them out of the scene |
| Dead or gone | The AI marks that they died or left the story for good | Keeps them out of every later scene, until the player taps Bring back |

Changes to the list apply from the next reply. Tapping a character opens a card with how they are in this story and a link to their Wiki page.

Panel visibility works alongside the list. Each Wiki panel is set to Always, seen on every reply, On stage, seen when the character is in the scene, or Private, never sent to the AI. Starred entries are always in the AI's context.

## Where the voices come from

The AI plays a character as well as the sheet teaches it. Lunafic's [character documentation](https://lunafic.ai/docs/building-characters) traces most flat voices to two panels: Speech Style, how a character sounds, and Personality, how they act. Speech Examples, lines of the character actually talking, teach the most of all.

Two more parts keep a cast from collapsing into agreement:

- **Pushback and Wants.** When Build with AI drafts a character, it gives each one a Pushback line, what they refuse or doubt even from someone they like, and a Wants line, what they want right now.
- **Secrets.** A Secrets table lists who knows what. On every reply, the characters in the scene who do not know a secret are written unaware of it.

## Example: an evening at court

[Who Put the Hearth Out](https://lunafic.ai/scenarios/who-put-the-hearth-out) is an original fantasy world on Lunafic, set at a royal court in the third year of a war. The player is Seraphine Aurel, the Queen's cousin and next in line for the throne. The richest Duke in the land offers peace if she marries his son at the spring Thaw Ceremony, a hundred and twenty days away. A Great Bell at court hears every lie, so Seraphine never lies. She only chooses which true things to say.

Each starting choice opens with a different cast on stage. In The Lemons, her servant Hobb "trips on the last step with a tray, saves it, drops the lemons". In A Hundred and Twenty Days, Duke Gerrit Vantrel "raises his cup to the Queen and states the terms of the Betrothal once, warmly". In I Am the Peace, his son Aurelien leans on the mantel and tells Seraphine "he is the peace, and also charming, and she may have either."

The open Personality panels give each of them a different want:

- **Duke Gerrit Vantrel** has studied the same table of the coming Drought as Seraphine and "drawn the opposite conclusion".
- **Aurelien Vantrel** is "a man who has been a peace offering his whole life and would quite like, once, to be asked."
- **Hadrian Durrand**, envoy of the northern Wall, arrives "with one bargain, stated once": his house comes south for a marriage and nothing less.
- **Hobb** is "the one person in Vaelmere who has never pitied her".

The stage list shapes the evening. With Aurelien alone in the blue room, the scene is a courtship. Add Hadrian to In this scene, and from the next reply two suitors who stand for two different houses share the room, each pressing his own bargain. Hobb stays backstage until the player calls him in. Through all of it, the AI does not decide what Seraphine answers, or which true thing she chooses to say. That is the player's turn.

## Running a scene, step by step

1. Open a world, press **Play**, choose who you are, and fill your hero sheet.
2. Tap a starting choice under **Your first move**, or write your own.
3. Open **In this scene** above the reply line. Add whoever should be in the room and remove whoever has left.
4. Write your character's line, and name the character you are speaking to.
5. When someone walks in or out in the story, update the list.
6. When a scene ends, type /newchapter in the reply line to start the next chapter.

More detail is in [Keep the scene in scene](https://lunafic.ai/docs/in-scene-and-memory) and [What you can do inside a Playable World](https://lunafic.ai/docs/playing-a-playable-world).

## Constraints and trade-offs

- **The stage list is mostly the player's job.** The AI takes the dead and departed off by itself. Any other character left on the list is treated as still in the room.
- **Smaller scenes cost less.** Fewer characters on stage use fewer credits per reply.
- **Mistakes still happen.** Retry writes a reply again, Remove deletes it, and any line can be fixed by hand. In your own world, a voice that keeps slipping is best fixed in its Wiki panel rather than with a note.
- **Someone else's world stays theirs.** In a Playable World the Wiki is read only, and some panels may be guarded: the AI uses them, the player cannot read them.
- **Author Mode is for Private worlds only.** Directing the whole scene, every character included, is not available in a Playable World.
- **No branches for now.** A story cannot split into two paths inside Lunafic at the moment.
- **A young library.** Lunafic has far fewer worlds than the large chat apps.

## FAQ

### Is there an app where I control my character and the AI plays everyone else?

Yes. Lunafic is built around this split: in MC Mode you write only your own character, and the AI plays the world and every other character, each from their own Wiki entry, limited to the characters in In this scene.

### Can the AI characters disagree with each other?

Yes, when their sheets give them different wants. Characters drafted with Build with AI get a Pushback line and a Wants line so they do not simply agree with everyone.

### Can I play one of the existing characters instead of a new hero?

In your own Private world, yes, through Who you play in the right panel. In a Playable World you pick one of the author's roles.

## Related

- [AI roleplay where you play your own character](https://lunafic-ai.github.io/roleplay/guides/play-your-own-character/), the companion guide
- [Multi-Character Roleplay: You Play Your Character, the AI Plays Everyone Else](https://lunafic.ai/blog/the-cast-engine-control-your-character-while-the-ai-plays-everyone-else) on the Lunafic blog
- [The World Bible: An AI Roleplay Wiki the AI Actually Reads](https://lunafic.ai/blog/ai-roleplay-world-bible-wiki) on the Lunafic blog
- [How to Start an AI Roleplay, What to Write in Your First Message](https://lunafic.ai/blog/how-to-start-an-ai-roleplay) on the Lunafic blog
