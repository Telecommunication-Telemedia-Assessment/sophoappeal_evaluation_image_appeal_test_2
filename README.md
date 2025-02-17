# Sophoappeal image appeal test #2 -- lab and crowd

Core idea of test #2: images and like views, using [aesthetics_srv](https://github.com/Telecommunication-Telemedia-Assessment/sophoappeal_aesthetics_srv) test framework, with a [1,5] star rating.

This repository is part of [Sohpappeal](https://github.com/Telecommunication-Telemedia-Assessment/sophoappeal).
Please use the main repository as starting point.

This repository is part of the DFG project [Sophoappeal (437543412)](https://www.tu-ilmenau.de/universitaet/fakultaeten/fakultaet-elektrotechnik-und-informationstechnik/profil/institute-und-fachgebiete/fachgebiet-audiovisuelle-technik/forschung/dfg-projekt-sophoappeal), it contains images and analysis scripts.


## Requirements


* python3, python3-pip, git, imagemagick, wget, unzip
* jupyternotebook for the analysis scripts


## Structure and scripts

* `eval_aesthetics.ipynb`: evaluation of tests
* `stats_clickworker.csv`: rating exports from clickworker test
* `stats_lab_test_1.csv`: rating exports from lab test

* raw exported ratings:
    * `export_aesthetics_clickworker`
    * `export_aesthetics_tuil`


## Acknowledgments

If you use this software or data in your research, please include a link to the repository and reference the following paper.

```bibtex
@article{goering2023imageappeal,
  title={Image Appeal Revisited: Analysis, new Dataset and Prediction Models},
  author={Steve G\"oring and Alexander Raake},
  journal={IEEE Access},
  year={2023},
  publisher={IEEE},
  note={to appear}
}
```

## License
GNU General Public License v3. See [LICENSE.md](./LICENSE.md) file in this repository.