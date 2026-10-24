---
title: "AI Roleplay With a World Wiki the AI Never Forgets"
description: "How an AI roleplay world wiki keeps your world's facts in front of the AI on every reply: what goes in it, who reads each panel, its limits, and a real example."
date: 2026-10-31
last_checked: 2026-10-25
---

> **Summary.** An AI roleplay app with a world wiki the AI never forgets keeps the facts of a world on separate pages and sends them to the AI by rule on every reply, so they do not fade as the chat grows. On Lunafic this is the Wiki (the World Bible), where each panel is set to Always, On stage or Private, and starred entries are always in the AI's context.

> Written by the Lunafic team. [Lunafic](https://lunafic.ai) is our AI roleplay app, and this guide covers it alongside other tools. Facts last checked October 25, 2026.

## Overview

A world wiki is a set of pages about a story's characters, places, groups and rules, kept outside the chat. Before the AI writes a reply, the app gives it the pages that apply.

Without a wiki, a world lives only in the chat history. A fact set up early sits behind hundreds of newer lines, and when old scenes fold into short recaps, a detail like "the bridge is out" can fall out. A wiki keeps that fact in its own place, word for word.

Three related tools are often confused:

- **Character description.** One text box per character, with looks, history and rules at the same weight.
- **Keyword lorebook.** An entry enters the prompt when a trigger word shows up in recent messages, as in NovelAI and SillyTavern. Both also allow always-on entries. A fact nobody names stays out.
- **Story memory.** What happened in one story. It changes as the story moves.

The Lunafic Wiki decides what the AI reads by the setting on each panel and by who is in the scene, not by the words in the last message.

## How the Lunafic Wiki works

Open the Wiki from the right panel under This world, or type `/wiki` in the reply line. An entry can be a Character, Location, Lore, Species, Faction, Magic System, Item, Artifact, Culture, Religion or Custom. Characters are the ones the AI plays. The other types hold the facts of the world.

Each entry is made of panels, such as Personality, Speech Style, Knowledge or Relationships, plus panels the author names. Visibility is set per panel, not per entry.

| Setting | When the AI reads it | Who else can read it | Good for |
| :--- | :--- | :--- | :--- |
| Always | On every reply | Players of a Playable World, unless guarded | Rules the whole story depends on |
| On stage | Only when that character is in the scene | Players of a Playable World, unless guarded | Voice, personality, what one character knows |
| Private | Never | Nobody, it is the author's notes | Ideas not decided yet, reminders |
| Starred entry | Always in the AI's context | Same as its panels | The few facts the AI must never miss |
| Guarded panel | The AI still uses it to write | Not players | Twists and the author's craft in a Playable World |

On stage depends on the In this scene row above the reply line. The AI reads the full sheet of every character on stage and keeps the rest of the Wiki backstage. When a character dies or leaves for good, the AI takes them off stage, and Bring back undoes it.

## A real example: The Crown's Auditor Keeps Building Canals by Accident

[The Crown's Auditor Keeps Building Canals by Accident](https://lunafic.ai/scenarios/the-crown-s-auditor-keeps-building-canals-by-accid) is an original fantasy comedy on Lunafic, part of our Vaelmere series. The player is Percy Hawe, a Crown auditor sent to count the Reach, a small realm that runs mostly on machines instead of magic. He has sixty days to file one number. These open panels show where a story like this keeps its rules, dates and mood.

- **A rule with a price.** The Lore entry The Audit explains the count in its Content panel, including the line that hangs over every chapter: "A ward that fails during the count is written as failed; a death proves the realm cannot keep its people."
- **A calendar.** The same entry has a Calendar panel with story beats by days left, such as "30: in front of the count, the Duke announces the Dry Month." A sixty-day story needs its dates in one fixed place more than it needs them in the chat.
- **An instruction about tone.** The Lore entry The Dry Month has a panel called What it costs. It lists what a month without magic takes away, then ends with a line meant for whoever writes the scene: "Write it as harm, plainly, never as spectacle." A panel can steer how the AI writes, not only what is true.
- **A voice for a crowd.** The Lore entry The Works has a panel called How the Works talk. It gives the wall crews and builders one shared way of speaking, flat and blunt about bad work, with the rule "Never insult a plan on the wall; always the work under it."
- **A hidden half.** The Lore entry The Charter of the Reach has an open Content panel with the public clauses, ending with "The houses read a death warrant on a sixty-day fuse." A second panel holds the clause nobody read. It is guarded, so players cannot open it, and the AI still writes with it.

This guide does not list which visibility each panel uses. The point is the kind of fact each one holds.

## Constraints and trade-offs

- **Every panel has a cost.** A panel the AI reads costs context on every reply, in every story played in that world. The docs advise the smallest Wiki that makes the voices ring true.
- **Sorting is the author's job.** Too much on Always is paid for on every reply, and a key rule set to Private never reaches the AI.
- **The Wiki does not follow the story.** It holds what is true when a story starts. What happens in play is kept by [story memory](https://lunafic.ai/docs/story-memory), separately for each story. One bridge exists: nicknames that characters start using are saved for that story, and in your own world Save to Wiki adds one to a character's Relationships.
- **Slips still happen.** A clear Wiki makes mistakes rarer, not impossible. A note fixes one reply, and a fixed panel fixes every later scene. Wrong voices usually trace back to thin Speech Style or Personality panels.
- **Guarded hides text, not ideas.** A sharp player can still guess a twist.
- **Plan limits.** The Free plan allows up to 50 Wiki entries, with 20,000 AI usage a month and the Flash model. Paid plans have no Wiki entry limit.

## Sorting a fact: a short checklist

Ask in this order:

1. Must every scene obey it? Put it on an Always panel, and star the entry if the story breaks without it.
2. Does it matter only when one character is present, like a voice, a habit or what they know? Put it on an On stage panel of that character.
3. Is it a reminder for you, or an idea you have not decided? Set it to Private.
4. In a Playable World, would reading it spoil the story? Guard it.
5. Did it happen during play, not before the story? It belongs in a story note, not the Wiki.

Then play one scene, find the line where a voice or a fact went wrong, and fix the panel behind it. More detail is in the docs: [The Wiki](https://lunafic.ai/docs/the-wiki), [Build a character the AI can play](https://lunafic.ai/docs/building-characters) and [Keep your Wiki lean](https://lunafic.ai/docs/world-bible-best-practices).

## Frequently asked questions

### Is the whole Wiki sent to the AI on every reply?

No. Always panels and starred entries are sent on every reply. On stage panels are sent only while that character is in the scene, and Private panels are never sent.

### What happens when the story changes a fact that is in the Wiki?

That story's memory keeps the change. The Wiki stays as the author wrote it, so other stories in the world are not affected. If the change should hold for every new story, the author edits the Wiki.

### How large can a Lunafic Wiki be?

Up to 50 entries on the Free plan and no entry limit on paid plans. In practice the real limit is context: each panel the AI reads is paid for on every reply.

### Can lore from another app be brought in?

Yes. Paste notes and Lunafic detects a whole world in the text and offers to import it. Import Characters copies characters from another world you can open. Chat logs go through [Move your chats](https://lunafic.ai/docs/import-your-chats), which takes a pasted log or a SillyTavern .jsonl file.

## Related

- [Best AI Apps for Writing Anime Fanfiction, Compared by How You Write](https://lunafic-ai.github.io/roleplay/guides/ai-anime-fanfiction-apps/)
- [The World Bible: An AI Roleplay Wiki the AI Actually Reads](https://lunafic.ai/blog/ai-roleplay-world-bible-wiki) (Lunafic blog)
- [How to Make a Worldbuilding Sheet for Your Story or Roleplay](https://lunafic.ai/blog/worldbuilding-sheet-template) (Lunafic blog)
- [AI roleplay with long-term memory that keeps the whole story](https://lunafic.ai/blog/ai-roleplay-long-term-memory) (Lunafic blog)
