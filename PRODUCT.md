# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Single user (the owner, Harris). This is a personal Firefox start page, not a multi-user product.

## Product Purpose

A custom Firefox homepage/new-tab replacement that gets the user to their most-used links in one glance and one click: YouTube playlists, Notion pages, and general bookmarks. Success = faster than digging through the bookmarks bar or typing a search.

## Positioning

Personal tool, not a competitive product — no market positioning needed.

## Operating Context

Loads as the browser's home page / new tab in Firefox on Linux (Arch). Static local HTML file, no server, no build step. Viewed many times a day, briefly, before navigating away — glanceability matters more than depth.

## Capabilities and Constraints

- Three link sections: YouTube playlists (quick-select), Notion links, general bookmarks.
- Single static HTML/CSS/JS file (plus assets), no framework, no backend.
- Set as Firefox's homepage via `browser.startup.homepage` / Settings > Home.
- Exact links/playlists to populate each section: pending user input.

## Brand Commitments

None (personal project). Visual reference supplied by user: dark, Arch Linux/terminal-rice aesthetic, monospace, pink/purple accents, `$HOME`-style prompt greeting, live clock, tiled/textured background with a piece of art. Visual direction is handled in design work, not here.

## Evidence on Hand

Reference screenshot provided by user showing the target aesthetic (terminal-style startpage, `~/general`, `~/devel`, `~/school`, `~/reddit` sections, live clock, welcome banner). No existing bookmarks/link data on hand yet.

## Product Principles

- Glanceable over exhaustive — a handful of curated links per section, not a full bookmark dump.
- Zero dependencies — plain HTML/CSS/JS, opens instantly as a local file.
- Personality in the details (terminal/rice aesthetic) without hurting scan speed.
