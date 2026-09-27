# ngoma - AI Scouting for Music Platforms

> *Hear the next breakout before anyone else does.*

ngoma is an AI scout for music platforms. It listens to every new track, scores its breakout potential on five signals, and routes the best songs to where they can grow: remix challenges, playlists, sync briefs and artist programs.

## Live demo

👉 **[View live site](https://lorrancia.github.io/ngoma/)**

Press play on any track. Every preview is synthesized live in your browser.

## What's in this repo

```
ngoma/
├── index.html          # Full interactive concept site
├── README.md           # This file
└── LICENSE
```

## Features demonstrated

- **Playable previews** - each track has its own short loop generated with the Web Audio API, with a real-time spectrum visualizer
- **Live re-ranking feed** - switch lanes and the tracklist animates into its new order
- **Mixing-desk scoring model** - drag the faders to reweight the five signals and watch the leaderboard re-rank as you mix
- **Explainable scores** - per-track signal breakdown, a "why it ranks here" summary and a next best move
- **Threshold alerts** - see which tracks crossed the score threshold in each lane
- **Tiered pricing** - Creator / Scout / Label & Sync, plus a platform partnership model

## The AI scoring model

ngoma outputs a 0–100 score from 5 signals, with **weights that shift by lane**, because a remix magnet and a sync-ready cue are different kinds of hit.

| Signal | Short-form viral | Playlist & streaming | Sync & licensing | Artist development |
|---|---|---|---|---|
| Hook pull - replays and saves within a day | 30 pts | 35 pts | 15 pts | 15 pts |
| Remix pull - covers, remixes and edits per 1,000 plays | 30 pts | 10 pts | 5 pts | 20 pts |
| Momentum - week-over-week growth | 25 pts | 20 pts | 5 pts | 15 pts |
| Creator consistency - catalog depth and a recognizable voice | 5 pts | 10 pts | 25 pts | 35 pts |
| Brief fit - match to playlist gaps, sync briefs and rising moods | 10 pts | 25 pts | 50 pts | 15 pts |

## Where tracks go next

| Lane | Next best move |
|---|---|
| Short-form viral | Feature in a remix challenge |
| Playlist & streaming | Send to distribution with release-ready metadata |
| Sync & licensing | Pitch to matching open briefs |
| Artist development | Invite to an artist incubator cohort |

## Business model

| Tier | Price | Target |
|---|---|---|
| Creator | Free | Anyone releasing music |
| Scout | $49/mo | Managers, curators and independent A&R |
| Label & Sync | $299/mo | Labels, sync agencies and brands |
| Platform partnership | Per active creator + revenue share on sync | Music-making platforms running Ngoma natively |

## Responsible by design

Scoring is opt-in, creators keep their rights, and every track is screened for close similarity to existing catalog before it's routed anywhere.

## Built with

- Vanilla HTML, CSS, JavaScript - no frameworks, no build step
- Web Audio API for the synthesized previews and visualizer
- Bricolage Grotesque typeface

## About

Built as a product concept and portfolio piece. All tracks, creators and figures are illustrative.

The name *ngoma* means drum, and the song and dance that go with it, in many Bantu languages.

---

*© 2026 Ngoma - Concept*
