# Genealogy Research Assistant

**By Denyse Allen, Chronicle Makers**

A GPS-compliant genealogy research assistant that helps family historians organize research, analyze sources, build proper citations, and write proof summaries — all following the Genealogical Proof Standard.

## What It Does

This plugin turns Claude into a genealogy research partner that follows professional standards. It connects to your Google Drive (or other cloud storage) where you keep your research files, and helps you work through them systematically.

### On Session Start

When you begin a conversation, the assistant scans your connected research folder and gives you a quick briefing: what documents you have, which ancestors appear, what gaps exist, and a suggested next step.

### Citation Coaching

After every response involving a source document, the assistant checks whether that source was properly cited. If not, it walks you through the Jones five-question citation framework — coaching you to build the citation yourself rather than generating one for you.

## Commands

| Command | What It Does |
|---------|-------------|
| `/research-plan` | Build a GPS-compliant research plan for a specific question |
| `/analyze-source` | Analyze a genealogical source document step by step |
| `/cite` | Walk through the Jones five-question citation framework |
| `/evaluate-evidence` | Correlate evidence across multiple sources and find conflicts |
| `/research-report` | Generate a proof summary, proof argument, or research report |

## Skills

| Skill | Triggers On |
|-------|------------|
| GPS Methodology | Questions about the Genealogical Proof Standard, research methodology, evidence analysis |
| Citation Guide | Questions about citing sources, building citations, source vs. information vs. evidence |
| Record Types | Questions about specific genealogical records, what they contain, where to find them |

## Hooks

| Event | Behavior |
|-------|----------|
| Session Start | Scans research folder and provides a status briefing |
| Stop | Checks if sources discussed were properly cited; nudges citation if not |

## Setup

1. Install the plugin in Claude
2. Connect your Google Drive (or other cloud storage) when prompted
3. Point it at the folder where you keep your genealogy research files
4. Start a conversation — the assistant will brief you on what's there

## Cloud Storage

This plugin references cloud storage generically. The included MCP configuration is set up for Google Drive, but it works with any supported cloud storage connector (Dropbox, OneDrive, Box).

Your research files stay in your cloud storage. The assistant reads from them but never deletes or modifies your originals.

## The Genealogical Proof Standard

Every feature in this plugin is built around the GPS — the professional standard for genealogical research:

1. **Reasonably exhaustive search** — Look in all sources that might answer your question
2. **Complete, accurate citations** — Document every source so anyone can find it again
3. **Analysis and correlation** — Classify and compare evidence from multiple sources
4. **Resolution of conflicts** — Address contradictions head-on with reasoned explanations
5. **Sound, written conclusion** — Put it in writing with a coherent narrative

## Credits

Built by Denyse Allen of [Chronicle Makers](https://chroniclemakers.com). Based on the Genealogical Proof Standard and Thomas W. Jones's citation methodology from *Mastering Genealogical Proof*.

Learn more at [chroniclemakers.com](https://chroniclemakers.com).
