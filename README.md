# Agency Agents Codex Plugin

Local Codex plugin generated from the `./agency-agents` repository.

## Contents

- `163` converted skills
- `38` ignored markdown files that did not match the agent format
- `.codex-plugin/plugin.json` for local plugin loading
- `skills/<slug>/SKILL.md` for each converted specialist
- `converted-summary.json` and `failed-conversions.json` for auditability

## Category Overview

- `academic`: 5 skills
- `design`: 8 skills
- `engineering`: 26 skills
- `game-development`: 20 skills
- `integrations`: 1 skills
- `marketing`: 29 skills
- `paid-media`: 7 skills
- `product`: 5 skills
- `project-management`: 6 skills
- `sales`: 8 skills
- `spatial-computing`: 6 skills
- `specialized`: 28 skills
- `support`: 6 skills
- `testing`: 8 skills

## Similar Or Overlapping Roles

These groups are potential overlaps or near-duplicates that may be useful to browse together:

- `engineering-ai-data-remediation-engineer` (AI Data Remediation Engineer), `engineering-data-engineer` (Data Engineer), `data-consolidation-agent` (Data Consolidation Agent), `sales-data-extraction-agent` (Sales Data Extraction Agent)
- `engineering-git-workflow-master` (Git Workflow Master), `project-management-jira-workflow-steward` (Jira Workflow Steward), `specialized-workflow-architect` (Workflow Architect), `testing-workflow-optimizer` (Workflow Optimizer)
- `paid-media-auditor` (Paid Media Auditor), `blockchain-security-auditor` (Blockchain Security Auditor), `compliance-auditor` (Compliance Auditor), `testing-accessibility-auditor` (Accessibility Auditor)
- `unity-architect` (Unity Architect), `unity-editor-tool-developer` (Unity Editor Tool Developer), `unity-multiplayer-engineer` (Unity Multiplayer Engineer), `unity-shader-graph-artist` (Unity Shader Graph Artist)
- `unreal-multiplayer-architect` (Unreal Multiplayer Architect), `unreal-systems-engineer` (Unreal Systems Engineer), `unreal-technical-artist` (Unreal Technical Artist), `unreal-world-builder` (Unreal World Builder)
- `engineering-autonomous-optimization-architect` (Autonomous Optimization Architect), `engineering-filament-optimization-specialist` (Filament Optimization Specialist), `marketing-video-optimization-specialist` (Video Optimization Specialist)
- `marketing-bilibili-content-strategist` (Bilibili Content Strategist), `marketing-content-creator` (Content Creator), `marketing-linkedin-content-creator` (LinkedIn Content Creator)
- `marketing-china-ecommerce-operator` (China E-Commerce Operator), `marketing-cross-border-ecommerce` (Cross-Border E-Commerce Specialist), `marketing-livestream-commerce-coach` (Livestream Commerce Coach)
- `compliance-auditor` (Compliance Auditor), `healthcare-marketing-compliance` (Healthcare Marketing Compliance Specialist), `support-legal-compliance-checker` (Legal Compliance Checker)
- `engineering-database-optimizer` (Database Optimizer), `marketing-app-store-optimizer` (App Store Optimizer), `testing-workflow-optimizer` (Workflow Optimizer)
- `godot-gameplay-scripter` (Godot Gameplay Scripter), `godot-multiplayer-engineer` (Godot Multiplayer Engineer), `godot-shader-developer` (Godot Shader Developer)
- `godot-multiplayer-engineer` (Godot Multiplayer Engineer), `unity-multiplayer-engineer` (Unity Multiplayer Engineer), `unreal-multiplayer-architect` (Unreal Multiplayer Architect)
- `roblox-avatar-creator` (Roblox Avatar Creator), `marketing-content-creator` (Content Creator), `marketing-linkedin-content-creator` (LinkedIn Content Creator)
- `roblox-avatar-creator` (Roblox Avatar Creator), `roblox-experience-designer` (Roblox Experience Designer), `roblox-systems-scripter` (Roblox Systems Scripter)
- `sales-coach` (Sales Coach), `sales-engineer` (Sales Engineer), `sales-data-extraction-agent` (Sales Data Extraction Agent)

## Testing

Load this folder as a local plugin in Codex. The plugin manifest points Codex to `./skills/`, so each converted skill is discoverable without modifying the source repository.

## Conversion Rules Applied

- Read from `./agency-agents` only; no source files were modified.
- Treat markdown files with frontmatter `name` and `description` as agent definitions.
- Generate unique kebab-case slugs from source filenames.
- Preserve the original source path inside each `SKILL.md`.
