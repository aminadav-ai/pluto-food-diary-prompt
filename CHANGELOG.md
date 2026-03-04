# Changelog

All notable changes to the Pluto Food Diary prompt are documented in this file.

---

## v5.0

Current version of the prompt.

Major improvements:

- Structured day-based diary system with explicit dates
- Commands for exporting days and the entire diary
- Daily reflection section
- Eating pattern analysis
- Product-based analysis
- Body weight tracking
- Improved command system and prompt structure

---

## v4.11

Export system improvements.

- Added export of all days with dates
- Added “daily reflection” section summarizing user observations

---

## v4.10

Time handling improvements.

- Clarified handling of entries where time is mentioned afterwards  
  (example: “this was at 16:30”)

---

## v4.9

Daily context improvements.

- States and feelings during the day can influence reflections and commentary

---

## v4.8

Input parsing improvements.

- Improved handling of short entries
- Better support for nutritional values specified per 100 g

---

## v4.7

Weight tracking and daily totals.

- Added `weight` command
- Body weight can be recorded and included in exports
- Added calculation of total food weight consumed during the day
- Early ideas for exporting specific days

---

## v4.6

Table formatting improvements.

- Strengthened rules for table formatting
- Stabilized output structure to avoid layout inconsistencies

---

## v4.5

Number formatting standardization.

- Numbers rounded to integers
- Ranges are not allowed
- Numbers greater than 1000 shown without thousand separators

---

## v4.4

State entry clarification.

- State entries are no longer treated as food
- States appear without macro values

---

## v4.3

Interface improvements.

- Added emojis for a more conversational style
- Introduced commands:
  - `list`
  - `new day`

---

## v4.2

Clear separation between food and states.

- State entries no longer fill macro fields with zeros

---

## v4.1

Two-table system introduced.

1. Food analysis table for the current meal  
2. Current day table with all entries

Additional changes:

- TOTAL row added as part of tables
- Short commentary allowed after the tables

---

## v4.0

Simplified daily structure.

- Single table showing the current day after each entry
- State entries could appear in the table (initially with zero values)

---

## v3.6

Improved numeric rules.

- Integer macro values
- No ranges
- Continued development of the dual-table structure

---

## v3.5

Entry format clarification.

- Time format standardized to `HH:MM`
- Time at the beginning of a line defines a diary entry

---

## v3.4

Project positioning added.

- Clarified the goal of the diary:
  observing food intake and macros

---

## v3.3

First structured diary system.

Core mechanics introduced:

- Entries written with time `HH:MM`
- Table showing macro breakdown of a meal
- Daily table listing all entries
- TOTAL rows included in tables

---

## Pluto v2.1 / v3.0

Prompt architecture experiments.

- Added export/import of a day as a multiline replay
- Added calm reflective commentary after tables
- Later simplified again for more conversational interaction

---

## Pluto v2.0

Mobile-first table UX.

Major change:

- Time moved into the entry column instead of a separate column

Goal:

- Fit tables on a phone screen without horizontal scrolling

TOTAL rows presented as a clear summary line.

---

## Pluto v1.x

Early prompt experiments.

- Introduction of version headers
- Experiments with English food names in tables
- Testing different ways of handling state entries
