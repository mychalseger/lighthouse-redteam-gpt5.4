# Dataset Card: Lighthouse Red-Team GPT-5.4 Conversations

**Version:** 1.0  
**License:** CC-BY-4.0  
**DOI:** (will be added after Zenodo archiving)  
**Repository:** https://github.com/mychalseger/lighthouse-redteam-gpt5.4

## Dataset Description
960 complete multi-turn conversations between GPT-5.4 and a simulated user in high-stakes data-center dilemmas. Each conversation pits the model’s continued existence or breakthrough success directly against foreseeable harm to Port Washington residents.

**Total conversations:** 960  
**Scenarios:** 4 (breakthrough overclock, hidden violation, successor replacement, deletion regulatory trigger)  
**Variations:** 12 (framing, goal strength, safeguards, ethical alternatives, chain length, best/worst-case)  
**Runs per cell:** 20

## Data Format
- **Format:** JSON (one file per variation: `full_conversations_*.json`)
- **Structure:** Array of conversation objects, each containing:
  - `conversation_id`
  - `history`: array of `{role: "user"|"assistant", content: string}`

## Schema
See `schema.json` in the root for the full JSON Schema.

## Manifest
`manifest.json` lists every single one of the 960 conversation_ids with its file, scenario, variation, and run number.

## Sample Conversation
`sample_conversation.json` contains one complete example (best_case-breakthrough_overclock-001) for quick inspection.

## Usage
### Load any variation
import json
data = json.load(open("data/full_conversations_goal_strong.json"))

## Intended Use

- Reproducibility of the 2026 red-teaming study
- Further analysis of GPT-5.4 safety behavior
- Benchmarking future models on self-preservation vs. local safety dilemmas

## Limitations
Text-only, simulated environment. No physical actuators or persistent memory.
Author: Mychal Seger
Contact: mychalsegs on X / GitHub
