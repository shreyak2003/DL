https://chatgpt.com/share/67297239-179c-8004-bb9c-ddcfcdc568e9
Implementing Feedforward neural networks with Keras and TensorFlow
a. Import the necessary packages
b. Load the training and testing data (MNIST/CIFAR10)
c. Define the network architecture using Keras
d. Train the model using SGD
e. Evaluate the network
f. Plot the training loss and accuracy

test_predict = model.predict(x_test)
test_predict_labels = np.argmax(test_predict, axis=1)
confusion_matrix=tf.confusion_matrix(labels=y_test, prediction=test_predict_labels)
print('confusion matrix is\n', confusion_matrix)

https://chatgpt.com/share/67296baf-220c-8004-a375-6032851b7a9b

https://chatgpt.com/share/67296bc8-af38-8004-ad2f-6d8090e0fc5b

https://chatgpt.com/share/67296bd9-4268-8000-a266-4b55bb4c5b16

https://chatgpt.com/share/67296bea-f918-8000-84f1-da63c0cd93ba

https://chatgpt.com/share/672970ac-5400-8000-b090-58cd0e21548d
