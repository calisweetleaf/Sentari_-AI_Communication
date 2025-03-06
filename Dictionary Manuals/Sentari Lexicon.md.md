# Sentari Lexicon

## Overview
This lexicon is a **comprehensive list of all Sentari words**, categorized by their **symbol, part of speech, and definition.**  

## 🔍 Dynamic Word List
Below is a **live-updating table** of Sentari words.

```dataview
TABLE symbol, part_of_speech, definition  
FROM "Dictionary Entries"
WHERE symbol AND part_of_speech
SORT symbol ASC
