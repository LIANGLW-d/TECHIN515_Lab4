# TECHIN515 Magic Wand

## Overview
This project is the final lab for TECHIN515: Magic Wand. It demonstrates data collection, machine learning model integration, and a custom hardware enclosure for gesture recognition using embedded systems.

## Table of Contents
- [Project Overview](#overview)
- [Directory Structure](#directory-structure)
- [Setup Instructions](#setup-instructions)
- [How to Run](#how-to-run)
- [Dependencies](#dependencies)
- [Demo Video](#demo-video)
- [Report](#report)
- [Enclosure](#enclosure)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Directory Structure
```
TECHIN515-magic-wand/
├── src/
│   ├── sketches/               # Arduino/MCU sketches and Edge Impulse exports
│   ├── python-scripts/         # Python scripts for data collection and processing
│   └── dataset/                # Collected dataset (not tracked in git)
│
├── docs/
│   └── report.pdf              # Final report
│
├── media/
│   └── demo.mp4                # Demo video
│
├── enclosure/
│   ├── final-enclosure-images/ # Images of the final enclosure
│   └── notes.md                # Materials, design decisions, battery info
│
├── README.md                   # This file
└── .gitignore                  # Files/folders to ignore
```

## Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd TECHIN515-magic-wand
   ```
2. **Install Python dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   *(Add a requirements.txt if you have Python dependencies)*

3. **Hardware Setup:**
   - Follow the instructions in `enclosure/notes.md` for assembling the enclosure and battery.
   - Upload the appropriate sketch from `src/sketches/` to your microcontroller.

## How to Run
- **Data Collection:**  
  Use scripts in `src/python-scripts/` to collect and preprocess gesture data.
- **Model Training:**  
  Export data to Edge Impulse, train your model, and export the model back to `src/sketches/`.
- **Deployment:**  
  Flash the microcontroller with the updated sketch for real-time inference.

## Dependencies
- Python 3.x
- (List any additional Python or system dependencies here)
- Arduino IDE (for uploading sketches)
- Edge Impulse account (for model training)

## Demo Video
See [`media/demo.mp4`](media/demo.mp4) for a demonstration of the project in action.

## Report
See [`docs/report.pdf`](docs/report.pdf) for the final project report.

## Enclosure
See [`enclosure/notes.md`](enclosure/notes.md) for details on the enclosure design, materials, and battery.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

<<<<<<< HEAD
=======
## License
(Add your license here, e.g., MIT, Apache 2.0, or leave as "All rights reserved" if not open source.)

>>>>>>> 9aebc6e (Save local untracked files before pulling from remote)
## Acknowledgments
- Based on the TECHIN515 Lab 4 template and structure.
- Thanks to the GIX faculty and Edge Impulse for tools and support.

---

**References:**
<<<<<<< HEAD
- [TECHIN515 Lab 4 Reference Repo](https://github.com/GIXLabs/TECHIN515_Sp25/tree/main/lab4) 
=======
- [TECHIN515 Lab 4 Reference Repo](https://github.com/GIXLabs/TECHIN515_Sp25/tree/main/lab4) 
>>>>>>> 9aebc6e (Save local untracked files before pulling from remote)
