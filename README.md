# Solar-Battery Node AI

**Power Health & Vision Anomaly Detection**

![AEROO Space AI Competition 2026](https://img.shields.io/badge/AEROO%20Space%20AI-2026-blue)
![STM32](https://img.shields.io/badge/STM32-NPU%20Enabled-orange)
![ML Accuracy](https://img.shields.io/badge/ML%20Accuracy-92%25-green)
![Inference](https://img.shields.io/badge/Vision%20Inference-%3C100ms-green)
![Prototype Cost](https://img.shields.io/badge/Prototype%20Cost-%24312-brightgreen)
![Languages](https://img.shields.io/badge/Languages-EN%20|%20KK%20|%20RU%20|%20TR-lightgrey)

## Overview

An integrated autonomous monitoring system for solar-powered space missions, combining machine learning-based battery health prediction with computer vision anomaly detection.

### Key Features

- **Dual STM32 Architecture**: IoT board + NPU-accelerated vision processing
- **92% ML Accuracy**: Battery Remaining Useful Life (RUL) prediction
- **Sub-100ms Inference**: Real-time solar panel anomaly detection
- **Edge AI Processing**: Autonomous diagnostics without cloud dependency
- **Multi-Platform**: Web dashboard + Flutter mobile app
- **AI Assistant**: GPT-4o-mini powered proactive maintenance recommendations
- **Multi-Language Support**: English, Kazakh, Russian, Turkish

## Hardware

| Component | Price |
|-----------|-------|
| STM32N6570-DK (NPU Board) | $193 |
| STM32 B-L475E-IOT01A (IoT Board) | $54 |
| IMX335 5MP Camera Module | $65 |
| **Total Prototype Cost** | **$312** |

## Technology Stack

- **ML Framework**: scikit-learn (Random Forest Regressor)
- **Vision**: YOLOv8 INT8 quantized, STEdgeAI Core v2.2.0
- **Backend**: Python Flask
- **Mobile**: Flutter (Dart)
- **AI Integration**: OpenAI GPT-4o-mini, Claude API
- **Data Storage**: Google Drive API

## Datasets

| Dataset | Samples | Purpose |
|---------|---------|---------|
| [NASA Battery Dataset](https://www.kaggle.com/datasets/patrickfleith/nasa-battery-dataset) | 168K cycles | Battery RUL prediction |
| [Roboflow Solar Panel](https://universe.roboflow.com/gao-shou-zheng-b6xqc/solar-panel-0swal) | 2,280 images | Panel anomaly detection (Normal, Dust, Crack, Coverage) |

## Documentation

| Document | Description |
|----------|-------------|
| [Main Website](index.html) | Project overview, features, and team information |
| [Technical Whitepaper](technical-whitepaper.html) | Detailed technical documentation and research methodology |
| [Pitch Deck](pitch-deck.html) | Investment presentation with roadmap (1-3-5-10 years) |
| [Dataset Documentation](dataset-documentation.html) | NASA Battery & Roboflow Solar Panel dataset details |

All documentation pages support 4 languages (EN, KK, RU, TR) and include PDF download.

## Research Team

**Talgar Private Boarding School No. 1**, Almaty Region, Kazakhstan

- **Amir Dilovarov** - Team Leader, Grade 11
- **Ayla Badalova** - Student Researcher, Grade 11
- **Süleyman Tongut** - Project Advisor, Computer Science Teacher, B.Sc. Electrical & Electronics Engineering

## Business Model

This research follows NASA's technology transfer paradigm:
1. **Space-first R&D**: Extreme environment validation
2. **Technology Transfer**: Commercial spin-offs for terrestrial solar monitoring
3. **Future Scalability**: Advanced material science sensor integration

## Competition

**AEROO Space AI Competition 2026** - Exploring the World of Science

## Live Demo

🌐 [Visit Website](https://solar-node-ai.onrender.com)

## Related Repositories

- [Computer Vision System](https://github.com/talgarph1/AEROO-Space-AI-Competition-Computer-Vision-STM32N657)
- [IoT & ML System](https://github.com/talgarph1/AEROO-Space-AI-Competition-IOT-MOBILE-ML)

## License

This project is developed for educational and research purposes as part of the AEROO Space AI Competition 2026.

---

© 2026 Talgar Private Boarding School No. 1
