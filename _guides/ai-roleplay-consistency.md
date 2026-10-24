---
title: "How to Keep AI Roleplay Consistent After Many Chapters"
description: "How to keep AI roleplay consistent after many chapters: where each kind of fact should live, how to keep the scene current, how to fix drift, and the limits."
date: 2026-10-28
last_checked: 2026-10-25
---

> **Summary.** AI roleplay stays consistent after many chapters when the few facts that must never break live where the AI reads them on every reply, the cast in the scene matches the story, and wrong lines are fixed at the source instead of argued with inside the story. In Lunafic, those places are the Wiki, story notes and secrets, the chapter recaps in story memory, and the In this scene row.

> Written by the Lunafic team. [Lunafic](https://lunafic.ai) is our AI roleplay app, and this guide describes it alongside the general method. Facts last checked October 25, 2026.

## Overview

Consistency in a long AI roleplay means that rules, promises, deaths and who-knows-what from early chapters still hold in late chapters. It usually fails one fact at a time, and each failure has a cause.

| Cause | What the player sees | Usual fix |
| :--- | :--- | :--- |
| A fact lived in one old message | A rule from chapter 4 breaks in chapter 20 | Move the fact to the Wiki or a story note |
| A wrong recap | The AI is sure about an event that went differently | Edit the recap |
| A crowded or stale scene | A character appears from nowhere, or answers a question they never heard | Update who is in the scene |
| An argument inside the story | The complaint itself becomes part of the story | Retry, edit by hand, or use `/ooc` |
| A thin character sheet | One voice drifts the same way every time | Fix Speech Style or Personality in the Wiki |

## Where each kind of fact should live

The core of the method is placement. A fact that sits only in an old message fades. A fact in a place the AI reads on every reply does not. The table maps each kind of fact to its place in Lunafic, as the live docs describe it.

| Kind of fact | Place in Lunafic | When the AI reads it | Who can change it |
| :--- | :--- | :--- | :--- |
| A rule of the world | A Wiki panel set to Always, or a starred entry | Every reply | The world's owner |
| A character's own details | A Wiki panel set to On stage | When that character is in the scene | The world's owner |
| One fact the page never says | A story note, saved with `/note` | Every reply, acted on by the characters picked | The player |
| Something only some characters know | A secret, saved with `/secret` | Every reply, with who in the scene does not know it | The player |
| What happened in each chapter | A chapter recap in story memory | Every reply | Written by memory, edited by the player on paid plans |
| A value that changes, like trust or health | Status, if the world has it | As the story shows a change | The player, with Change and Undo |
| A nickname or title | Names your characters use, on the character's card | Every later chapter | The player, from In this scene |

In a Playable World the [Wiki](https://lunafic.ai/features/world-bible/) is read only. The AI still uses all of it, and the player's own facts go into story notes and secrets. [In this scene](https://lunafic.ai/features/in-this-scene/) has its own feature page.

## Step by step

1. **Before chapter 1, pick three to five facts that must never break.** A promise, a death, a deadline, a rule of magic. In a world the player owns, put them in the Wiki with visibility set to Always. In a Playable World, save them as story notes.
2. **Keep the stage current.** Open In this scene above the reply line and add or remove characters as they arrive and leave. The AI reads the full sheet of everyone on stage, and a smaller scene costs less AI usage.
3. **Fix a wrong reply, do not argue with it.** Retry writes the reply again. Remove deletes it. A hand edit uses no AI usage, and the AI reads the edited version from then on. Right after a reply, `/ooc` and a short note asks for that reply again. No character hears it.
4. **Close chapters at natural breaks.** Type `/newchapter` or press the plus. Each chapter gets its own recap.
5. **Run the end-of-chapter routine from the docs.** Glance at the Memory bar and press Fold now if it is amber or pink. Add one note only if the chapter earned one. If a reply felt off, open the Memory dialog and fix the wrong line there.
6. **Fix voices at the sheet.** When a character drifts, a note fixes one reply. The voice lives in the character panels, so in a world the player owns, fixing Speech Style or Personality improves every later scene.

## Example: My Charter Company Has Seven Death Flags and One Road

[My Charter Company Has Seven Death Flags and One Road](https://lunafic.ai/scenarios/my-charter-company-has-seven-death-flags) is an original Playable World on Lunafic, the third in the team's Vaelmere series. The player is Bea Kestrane, a courier captain who runs the only post still moving through a ninety-day Drought, when every sworn character's magic weakens.

Its open Wiki panels already hold the facts that must not break, and a player can use them as a checklist.

| Fact | Kind | Open Wiki panel | What a break looks like |
| :--- | :--- | :--- | :--- |
| Mana is halved in the Drought, then quartered from day 45 | World rule | The Drought of 702 | A sworn character casts at full strength in week eight |
| Bea's Vows: "never stay in one town past the new moon, and never let a letter go undelivered" | Character rule | Bea Kestrane, Abilities | Bea leaves a letter behind to save a day |
| Rafe Ashby's first Vow: "never eat bread" | Character rule | Rafe Ashby, Abilities | Rafe eats bread at a relay |
| Wenna Holt has no cord and no Mana, so "the Drought takes nothing from her" | Fixed trait | Wenna Holt, Abilities | Wenna casts a spell, or grows weaker |
| Mr. Pell counts himself the Captain's seventh suitor, "which she has not been told" | Who knows what | Mr. Pell, Background | Bea acts as if she knows |
| Contracts rise with every relay reached and fall with every cargo lost | Changing number | The Relay Posts | The count moves with no relay reached and no cargo lost |

The player does not edit these panels, and adds only what the story itself creates. A sample story note, well under the 200-character limit: *Bea owes Ewan Ross a sack of oats from Cairn Hollow.* If Bea later tells only one person something, `/secret` keeps it with that person's face, and everyone else in the scene is written as not knowing it.

## Constraints and trade-offs

- **Not a guarantee.** These habits make breaks rarer, not impossible. A character may still agree when the player states something false about the past.
- **Recaps blur small details.** A fold turns old scenes into short recaps. Anything that must stay exact belongs in a note.
- **Notes are small and limited.** One fact per note, up to 200 characters. A story holds 10 notes on Free and 30 on paid plans, secrets included.
- **Seeing inside memory is paid.** The Memory dialog, and Fold now inside it, open on paid plans. On Free, memory works on every reply and folds by itself, but the player cannot read or edit it.
- **The Wiki has a cost.** Every panel the AI reads costs something on every reply, so a lean Wiki with a few starred entries works better than a long one.
- **A bigger memory costs more.** On Ultra and Ultra+, one story can get a bigger memory. Folds come later, and each reply uses more AI usage, up to about twice at the largest size.

## FAQ

### Why does the AI break a rule from early chapters?
Usually the rule lived in one old message and has faded under later chapters. Moving it to a place the AI reads on every reply, the Wiki or a story note, is the fix.

### Does a bigger memory solve consistency?
It helps, because more of the story stays word for word. It does not fix a wrong recap, a crowded scene or a thin character sheet.

### What should a story note say?
A fact that is true in the story and appears nowhere on the page yet. Not an instruction like "make her colder", and not something a chapter already says.

### What happens when a character dies?
The AI marks the character as gone and takes them off stage, so they do not return by accident. If that was wrong, Bring back undoes it.

### Does switching between MC Mode and Author Mode reset memory?
No. Both modes share the same chapters and the same memory.

## References

- [Story memory, how a long story stays remembered](https://lunafic.ai/docs/story-memory)
- [Keep the scene in scene](https://lunafic.ai/docs/in-scene-and-memory)
- [The Wiki, where your characters and rules live](https://lunafic.ai/docs/the-wiki)
- [Commands in the reply line](https://lunafic.ai/docs/story-commands)
- [What you can do inside a Playable World](https://lunafic.ai/docs/playing-a-playable-world)
- [Plans, AI usage, and why we charge](https://lunafic.ai/docs/plans-and-credits)

## Related

- [AI App for Writing Long Stories Chapter by Chapter: How It Works](https://lunafic-ai.github.io/roleplay/guides/ai-roleplay-chapters/)
- [AI roleplay with long-term memory that keeps the whole story](https://lunafic.ai/blog/ai-roleplay-long-term-memory)
- [The World Bible: An AI Roleplay Wiki the AI Actually Reads](https://lunafic.ai/blog/ai-roleplay-world-bible-wiki)
- [Multi-Character Roleplay: You Play Your Character, the AI Plays Everyone Else](https://lunafic.ai/blog/the-cast-engine-control-your-character-while-the-ai-plays-everyone-else)
