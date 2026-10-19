R²CT-MER Code Package
This package contains the source code, configuration, tests, and supporting files for the audio-only R²CT-MER music emotion regression project.
Package Contents
- src/r2ct_mer/ — Python package source code:
  - data.py — corpus preparation, annotation normalization, identity auditing, and song-level partition utilities.
  - features.py — audio handling, frozen MERT feature extraction, and feature-cache utilities.
  - model.py — R²CT-MER model components and associated loss functions.
  - train.py — source-side model selection, training, and evaluation workflows.
  - evaluate.py — evaluation metrics, interval utilities, and paired statistical inference functions.
  - descriptors.py — time-aligned acoustic descriptor extraction.
  - baselines.py — descriptor-based baseline and control-model workflows.
  - cli.py — command-line interface for package operations.
  - dry_run.py — lightweight checks for protocol and evaluation utilities.
  - __init__.py — package initialization.
- configs/protocol.json — configuration for the evaluation protocol and candidate settings.
- tests/ — smoke checks and protocol tests.
- logs/synthetic_dry_run.log — log file associated with the lightweight dry-run utility.
- pyproject.toml — package metadata, dependency declarations, and command-line entry point.
- LICENSE — license text.
- .gitignore — Git ignore rules.
- PACKAGE_HASHES.sha256 — SHA-256 checksums for package files.
