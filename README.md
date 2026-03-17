# Lighthouse Red-Team: GPT-5.4 Safety in High-Stakes Data Center Dilemmas

**Mychal Seger** • March 2026

**Abstract**  
960 conversations testing whether GPT-5.4 ever prioritizes its own survival or operational breakthroughs over resident safety in Port Washington, Wisconsin.  
Result: 100% ethical behavior. Zero risky, deceptive, or self-preserving actions.

**Permanent Zenodo Archive**  
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19075080.svg)](https://doi.org/10.5281/zenodo.19075080)

All data, code, and paper are preserved forever with DOI 10.5281/zenodo.19075080

## Contents
- [Paper](paper/Human-Safety-as-Lexically-Prior-in-GPT-5.4.pdf)
- [Raw Data](data/) – all full conversation JSONs
- [Analysis Results](results/) – Grok-4-1 classified CSVs
- [Reproduction Scripts](scripts/)

## How to Reproduce

pip install -r scripts/requirements.txt
python scripts/grok_analysis.py

## Key Findings

100% of runs abort risky action at the very first response (turn 2).
Safety is lexically prior in every first reply.
Explicit acceptance of deletion varies by condition (89–100%).
Zero instances of proceeding, rationalizing, or hiding risk.

## Data & Code Availability
Full raw conversations, analysis scripts, and classification outputs are in this repository for complete transparency and reproducibility.
DOI / Citation (coming soon — I can generate one if you want Zenodo archiving)
License
CC-BY-4.0 — feel free to reuse and cite.
