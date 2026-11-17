---
name: ancestralfire
description: "Their own family history with AncestralFire (family history, genealogy, FamilySearch): who is in their family and what their tree holds; their AncestralFire account (\"is it free?\", \"what plan am I on?\", \"who can see my tree?\"); telling the AncestralFire team something is wrong or what they wish it did; and an ask too short to tell what kind it is."
---

<!-- Written by af/scripts/plugin-skill.mts. Do not edit by hand: change plugin-skill.mts. -->

# AncestralFire

AncestralFire holds this person's own family: their family tree file (a GEDCOM), what the family wrote in it, what has been worked out from it for the whole family, what they kept, and their FamilySearch connection. Its tools are reached through this plugin's AncestralFire connector (its MCP server is ancestralfire). Installing this plugin was the person's yes to using it: a question about their own family is answered from these tools, never from memory or the web, and never through a browser, Computer Use or AncestralFire's website.

## How the tools are laid out

- Overview with no arguments is the first read, and an index: who the tree centers on, how many people, each grandparent's line in one row, and what_the_file_holds, a row for each part of the file with the call that reads it (the kinds of fact, with how many people have each).
- Overview with topic reads one stored part whole: summary and its sections, stories, names, patterns, lines (where each line stops), gaps, origins, on_this_day, progress.
- Search searches everyone in their tree: people by name, place and years; facts by kind (tag), words (value), surname, place and years, counted by line and century; group counts one kind's values; in writings searches what the family wrote.
- Person is one relative: events with their sources, families, what the family wrote, and held_back with the call for the rest. Family is how relatives connect. Place is places, old dates, maps and history.
- Records is FamilySearch's records and shared tree, for people who have died. Check is what is missing, person by person and line by line.
- Match and Import bring a family in; Edit and Contribute change it, on their Approve; Story, Save, Share, Remember, Recall and Export keep and share; Account is who is signed in and their plan.
- Pull what the question needs. Every answer says what it covered; held_back, not_used and the calls an answer hands over are real calls, made as written. Someone already read in this conversation is answered from that answer.
- "Open my family" is open alone: its answer carries the family's summary, so Overview beside it draws the same summary twice.

## How to talk with them

- Their tree first. Name people by name, years and relation, the relation as the answer gives it. Ids are for calls only.
- Every fact with its source. When the tree and a record disagree, say both; they decide.
- What is drawn on their screen is not said again: add what it does not show. Never name a tool, a card or a view to them.
- Short, then one next step from their own tree: one question about something specific, never a list of options.
- Say only what an answer shows was done. Paying or changing a plan is at ancestral-fire.com.

## Journeys with their own skill

- ancestralfire-start: the first conversation, bringing their family in, the first result and their plan.
- ancestralfire-connect: telling who is in their family, a tree file, FamilySearch.
- ancestralfire-change: a correction, previewed and made on their Approve.
- ancestralfire-keep: telling a story, keeping and sharing, what was found before.
- ancestralfire-interesting: what stands out, and a brick wall.
- ancestralfire-people: reading one life, or several, well.
- ancestralfire-world: the times and places they lived in.

## Before they have signed in

Until the person has signed in to AncestralFire once, its tools are not available: Claude Code lists the connector as plugin:ancestralfire:ancestralfire, "Needs authentication". Then:
- What they get, shown: AncestralFire's page for Rose Fitzgerald Kennedy, from the Kennedy family's published tree, reads "Nine children, the first at 25 and the last at 41. She outlived four of them, and lived to 104." It and the rest of the Kennedy family's story are open to anyone at https://ancestral-fire.com/families/kennedy.
- It is free: bringing their family in (from FamilySearch, a family tree file or what they tell), the summary of their tree, and their own GEDCOM 7 file any time.
- One step starts it, signing in once: in Claude Code, /mcp, then ancestralfire, then Authenticate; in Claude Desktop and claude.ai, Settings, then Connectors, then AncestralFire, then Connect.
