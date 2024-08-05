Seq2Seq Translation Model
This project demonstrates training a sequence-to-sequence (Seq2Seq) model for translation from Tshiluba to English using the Helsinki-NLP/opus-mt-mul-en model available in the MarianMT library on Hugging Face. The pretrained model is fine-tuned using the best hyperparameters obtained through Optuna and is evaluated using the BLEU score. The final model is deployed on Streamlit.

Overview
Model: Helsinki-NLP/opus-mt-mul-en
Task: Translation from Tshiluba to English
Optimization: Hyperparameters are tuned using Optuna.


Evaluation: Model performance is evaluated using the BLEU score.


Deployment: The best model is deployed on Streamlit.


Hyperparameter Optimization
The best hyperparameters are printed to the console after optimization.


Evaluation
The model's performance is evaluated using BLEU score, which measures the quality of the translations.

Saving and Loading
The model and tokenizer are saved to the following paths:

Model: /content/drive/My Drive/New_best_model
Tokenizer: /content/drive/My Drive/New_best_tokenizer


Application Deployment




Youtube video link of deployement explanation: https://youtu.be/HFZCnpz9ZDM



We deployed our translation model through Streamlit. You can access the app via the following link:

Streamlit App Link: [Streamlit App](https://sad-results-wish.loca.lt/)


To Run the App

Download the Streamlit app source file called: translation.py
Download the Colab notebook that includes the model fun process called finaltshiluba grouplydia.ipng
Use the provided run code with the specified paths for the applications called streamlitrun.




Contributing
If you would like to contribute to this project, please submit a pull request or open an issue.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Feel free to adjust the details as necessary to fit your specific project and provide any additional links or information needed.
