📁 MCRLab Dataset Contribution Template
# Only for the MCRLab members

✅ Steps to Add a New Dataset:

1️⃣ Create a Dataset Folder
	•	Navigate to the Datasets-/ directory.
	•	Create a new folder named after your dataset. 
Example:

Datasets/Your Dataset Name/


2️⃣ Add Your Dataset Files
	•	Place all raw or processed data inside the new folder.
	•	Include any supporting files (scripts, documentation) in a subfolder called supporting_files/ (if needed).

Example folder structure:

datasets/
└── Railway_Defect_Texture_FT/
    ├── Data_Card.md                  # Metadata and description
    ├── texture_training_examples.jsonl # Dataset file
    └── supporting_files/             # (Optional) Additional resources

3️⃣ Complete the Data Card (Data_Card.md)

Create a Data_Card.md inside your dataset folder with the following template:

# 📊 [Dataset Name]

## 📖 Description
[Brief description of the dataset, its purpose, and its relevance.]

## 📅 Creation Date
[YYYY-MM-DD]

## 📁 Data Contents
- **File Name(s):** [List of files, e.g., texture_training_examples.jsonl]
- **Type:** [Images, Text, Tabular, etc.]
- **Format:** [CSV, JSONL, PNG, etc.]
- **Size:** [e.g., 500MB]

## 👥 Contributors
- [Full Name 1]
- [Full Name 2] *(if applicable)*

## 📚 Citation
If you use this dataset, please cite:
- *[Paper Title, Author, Year]* — [Link to Paper](#)

## ⚖️ License
[Specify license, e.g., CC BY 4.0]

## 📬 Contact
For questions or support, contact: **[email@example.com]**

4️⃣ Update the Main README.md Tables

📊 MCRLab Created Datasets
	1.	Open the main README.md file.
	2.	Scroll to the MCRLab Created Datasets table.
	3.	Add a new row for your dataset.

Example Format:

## 📊 **MCRLab Created Datasets**

| Dataset Name               | Type    | Source            | Contributor(s)      | Citation(s)                                      |
|-----------------------------|---------|-------------------|---------------------|--------------------------------------------------|
| Railway Defect Texture FT    | Created | [Internal Research](link to the folder) | Rahatara Ferdousi   | [Rahatara et al., 2024](https://arxiv.org/pdf/2410.18085) |
| [Your Dataset Name]         | Created |[Internal Research](link to the folder) | [Your Name]         | [Citation](#)                                    |

🌐 External Datasets Used (if applicable)

If your project uses an external dataset, add it to the External Datasets Used table.

Example Format:

## 🌐 **External Datasets Used**

| Dataset Name                | Used In Project         | Used by           | Link                                               |
|------------------------------|-------------------------|-------------------|----------------------------------------------------|
| Rail Track Fault Detection   | DefectTwin              | Rahatara Ferdousi | [Dataset Link](https://www.kaggle.com/datasets/salmaneunus/railway-track-fault-detection/data) |
| [External Dataset Name]      | [Project Name]          | [Your Name]       | [Dataset Link](#)                                  |


💡 Quick Example Walkthrough:

Let’s say you’re adding a new dataset called “Railway Signal Anomaly FT”:
	1.	Folder Structure:

datasets/Railway_Signal_Anomaly_FT/
├── Data_Card.md
└── signal_anomaly_data.jsonl


	2.	Data_Card.md:

# 📊 Railway Signal Anomaly FT

## 📖 Description
This dataset focuses on railway signal anomalies for fine-tuning anomaly detection models.

## 📅 Creation Date
2025-02-19

## 📁 Data Contents
- **File Name:** signal_anomaly_data.jsonl
- **Type:** Time-series data
- **Format:** JSONL
- **Size:** 250MB

## 👥 Contributors
- Alex Johnson

## 📚 Citation
If you use this dataset, please cite:
- *Anomaly Detection in Railways, Johnson et al., 2025* — [Link to Paper](#)

## ⚖️ License
CC BY 4.0

## 📬 Contact
For questions or support, contact: **alex.j@example.com**


	3.	Update Main README.md:

## 📊 **MCRLab Created Datasets**

| Dataset Name               | Type    | Source            | Contributor(s)      | Citation(s)                                      |
|-----------------------------|---------|-------------------|---------------------|--------------------------------------------------|
| Railway Defect Texture FT    | Created | Internal Research | Rahatara Ferdousi   | [Rahatara et al., 2024](https://arxiv.org/pdf/2410.18085) |
| Railway Signal Anomaly FT    | Created | Internal Research | Alex Johnson        | [Johnson et al., 2025](#)                        |

This template ensures all datasets follow a consistent structure, making them easy to find, use, and cite.
