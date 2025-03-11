# Back to the Feature

Back to the Feature is a research project analyzing movie screenplays using NLP, graph theory, and data mining techniques to explore the relationship between themes and financial success.

## Project Structure

### 1. `BigDataShort/`  
Contains resources for the first poster presentation.
- **`plots/`** – Contains BERTopic-generated plots. *(Currently outdated, pending replacement.)*
- **`BertopicPractice.ipynb`** – Notebook for subgenre classification using BERTopic and zero-shot classification.  
  - **To-Do:** Implement a neural network or regression model for subgenre prediction and compare against zero-shot classification.
- **`word_frequencies.json`** – Word frequency data from sampled screenplays.

### 2. `TheNodeFather/`  
Resources for the second poster presentation. *(Currently empty.)*

### 3. `ReadyVector1/`  
Resources for the third poster presentation. *(Currently empty.)*

### 4. `Data/`  
Contains various datasets used in the project.
- **`HierTags/`** – Archived IMDb dataset with keywords. *(Not usable due to missing movie ID lookups.)*
- **`IMDB/`** – Main dataset for the project.
  - **`subgenrefilms/`** – Text files with IMDb subgenre movie lists.
  - **`parsetextdata.ipynb`** – Parses subgenre movie lists and JSON datasets.
  - **`exploredata.ipynb`** – General data exploration.
  - **`imdb_titles_years_clean.csv`** – Contains movie titles and release years. (Indexed by IMDb title ID.)
  - **`imdb_titles_years.csv`** – Same as above but with an extra, confusing index. *(Do not use.)*
  - **`parsedsubgenres.json`** – Processed IMDb subgenre descriptions.
  - **`subgenre_counts.pdf`** – Horizontal bar plot of movie counts per subgenre.
  - **`subgenres_info.txt`** – Raw data used to generate `parsedsubgenres.json`.
  - **`subgenres_movies.json`** – JSON dataset of subgenre-classified movies.
  - **IMDb Public Datasets:**
    - `subgenres.txt`, `title_crew.tsv`, `title_episode.tsv`, `title_ratings.tsv` – IMDb-provided datasets.

### 5. `docs/`  
Files for the GitHub Pages dashboard.
- **`index.html`** – Main dashboard page.
- **`plots/`** – Supporting visualizations for the dashboard.

### 6. Root-Level Files
- **`explore_data.ipynb`** – Notebook for general data exploration.
- **`generate_dashboard.ipynb`** – *(Deprecated, no longer used.)*
- **`README.md`** – This file.