# MCRLab Datasets Repository

This repository hosts datasets created and/or used by MCRLab researchers for various research projects. The goal is to ensure data transparency, reproducibility, and easy access for all team members and collaborators.

## 📁 Repository Structure Example

datasets/
│
├── Defect_Texture_Fine-Tuning_LLM_Dataset/
│   ├── Data_Card.md                  # Metadata and dataset description
│   ├── texture_training_examples.jsonl # Actual dataset file
│   └── supporting_files/             # (Optional) Additional files or scripts
│
└── README.md                         # Main repo documentation


## 📊 **MCRLab Created Datasets**

| Dataset Name               | Type    | Source            | Contributor(s)      | Citation(s)                                      |
|-----------------------------|---------|-------------------|---------------------|--------------------------------------------------|
| Railway Defect Texture FT    | Created | [Internal Research](https://github.com/aelsaddik/Datasets-/tree/main/Defect%20Texture%20Fine-Tuning%20LLM%20Dataset) | Rahatara Ferdousi   | [Rahatara et al., 2024](https://arxiv.org/pdf/2410.18085) |

---

## 🌐 **External Datasets Used**

| Dataset Name                | Used In Project              | Used by | Link                                               |
|------------------------------|------------------------------|------------------|----------------------------------------------------|
| Rail Track Fault Detection   | [DefectTwin](https://github.com/turna1/DefectTwin)    | Rahatara Ferdousi        | [Dataset Link](https://www.kaggle.com/datasets/salmaneunus/railway-track-fault-detection/data) |

## 🔗 **How to Use the Datasets**

1. Clone the repository:
    ```bash
    git clone https://github.com/MCRLab/datasets.git
    ```
2. Navigate to the desired dataset directory:
    ```bash
    cd datasets/dataset_name/
    ```
3. Review the `README.md` and `metadata.json` for detailed information on the dataset structure and usage.

---

## 📖 **Citation Guidelines**

If you use any dataset from this repository in your research, please make sure to:

1. Cite the original paper (if public).
2. Credit the MCRLab and the contributor(s) who created the dataset.

---

## 🤝 **Contributors**
We welcome contributions! If you are not directly part of MCRLab (e.g., alumni, current student, or employee), please fork the repository, make your changes in your fork, and submit a pull request. Direct modifications to the main repository are not allowed.

---

## 📬 **Contact**

For any queries regarding the datasets or repository management, reach out to individual contributors or Prof. Abdulmotaleb El Saddik.
