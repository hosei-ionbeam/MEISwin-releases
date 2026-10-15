**English** | [日本語](README.ja.md)

# MEISwin — MEIS & RBS analysis software

Research Center of Ion Beam Technology, Hosei University

Author: Tomoaki Nishimura, t-nishi (a) hosei.ac.jp

MEISwin simulates and analyzes medium-energy ion scattering (MEIS) and Rutherford backscattering spectrometry (RBS) spectra.

## Download

Download the packages from [Releases](https://github.com/hosei-ionbeam/MEISwin-releases/releases). The latest version is **v1.582 (2017-02-21)**.

A reference video, "Operation when specifying isotope" (`Specification_of_isotope.mp4`, 2018-05-18), is attached to the v1.582 release.

This repository hosts the distribution packages and their notes only. It contains no source code.

The "Source code (zip)" and "Source code (tar.gz)" links under Assets are added automatically by GitHub to every release and cannot be removed. They contain only these README files, not the software's source code. Download the files listed in the Files table of each release.

## Verifying the files

You can confirm that a downloaded file has not been altered by comparing its SHA-256 with the table below.

```powershell
Get-FileHash .\MEISwin-v1.582-releaseVersion-170221.zip -Algorithm SHA256
```

| Version | File | SHA-256 |
|---|---|---|
| 1.582 | `MEISwin-v1.582-releaseVersion-170221.zip` | `05f18679798d4e07ccd40bf37aad4363a3285cf384e20193f0bea833069563bb` |
| 1.581 | `MEISwin-v1.581-releaseVersion-130718.zip` | `c9c8a7e33505463bd6c3450cc7c583e562d1f5801d8a3a217f77e8513341f74d` |
| 1.58 | `MEISwin-v1.58-releaseVersion-130713.zip` | `7dd6ae7f0dd1c41385ce0a09d0a7eacd04e036f73311566edd16cc0d234c110e` |
| 1.57 | `MEISwin-v1.57-releaseVersion-130619.zip` | `8876404e682ede95e15abfe1df1c683e5f841a612779cb854babc99955aa56df` |
| (video) | `Specification_of_isotope.mp4` | `9e40de232089e2d608bc29a6e0f532846a27b9c39a88683bba720ff932c61509` |

The video is also on YouTube for reference: https://youtu.be/GkY538oCmec

## Version history

Dates are those listed on the old website.

| Version | Date | Changes |
|---|---|---|
| [1.582](https://github.com/hosei-ionbeam/MEISwin-releases/releases/tag/v1.582) | 2017-02-21 | EMG5.0 now can be used from GUI menu. sigma_0 of EMG 5.0 are as same as that of EMG5.2.<br>The simulation has become faster by using large BLOCKSIZE with OPEN statements. |
| [1.581](https://github.com/hosei-ionbeam/MEISwin-releases/releases/tag/v1.581) | 2013-07-18 | Max of smoothing number for experimental data, 10->50<br>Warning message when OS uses comma as decimal point. |
| [1.58](https://github.com/hosei-ionbeam/MEISwin-releases/releases/tag/v1.58) | 2013-07-13 | Error message, Japanese -> English |
| [1.57](https://github.com/hosei-ionbeam/MEISwin-releases/releases/tag/v1.57) | 2013-06-17 | Earliest version listed on the old website (no changes described). |

## About the move

These versions were originally distributed on the Research Center's website between 2013 and 2017. In October 2026 the distribution was moved to this GitHub repository. The files are unchanged (verified byte-identical to the original builds).

## Reference

When you publish results obtained with MEISwin, please cite:

T. Nishimura, "Computer simulation program for medium-energy ion scattering and Rutherford backscattering spectrometry", Nuclear Instruments and Methods in Physics Research B 371 (2016) 97–100. https://doi.org/10.1016/j.nimb.2015.10.007
