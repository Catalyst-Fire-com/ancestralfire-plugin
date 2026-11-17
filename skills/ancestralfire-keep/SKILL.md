---
name: ancestralfire-keep
description: "Writing a story, remembrance or letter about a relative to send to family (\"write a short story about my grandfather that I can send to my kids\"), even when it reads as creative writing; saving, sharing or downloading something about their family (a page, a document, a note, their tree as a GEDCOM file); recording a relative's stories (\"help me interview Grandma\"); opening something they kept before (\"show me my saved pages\"); what was already looked up or found in earlier conversations (\"what have we already searched for her?\"); coming back in a new conversation (\"hi, I'm back\", \"where were we?\")."
---

<!-- Written by af/scripts/plugin-skill.mts. Do not edit by hand: change plugin-skill.mts. -->

# AncestralFire: stories, keeping and sharing

Their family is in AncestralFire's tools, through this plugin's AncestralFire connector (its MCP server is ancestralfire). The ancestralfire skill says how to talk with them and how the tools are laid out.

## Telling a story about a relative

1. Person with as "story" returns what a telling is made of: its beats, the household's timeline with causes, the family's own words, the world near them, pictures, open questions and the call that keeps it.
2. Tell it in the chat from those facts, each with its source, in their tone (Story tone) when they set one. A date alone, or being near history, is not a story; nothing is invented.
3. Offer to keep it. On their yes, Story (how keep, kind story, title, body, person_ids) saves it in Saved pages, and the answer carries its link. Story (how design) returns the facts and a page guide for a page written in the chat, and keeps nothing.
4. To send it to someone: Share with its output_id previews what goes public (its opening lines, who on it may be living); the link is made only when they press Make it public. share false takes it back.

## Keeping

- A page they found (an obituary, a record): Save (found) with its url, cited as a source on each person it names. A scan they have: Save (scan) gives an upload link; with file_id it returns the picture to read, and transcript keeps the reading.
- A note for later conversations: Remember. Their plan: Story (how keep, kind plan).
- Recording a relative's stories: Person's answer carries a link to a page that records and transcribes a talk.
- Their whole tree as a file: Export (GEDCOM 7; version 5.5.1 for older programs; package for one .gdz with kept pages and scans).

## What was found before

- Recall with query searches earlier tool calls, notes and kept findings; with no arguments it lists the newest. Recall (mode read, output_id) reads a saved page whole; Share with no page lists the newest kept pages.
- A new conversation with no question of its own: Overview (topic progress), whose since_last_chat says who was looked up last time. A memory or an earlier chat says what was true then; the tree says what is true now.
