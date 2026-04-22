# Alone TV Show — Unsupervised Learning Project (BA820)

A Boston University **BA820** group project applying unsupervised learning methods to two datasets: contestant and season-level data from the survival reality TV show **Alone**, and a separate **Cats UK** dataset used for comparative exploration.

> The canonical write-ups of methodology and findings are the PDFs in `M3_Integrated&Synergized_Analysis/` and `M5_Final/` — this README is a map of the repository, not a substitute for the report.

## Team

- Mika Ismayilli
- Akbar Wibowo
- Burak Ataseven
- Steven Marathias

## Datasets

| Dataset | Location |
|---|---|
| Alone TV Show | `Alone TV Show Dataset/` |
| Cats UK | `Cats UK Dataset/` |

Field-level definitions and cleaning decisions live inside the notebooks rather than here.

## Repository Structure

The project was delivered in five milestones, each in its own directory.

| Milestone | Directory | Contents |
|---|---|---|
| **M1 — Proposal** | `M1_Proposal/` | EDA notebooks for both datasets: `Alone_TV_Data_EDA.ipynb`, `CatsUK_EDA_Notebook.ipynb` |
| **M2 — Individual work** | `M2_Individual/` | Per-teammate subdirectories: `Akbar/`, `Burak/`, `Mika/`, `Steven/` |
| **M3 — Integrated & synergized analysis** | `M3_Integrated&Synergized_Analysis/` | Combined notebook `M3_Integration_Submission.ipynb`, written report `BA820_Project_M3_Report.pdf`, and `figures/` |
| **M4 — Refinement** | `M4_Refinement/` | Per-teammate refinement folders |
| **M5 — Final** | `M5_Final/` | Final presentation `AloneTV_Final_Presentation.pdf` and `contribution table.pdf` |

## Final Deliverables

- **Written report:** `M3_Integrated&Synergized_Analysis/BA820_Project_M3_Report.pdf`
- **Final presentation:** `M5_Final/AloneTV_Final_Presentation.pdf`
- **Contribution table:** `M5_Final/contribution table.pdf`

## Tech Stack

Python, in Jupyter Notebooks. No `requirements.txt` is pinned — the notebooks themselves document the libraries in use.

## Notes

- The `.gitkeep` files in several milestone directories are placeholders that predate the content commits.
- Raw data files are committed directly to the dataset directories; no external data fetching is required to run the notebooks.
