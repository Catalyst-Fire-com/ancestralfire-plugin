---
name: ancestralfire-change
description: "Adding, fixing, correcting, removing or merging someone or something in their own family tree or on FamilySearch (\"fix his birth year\", \"these two are the same person\", \"that's the wrong date\"); putting a story, photo or document they have as a file onto FamilySearch as a memory."
---

<!-- Written by af/scripts/plugin-skill.mts. Do not edit by hand: change plugin-skill.mts. -->

# AncestralFire: a correction

Their family is in AncestralFire's tools, through this plugin's AncestralFire connector (its MCP server is ancestralfire). The ancestralfire skill says how to talk with them and how the tools are laid out.

From their words to their Approve.

1. Read what the change touches first: Person, or Family for a relationship, so the preview names the right person. When others in the tree share the name, say which by years.
2. Their own tree is Edit; FamilySearch's shared tree is Contribute. A correction said in one sentence is one Edit call: changes lists every step (move_marriage, set_event, a person added, a name, a parent link), reason holds their words and is written into their file as a note, and cite names a source.
3. The answer is a preview, old beside new. It is made when they press Approve. Where the answer says no card is drawn, it is made by a second call carrying the preview's confirm_token, after their yes. Until an answer says it was written, nothing has changed.
4. A single correction can be undone on its card for 30 minutes; a moved marriage, a removal or a merge cannot.

- Which date is wrong: a finding's likely says what is most likely wrong and what it rests on, and its fix is an Edit call that previews, given only where the tree holds the value. A fix is offered when a record settles it; "nothing in the tree says which" is said as that.
- Contribute changes FamilySearch under their name: correct_fact, add_person, merge, attach_relative, detach_relative, attach_source, add_memory. Each is a preview made on their Approve, and nothing about a living person is sent.
- A story, photo or document they have as a file, for FamilySearch: Contribute (change add_memory). Its first call gives them the page to pick the file; it is never looked for in this chat.
- Which person is them: Edit (change home).
- A kept finding that is wrong (an article about another family): Finding with status wrong, wrong_person or obsolete, and note for their reason.
