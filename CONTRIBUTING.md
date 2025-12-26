# Contributing to Open ML Datasets

Thank you for your interest in contributing!

## 📌 Contribution Rules

1. Only **open-source or public domain** datasets are allowed.
2. Each dataset **must include**:
   - `data.csv`
   - `data_description.md` 
   - `license.txt`(optional but mention license details must mention in data_description file)
   - `source.txt`(optional)
3. **No personal, sensitive, or private data**.
4. The dataset must be **useful for Machine Learning practice**.

---

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


## 📂 Where to Add a Dataset

Datasets are organized by **domain** (not by ML task).

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