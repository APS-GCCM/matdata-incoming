# matdata-incoming

**Submission repo** for new datasets to the [matdata](https://github.com/APS-GCCM/matdata) high-pressure materials database.

This repository is *only* for incoming data. Accepted submissions are checked and merged into the main `matdata` database repository.

---

## 📤 How to submit data

### 1. Using the GitHub submission form (preferred)
If you have a GitHub account:

1. Open the [Data submission form](https://github.com/APS-GCCM/matdata-incoming/issues/new?template=data-submission.yml).
2. Fill in the metadata fields as far as possible.
3. Drag and drop your data file(s) into the issue:
   - **Data**: `.tsv` / `.csv` / `.txt` (tab- or space-delimited preferred)
   - **Metadata**: optional `submission.yaml` (see [template](templates/submission.yaml))
4. Submit the issue.

Your submission will be automatically labeled for processing.

---

### 2. No GitHub account? Submit by email
Email your files to: **dswift@llnl.gov** with the subject `Matdata submission`.

Please attach:
- `submission.yaml` (metadata, see [template](templates/submission.yaml))
- Your data file(s) in tab or space delimited format

We will transfer the data to the repo on your behalf.

---

## 📄 File formats

### Metadata file (`submission.yaml`)
Example: [`templates/submission.yaml`](templates/submission.yaml)
