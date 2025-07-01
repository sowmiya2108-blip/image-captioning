# image-captioning
📸 Flickr Datasets for Image Captioning
Flickr8k:
Available at: https://www.kaggle.com/datasets/adityajn105/flickr8k
🧰 Technologies Used
Python

TensorFlow or PyTorch

Keras (for building models easily)

OpenCV / PIL (for image processing)

NLTK / SpaCy (for text preprocessing)

🔄 Workflow
Load dataset (images + captions)

Preprocess text (tokenization, padding, vocab creation)

Extract image features using CNN (e.g., ResNet)

Prepare sequences for training (image + partial caption → next word)

Train model with CNN + RNN/LSTM

Generate caption for new image by predicting one word at a time

