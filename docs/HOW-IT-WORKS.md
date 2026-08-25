# How Understand Domain Works

The visuals on this page are static SVGs, so they render directly on GitHub on phones and desktop browsers. Each one is generated from a model specific to this skill.

## System architecture

![Detailed system map for Understand Domain](../assets/system-map.svg)

### Components

- **1. Repository evidence:** participates in extract nouns events states and actors.
- **2. Domain entities:** participates in resolve code names into domain concepts.
- **3. Business rules:** participates in link rules to implementing components.
- **4. Use-case flows:** participates in trace representative business workflows.
- **5. Domain knowledge graph:** participates in cluster bounded contexts and ownership.

## Actor and data sequence

![Actor and data sequence for Understand Domain](../assets/operation-sequence.svg)

### 1. Extract nouns events states and actors

**Primary surface:** `Repository evidence`

Record the concrete input, the operation performed, and the evidence produced at this stage. Continue only when the output is sufficient for the next stage; otherwise preserve the blocker and stop.
### 2. Resolve code names into domain concepts

**Primary surface:** `Domain entities`

Record the concrete input, the operation performed, and the evidence produced at this stage. Continue only when the output is sufficient for the next stage; otherwise preserve the blocker and stop.
### 3. Link rules to implementing components

**Primary surface:** `Business rules`

Record the concrete input, the operation performed, and the evidence produced at this stage. Continue only when the output is sufficient for the next stage; otherwise preserve the blocker and stop.
### 4. Trace representative business workflows

**Primary surface:** `Use-case flows`

Record the concrete input, the operation performed, and the evidence produced at this stage. Continue only when the output is sufficient for the next stage; otherwise preserve the blocker and stop.
### 5. Cluster bounded contexts and ownership

**Primary surface:** `Domain knowledge graph`

Record the concrete input, the operation performed, and the evidence produced at this stage. Continue only when the output is sufficient for the next stage; otherwise preserve the blocker and stop.
### 6. Render an evidence-linked domain graph

**Primary surface:** `Repository evidence`

Record the concrete input, the operation performed, and the evidence produced at this stage. Continue only when the output is sufficient for the next stage; otherwise preserve the blocker and stop.

## Example output shape

![Illustrative output for Understand Domain](../assets/example-output.svg)

The example is a visual contract: a real run may look different, but it should expose comparable state, provenance, and verification information. It is not presented as evidence of a live external action.

## Decision and stop conditions

![Decision guide for Understand Domain](../assets/decision-guide.svg)

The workflow stops when the target is ambiguous, the relevant surface is unavailable or unauthorized, or the final artifact cannot be checked. A logged-in session or successful tool call is not by itself proof that the requested outcome is complete.

## Verification checklist

- Confirm every component shown in the system map exists in the target environment.
- Trace the actor sequence using actual tool output or artifact state.
- Compare the result with the example-output information contract.
- Re-read or reopen the final artifact instead of trusting an attempt message.
- Report omitted stages, unsupported capabilities, and remaining human decisions.
