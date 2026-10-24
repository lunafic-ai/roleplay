---
title: "Japanese Dialogue in AI Roleplay: How the Dual-Language Settings Work"
description: "How AI roleplay shows Japanese dialogue with an English translation: the three language dials in Lunafic, each dialogue format, which languages, and limits."
date: 2026-10-25
last_checked: 2026-10-25
---

> **Summary.** An AI roleplay app can keep its characters speaking Japanese while the narration and a translation of every spoken line stay in English. In Lunafic this is controlled by three settings in Narrative settings: Character Language, Narrative Language and Dialogue Format.

> Written by the Lunafic team. [Lunafic](https://lunafic.ai) is our AI roleplay app, and this guide describes it alongside the general method. Facts last checked October 25, 2026.

## Overview

Dual-language dialogue separates two things that most chat tools treat as one: the language the characters speak, and the language the story is told in. A single Language option cannot say "Japanese speech inside an English story". It turns the whole page Japanese, or it turns the characters into English speakers.

The general method has three parts, and they apply to any tool:

1. **A fixed language rule.** Spoken lines use one language. Narration and action use another.
2. **A fixed display pattern.** Every spoken line appears the same way, for example the line in romaji with the translation under it.
3. **A voice description.** The character sheet says how the character sounds in that language, such as their word for "I" and their sentence endings.

In Lunafic, the first two parts are settings, and the third lives in the character's Speech Style and Speech Examples panels in the Wiki.

## The three language dials

The dials sit in Narrative settings. Open the right panel, find **This world**, open **Narrative settings** and go to the **Language** tab. The row in the right panel shows the current pair, for example "English plus English".

| Dial | What it controls | Example value |
| :--- | :--- | :--- |
| Character Language | The language the characters speak in dialogue | Japanese |
| Narrative Language | The narration, the action between lines, and the language of the translations | English |
| Dialogue Format | How each spoken line is shown to the reader | Romanized plus Translation |

Narrative settings has two other tabs. **Writing** covers story feel, narration and fine tuning. **Save** covers auto save. They do not change languages.

## The three dialogue formats

| Format | What the reader sees | Suited to |
| :--- | :--- | :--- |
| Native Only | The line in the character language and its own script, with no translation | Readers who read the language. Also the only format when both languages are the same. |
| Romanized plus Translation | The line in Latin letters (romaji, for Japanese), with the translation in brackets under it | Readers who want the sound of the line and its meaning |
| Translation Only | Only the translation, in the narrative language. The romaji is removed. | Fast reading in long sessions |

Here is one line in each format. It comes from Euler Florence's Speech Examples in [Vengeance and Love Languages](https://lunafic.ai/scenarios/vengeance-and-love-language), an original world by the Lunafic team. The layout is simplified, and the Japanese script row is our own transcription, because the sheet stores the romaji and the English.

| Format | The line |
| :--- | :--- |
| Native Only | もういいわ。勝手にしなさい。 |
| Romanized plus Translation | "Mou ii wa. Katte ni shinasai." [Enough. Do as you please.] |
| Translation Only | "Enough. Do as you please." |

Japanese lines in dual language also carry a small speaker button at the end. It reads the line aloud with the voice built into the phone or computer, so it uses no AI usage.

## Which languages, and which formats appear

The docs name Japanese, Korean, Russian, Indonesian and English as examples. The full list is the dropdown itself.

| Setup | Example | Formats offered |
| :--- | :--- | :--- |
| Same language for characters and narrative | English plus English | Native Only |
| Character language written in another script | Japanese, Korean or Russian characters in an English story | Native Only, Romanized plus Translation, Translation Only |
| Different language in the Latin alphabet | Indonesian characters in an English story | Romanized plus Translation does not appear |

Indonesian characters have one extra choice, **formality**: formal, informal or casual slang. The characters follow the level that is picked.

## Step by step: Japanese dialogue in a Private world

1. **Start a Private world.** Give it a name, one character, and who you are. Chapter 1 opens.
2. **Open the Language tab.** Right panel, This world, Narrative settings, Language.
3. **Set Character Language to Japanese.** The characters now speak Japanese.
4. **Set Narrative Language to English.** Narration and translations follow this dial.
5. **Set Dialogue Format to Romanized plus Translation.** Each spoken line now shows romaji with the English under it.
6. **Describe the voice.** In the Wiki, write the character's Speech Style (sentence endings, word for "I", rhythm) and at least five Speech Examples that sound different from each other. The [romaji lookup guide](https://lunafic-ai.github.io/roleplay/guides/romaji-and-translation/) lists the common pieces.
7. **Test one short scene.** If the voice comes out flat, fix the panel and run the scene again.

New Private worlds start with the Story language chosen under Settings, Language, which is English by default. The dials are saved with the story, so they follow the player to another device.

## Playable World or Private world

| Question | Private world (your own) | Playable World (built by an author) |
| :--- | :--- | :--- |
| Who sets the dials | You, in Narrative settings | The author, in the builder's Languages and rules step |
| When | Any time during the story | While building the world. The story opens with the author's setup. |
| The character sheets | You can edit the Wiki, including Speech Style | The Wiki is read only for the player |
| Who you play | MC Mode or Author Mode | The role you picked, in MC Mode |

The right panel of a Playable World also lists the narrative settings under This world. Vengeance and Love Languages is set to Japanese characters, English narration and Romanized plus Translation. The player takes the role of Haru, the scholarship student, and Euler Florence answers in romaji with the English under each line.

## What the settings do not change

- **The quality of the voice.** The dials choose the language. How the character sounds in it comes from the Speech Style and Speech Examples panels.
- **Who writes your character.** In MC Mode the AI never writes your character's dialogue, thoughts or actions, in any language.
- **The narration.** Dialogue Format changes only spoken lines. Narration always follows Narrative Language.
- **Older lines.** The docs describe the format as how each line reaches the reader. They do not say whether lines already in the story are redrawn after a change.

## Limits

- **The AI's Japanese is not perfect.** A line can come out stiff, too polite for the character, or wrong. Check the translation, retry the reply, or edit the line by hand, which uses no AI usage.
- **Romaji spelling can vary.** The AI writes the romaji, so a long vowel can appear as "ou" in one line and "oo" in another.
- **It is not a language course.** Nothing checks your Japanese or teaches grammar.
- **Romanized plus Translation needs another script.** It is offered for languages like Japanese, Korean and Russian only.
- **Playable World languages belong to the author.** The setup a world opens with is the author's choice.

## FAQ

### Do I need to read Japanese to use this?

No. Romanized plus Translation shows how each line sounds in Latin letters, and the English translation sits under it.

### Can the romaji be turned off?

Yes. Native Only shows only the Japanese script, and Translation Only shows only the English.

### Does it work for languages other than Japanese?

Yes. The docs name Korean and Russian as other languages that get the romanized format, and Indonesian with a formality choice.

### Does the read-aloud button cost AI usage?

No. It uses the voice built into the device.

## Related

- [Romaji and translation in AI roleplay: a lookup table for anime dialogue](https://lunafic-ai.github.io/roleplay/guides/romaji-and-translation/)
- [AI roleplay with Japanese dialogue and the English translation under every line](https://lunafic.ai/blog/ai-roleplay-japanese-dialogue-translation)
- [AI roleplay in Japanese with English translation side by side](https://lunafic.ai/blog/ai-roleplay-in-japanese-with-english-translation-side-by-side)
- [Narrative settings, the three language dials (docs)](https://lunafic.ai/docs/narrative-settings)
