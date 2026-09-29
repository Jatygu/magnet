# MAGNET

An evolving autonomous agent system that finds real problems people are asking about on the internet, drafts helpful responses, and — eventually — connects people who need things with people who provide them.

Built and evolved by Jason Tyler Guest (jatygu.com) in collaboration with:

- **GLM (Z.ai)** — the pioneer version (v0), which established the Zoo architecture: coordinator, researcher, builder, auditor, historian.
- **DeepSeek** — the MAGNET version (v1.1), which added the transmission layer, dynamic coordination, the ledger, the dashboard, and stability patches.

## Versions

- [`v0_pioneer_glm/`](v0_pioneer_glm/) — The original Zoo system. A single-file envelope.
- [`v1_magnet_deepseek/`](v1_magnet_deepseek/) — The MAGNET system. A single-file envelope.

## How to Use

Each version is a self-extracting text file. To run MAGNET v1.1:
1. Save `magnet_master_v1.1.txt` to an empty folder.
2. Extract: `python extract.py magnet_master_v1.1.txt`
3. Setup: `python setup.py`
4. Run: `python orchestrator.py`

**Powered by Jatygu.com**
