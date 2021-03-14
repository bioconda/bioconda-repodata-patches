This repository contains the set of patches applied to the Bioconda repodata. It is primarily used to patch incorrect pinnings.

This is based on [conda-forge-repodata-patches](https://github.com/conda-forge/conda-forge-repodata-patches-feedstock).

# Usage

To modify package metadata edit and then run `gen_patch_json.py`. The resulting differences can then be viewed with `show_diff.py`.
