# AncestralFire

There's more to your family tree than names and dates.

This plugin connects Claude to AncestralFire (https://ancestral-fire.com): your own family tree, and the shared FamilySearch Family Tree through your FamilySearch sign-in. Changes to FamilySearch are made only when you approve them.

## What you can ask

- "What stands out in my family?"
- "Where did my great-grandparents live?"
- "Tell me about my grandmother's parents."

Claude reads your tree, answers with the sources behind what it finds, and, where Claude can show them, draws the people it found as a fan, a map or a page about each person.

In Claude Code the answers come as text; the fan, the map and the person cards draw in Claude on the web, the desktop app and mobile.

## Install

- **Claude (claude.ai, the desktop app and mobile):** open [AncestralFire in Claude's directory](https://claude.ai/plugins/id/b459138e-f102-4b1a-ace5-9968e9ee1f85%40anthropic-plugin-directory), press **Add**, then **Connect** and sign in. Then ask Claude: "Who's in my family?"
- **Claude Code:** `/plugin marketplace add Catalyst-Fire-com/ancestralfire-plugin`, then `/plugin install ancestralfire@ancestralfire`.

## Getting started

1. Sign in to AncestralFire when Claude asks. Then start your tree: tell Claude about a grandparent or great-grandparent who has passed away (a name and about when), sign in to FamilySearch, or bring a family-tree file.
2. Searching and understanding your family tree is free: bring your family in, ask about the people in it, download your own GEDCOM 7 file, and get a summary of your tree.

## Where your data goes

Most of a family tree is people long gone, from public records; the living people in it stay private: a living relative goes to FamilySearch only when you approve it, marked living, where it is not shown publicly. Your tree is yours alone: we never sell it or pool it with anyone else's.

- **Claude** reads what a question needs from your tree, and any scan you add in the chat, under the terms you accepted with Anthropic.
- **AncestralFire** keeps your tree in a database that belongs to your account only, and runs the small models that search your notes and double-check a change before you approve it.
- **FamilySearch**, only if you connect it: we search it for the people in your tree who have passed away, and a change to the shared tree is written only when you approve it, under your own FamilySearch account.
- **Outside sources**, asked only what a question needs: Wikipedia, Wikidata, Wikisource, the Library of Congress, YouTube, and the map tiles of OpenFreeMap and OpenHistoricalMap.
- **WorkOS** signs you in, and **Stripe** takes payment if you subscribe.

Delete your account in Settings and your tree, conversations and saved pages go with it, at once; what Stripe and WorkOS keep under their own terms is on the Privacy page: https://ancestral-fire.com/privacy. Help: https://ancestral-fire.com/help, or support@ancestral-fire.com.
