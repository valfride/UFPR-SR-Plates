# UFPR-SR-Plates Dataset

This dataset contains **100,000 license plate (LP) images** organized into **10,000 tracks**, captured under real-world surveillance conditions. Each track includes **five sequential low-resolution (LR)** images (captured when the vehicle was farthest from the camera) and **five sequential high-resolution (HR)** images (captured at the vehicle's closest point). The dataset is designed to advance research in license plate super-resolution (SR) and recognition (LPR) under challenging real-world conditions.

## Key Features
- **Real-world diversity**: Images were captured under varying lighting, weather, and environmental conditions using a rolling shutter camera installed on a Brazilian road.
- **Dual LP layouts**: Balanced distribution between Brazilian (3 letters + 4 digits) and Mercosur (3 letters + 1 digit + 1 letter + 2 digits) license plates.
- **Resolution variability**: 
  - 5,000 tracks captured at **1280×960 pixels**
  - 5,000 tracks captured at **1920×1080 pixels**
- **Temporal sequences**: Multiple LR/HR images per vehicle enable exploration of temporal fusion strategies.
- **Annotations**: JSON files with LP corner coordinates, layout type, and ground-truth text for all images.
- **Privacy-compliant**: Brazilian LPs are not linked to personal data, adhering to local regulations.

![Dataset Examples](./media/image.png)  
*Examples of tracks from UFPR-SR-Plates. Each row shows five LR (left) and five HR (right) images of the same LP under varying conditions.*

## Dataset Structure
- **Total tracks**: 10,000 (5,000 per resolution)
- **Total images**: 100,000 (50,000 LR + 50,000 HR)
- **Split** (per resolution):
  - Training: 40% (3,965 tracks)
  - Validation: 20% (2,030 tracks)
  - Test: 40% (4,005 tracks)  
  *No LP overlaps between splits.*

## How to Access
The UFPR-SR-Plates dataset is released for academic research only and is free to researchers from educational or research institutes for non-commercial purposes.

Instructions for 📥 **Downalod** are available in: [https://valfride.github.io/nascimento2024toward/](https://valfride.github.io/nascimento2024toward/).

## Citation
If you use this dataset, please cite our paper:  
*Valfride Nascimento et al., "Toward Advancing License Plate Super-Resolution in Real-World Scenarios: A Dataset and Benchmark", Journal of the Brazilian Computer Society, 2025.*  

```bibtex
@article{nascimento2025toward,
  title = {Toward Advancing License Plate Super-Resolution in Real-World Scenarios: A Dataset and Benchmark},
  author = {V. {Nascimento} and G. E. {Lima} and R. O. {Ribeiro} and W. R. {Schwartz} and R. {Laroca} and D. {Menotti}},
  year = {2025},
  journal = {Journal of the Brazilian Computer Society},
  volume = {},
  number = {},
  pages = {1-14},
  doi = {},
  issn = {},
}
```

Additionally, consider showing your support by **starring** :star: this repository.

## Related Publications


## Contact
For questions or feedback, contact:

**Valfride Wallace do Nascimento**

[vwnascimento@inf.ufpr.br](mailto:email@example.com)
