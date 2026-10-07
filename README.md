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

- **From Claude's plugin directory:** add AncestralFire under Customize > Plugins.
- **Claude (claude.ai and the desktop app):** Customize > Plugins > Add > Add marketplace, enter `Catalyst-Fire-com/ancestralfire-plugin`, then install AncestralFire.
- **Claude Code:** `/plugin marketplace add Catalyst-Fire-com/ancestralfire-plugin`, then `/plugin install ancestralfire@ancestralfire`.

## Getting started

1. Sign in to AncestralFire when Claude asks. Then connect your tree: FamilySearch, a family-tree file, or one name.
2. Free: bring your family in, download your own GEDCOM 7 file, and get a summary of your tree. Exploring it is a plan: https://ancestral-fire.com/pricing.

## Where your data goes

Most of a family tree is people long gone, from public records; the living people in it stay in your own file: we never add, change, attach or publish anything about them on FamilySearch, or search for them there. Your tree is yours alone: we never sell it or pool it with anyone else's.

- **Claude** reads what a question needs from your tree, and any scan you add in the chat, under the terms you accepted with Anthropic.
- **AncestralFire** keeps your tree in a database that belongs to your account only, and runs the small models that search your notes and double-check a change before you approve it.
- **FamilySearch**, only if you connect it: we search it for the people in your tree who have died, and a change to the shared tree is written only when you approve it, under your own FamilySearch account.
- **Outside sources**, asked only what a question needs: Wikipedia, Wikidata, Wikisource, the Library of Congress, YouTube, and the map tiles of OpenFreeMap and OpenHistoricalMap.
- **WorkOS** signs you in, and **Stripe** takes payment if you subscribe.

Delete your account in Settings and your tree, conversations and saved pages go with it, at once; what Stripe and WorkOS keep under their own terms is on the Privacy page: https://ancestral-fire.com/privacy. Help: https://ancestral-fire.com/help, or support@ancestral-fire.com.
