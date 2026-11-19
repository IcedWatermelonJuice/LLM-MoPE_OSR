![FocusLab](https://github.com/IcedWatermelonJuice/IcedWatermelonJuice/blob/main/FocusLab_Logo.png?raw=true)
# LLM-MoPE_OSR (Coming soon)
<p align="center"><strong>English</strong> · <a href="README.zh-CN.md">简体中文</a></p>

<p align="center">
  <img alt="Python 3.12" src="https://img.shields.io/badge/Python-3.12-3776AB">
  <img alt="PyTorch 2.12.1" src="https://img.shields.io/badge/PyTorch-2.12.1-EE4C2C">
  <img alt="CUDA 13.0" src="https://img.shields.io/badge/CUDA-13.0-76B900">
  <img alt="Transformers 5.17.0" src="https://img.shields.io/badge/Transformers-5.17.0-DAA520">
</p>

This repository reproduces LLM-MoPE, our method for open-set radio-frequency fingerprint identification of UAV emitters. **This repository will be released after the acceptance of the paper.**

<p align="center">
  <a href="#paper-and-citation">Paper and citation</a> ·
  <a href="#requirements">Requirements</a> ·
  <a href="#data-and-downloads">Data and downloads</a> ·
  <a href="#reproduction">Reproduction</a> ·
  <a href="#repository-structure">Repository structure</a> ·
  <a href="#contact-and-links">Contact and links</a>
</p>

## Paper and citation
The paper is currently under submission to TIFS, and citation information will be provided once it is accepted.

## Requirements

The reference environment uses Linux x86_64, Python 3.12, and a BF16-capable NVIDIA GPU. For exact versions, see the [installation guide](docs/ENVIRONMENT.md) and [dependency constraints](environment/constraints.txt).

## Repository structure

- `main.py` provides the four-stage command-line interface.
- `src/llm_mope_osr/` contains the implementation and RFUAV configuration.
- `data/`, `cache/`, and `models/` contain download and setup instructions.
- `tests/` contains CPU tests using synthetic data. Run `python -B -m unittest discover -s tests -v`.

## Contact and links

### Contact

- [xulai@njupt.edu.cn](mailto:xulai@njupt.edu.cn)

### Related links

- [Academic homepage](https://my.xulai.work)
- [Code archive](https://cloud.xulai.work/Repo)
- [FocusLab projects](https://github.com/focuslabcode/Code)
- [Dataset archive](https://cloud.xulai.work/Datasets)
