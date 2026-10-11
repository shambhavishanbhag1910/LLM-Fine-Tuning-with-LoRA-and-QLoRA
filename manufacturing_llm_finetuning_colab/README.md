# Manufacturing LLM Fine-Tuning with LoRA / QLoRA

Google Colab-ready package with 360 labelled synthetic manufacturing cases: 280 train, 40 validation, and 40 held-out test.

## Run
1. Extract ZIP.
2. Open the notebook in Colab.
3. Enable T4 GPU.
4. Upload the three split JSONL files when prompted.
5. Run all cells.
6. Optionally add GROQ_API_KEY in Colab Secrets.

## Metrics
Validation loss, perplexity, valid JSON rate, severity/component/failure-category accuracy, exact three-field accuracy, concept coverage, ROUGE-L, BERTScore F1, latency, GPU memory, and optional Groq judge.

All data is synthetic and contains no OEM confidential information.