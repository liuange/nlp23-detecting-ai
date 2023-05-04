# nlp23-detecting-ai
Final project for info259

* **data_preprocessing**: separate notebook for HC3 import and transformations to get dataframe into form: q_id / question / answer / true_label (real/fake) / source
* **research_pipeline**: import dataframe from preprocessing step, run detector model and extract / analyze misclassified texts
* **shap_analysis** runs detector model on subset of data to obtain SHAP score for quantitative evaluation