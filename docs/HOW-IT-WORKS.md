# How Understand Domain Works

Extract business-domain knowledge from a codebase and generate an interactive domain flow graph.

![Detailed systems blueprint for Understand Domain](../assets/system-blueprint.png)

## Stages

### 1. Extract nouns events states and actors

**Primary surface:** `Repository evidence`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 2. Resolve code names into domain concepts

**Primary surface:** `Domain entities`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 3. Link rules to implementing components

**Primary surface:** `Business rules`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 4. Trace representative business workflows

**Primary surface:** `Use-case flows`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 5. Cluster bounded contexts and ownership

**Primary surface:** `Domain knowledge graph`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 6. Render an evidence-linked domain graph

**Primary surface:** `Domain knowledge graph`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.

## Failure handling

- **Authorization failure:** do not probe credentials or broaden access; report the missing authority.
- **Target ambiguity:** stop before mutation and request the minimum identifying information.
- **Tool or service failure:** retain error evidence, retry only safe transient failures, and cap retries.
- **Verification failure:** classify the run as incomplete even when the preceding operation returned success.

## Completion evidence

The handoff should contain the original request, inspection state, preview or plan, exact execution result, direct verification, and a final receipt naming limitations and withheld actions.
