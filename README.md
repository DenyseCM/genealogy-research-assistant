# Genealogy Research Assistant

An AI-powered research assistant for family historians using Claude. Applies the Genealogical Proof Standard (GPS) to help you plan research, analyze sources, build citations, evaluate conflicting evidence, and write proof arguments.

Built by [Denyse Allen](https://chroniclemakers.com) / [Chronicle Makers](https://chroniclemakers.com).

## What It Does

This plugin adds five commands and three knowledge skills to Claude, turning it into a genealogy research partner that follows professional methodology.

### Commands

| Command | What It Does |
|---|---|
| `/research-plan` | Creates a GPS-compliant research plan with prioritized record searches, repositories, and tracking |
| `/analyze-source` | Classifies any genealogical source (original/derivative, primary/secondary, direct/indirect) and extracts every genealogically relevant detail |
| `/cite` | Coaches you through building proper citations using the Jones five-question framework — teaches you the skill, doesn't just generate citations |
| `/evaluate-evidence` | Correlates multiple sources, identifies conflicts, and assesses which evidence is strongest — honest about what's proven vs. what's claimed |
| `/research-report` | Generates GPS-compliant proof summaries, proof arguments, or full research reports — refuses to write conclusions the evidence doesn't support |

### Skills (activate automatically)

| Skill | When It Activates |
|---|---|
| **GPS Methodology** | When you ask about proof standards, exhaustive searches, or whether your research is "done" |
| **Record Types** | When you ask what records exist for a time period, place, or research question |
| **Citation Guide** | When you ask how to cite a source or document your research |

## What Makes This Different

**It follows the Genealogical Proof Standard.** Every command is built around the five GPS elements: reasonably exhaustive search, complete citations, evidence analysis, conflict resolution, and soundly reasoned conclusions.

**It won't tell you what you want to hear.** If your evidence doesn't support a conclusion, it says so. If your search isn't exhaustive enough, it tells you what's missing. If a source is derivative with secondary information, it explains why that matters for how much weight it carries.

**It teaches, not just generates.** The `/cite` command coaches you through building citations yourself using the Jones five-question framework. The `/analyze-source` command explains *why* a source is classified the way it is. You learn the methodology as you use it.

**It knows what records exist — everywhere in the U.S.** The record-types skill includes era-specific guidance — Colonial, Revolutionary, Early Republic, Civil War, Gilded Age, and Modern — so it can tell you what to look for based on when and where your ancestor lived, in any state. It understands that record availability varies by era and jurisdiction: when vital records began, what each census year asked, what military records exist for each conflict, and which repositories hold what.

## Installation

### Claude Desktop (Cowork)

Download `genealogy-research-assistant.plugin` and install it through Cowork's plugin manager.

### Claude Code

```bash
claude install genealogy-research-assistant
```

## Example: Resolving a Death Date Conflict

Here's what the plugin does with a real research problem — a Revolutionary War militia captain whose death date is recorded differently in two lineage society applications.

**The problem:** The SAR application (1962) says Stephen Crumrine died in 1792. The DAR application (1998) says April 10, 1812. Federal census records show him alive in 1800 and 1810.

**What `/evaluate-evidence` produced:**

- Classified all five sources (SAR, DAR, 1800 census, 1810 census, tax records) by source type, information type, and evidence type
- Built a correlation table showing what each source says about each key fact
- Identified that the SAR application contains a provable error (mother's death date listed as 1725 — 12 years before the subject's birth) that passed review uncorrected
- Concluded the 1792 date is **disproven** by two original census records
- Assessed the 1812 date as **plausible but unverified** — honest about the gap
- Listed specific records still needed (probate, church burial, cemetery, deed records) before a GPS-compliant conclusion can be written

**What `/research-report` did next:**

- Refused to write a proof summary (evidence insufficient)
- Chose proof argument format instead (appropriate for unresolved conflicts)
- Wrote a 9-section document with full citations, evidence analysis, conflict resolution, and honest GPS assessment
- Left citation placeholders where microfilm numbers were missing rather than fabricating them
- Ended with prioritized next steps the researcher can act on

## Who This Is For

Family historians anywhere in the United States who want to do credible research — not just collect names and dates, but build conclusions that hold up. Whether you're working toward a lineage society application, writing a family chronicle, or just want to know if your brick wall is actually solved, this plugin applies professional methodology to your research.

**Want to go deeper?** An extended version of this plugin — with additional skills, hands-on workshops, and community support — is featured in the [Chronicle Makers community on Skool](https://www.skool.com/chronicle-makers).

## About the Author

Denyse Allen is a Pennsylvania genealogy researcher, published author (*Colonial Pennsylvania Genealogy Research*, *Pennsylvania Vital Records Research*, *Archives in Pennsylvania for Genealogy Research*), and founder of [Chronicle Makers](https://chroniclemakers.com) — helping family historians transform research into published stories.

## License

[FSL-1.1-MIT](LICENSE.md) — Free to use for research, education, and personal projects. Cannot be repackaged as a competing commercial product. Converts to MIT after two years.
