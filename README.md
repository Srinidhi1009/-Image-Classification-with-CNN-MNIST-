# Task 4: Image Classification with CNN (MNIST)

## 📌 Description
Build and train a **Convolutional Neural Network (CNN)** on the MNIST dataset to classify handwritten digits.

---

## 📖 Overview
Image classification is a core application of deep learning.  
In this task:
- The **MNIST dataset** of 70,000 handwritten digits (0–9) is used.  
- The dataset is normalized (pixel values scaled between 0 and 1).  
- A **CNN model** is built with TensorFlow/Keras.  
- The model is trained and evaluated for accuracy on test images.  

---

## ⚙️ Steps Performed
1. Load the MNIST dataset from TensorFlow.  
2. Normalize pixel values for better training performance.  
3. Build a CNN model with Conv2D, MaxPooling, Flatten, Dense layers.  
4. Compile the model with Adam optimizer and categorical crossentropy loss.  
5. Train the model on training data.  
6. Evaluate model accuracy on the test set.  

---

## 📊 Expected Output

```
Epoch 1/1
1688/1688 [==============================] - 12s 7ms/step - loss: 0.2004 - accuracy: 0.9417 - val_loss: 0.0852 - val_accuracy: 0.9745
313/313 - 1s - loss: 0.0795 - accuracy: 0.9750
Test accuracy: 0.9750
```

*(Accuracy may vary depending on number of epochs and hardware used.)*

---

## 🛠️ Requirements

Install the required library:

```bash
pip install tensorflow
```

---

## 🚀 How to Run

Run the script:

```bash
python task4_cnn.py
```

## 🔮 Future Enhancements

* Add more convolutional and pooling layers for better accuracy.
* Train for more epochs to achieve higher test accuracy.
* Use data augmentation to improve generalization.
* Experiment with transfer learning (e.g., pretrained CNN models).

---

## 👨‍💻 Author

Your Name
📧 [srinidhimudumba@gmail.com](mailto:srinidhimudumba@gmail.com)
🌐 [GitHub Profile](https://github.com/Srinidhi1009)

```
