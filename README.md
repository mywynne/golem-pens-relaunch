# Golem Pens Relaunch Dashboard

_Last updated 2026-11-22 08:40_

Status key: ⬜ not started · 🔄 in progress · ✅ complete · 🚫 blocked · ⏸️ paused

|  | Tasks | Done | In progress | Progress |
| ---- | ----: | ---: | ----------: | -------- |
| ✒️ **Pen production** | 5 | 0 | 2 | ░░░░░░░░░░   0% |
| 🛠️ **Lathe configuration** | 4 | 1 | 1 | ▓▓▓░░░░░░░  25% |
| ✏️ **Pen designs** | 6 | 1 | 2 | ▓▓░░░░░░░░  17% |
| 🔩 **Pen tooling** | 7 | 0 | 0 | ░░░░░░░░░░   0% |
| 🧰 **Lathe tools** | 8 | 5 | 1 | ▓▓▓▓▓▓░░░░  63% |
| ⬆️ **Upgrades** | 4 | 0 | 0 | ░░░░░░░░░░   0% |
| **TOTAL** | **34** | **7** | **6** | **▓▓░░░░░░░░  21%** |

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
○─ 🔄 Bed twist
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

#### 🛠️ Lathe configuration (1/4)

| ID | Task | Needs | Status | Blocks |
|----|------|-------|--------|--------|
| S1 | Bed twist | Shims ✓, V-blocks (on order), Precision level (need to borrow), Measurement test | 🔄 | S2 |
| S2 | Headstock alignment | Dial indicator ✓, Cut test | 🚫 | S3 |
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

#### 🧰 Lathe tools (5/8)

| ID | Task | Status | Blocks |
|----|------|--------|--------|
| T1 | QCTP | ✅ | — |
| T2 | Collet chuck | ✅ | — |
| T3 | 3 jaw chuck | ⬜ | — |
| T4 | 4 jaw independent chuck | ⬜ | — |
| T5 | 1-2-3 blocks | ✅ | — |
| T6 | V-blocks | 🔄 | — |
| T7 | Dial indicator | ✅ | — |
| T8 | Dial test indicator | ✅ | — |

#### ⬆️ Upgrades (0/4)

| ID | Task | Status | Blocks |
|----|------|--------|--------|
| U1 | ELS | ⬜ | — |
| U2 | Tailstock travel | ⬜ | — |
| U3 | DRO | ⬜ | — |
| U4 | New cabinet | ⬜ | — |


## History

```
2024
├─         First Spindle run: GS-24-01 to GS-24-25
├─         GX-24-01, GX-24-07, GX-24-08
├─ Apr     Brand launch
├─ Dec 16  Spindle OG design
└─ Dec 29  Augur OG design
2025
├─ Aug     Augur clip design
├─ Oct     Spindle Pocket design
└─ Nov     South Bend Workshop 9 lathe arrives
2026
├─ Aug     Spindle IMP design begins
├─ Oct     Spindle IMP CAD, mandrels, nib and feed models
├─ Oct 19  Spindle IMP schematics
└─ Nov 21  Relaunch tracking starts
```
