# Agent Outputs Repository

This repository stores outputs from OpenClaw sub-agents:

## Structure

```
/research/          - Research reports from researcher agent
/generated-images/  - Images from image-generator agent  
/plans/             - PRDs and plans from planner agent
/reviews/           - Code reviews from qa-reviewer agent
/implementations/   - Code snippets and notes from developer agent
```

## Workflow

- **Session Start:** Agent pulls latest from origin
- **Session End:** Agent commits and pushes changes
- **Naming:** Files use ISO date format: `YYYY-MM-DD-description.md`

## Agents

- `planner` - Architecture and planning outputs
- `developer` - Implementation notes and snippets
- `researcher` - Research reports and analysis
- `qa-reviewer` - Code review reports
- `image-generator` - Generated diagrams and visuals
