LIVE_DEMO-->https://emotion-classification-1.onrender.com

Name: Emotion Classification
Description: Small NLP project to classify emotions from text using a pretrained BiGRU model.

The project loads a pretrained BiGRU model from Artifacts/BiGRU_Modle.keras, preprocesses input text (tokenization, padding and embedding) as implemented in main.py, feeds the processed sequences into the BiGRU network to produce class probabilities, and maps the highest-probability output to an emotion label; predictions are exposed either via the CLI/HTTP endpoint in main.py or through the simple web demo in static (index.html, script.js) for interactive testing.

