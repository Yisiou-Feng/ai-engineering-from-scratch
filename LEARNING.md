# My AI Engineering Path
<!-- Managed by the ai-engineering-from-scratch learning skills.
     Repo: https://github.com/rohitg00/ai-engineering-from-scratch -->

## Mission
Career change: moving into an AI engineering role.
Build goal: not sure yet; to be discovered along the way.

## Placement
- Date: 2026-11-12
- Score: 5/10 (Math & Statistics 1/2, Classical ML 2/2, Deep Learning 0/2, NLP & Transformers 1/2, Applied AI 1/2)
- Entry point: Phase 0: Setup & Tooling (learner chose to start here and do Phases 0-2 in full; quiz placement was Phase 3: Deep Learning Core)
- Pace: ~10 h/week

## Path
| Phase | Name | Status | Est. hours |
|-------|------|--------|------------|
| 0 | Setup & Tooling | Do | 16 |
| 1 | Math Foundations | Do | 23 |
| 2 | ML Fundamentals | Do | 26 |
| 3 | Deep Learning Core | Do | 15 |
| 4 | Computer Vision | Do | 27 |
| 5 | NLP — Foundations to Advanced | Do | 30 |
| 6 | Speech & Audio | Do | 18 |
| 7 | Transformers Deep Dive | Do | 14 |
| 8 | Generative AI | Do | 14 |
| 9 | Reinforcement Learning | Do | 13 |
| 10 | LLMs from Scratch | Do | 26 |
| 11 | LLM Engineering | Do | 19 |
| 12 | Multimodal AI | Do | 65 |
| 13 | Tools & Protocols | Do | 76 |
| 14 | Agent Engineering | Do | 55 |
| 15 | Autonomous Systems | Do | 20 |
| 16 | Multi-Agent & Swarms | Do | 28 |
| 17 | Infrastructure & Production | Do | 34 |
| 18 | Ethics, Safety & Alignment | Do | 31 |
| 19 | Capstone Projects | Do | 620 |
| | **Total (Review + Do)** | | **1170** |

## Progress log
| Date | Lesson | Quiz | Note |
|------|--------|------|------|
| 2026-11-12 | 00/01-dev-environment | 3/3 | Predicted Anaconda packages would carry into the new .venv (they don't; each Python has its own packages). Course env: uv + Python 3.12 .venv with RTX 3060 CUDA; on this machine use `python` after activating, not the Windows Store `python3` stub. |
| 2026-11-12 | 00/02-git-and-collaboration | 1/3 | Thought a commit saves unstaged edits (it saves only what `git add` staged); mixed up `checkout -b` (create+switch) with fetching from GitHub; unsure why checkpoints go in .gitignore (huge + regenerable). Set up: global identity (GitHub no-reply email), fork, remotes origin=fork / upstream=course, branch `my-progress` pushed. |
| 2026-11-12 | 00/03-gpu-setup-and-cloud | 2/3 | Missed `nvidia-smi` (picked nonexistent torch.cuda.list_devices); didn't know why synchronize() matters until the run showed 1.54 ms vs 174 ms. GPU is RTX 3060 **Laptop, 6 GB VRAM** (~2-2.5B params fp16 with margin), not 12 GB. Repaired .venv: uv's Python 3.12.16 had been deleted; reinstalled with `uv python install 3.12.16`. Warm-up: both 00/02 review items correct. |
| 2026-11-12 | 00/04-apis-and-keys | 3/3 | Knew a pushed key stays unsafe, but the fix is to revoke/rotate the key in the console (history keeps the old commit). Didn't know what an HTTP status code was; ran fake-key call -> 401 authentication_error. Didn't know SDK reads ANTHROPIC_API_KEY env var itself. Skipped real API call (no key yet; set up in Phase 11). Warm-up: 00/03 review item (nvidia-smi) correct. |

## Review queue
