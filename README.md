# nlp23-detecting-ai
Final project for info259

* **data_preprocessing**: separate notebook for HC3 import and transformations to get dataframe into form: q_id / question / answer / true_label (real/fake) / source
    ** TO DO: bring "!\nnetwork error" code over from research pipeline
* **research_pipeline**: import dataframe from preprocessing step, run detector model and extract / analyze misclassified texts
    ** TO DO: update Extract Misclassified Data section to run on cleaned dataframe from data_preprocessing
* **shap_analysis** runs detector model on subset of data to obtain SHAP score for quantitative evaluation