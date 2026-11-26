# Golem Pens Relaunch Dashboard

_Last updated 2026-11-26 10:51_

Status key: ⬜ not started · 🔄 in progress · ✅ complete · 🚫 blocked · ⏸️ paused

|  | Tasks | Done | In progress | Progress |
| ---- | ----: | ---: | ----------: | -------- |
| ✒️ **Pen production** | 5 | 0 | 2 | ░░░░░░░░░░   0% |
| 🛠️ **Lathe configuration** | 4 | 2 | 0 | ▓▓▓▓▓░░░░░  50% |
| ✏️ **Pen designs** | 6 | 1 | 2 | ▓▓░░░░░░░░  17% |
| 🔩 **Pen tooling** | 7 | 0 | 0 | ░░░░░░░░░░   0% |
| 🧰 **Lathe tools** | 9 | 7 | 0 | ▓▓▓▓▓▓▓▓░░  78% |
| ⬆️ **Upgrades** | 4 | 0 | 0 | ░░░░░░░░░░   0% |
| **TOTAL** | **35** | **10** | **4** | **▓▓▓░░░░░░░  29%** |

## Pen production

```
○─ 🔄 Lathe configuration
│
○─ 🔄 Pen designs
│
○─ 🚫 Pen tooling
│
○─ 🚫 Prototypes
│
○─ 🎯 Production
```

## Lathe configuration

```
●─ ✅ Bed twist
│
○─ 🚫 Headstock alignment
│
○─ 🚫 Tailstock alignment
│
●─ ✅ Gearing configuration
```

## Backlog

#### ✒️ Pen production (0/5)

| ID | Task | Status | Blocks |
|----|------|--------|--------|
| PR1 | Lathe configuration | 🔄 | PR2 |
| PR2 | Pen designs | 🔄 | PR3 |
| PR3 | Pen tooling | 🚫 | PR4 |
| PR4 | Prototypes | 🚫 | PR5 |
| PR5 | Production | 🚫 | — |

#### 🛠️ Lathe configuration (2/4)

| ID | Task | Needs | Status | Blocks |
|----|------|-------|--------|--------|
| S1 | Bed twist | Shims ✓, V-blocks ✓, Precision level ✓, Measurement and correction ✓ | ✅ | S2 |
| S2 | Headstock alignment | Dial indicator ✓, Bar test, Cut test | 🚫 | S3 |
| S3 | Tailstock alignment | Tailstock alignment bar ✓, Cut test | 🚫 | S4, P1, P2, P3, P4, P5, P6, P7 |
| S4 | Gearing configuration | — | ✅ | — |

#### ✏️ Pen designs (1/6)

| ID | Task | Status | Blocks |
|----|------|--------|--------|
| D1 | Spindle design | ✅ | P1, P2 |
| D2 | Augur design | 🔄 | P3, P4 |
| D3 | Clips | ⬜ | — |
| D4 | Pocket | ⬜ | — |
| D5 | Big | ⬜ | — |
| D6 | Nib holder | 🔄 | — |

#### 🔩 Pen tooling (0/7)

| ID | Task | Status | Blocks |
|----|------|--------|--------|
| P1 | Spindle mandrels — Cap mandrel | 🚫 | — |
| P2 | Spindle mandrels — Body mandrel | 🚫 | — |
| P3 | Augur mandrels — Cap mandrel | 🚫 | — |
| P4 | Augur mandrels — Body mandrel | 🚫 | — |
| P5 | Section mandrels — Jowo #6 | 🚫 | — |
| P6 | Section mandrels — Bock 250 | 🚫 | — |
| P7 | Section mandrels — Bock 380 | 🚫 | — |

#### 🧰 Lathe tools (7/9)

| ID | Task | Status | Blocks |
|----|------|--------|--------|
| T1 | 3 jaw chuck | ⬜ | — |
| T2 | 4 jaw independent chuck | ⬜ | — |
| T3 | 1-2-3 blocks | ✅ | — |
| T4 | V-blocks | ✅ | — |
| T5 | Dial indicator x 2 | ✅ | — |
| T6 | Dial test indicator | ✅ | — |
| T7 | QCTP | ✅ | — |
| T8 | Collet chuck | ✅ | — |
| T9 | Alignment test bar | ✅ | — |

#### ⬆️ Upgrades (0/4)

| ID | Task | Status | Blocks |
|----|------|--------|--------|
| U1 | ELS | ⬜ | — |
| U2 | Tailstock travel | ⬜ | — |
| U3 | DRO | ⬜ | — |
| U4 | New cabinet | ⬜ | — |


## History

```
━━ 2024 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━
┃
●  Apr            Brand launch
●  Apr–Dec        Spindle OG run: GS-24-01 to GS-24-25
●  Dec 16         Spindle OG design
●  Dec 29         Augur OG design
┃
━━ 2025 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━
┃
●  Aug            Augur clip design
●  Oct            Spindle Pocket design
●  Oct            Final OG run
●  Nov            South Bend Workshop 9 lathe arrives
●  Dec–Mar 2026   A lot of tests, with the end result being that the original headstock and 1-1/8" spindle are too worn, and are not reasonable replaceable.
┃
━━ 2026 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━
┃
●  Apr            New lathe headstock replacement with a more "modern" 1-1/2" spindle.
┏━ Aug–Oct        Spindle IMP design phase
┃  ○ Aug          Spindle IMP design begins
┃  ○ Oct          Spindle IMP, nib, and feed CAD models
┗━ ○ Oct 19       Spindle IMP schematics
●  Nov 25         Inspecting and assessing bed twist
```
