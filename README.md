# Cybersecurity in an Intelligent and Connected World

**A Review of Legal, Technical, Organizational, and Economic Perspectives**

A short review paper (IEEE conference format) that combines ten recent cybersecurity studies into one overview.

**Author:** Md. Adnun Ahemed Methun
**Affiliation:** Department of Computer Science and Engineering, Northern University of Business and Technology Khulna, Bangladesh
**Course:** Technical Writing and Presentation (CSE 3200), Section 6D
**Contact:** adnunahemed@gmail.com

---

## About the paper

Cybersecurity is no longer only an IT problem. This paper reviews ten studies and groups them into four themes:

| Theme | What it covers |
|---|---|
| Legal and social foundations | South Africa's POPIA and Cybercrimes Act; cybercrime in Nigeria |
| AI in cyber defense | Future of AI in security; large language models; endpoint detection and response (EDR) |
| Connected infrastructure | Machine learning intrusion detection for IoT; digital twins in Industry 4.0 |
| Organizational and economic factors | Business security challenges; economic impact (Norsk Hydro case); global vulnerability |

**Main conclusion:** no single tool or law is enough. Resilient protection needs sound laws, AI with human oversight, trained people, and continuous improvement.

## Repository contents

| File | Description |
|---|---|
| `conference_101719.pdf` | The compiled paper (4 pages) |
| `conference_101719.tex` | LaTeX source of the paper |
| `IEEEtran.cls` | IEEE conference class file |
| `fig1.png` | Figure 1 (thematic framework) |
| `Review_Paper_Presentation.pptx` | Presentation slides (15 slides) |
| `Presentation_Speech.pdf` | Speech script for the presentation (about 9 minutes) |

## How to build the PDF

**On Overleaf:**
1. Create a new project and upload `conference_101719.tex`, `IEEEtran.cls`, and `fig1.png`.
2. Set `conference_101719.tex` as the main file.
3. Click **Recompile** (compiler: pdfLaTeX).

**On your computer:**
```bash
pdflatex conference_101719.tex
pdflatex conference_101719.tex
```
Run it twice so the citations and table numbers resolve.

## Sources reviewed

The paper synthesizes the ten studies listed in its reference section, with links. Some references are listed by title and link only, because author names were not recorded in the original notes.

## Notes and limitations

- This is a **narrative literature review**. It adds no new data or experiments and relies on the findings reported by the original authors.
- Publication years for some sources are not confirmed.
- Reference [2] currently has a file name instead of a full link.
- Part of this work, including drafting and formatting, was prepared with the help of an AI assistant (Claude by Anthropic). Please verify key claims against the original papers before citing.

## Citation

If you use this work, please credit it as:

> M. A. A. Methun, "Cybersecurity in an Intelligent and Connected World: A Review of Legal, Technical, Organizational, and Economic Perspectives," Northern University of Business and Technology Khulna, 2026.

## License

No license has been chosen yet. Add a `LICENSE` file (for example, CC BY 4.0 for the paper) if you want others to reuse it.
