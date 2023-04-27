# OSCTI Dataset


This repository contains the OSCTI (open-source cyber threat intelligence) reports data collected by a team of Virginia Tech and UC Berkeley researchers. In this README, you'll find important information about the structure and content of the dataset. For detailed information on the websites that we track, please refer to the Google sheet: [oscti-data](https://docs.google.com/spreadsheets/d/1HhA0CSSSa8lg_lQzoXNrdvaGVHidLZpdzk6krU5xpvI/edit?usp=sharing).

The OSCTI dataset is collected for our ThreatKG research published on arXiv. If you use this dataset for your research, we kindly request that you cite the following papers: 

[ThreatKG: A Threat Knowledge Graph for Automated Open-Source Cyber Threat Intelligence Gathering and Management](https://arxiv.org/pdf/2212.10388.pdf).

```bibtex
@misc{gao2022threatkg,
      title={ThreatKG: A Threat Knowledge Graph for Automated Open-Source Cyber Threat Intelligence Gathering and Management}, 
      author={Peng Gao and Xiaoyuan Liu and Edward Choi and Sibo Ma and Xinyu Yang and Zhengjie Ji and Zilin Zhang and Dawn Song},
      year={2022},
      eprint={2212.10388},
      archivePrefix={arXiv},
      primaryClass={cs.CR}
}
```

[A System for Automated Open-Source Threat Intelligence Gathering and Management](https://people.cs.vt.edu/penggao/papers/securitykg-sigmod21demo.pdf).

```bibtex
@inproceedings{10.1145/3448016.3452745,
author = {Gao, Peng and Liu, Xiaoyuan and Choi, Edward and Soman, Bhavna and Mishra, Chinmaya and Farris, Kate and Song, Dawn},
title = {A System for Automated Open-Source Threat Intelligence Gathering and Management},
year = {2021},
isbn = {9781450383431},
publisher = {Association for Computing Machinery},
url = {https://doi.org/10.1145/3448016.3452745},
doi = {10.1145/3448016.3452745},
booktitle = {Proceedings of the 2021 International Conference on Management of Data},
pages = {2716–2720},
numpages = {5},
series = {SIGMOD '21}
}
```

## Table of Contents

1. [Dataset Overview](#dataset-overview)
2. [File Structure](#file-structure)
3. [Data Format](#data-format)
4. [License](#license)

## Dataset Overview

The OSCTI dataset contains unstructured OSCTI reports collected from various cybersecurity sources, including: articles, blogs, news, etc. Our goal is to provide a comprehensive, up-to-date resource for security professionals, researchers, and enthusiasts.

## File Structure

The dataset is organized into the following directory structure:

```
.
├── 20220620-all-reports
│     ├── attcybersecurity_html
│     │   ├── 0-day-in-microsoft-iis-5-6-ftp.html
│     │   ├── 25c3-fake-ca-certificates.html
│     │   └── ...
│     ├── ciscoumbrella_html
│     └── ...
├── LICENSE
└── README.md
```

## Data Format

The data files are in PDF or HTML format.

## License

The OSCTI dataset is released under the MIT License. By using the dataset, you agree to the terms and conditions of the license.
