# CLAUDE.md

## What this repository is

Design concepts for Seed Ship, a game about an intelligent AI ship that cultivates and
collects alien life across a galaxy.

## How it's structured, and why

This is deliberately **additive, not a wiki**. `docs/` holds dated markdown files
(`YYYY-MM-DD-title.md`), each one a snapshot of the design thinking from a particular
session: a new angle, a refinement, a deep dive on some subsystem. A later file may
extend, refine, or outright contradict an earlier one, and that's fine and expected.
There is no single merged, fully-reconciled canonical document yet, and reconciling
everything into one tidy structure (a proper wiki, a glossary, cross-linked topic
pages) is intentionally deferred until there's enough material for that effort to be
worth it. Don't try to force that structure prematurely.

Practically, this means:

- To understand the current state of the design, read across the dated files in
  `docs/`, newest first, rather than expecting one authoritative entry point.
- When adding a new idea or exploring a new angle, prefer creating a **new** dated
  file in `docs/` over trying to precisely slot the addition into the exact right
  paragraph of an existing file. Precision editing of an existing file is fine when
  the user explicitly asks for it (e.g. "add a sentence about X to file Y").
- Don't feel obliged to flag or resolve every contradiction between files. Light
  flagging is useful; heavy reconciliation is not the point right now.
- `scratchpad.txt` is an unstructured inbox for raw fragments the author hasn't
  synthesized yet. Treat it as lower-confidence and less complete than anything in
  `docs/`.

## Writing style

- Never use em dashes (—) or en dashes (–) in any written content. Use a regular hyphen (-) instead.
- Don't hard-wrap text inside a paragraph or list item. Each paragraph and each list item should be written as a single line, with no manual line breaks in the middle of it - files are read with automatic soft-wrap enabled, so hard line breaks just fragment a paragraph across multiple lines in the source. Blank lines between paragraphs/list items are still used as normal.