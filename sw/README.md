# Paper Submission Package

This directory contains two artifact folders:

- `dataset/`: original CSEDM source distributions used as the raw data source.
- `software/`: preprocessing code, model source code, evaluation utilities, and
  the implementation-skill resources required by the proposed model.

The packaged proposed model is **Ours (full)**. Its implementation-skill
resource contains 36 retained skills and 294 problem-skill edges covering all
50 CSEDM problems.

The package intentionally excludes experiment outputs, trained checkpoints,
cached tensor embeddings, API credentials, and local virtual environments.

Before redistributing `dataset/`, verify that the CSEDM Data Challenge license
and the submission site's artifact policy permit redistribution of the original
files. The dataset files remain third-party data.
