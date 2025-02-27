# Pavement Social Impact

This repository contains the code used in the studies titled [A quantitative methodology for measuring the social sustainability of pavement deterioration](https://doi.org/10.1038/s41598-024-52655-7) and [Which impacts matter for pavement management decisions? Quantifying social sustainability based on a capability approach](https://doi.org/10.1016/j.trip.2024.101312)

## Description
This study introduces a methodology to quantify the impact of road condition on vulnerable communities, specifically Environmental Justice (EJ) communities. It analyzes fuel consumption for road users during recurrent home-work trips as a function of pavement condition for EJ and non-EJ communities. 

The main components of the code include:
- `Network_ARCGIS`: Builds a network and calculates the shortest path.
- `RoadAnalysis`: Calculates the impacts due to road condition.
- `Plot_Functions`: Displays the final results, also presented in the study.

## Data
The files used for this study are stored in:
- Pickle files: [Google Drive - Pickle](https://drive.google.com/drive/folders/1IpB7L99t5ykQkgYfUaIhvlB1PqV3k_M-?usp=sharing)
- Shape files: [Google Drive - Shapes](https://drive.google.com/drive/folders/1Pt-i94HkkJOsWdGYGXS4hwxxzKbzTfji?usp=sharing)
- Trip data: [Google Drive - Trips](https://drive.google.com/drive/folders/1wz2_TlpEbhe_jiI2guqzhktK_5E48Joq?usp=sharing)

## Citation
If you use this code or the methodology in your research, please cite one or both of the following papers:

* Egemen Okte, Jessica Boakye, & Mark Behrend. (2024). A quantitative methodology for measuring the social sustainability of pavement deterioration. *Scientific Reports, 14*(2112). https://doi.org/10.1038/s41598-024-52655-7

* Boakye, J., & Okte, E. (2025). Which impacts matter for pavement management decisions? Quantifying social sustainability based on a capability approach. *Transportation Research Interdisciplinary Perspectives*, 29, 101312. https://doi.org/10.1016/j.trip.2024.101312

@article{Okte2024Quantitative,
  title={A quantitative methodology for measuring the social sustainability of pavement deterioration},
  author={Okte, Egemen and Boakye, Jessica and Behrend, Mark},
  journal={Scientific Reports},
  volume={14},
  number={2112},
  year={2024},
  publisher={Nature Publishing Group},
  doi={10.1038/s41598-024-52655-7}
}

@article{boakye2025impacts,
  title={Which impacts matter for pavement management decisions? Quantifying social sustainability based on a capability approach},
  author={Boakye, Jessica and Okte, Egemen},
  journal={Transportation Research Interdisciplinary Perspectives},
  volume={29},
  pages={101312},
  year={2025},
  publisher={Elsevier}
}
