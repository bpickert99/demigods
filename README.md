# Demigods Campaign

A real-time campaign management tool for a Forged in the Dark TTRPG campaign set in modern North America.

## Player Screens
- `lewis.html` — Lewis, Child of the Morrigan
- `murphy.html` — Murphy, Child of Brigid
- `kara.html` — Kara, Child of Goibniu
- `finn.html` — Finn, Púca

## DM Screen
- `dm.html` — Weaver screen (initiative, party overview, NPC tracker, roll approvals)

## How It Works
All files connect to a shared Supabase database. Changes made on any screen update in real time on all other screens. Data persists between sessions automatically.

## Setup
No build step required. All files are self-contained HTML. Deploy via GitHub Pages.
