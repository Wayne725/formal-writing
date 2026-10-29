# Formal Writing

A Codex skill for submission-ready coursework, reports, project documents, presentation content, and formal correspondence.

Correct the claim. Keep essential facts. Deliver the finished text.

## What it does

- Writes in the language and format requested by the user.
- Prefers affirmative descriptions of methods, findings, and next steps.
- Replaces unsupported claims with statements the evidence supports.
- Embeds sample scope, observation periods, and metric definitions in the methods or findings.
- Places study-specific limitations and risks once, where the document calls for them, with follow-up or mitigation.
- Removes boilerplate disclaimers, defensive wording, and unsolicited editing explanations.
- Keeps headings aligned with the actual content.
- Reviews the draft silently and returns the finished deliverable.

## Install in Codex

Ask Codex:

```text
Use $skill-installer to install formal-writing from:
https://github.com/Wayne725/formal-writing/tree/main/skills/formal-writing
```

## Use

```text
Use $formal-writing to turn the following draft into a submission-ready report:

[Paste your draft]
```

The skill also allows automatic selection when a task matches its description. Its instructions are in English; the deliverable follows the user's requested language.

## Examples

See [before-and-after examples](examples/before-after.md) for a revenue report with a partial month and a survey draft that confuses correlation with causation.

## Structure

```text
skills/formal-writing/
  SKILL.md
  agents/openai.yaml
```

The skill consists of instructions and metadata. No scripts or runtime dependencies are required.
