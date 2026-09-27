        # D-LORD

        [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
        [![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FD--LORD--DYSL--AI-181717?logo=github)](https://github.com/biometric-community/D-LORD-DYSL-AI)
        [![Access: register](https://img.shields.io/badge/access-register-important.svg)](https://dyslai.org/datasets/D-LORD/)

        **D-LORD** (DYSL-AI) — large-scale **low-resolution disguised face** recognition database (mugshots + surveillance videos).

        - **Dataset repository**: https://github.com/biometric-community/D-LORD-DYSL-AI
        - **Upstream source**: https://dyslai.org/datasets/D-LORD/
        - **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
        - **License (data)**: upstream terms — this packaging does **not** relicense the data

- **Paper DOI**: https://doi.org/10.1109/TBIOM.2023.3306703
- **Upstream GitHub / datasheet**: https://github.com/IAB-IITJ/D-LORD
- **Scale (paper)**: ~2,100 identities; 14,098 LR surveillance videos; >1.2M annotated frames

        | Field | Value |
        |-------|-------|
        | Catalog id (tbiom) | `d-lord` |
        | Category | `face-recog` |
        | Access | `register` |
        | Upstream homepage | https://dyslai.org/datasets/D-LORD/ |

        ## TL;DR

        - **Task**: low-resolution / disguised face recognition
        - **Access**: **register**
        - **This mirror**: documentation + download helpers only (no bulk payload in git)
        - **Notes**: Request via signed institute license (IAB-IITJ / DYSL-AI). GitHub datasheet: https://github.com/IAB-IITJ/D-LORD — this mirror ships docs/helpers only.

        ## Table of contents

        - [Download](#download)
        - [Dataset structure](#dataset-structure)
        - [Known issues and caveats](#known-issues-and-caveats)
        - [License](#license)
        - [Citation](#citation)
        - [Contact](#contact)

        ## Download

        ### Clone this repository

        ```bash
        git clone git@github.com:biometric-community/D-LORD-DYSL-AI.git
        cd D-LORD-DYSL-AI
        ```

        ### tbiom monorepo helper

        ```bash
        bash projects/datasets/scripts/download_d_lord.sh
        ```

        Then follow the printed upstream steps and place archives under `projects/datasets/d-lord/`.

        ## Dataset structure

        ```text
        D-LORD-DYSL-AI/
        ├── README.md
        ├── LICENSE                 # helpers / docs (CC BY 4.0)
        ├── .gitignore
        └── extracted/              # local only after you download (gitignored)
        ```

        ## Known issues and caveats

        - Upstream hosts / Drive quotas often block fully automated downloads.
        - Do not commit multi-GB payloads to this GitHub mirror.

        ## License

        Helpers/docs: CC BY 4.0. Dataset files: upstream license / access agreement.

        ## Citation

        ```bibtex
        @article{manchanda2023dlord,
  title={{D-LORD}: {DYSL-AI} Database for Low-Resolution Disguised Face Recognition},
  author={Manchanda, Sunny and others},
  journal={IEEE TBIOM},
  year={2023},
  doi={10.1109/TBIOM.2023.3306703}
}
        ```

        ## Contact

        - Upstream: https://dyslai.org/datasets/D-LORD/
        - Packaging: https://github.com/biometric-community/D-LORD-DYSL-AI/issues
