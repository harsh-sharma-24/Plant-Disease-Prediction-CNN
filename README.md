# 🥬 PlantVillage Crop Disease Classification using Deep Learning
This deep learning project classifies leaf diseases in tomato, potato, and bell pepper plants using the PlantVillage dataset. It leverages Convolutional Neural Networks (CNNs) built with TensorFlow/Keras to automate plant disease diagnosis based on image data.

## 🔍 Dataset Classes (15 total)
The model is trained to classify the following leaf conditions:

## 🫑 Pepper (Bell Pepper)
Pepper__bell___Bacterial_spot

Pepper__bell___healthy

## 🥔 Potato
Potato___Early_blight

Potato___Late_blight

Potato___healthy

## 🍅 Tomato
Tomato_Bacterial_spot

Tomato_Early_blight

Tomato_Late_blight

Tomato_Leaf_Mold

Tomato_Septoria_leaf_spot

Tomato_Spider_mites_Two_spotted_spider_mite

Tomato__Target_Spot

Tomato__Tomato_YellowLeaf__Curl_Virus

Tomato__Tomato_mosaic_virus

Tomato_healthy

## 🧠 Model Highlights
🗂️ Trained on 15 classes from the PlantVillage dataset

🖼️ Images resized to a fixed shape (256x256) and normalized

⚙️ Augmentation applied: rotation, zoom, flips

📊 Training/validation loss and accuracy plotted

🧪 Predicts disease from single or batch leaf images

