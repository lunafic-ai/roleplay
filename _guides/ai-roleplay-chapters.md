---
title: "AI App for Writing Long Stories Chapter by Chapter: How It Works"
description: "How an AI app for writing long stories chapter by chapter works: where chapters live, what the AI remembers between them, search, export and the honest limits."
date: 2026-10-25
last_checked: 2026-10-25
---

> **Summary.** An AI app for writing long stories chapter by chapter splits one long roleplay into chapters the player closes, and the AI keeps a short recap of each chapter so later chapters still know what happened. In Lunafic, the player starts a chapter with the plus in the chapter column or the `/newchapter` command, and story memory reads the recaps before every reply.

> Written by the Lunafic team. [Lunafic](https://lunafic.ai) is our AI roleplay app, and this guide describes it alongside the general method. Facts last checked October 25, 2026.

## Overview

A chapter-based AI story app treats a long roleplay as a book, not as one chat. The player decides where each chapter ends. The app lists the chapters in order, keeps the full text of every chapter, and gives the AI a shorter version of the older ones.

The method exists because a single chat log has no shape. After a few hundred messages, the player cannot find an old scene, and nothing marks where one part of the story ended. Chapters solve the first problem directly. A recap for each chapter helps with the second, because the AI gets the story so far in order, not one long pile of messages.

| Question | One long chat | Chapters |
| :--- | :--- | :--- |
| How does the player find an old scene? | Scrolls up | Opens the chapter from a list |
| Where are the turning points? | Not marked | Each chapter ends on one |
| What does the AI get for old events? | Depends on the app | A recap per chapter, plus recent scenes word for word |
| How does the text leave the app? | Copy and paste | Export, one chapter at a time (in Lunafic) |

## How it works in Lunafic

Chapters work the same way in a Private world and in a [Playable World](https://lunafic.ai/features/playable-worlds/). The table lists each part, as the live docs describe it.

| Part | What it does | Plan |
| :--- | :--- | :--- |
| Chapter list | The left column of the writing screen lists chapters in order and marks the current one. On a phone it opens as a drawer. | All |
| New chapter | The plus in the chapter column, or `/newchapter` in the reply line. It creates the next chapter and opens it. | All |
| What the AI reads | The newest scenes word for word, chapter recaps, promises and rules, the Wiki, and story notes. | All |
| Folding | When memory fills, older scenes fold into short recaps. A fold never changes the story text. | All |
| Memory dialog | Shows each earlier chapter's own memory, to read, edit, or write again with Update memory. Fold now is here. | Paid |
| Story notes | `/note` keeps one fact, up to 200 characters. A story holds 10 notes on Free and 30 on paid plans. | All |
| Search | Cmd+K searches the whole story, grouped into Wiki, Chapters, Plot and Events. Cmd+Shift+F searches one chapter. | Paid |
| Export | Right panel, under Tools. Saves the current chapter as DOCX or HTML, or copies it with formatting. | All |
| Branches | Off for now. A new session in the Library starts a second story in the same world. | All |

The story text belongs to the player. Any line, the player's or a character's, can be fixed by hand, and a hand edit uses no AI usage. More detail is on the [story memory](https://lunafic.ai/features/story-memory/) feature page.

## Step by step

1. **Start a story.** Press Play on a Playable World and choose a role, or [start a Private world](https://lunafic.ai/docs/start-a-private-world) with a name, one character and who the player is. Chapter 1 opens.
2. **Play until something turns.** A deal is made, someone leaves, a day ends. That is the natural end of a chapter.
3. **Keep the one fact that must not slip.** Type `/note` and the fact. It goes to Story notes, and the AI keeps it in mind from then on.
4. **Close the chapter.** Type `/newchapter` or press the plus. The next chapter opens.
5. **Check the memory bar.** The small bar inside the Memory button is grey, turns amber at three quarters full and pink at nine tenths. On paid plans, Fold now in the Memory dialog is most useful between chapters.
6. **Read the recaps now and then.** On paid plans, open an earlier chapter in the Memory dialog and fix any wrong line.
7. **Export finished chapters.** One chapter at a time, from the right panel.

## Example: Her Name Is Never Said

[Her Name Is Never Said](https://lunafic.ai/scenarios/her-name-is-never-said) is an original Playable World on Lunafic, the sixth in the team's Vaelmere series. The player is Tomas Ferrow, steward of Cindermere, a black castle in a marsh. His Duchess, Serane Morrow, has forty days to answer a summons from the King.

In the open Wiki entry The Summons, Serane reads the summons on the Causeway, hands it to her steward and says "forty days, then", which the entry calls "the only thing she says about it." The same entry has a calendar written "by days of the summons left", where each beat lands on its day. A countdown like this is a ready-made chapter plan.

One possible plan, built only from that open calendar. It is a plan, not a transcript of play.

| Chapter | Days left | Beat from the calendar |
| :--- | :--- | :--- |
| 1 | 40 | The summons on the Causeway. The nine wards are written down. |
| 2 | 38 | The arithmetic laid out for Tomas on the crypt stair. |
| 3 | 32 to 30 | Her brother asks to be named. The Keeper arrives by barge at night. |
| 4 | 28 | The letter to the King is sealed. The first ward is let die. |
| 5 | 18 to 15 | The Seal is carried to the crypt. The reeve of Saltfen is asked to keep the name unspoken. |
| Later | 12 to 0 | The errands, the ride north, and the summons day. |

A note at the end of chapter 1 could be: *Nine wards at Cindermere. Six are on Serane's name.* It is short, it is a fact, and later chapters need it.

The world has five endings, from Common to Legendary. Endings are written for roles, so a player who wants a finish plays the role of Tomas Ferrow. Every ending has a minimum number of turns, never lower than 10, and after that the AI reads the author's conditions and decides if the story earned it.

## Constraints and trade-offs

- **Chapters are manual.** If the player never presses the plus, the story is one very long Chapter 1.
- **Recaps are short on purpose.** A small detail can blur when scenes fold. Exact facts belong in story notes. On paid plans, a recap can be kept detailed so it is never shortened.
- **Export is per chapter.** There is no whole-book export. Formatting, speakers, languages and scene breaks come along.
- **No branches inside a story right now.** Branching is switched off while story memory is rebuilt. Another path means a new session, or Duplicate world for a world the player made.
- **Some tools are paid.** Search, Find and replace, and the Memory dialog open on paid plans. Free gives 20,000 AI usage a month and the Flash model, and memory still works on every reply.
- **Old edits need a choice.** Changing something early in an old chapter marks its memory as changed. The player decides when to press Update memory.

## FAQ

### Does a new chapter make the AI forget the old one?
No. Story memory keeps a recap for each chapter and reads the recaps before every reply. The newest scenes stay word for word.

### Can an old chapter be edited?
Yes, by hand, at no AI usage. If the player edits the latest replies of an old chapter, its memory catches up a few minutes later. A change further back is marked in the Memory dialog, and a replaced memory can be put back with Restore previous memory.

### How long should a chapter be?
The docs set no length. A chapter ends well on a turn: a departure, a promise, a jump in time.

### Can the whole story be exported as one book?
Not today. Export saves the chapter the player is in, as DOCX or HTML, or copies it to the clipboard.

### Can the player try a different path from chapter 3?
Not as a branch. A new session starts a separate story in the same world, and the first story stays as it was.

## References

- [What you can do inside a Playable World](https://lunafic.ai/docs/playing-a-playable-world)
- [Your writing screen, one area at a time](https://lunafic.ai/docs/the-writing-screen)
- [Commands in the reply line](https://lunafic.ai/docs/story-commands)
- [Story memory](https://lunafic.ai/docs/story-memory)
- [Search, find and replace, and export](https://lunafic.ai/docs/search-and-export)
- [New sessions and save points](https://lunafic.ai/docs/branches-and-save-points)
- [Plans, AI usage, and why we charge](https://lunafic.ai/docs/plans-and-credits)

## Related

- [How to Keep AI Roleplay Consistent After Many Chapters](https://lunafic-ai.github.io/roleplay/guides/ai-roleplay-consistency/)
- [AI roleplay with long-term memory that keeps the whole story](https://lunafic.ai/blog/ai-roleplay-long-term-memory)
- [The Best AI Apps for Long Roleplay Stories in 2026](https://lunafic.ai/blog/best-ai-apps-for-long-roleplay-stories-2026)
