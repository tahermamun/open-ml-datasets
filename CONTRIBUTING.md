# Contributing to Open ML Datasets

Thank you for your interest in contributing! 🎉  
This guide will help you add datasets easily and correctly.

---

## 📌 Contribution Rules

1. Only **open-source or public domain** datasets are allowed.  
2. **Mandatory files** for every dataset:
   - `data.csv` — the dataset itself
   - `data_description.md` — includes dataset details, features, and ML usage  
     > If `license.txt` or `source.txt` are not included, mention the license and source in this file.  
3. **Optional files**:
   - `license.txt` — full license text  
   - `source.txt` — original source or URL  
4. Add dataset link in Main Readme File in **Available Dataset** table of content option.
4. **Do not include** personal, sensitive, or private data.  
5. The dataset must be **useful for Machine Learning practice**.

---

## 📂 Where to Add a Dataset

Datasets are organized by **domain** (not ML task).  
Example domains:

```text
datasets/
├── finance/
├── healthcare/
├── education/
├── retail/
├── transportation/
├── social/
└── synthetic/
```



## 📂 How to Add a Dataset

1. Fork this repository
2. Choose the most relevant domain folder inside `datasets/`
3. Create a new folder: `datasets/<domain>/dataset-name`
4. Add all required files
5. Submit a Pull Request

---

## ❌ Rejected Contributions

- Missing or unclear license
- Paid or proprietary datasets
- Scraped personal or private data
- Incomplete documentation

---

## ✅ Review Process

Maintainers will:
- Verify the dataset license
- Check documentation completeness
- Validate dataset usability