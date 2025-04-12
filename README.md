# QTI Package Analyzer

## 🎯 Purpose
This project is a desktop-based tool for analyzing and validating QTI (Question and Test Interoperability) packages, as well as inspecting user upload files (CSV format). It provides an intuitive graphical interface, detailed validation of QTI XML structures, and flexible summary exports.

## 🧰 Use Cases
- Validate QTI test or item packages for structure and specification compliance.
- Summarize QTI package metadata including interactions, scoring, and outcome declarations.
- Cross-check content consistency across imsmanifest.xml, test.xml, and qti.xml.
- Upload and review user CSV files (e.g., for test-takers or group assignment).
- Highlight duplicates, language mismatches, and group/role inconsistencies.
- Export summaries to JSON, HTML, or DOCX for reporting and auditing.

## 💡 Key Features
- Modular, multi-phase QTI processing pipeline
- Clean GUI with upload, preview, and export options
- Extended support for item banks and test packages
- Separate analysis flow for user lists
- Tabbed interface (QTI + User Files)
- Detailed warnings and summary reporting

## 📂 Folder Structure
Please refer to the `qti_analyzer/` directory structure for all modules and logical breakdown of processing phases.

## 🔗 References
- [1EdTech QTI Standard](https://www.imsglobal.org/question/index.html)
- [QTI v2.2 Specification](https://www.imsglobal.org/spec/qti/v2p2)
- [PyQt5 Documentation](https://doc.qt.io/qtforpython/)

## 🚀 Getting Started
To run this project on a fresh Windows 10/11 installation:
1. Install Python 3.9 or newer
2. Create a virtual environment (optional but recommended)
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch the application:
   ```bash
   python main.py
   ```

## 📝 License
MIT License – free for personal and commercial use.
