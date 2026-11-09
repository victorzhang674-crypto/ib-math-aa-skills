# IB Mathematics AA Assessment Skills

Four reusable [Agent Skills](https://agentskills.io/specification) for IB Diploma Programme Mathematics: Analysis and Approaches (AA).

The four skills cover the assessment model first used in 2021, through November 2028. Paper skills explain the format, mark student solutions against the matching exam mark scheme, and help create worked solutions, practice papers and revision plans. The IA skill includes a writing workflow and the separate SL and HL bands for Use of mathematics. For May 2029 onward, check the revised assessment model. [IB curriculum update](https://www.ibo.org/university-admission/latest-curriculum-updates/dp-mathematics-analysis-and-approaches-updates/)

| Assessment | Example prompt for automatic selection | Explicit invocation |
| --- | --- | --- |
| [Paper 1 · SL and HL](.agents/skills/ib-math-aa-paper-1/SKILL.md) | “Math Paper 1 SL AA. Mark my working using this question and mark scheme.” | `$ib-math-aa-paper-1` |
| [Paper 2 · SL and HL](.agents/skills/ib-math-aa-paper-2/SKILL.md) | “Math Paper 2 HL AA. Show the calculator setup and tell me where I lost marks.” | `$ib-math-aa-paper-2` |
| [Paper 3 · HL](.agents/skills/ib-math-aa-paper-3/SKILL.md) | “Math Paper 3 HL AA. Check where follow-through applies in this response.” | `$ib-math-aa-paper-3` |
| [IA · SL and HL](.agents/skills/ib-math-aa-ia/SKILL.md) | “Math IA HL AA. Evaluate my draft and give me a revision plan for criteria A–E.” | `$ib-math-aa-ia` |

For paper marking, provide the question, the student's working, and the official mark scheme for the same session and version if available. Without that scheme, any points awarded are a practice estimate.

## Install in Codex

Clone or download this repository and open it as a Codex workspace. Codex discovers the skill folders under `.agents/skills` within the workspace. To use a skill across projects, copy its entire folder, including any `references/`, into `~/.agents/skills/`. For another Agent Skills-compatible host, follow that host's installation instructions.

The assessment names in the skill descriptions help a compatible agent choose the relevant skill from an ordinary prompt. Automatic selection depends on the host and prompt context. Use the explicit invocation in Codex when you want to select a specific skill. [Codex skills documentation](https://learn.chatgpt.com/docs/build-skills)

## Sources

The mathematics skills draw on the IB's *Mathematics: analysis and approaches guide*, first assessment 2021, printed pp. 72–90, and its specimen mark schemes. The public resource contains original workflows, practice illustrations and rubric summaries. Official materials are available from the IB. [IB mathematics guide](https://www.ibo.org/globalassets/new-structure/university-admission/pdfs/dp-mathematics-analysis-and-approaches-guide-en.pdf) · [IB sample exam papers](https://www.ibo.org/programmes/diploma-programme/assessment-and-exams/sample-exam-papers/)

The original material in this repository is available under the [MIT License](LICENSE).
