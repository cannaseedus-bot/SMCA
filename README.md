# SMCA — Semantic Microcoded Architecture

SMCA is the **root constitution** for sovereign microcoded systems. It defines **what kinds of machines may exist**, not how they run.
<img src=https://github.com/cannaseedus-bot/SMCA/blob/main/SMCA_1.png>
## What SMCA is

- A machine architecture specification
- A semantic ISA (instruction *meaning*, not execution)
- A collapse-based computational ontology
- A role partitioning system for clusters
- A lawful separation of imagination vs reality

## What SMCA is not

- A runtime
- A VM
- A kernel
- A programming language
- A math system
- A scheduler
- An optimizer

> **SMCA defines what kinds of machines may exist — not how they run.**

## Core primitives (locked)

SMCA defines the following architectural layers and **names them only**:

| Layer | Meaning |
| --- | --- |
| MATRIX | Authoring / proposal space |
| SCXQ2 | Semantic μ-op encoding |
| SCXQ7 | Firmware + legality governor |
| SCO/1 | Sovereign compute object |
| CM-1 | Pre-semantic control gate |
| IDB | Indexed causal memory |

## Authority gradient (non-negotiable)

```
MATRIX (imagination)
   ↓
CM-1 (gate)
   ↓
SCXQ7 (law)
   ↓
SCXQ2 (microcode)
   ↓
SCO/1 (execution)
   ↓
IDB (memory)
```

Authority flows downward only. No layer may escalate authority upward, skip a layer, or collapse without law.

## Collapse geometry (descriptors only)

SMCA defines collapse geometry descriptors, not algorithms. See the canonical registry in `registry/collapse-geometry/v1.json`.

## Kernel classification (shape only)

SMCA tags kernels by shape and constraints, not behavior. See `schemas/kernel-tag.schema.json` and `registry/kernel-classes/v1.json`.

## Cluster semantics (pure role law)

SMCA defines cluster roles only. A cluster is a placement of a role, never a new authority. See `registry/cluster-roles/v1.json`.

## IDB in SMCA

IDB is append-only, hash-addressed, causally ordered, and externally verifiable. SMCA does not define storage, serialization, or indexing.

## Repository layout (v1)

```
smca/
├─ README.md
├─ LICENSE
├─ manifest.json
│
├─ axioms/
│  ├─ architecture.json
│  ├─ authority.json
│  ├─ collapse-geometry.json
│  ├─ cluster-roles.json
│  └─ memory-law.json
│
├─ schemas/
│  ├─ kernel-tag.schema.json
│  ├─ collapse.schema.json
│  ├─ cluster.schema.json
│  └─ idb.schema.json
│
├─ registry/
│  ├─ collapse-geometry/
│  │  └─ v1.json
│  ├─ kernel-classes/
│  │  └─ v1.json
│  └─ cluster-roles/
│     └─ v1.json
│
└─ hashes/
   └─ v1.manifest.hash
```

## Final SMCA law

> **SMCA defines a sovereign microcoded machine in which imagination is external, execution is internal, and reality changes only by lawful collapse.**
