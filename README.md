# CV Generator

This repo uses [RenderCV](https://rendercv.com/) to generate a CV from `classic.yaml`.

## Prerequisites

- Python 3

## Setup

Create and activate a virtual environment, then install dependencies:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Generate CV

Run:

```bash
rendercv render classic.yaml
```

Generated files (PDF/HTML/Markdown/PNG) will be written to `rendercv_output/`.

## Edit your CV

1. Open `classic.yaml`
2. Replace placeholder content with your own details
3. Run the render command again

## Use Codex to update your resume

This project includes `SKILL.md` instructions, so Codex can help you edit the CV directly.

Example prompts you can give Codex:

- "Generate persian version for my resume and use Vazir font"
- "Fill `classic.yaml` with my details: [paste your info]"
- "Rewrite my summary for a senior backend engineer role"
- "Update experience bullets to be achievement-focused"
- "Keep structure, but shorten to one page"

Suggested workflow:

1. Ask Codex to update `classic.yaml`
2. Review the changes
3. Generate the CV again
