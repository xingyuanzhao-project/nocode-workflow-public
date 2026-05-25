# Academic Pipeline

Academic Pipeline is a **visual workflow editor for LLM-powered structured text processing**.

**[Open App](https://academic-pipeline-gui.onrender.com)** · **[Documentation](https://xingyuanzhao-project.github.io/academic-pipeline/)**

---

## What it does

Upload a CSV or JSONL file where each row has a text field. Build a processing flow on a canvas by connecting nodes. Run against any OpenAI-compatible model. Export results as CSV.

Supported operations per row:

- **Summarisation** — free-form LLM instruction with a defined output schema
- **Classification** — codebook-driven taxonomy labelling; the codebook is injected into the prompt automatically
- **Extraction** — structured field extraction with JSON output
- **Chained steps** — multiple processor nodes in sequence or parallel

Runs checkpoint automatically. Interrupted runs resume from the last completed row.

---

## Who it is for

- **Political science** — coding legislative texts, judicial records, media coverage, human rights documentation
- **Computational social science** — structured content analysis on large corpora
- **Any domain** where tabular text data needs systematic, reproducible LLM processing

---

## Quick start

1. Open the app at [academic-pipeline-gui.onrender.com](https://academic-pipeline-gui.onrender.com)
2. Click **CSV Input** — upload a file with a text column
3. Drag a **Processor** node — write an instruction and define an output schema
4. Drag an **LLM Call** node — select a provider and model (any OpenRouter-compatible endpoint)
5. Optionally attach a **Codebook** node for classification tasks
6. Connect a **CSV Output** node and click **Run**

See the [documentation](https://xingyuanzhao-project.github.io/academic-pipeline/) for detailed usage.

---

## Citation

*Citation details to be added.*
