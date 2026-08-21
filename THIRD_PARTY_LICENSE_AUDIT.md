# Third-party dependency license audit

Status: verified for the dependencies imported by the included Python source. The package does not vendor these projects; users install them separately.

| Dependency | Upstream license | Official license file | Verified Git blob SHA |
|---|---|---|---|
| datasets | Apache-2.0 | https://github.com/huggingface/datasets/blob/main/LICENSE | `d645695673349e3947e8e5ae42332d0ac3164cd7` |
| networkx | BSD-3-Clause | https://github.com/networkx/networkx/blob/main/LICENSE.txt | `02547fc890c22287c5cacfc4ec6bfc384e6ce785` |
| numpy | BSD-3-Clause | https://github.com/numpy/numpy/blob/main/LICENSE.txt | `f37a12cc4cccf83af4517809791777e71c1df2a9` |
| pandas | BSD-3-Clause | https://github.com/pandas-dev/pandas/blob/main/LICENSE | `bd1cc2a30c626d0bbe43ab6ec1c4744c2e2df831` |
| scikit-learn | BSD-3-Clause | https://github.com/scikit-learn/scikit-learn/blob/main/COPYING | `3d7ee432c15b685eaa654b6abe8f8e3ea8126a8d` |
| scipy | BSD-3-Clause | https://github.com/scipy/scipy/blob/main/LICENSE.txt | `1032aece8a8109d67f238de6865d8b08e750a8c0` |
| sentence-transformers | Apache-2.0 | https://github.com/huggingface/sentence-transformers/blob/main/LICENSE | `8e5d3560eeeb3e6bb8f233d0ff7cee7372cca397` |
| torch | BSD-style | https://github.com/pytorch/pytorch/blob/main/LICENSE | `c23172f7aff0254e4f0f163fb2e6e355cbaec5f4` |
| transformers | Apache-2.0 | https://github.com/huggingface/transformers/blob/main/LICENSE | `68b7d66c97d66c58de883ed0c451af2b3183e6f3` |

These permissive dependency licenses are compatible with the MIT License applied to the project-authored source. They do not change the licenses of the dependencies themselves.

Dataset content is a separate rights issue. No third-party dataset text, graph rows derived from real datasets, retrieved contexts, or raw answers are included. Users must obtain the upstream datasets themselves.
