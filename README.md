# 📖 The Noble Quran Data Repository

<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/thinkasjunaid/Quran?style=for-the-badge)](https://github.com/thinkasjunaid/Quran/stargazers)

[![GitHub forks](https://img.shields.io/github/forks/thinkasjunaid/Quran?style=for-the-badge)](https://github.com/thinkasjunaid/Quran/network)

[![GitHub issues](https://img.shields.io/github/issues/thinkasjunaid/Quran?style=for-the-badge)](https://github.com/thinkasjunaid/Quran/issues)

[![GitHub license](https://img.shields.io/github/license/thinkasjunaid/Quran?style=for-the-badge)](LICENSE)

**A comprehensive, open-source data collection for the Holy Quran, featuring multiple Arabic script styles, translations, transliterations, tafsir, metadata, and audio resources.**

</div>

## 📚 Overview

This repository provides a meticulously organized and extensive dataset of the Holy Quran, designed to empower developers and researchers to build rich, accurate, and feature-complete Quranic applications and platforms. It centralizes various textual editions of the Quran, including different Arabic script styles, alongside valuable supplementary resources.

The goal is to offer a reliable and easily consumable data source that covers diverse needs, from displaying the Quran in various scripts to providing comprehensive study tools through translations, transliterations, and detailed exegesis (tafsir).

## ✨ Key Features & Data Provided

This repository offers a wealth of structured data, including:

*   **Multiple Arabic Quranic Script Editions**: Access the Quranic text in several widely recognized scripts, each optimized for different display and study preferences:
    *   **Uthmani Script**: Traditional and simplified versions.
    *   **Imlaei Script**: Modern, clear script suitable for digital display.
    *   **Indopak Nastaleeq Script**: Distinctive script commonly used in the Indian subcontinent.
    *   **QPC Hafs Script**: Quran Publishing Complex (King Fahd Complex) Hafs edition.
    *   **Digital Khatt**: A modern digital rendering of the Quranic text.
*   **Ayah-by-Ayah Data**: Each script edition provides the text structured per ayah, facilitating precise rendering, navigation, and synchronized playback.
*   **Extensive Translations**: A dedicated directory for various translations of the Quran into multiple languages (content to be added/organized within `translations/`).
*   **Accurate Transliterations**: Resources for phonetic transliteration of Arabic text, aiding non-Arabic speakers in pronunciation (content to be added/organized within `transliterations/`).
*   **Detailed Tafsir (Exegesis)**: A collection of commentaries and explanations of Quranic verses (content to be added/organized within `tafsir/`).
*   **Comprehensive Metadata**: Structured information about Surahs, Juz (parts), Manzil (stages), Ruku (sections), and Hizb (sub-sections) to enrich navigation and study.
*   **Organized Audio Recitations**: A directory to host audio files, structured by Surah and Ayah, for various reciters (content to be added/organized within `audio/`).

## 🛠️ Technology Stack

This repository primarily serves as a **data source**. The data is provided in:

**Data Format:**

![JSON](https://img.shields.io/badge/JSON-5E5C5C?style=for-the-badge&logo=json&logoColor=white)

No specific programming languages, frameworks, or databases are utilized *within this repository itself*. The data is designed to be consumed by applications built with various technologies.

## 🚀 Getting Started

This repository contains raw data files. To utilize them, you typically clone the repository and then integrate the JSON data into your application.

### Prerequisites
-   A Git client to clone the repository.
-   A programming language or framework capable of parsing JSON data (e.g., JavaScript, Python, Java, C#, Go).

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/thinkasjunaid/Quran.git
    cd Quran
    ```

2.  **Access the Data**
    Once cloned, you can access the various JSON files and directories directly within the `Quran/` folder. For example, to read the Uthmani script data:
    ```
    # In your application code (example for Node.js/JavaScript)
    const uthmaniData = require('./path/to/cloned/repo/uthmani.json');
    console.log(uthmaniData[0]); // Access the first ayah/surah data
    ```

## 📁 Project Structure

The repository is organized to provide easy access to different types of Quranic data:

```
Quran/
├── audio/                          # Directory for audio recitations (Surah/Ayah based)
├── metadata/                       # Directory for metadata (Surah, Juz, Hizb, etc. info)
├── tafsir/                         # Directory for Quranic commentaries/exegesis
├── translations/                   # Directory for translations of the Quran
├── transliterations/               # Directory for phonetic transliterations
├── digital-khatt-v2.json           # Quran text in Digital Khatt v2 script
├── folder_structure_final.json     # Metadata or guide for logical folder/data structure
├── imlaei-script-ayah-by-ayah.json # Quran text in Imlaei script, ayah-by-ayah
├── imlaei-simple.json              # Simplified Quran text in Imlaei script
├── indopak-nastaleeq.json          # Quran text in Indopak Nastaleeq script
├── qpc-hafs.json                   # Quran text in QPC Hafs script
├── uthmani-simple.json             # Simplified Quran text in Uthmani script
└── uthmani.json                    # Quran text in full Uthmani script
```

## 🤝 Contributing

We welcome contributions to enhance the completeness, accuracy, and variety of the data within this repository. If you have corrections, additional translations, tafsir, or new script versions in a structured JSON format, please feel free to contribute.

To contribute:
1.  Fork the repository.
2.  Create a new branch for your feature or fix.
3.  Ensure your data is accurately formatted according to existing JSON structures.
4.  Commit your changes and push to your fork.
5.  Open a Pull Request with a clear description of your contribution.

## 📄 License

This project is open-source and released under the [LICENSE_NAME](LICENSE) - see the `LICENSE` file for details. <!-- TODO: Add actual license file (e.g., MIT, Apache 2.0) -->

## 🙏 Acknowledgments

This data collection is built upon the efforts of numerous individuals and organizations who have dedicated themselves to preserving and disseminating the Holy Quran. Specific data sources will be credited within their respective JSON files or `metadata/` directory.

## 📞 Support & Contact

If you have any questions, suggestions, or encounter issues with the data, please feel free to:
-   📧 Email: [me@junaid.pro.bd] <!-- TODO: Add contact email -->
-   🐛 Open an Issue: [GitHub Issues](https://github.com/thinkasjunaid/Quran/issues)

---

<div align="center">

**⭐ Star this repo if you find this data helpful for your projects!**

Made with ❤️ by [thinkasjunaid](https://github.com/thinkasjunaid)

</div>

