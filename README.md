# Lung Sound Recorder and Classification System

This repository contains the code for a comprehensive system developed by The Quad Chips team. The project focuses on recording and analyzing lung sounds using an ESP32 microcontroller and an INMP441 I2S microphone module. The system captures bronchovesicular (BV) and vesicular (V) signals, processes them through noise reduction, removes heartbeats, generates Mel spectrograms, and classifies the lung sounds using Support Vector Machines (SVMs). The processed data is visualized on a dedicated webpage, providing an intuitive interface for interpreting respiratory conditions.

## Features
- **Recording System:** Integrates an INMP441 microphone with a Littmann Stethoscope for high-fidelity lung sound capture.
- **Audio Processing:** Includes noise reduction techniques and heartbeats removal to enhance signal clarity.
- **Mel Spectrograms:** Utilizes MEL spectrograms for visualizing frequency content over time.
- **Classification:** Uses SVMs for accurate classification of lung sounds into categories like wheeze, crackle, and normal.
- **Web Dashboard:** Displays processed data and classification results on a web-based interface for easy interpretation.

## Setup and Usage
- **Hardware Requirements:** ESP32 microcontroller, INMP441 I2S microphone module, and Littmann Stethoscope.
- **Software Requirements:** Arduino IDE for ESP32 programming.
- **Installation:** Clone the repository and upload the code to your ESP32 using Arduino IDE.
- **Usage:** Follow instructions in the `README` to start recording and analyzing lung sounds.

## Future Enhancements
- Enhance classification accuracy through further training and algorithm refinement.
- Expand system capabilities to detect and classify additional respiratory conditions.
- Improve user interface and data visualization for enhanced usability.

## Team Members
- Dhulipati Vaishnavi Priya (2022101108)
- Sai Divya Ravipati (2022101090)
- Venkamsetty Venkata Jahnavi (2022101118)
- Sai Praneeth Bommana (2022101097)

## Acknowledgments
- **Associated Professor:** Prof. Abhishek Srivastava
- **Associated TA:** Santhoshini Thota

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
