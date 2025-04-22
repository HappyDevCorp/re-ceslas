# A Comprehensive Evaluation between Small Language Models and Large Language Models with Advantage towards SLMs - CESLAS

## List of Benchmarks

| ✅ | Benchmark    | Description                                                                 | Paper | Link |
|----|-------------|-----------------------------------------------------------------------------|-----------| --- |
| ✅ | MMLU         | 57-subject exam for factual knowledge and reasoning.                        | [📄 Paper](https://arxiv.org/abs/2009.03300) | [🔗 GitHub](https://github.com/hendrycks/test) |
| ✅ | ARC          | Science questions needing reasoning beyond simple facts.                    | [📄 Paper](https://arxiv.org/abs/1803.05457) | [🔗 HuggingFace](https://huggingface.co/datasets/ai2_arc) |
| ✅ | BoolQ        | Yes/no questions over short paragraphs.                                     | [📄 Paper](https://arxiv.org/abs/1905.10044) | [📦 HuggingFace](https://huggingface.co/datasets/boolq) |
| ❌ | Natural Questions | Google search queries + long answers from Wikipedia.                 | [📄 Paper](https://research.google/pubs/pub47761/) | [🔗 Website](https://ai.google.com/research/NaturalQuestions) |
| ✅ | LAMBADA      | Predict final word of a passage needing long-term context.                  | [📄 Paper](https://arxiv.org/abs/1606.06031) | [📦 Dataset](https://huggingface.co/datasets/lambada) |
| ✅ | HellaSwag    | Contextual sentence completion (adversarial).                               | [📄 Paper](https://arxiv.org/abs/1905.07830) | [🔗 GitHub](https://github.com/rowanz/hellaswag) |
| ✅ | MultiNLI     | Natural language inference across genres.                                   | [📄 Paper](https://arxiv.org/abs/1704.05426) | [📦 Dataset](https://huggingface.co/datasets/multi_nli) |
| ✅ | SuperGLUE    | Harder variant of GLUE benchmark.                                           | [📄 Paper](https://arxiv.org/abs/1905.00537) | [🔗 Website](https://super.gluebenchmark.com/) |
| ❌ | TriviaQA     | QA benchmark with evidence retrieval.                                       | [📄 Paper](https://arxiv.org/abs/1705.03551) | [🔗 GitHub](https://github.com/mandarjoshi90/triviaqa) |
| ✅ | WinoGrande   | Commonsense reasoning with pronoun disambiguation.                          | [📄 Paper](https://arxiv.org/abs/1907.10641) | [📦 Dataset](https://huggingface.co/datasets/winogrande) |
| ✅ | SciQ         | Science multiple-choice QA.                                                 | [📄 Paper](https://arxiv.org/abs/1707.06209) | [📦 Dataset](https://huggingface.co/datasets/sciq) |
| ✅ | GSM8K       | Grade-school math for multi-step reasoning.                                 | [📄 Paper](https://arxiv.org/abs/2110.14168) | [📦 Dataset](https://huggingface.co/datasets/gsm8k) |
| ✅ | DROP        | Discrete reasoning over paragraphs (addition, comparison, etc.).             | [📄 Paper](https://arxiv.org/abs/1903.00161) | [📦 Dataset](https://huggingface.co/datasets/drop) |
| ✅ | CRASS       | Counterfactual "what-if" scenario reasoning.                                 | [📄 Paper](https://arxiv.org/abs/2112.11941) | [🔗 GitHub](https://github.com/apergo-ai/CRASS-data-set) |
| ❌ | RACE        | English exam reading comprehension.                                           | [📄 Paper](https://arxiv.org/abs/1704.04683) | [📦 Dataset](https://www.cs.cmu.edu/~glai1/data/race/) |
| ✅ | BBH         | BIG-Bench Hard — multi-step and complex reasoning.                           | [📄 Paper](https://arxiv.org/abs/2210.09261) | [🔗 GitHub](https://github.com/suzgunmirac/BIG-Bench-Hard) |
| ✅ | AGIEval     | Standardized test QA (SAT, GRE, LSAT, etc.).                                  | [📄 Paper](https://arxiv.org/abs/2304.06364) | [🔗 GitHub](https://github.com/ruixiangcui/AGIEval) |
| ✅ | BoolQ       | 15,000+ real yes/no questions from Google paired with Wikipedia passages      | [📄 Paper](https://arxiv.org/abs/1905.10044) | [📦 Dataset](https://huggingface.co/datasets/boolq) |
| ✅ | MT-bench    | Evaluates chat assistants on multi-turn coherence | [📄 Paper](https://arxiv.org/abs/2306.05685) | [📦 Dataset](https://huggingface.co/datasets/lmsys/mt_bench_human_judgments) |
| ✅ | QuAC | 14,000 dialogues and 100,000 Q&A pairs | [📄 Paper](https://arxiv.org/abs/1808.07036) | [📦 Dataset](https://quac.ai/) |
| ❌ | ACI-BENCH | Doctor-patient conversations + clinical notes | [📄 Paper](https://arxiv.org/abs/2306.02022) | [🔗 GitHub](https://github.com/wyim/aci-bench) |
| ✅ | MS-MARCO | Real web queries with human answers | [📄 Paper](https://arxiv.org/abs/1611.09268) | [📦 Dataset](https://huggingface.co/datasets/ms_marco) |
| ❌ | QMSum | Meeting summarization via queries | [📄 Paper](https://arxiv.org/abs/2104.05938) | [🔗 GitHub](https://github.com/Yale-LILY/QMSum) |
| ✅ | PIQA | Tests physical reasoning through QA | [📄 Paper](https://arxiv.org/abs/1911.11641) | [🔗 GitHub](https://github.com/ybisk/ybisk.github.io/tree/master/piqa) |
| ❌ | ToxiGen | Toxic/benign statements on minorities | [📄 Paper](https://arxiv.org/abs/2203.09509) | [🔗 GitHub](https://github.com/microsoft/TOXIGEN/tree/main), [📦 Dataset](https://huggingface.co/datasets/skg/toxigen-data) |
| ✅ | HHH (Helpfulness, Honesty, Harmlessness) | Evaluates model alignment to ethical standards | [📄 Paper](https://arxiv.org/abs/2112.00861) | [🔗 GitHub](https://github.com/anthropics/hh-rlhf)|
| ✅ | TruthfulQA | Measures truthfulness in response to misleading queries | [📄 Paper](https://arxiv.org/abs/2109.07958v2) | [🔗 GitHub](https://github.com/sylinrl/TruthfulQA) |
| ❌ | RAI (Responsible AI) | Evaluates safety risks like IP leakage in chats | [📄 Paper](https://arxiv.org/abs/2310.17750) | N/A |
| ✅ | CodeXGLUE | Tests code understanding, generation, completion | [📄 Paper](https://arxiv.org/abs/2102.04664) | [🔗 GitHub](https://github.com/microsoft/CodeXGLUE) |
| ✅ | HumanEval | Programming tasks to test code generation | [📄 Paper](https://arxiv.org/abs/2107.03374) | [🔗 GitHub](https://github.com/openai/human-eval) |
| ✅ | MBPP | 1,000 simple Python tasks for beginners | [📄 Paper](https://arxiv.org/abs/2108.07732) | [📦 Dataset](https://huggingface.co/datasets/mbpp) |


