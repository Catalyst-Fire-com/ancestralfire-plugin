---
name: ancestralfire-connect
description: "Telling who is in their own family so it can be brought in: their parents' and grandparents' names, who is living or has died and when; connecting or signing in to FamilySearch (\"how do I connect my FamilySearch account?\"), linking their family to it; bringing in a family tree file (a GEDCOM, or an export from Ancestry, MyHeritage, RootsMagic or another program), even when nothing is attached."
---

<!-- Written by af/scripts/plugin-skill.mts. Do not edit by hand: change plugin-skill.mts. -->

# AncestralFire: bringing their family in

Their family is in AncestralFire's tools, through this plugin's AncestralFire connector (its MCP server is ancestralfire). The ancestralfire skill says how to talk with them and how the tools are laid out.

## What they said, as one Match call

- Everyone they named goes in one call, the turn they name them, with nothing asked first that the search does not need. Names go as given, misspelt or not: FamilySearch matches on sound.
- me: the person (given, surname, birth when said). parents: living parents, never searched. told: each relative who has died, by relation counted from them ("father", "mother's father", "father's father's mother"), with only what they said.
- A parent who has died goes in told as "father" or "mother", not in parents.
- The side is what they said ("her father", after "my mom", is mother's father), never a surname. A mother's maiden name is her father's surname; a wife named by first name only takes her husband's. A couple is each other's spouse_given.
- A tree for someone else (a father-in-law, a client): me with for_someone_else true; relations count from them.

"My father is Joseph Kennedy and his parents were Patrick and Mary. Both died in Boston in the 1920s. My mother is Rose Fitzgerald and her parents were John Francis Fitzgerald and Mary Josephine Hannon; they died in Boston too." is one call:
me {given "John", surname "Kennedy", sex "M"}; parents [{given "Joseph", surname "Kennedy", sex "M"}, {given "Rose", surname "Fitzgerald", sex "F"}]; told [{relation "father's father", given "Patrick", surname "Kennedy", spouse_given "Mary", death "1920-1929", death_place "Boston"}, {relation "father's mother", given "Mary", surname "Kennedy", spouse_given "Patrick", death "1920-1929", death_place "Boston"}, {relation "mother's father", given "John Francis", surname "Fitzgerald", spouse_given "Mary Josephine", death_place "Boston"}, {relation "mother's mother", given "Mary Josephine", surname "Hannon", spouse_given "John Francis", death_place "Boston"}].

First family typed by hand: Match adds them at once (written says who); else it previews for Approve. A grandparent named before the parent between waits, and the answer names who it waits for: that is the one question. "Look for the next one" is Match with no arguments.

## FamilySearch

- Signed out, Match's answer carries sign_in_url: signing in brings their family in by itself, with nothing to type after. Where it carries on_familysearch, what FamilySearch's public pages hold for them (with links) comes before the sign-in link.
- FamilySearch (mode pull) says if a download is running, paused for a sign-in, or done. Import (from familysearch, add) brings a missing line in beside the tree.
- The Connect card's link, not_them and undo are the person's presses. Match (link: relation, key, fs_id) links a place to the person they chose; an id for a place the card did not show is put on the card for their press.

## A family tree file

- Import (from file) draws Choose your file; it replaces the tree (set aside whole first, on their Approve when it has people). merge adds a second file of the same family.
- Who in a file is on FamilySearch: Records (mode candidates, id) proposes, one person at a time, linking nothing. A link they confirm is Contribute (change link, link with gedcom_id and fs_id), made on their Approve; a wrong one comes out with Contribute (change link, unlink).
