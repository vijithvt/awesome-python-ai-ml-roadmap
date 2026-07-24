# Track A — NLP, LLMs & Generative AI

**Time:** 8–12 weeks after the shared core  
**Goal:** build evaluated, secure LLM applications rather than prompt-only demos.

## Learning sequence

1. Text preprocessing and classical NLP baselines
2. Embeddings, attention, transformer architecture, tokenization
3. Pretrained models and inference
4. Prompt design, structured outputs, tool/function calling
5. Retrieval: chunking, embeddings, search, reranking, citations
6. Evaluation datasets, retrieval metrics, answer quality, regression tests
7. Agents and workflows: state, tools, retries, approval boundaries
8. Fine-tuning concepts: when adapters/SFT are justified
9. Safety: injection, data leakage, permissions, moderation, abuse cases
10. Latency, cost, observability, caching, fallbacks

## Primary resources

- [Hugging Face LLM Course](https://huggingface.co/learn/llm-course/)
- [Hugging Face Agents Course](https://huggingface.co/learn/agents-course/)
- [Full Stack Deep Learning: LLM Bootcamp](https://fullstackdeeplearning.com/llm-bootcamp/)
- [OWASP Top 10 for LLM Applications](https://genai.owasp.org/llm-top-10/)
- Provider documentation for the API/model you actually use

Frameworks change quickly. First implement one small RAG flow from components so you
can evaluate chunking, retrieval, prompting, and citations independently. Adopt an
orchestration framework only when its abstractions solve a demonstrated need.

## Exercises

1. Beat a transformer with a TF-IDF baseline on a small classification problem—or
   explain why you cannot.
2. Measure how tokenization changes with language and formatting.
3. Create a prompt evaluation set with normal, edge, and adversarial cases.
4. Require schema-valid output and implement validation/retry behavior.
5. Compare fixed, semantic, and structure-aware chunking.
6. Measure retrieval recall@k before judging generated answers.
7. Add citations and verify each citation supports the claim.
8. Implement “I don't know” behavior for absent evidence.
9. Test prompt injection in retrieved content and add boundaries.
10. Compare two models on quality, latency, and cost with a fixed dataset.
11. Build a tool call with input validation and explicit user approval for writes.
12. Decide whether fine-tuning is warranted using evidence.

## Capstone: cited knowledge assistant

Build a domain assistant for public or authorized documents:

- ingestion with provenance and document-level permissions;
- parsing, chunking, embedding, retrieval, optional reranking;
- answer generation with citations and abstention;
- offline evaluation dataset and automated regression tests;
- injection/privacy threat model;
- API/UI, logs without sensitive content, cost/latency report;
- runbook, architecture decision records, and model/system card.

Do not claim that RAG eliminates hallucinations. Report measured retrieval and answer
quality, known gaps, and escalation paths.
