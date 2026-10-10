# Notes

Claude memos and decisions for this project.

## Decisions

### 1. Source of truth (tentative)
- Goal: all three representations (visual designer, Blockly, Python text) stay in sync (round-trip, "C").
- Plan: ship one-way + Blockly first ("B"), design so round-trip stays possible.
  - the design model is the single canonical form; generator is deterministic
  - generated Python stays in a small, regular subset (one pattern per widget) so it can be parsed back later
  - model <-> Blockly bidirectional from the start
  - Python -> model later; early version may embed the model as a JSON comment block in `display.py`
