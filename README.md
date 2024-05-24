# pitch-classification
Since you did not explicitly mention using Docker, I will omit it from the description. Here is the revised version without Docker:

---

**Machine Learning System for MLB Pitch Classification**

*Project Overview:*
Developed a machine learning system to classify pitches thrown in Major League Baseball (MLB) games, making real-time predictions based on pitch characteristics. Created individual models for each pitcher and connected the outputs to larger systems through APIs.

*Key Contributions:*
- **Data Processing:**
  - Utilized MLB Statcast data for pitch characteristics and processed data using pybaseball and custom scripts.
  - Developed scripts for data cleaning, feature extraction, and data transformation to prepare datasets for model training.

- **Machine Learning:**
  - Trained multiple machine learning models (one for each pitcher) using scikit-learn and PyTorch.
  - Implemented pipelines and composite estimators to streamline model training and evaluation processes.
  - Evaluated model performance using metrics like accuracy, precision, recall, and F1-score.

- **API Development:**
  - Developed a FastAPI-based web API to serve the machine learning model predictions in real-time.
  - Ensured seamless integration of the machine learning models with the larger system through API endpoints.
  - Implemented robust error handling and logging to ensure reliability and maintainability of the API service.

*Technologies Used:*
- **Programming Languages:** Python
- **Libraries:** scikit-learn, PyTorch, FastAPI, pybaseball
- **Tools:** MLB Statcast, Baseball Savant, Git (for version control)

*Project Impact:*
- Enabled real-time prediction and classification of MLB pitches, enhancing the analytical capabilities of the system.
- Provided a scalable solution for integrating machine learning models into production environments through APIs.

*Project Files:*
- Developed several Python scripts for data processing (`make-data.py`), model training (`make-models.py`), and metrics evaluation (`make-metrics.py`).
- Implemented API server (`server.py`) and client (`client.py`) scripts to manage and query model predictions.
- Created a main script (`run.py`) to orchestrate the entire workflow.

Baseball Data
1. [MLB Technology Blog: Introducing Statcast](https://technology.mlblogs.com/introducing-statcast-2020-hawk-eye-and-google-cloud-a5f5c20321b8)
    - [Baseball Savant](https://baseballsavant.mlb.com/)
    - [Statcast Search](https://baseballsavant.mlb.com/statcast_search)
    - [Statcast Search CSV Documentation](https://baseballsavant.mlb.com/csv-docs)
    - [pybaseball](https://pypi.org/project/pybaseball/)

Machine Learning
1. [scikit-learn](https://scikit-learn.org/stable/index.html)
    - [scikit-learn: Pipelines and Composite Estimators](https://scikit-learn.org/stable/modules/compose.html)
    - [A Comprehensive Guide For scikit-learn Pipelines](https://mahmoudyusof.github.io/general/scikit-learn-pipelines/)
2. [pytorch](https://pytorch.org/)
3. [Designing Machine Learning Systems](https://i-share-uiu.primo.exlibrisgroup.com/discovery/fulldisplay?docid=alma99955167516705899&context=L&vid=01CARLI_UIU:CARLI_UIU&search_scope=MyInstitution&tab=LibraryCatalog&lang=en)
    - [Chip Huyen](https://huyenchip.com/)
4. [Sebastian Raschka: Introduction to Machine Learning](https://sebastianraschka.com/blog/2021/ml-course.html)

Web API
1. [FastAPI](https://fastapi.tiangolo.com/)
