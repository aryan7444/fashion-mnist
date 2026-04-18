# fashion-mnist
👕 Fashion MNIST Classification using PyTorch
A deep learning project that classifies clothing images from the Fashion MNIST dataset using a fully connected neural network built with PyTorch.

📌 Project Overview
This project demonstrates how to build, train, and evaluate a neural network for image classification. The model takes grayscale images of clothing items and predicts the correct category.

🧠 Model Architecture
The neural network consists of:

Input Layer: 28 × 28 pixels (flattened to 784)
Hidden Layer 1: 512 neurons + ReLU activation
Hidden Layer 2: 512 neurons + ReLU activation
Output Layer: 10 classes (Softmax applied during evaluation)
🗂 Dataset
The project uses the Fashion MNIST dataset, which includes:

60,000 training images
10,000 testing images
10 classes of clothing:
Label	Class
0	T-shirt/top
1	Trouser
2	Pullover
3	Dress
4	Coat
5	Sandal
6	Shirt
7	Sneaker
8	Bag
9	Ankle boot
⚙️ Tech Stack
Python
PyTorch
NumPy
Matplotlib
🚀 Features
Custom neural network using nn.Module
Forward and backward propagation
Loss calculation using Mean Squared Error (MSE)
GPU/CPU device support
Image visualization with predictions
📊 Sample Output
Displays input image
Shows predicted vs actual label
🛠 Installation & Setup
# Clone the repository
git clone https://github.com/your-username/fashion-mnist-classification-pytorch.git

# Navigate to project folder
cd fashion-mnist-classification-pytorch

# Install dependencies
pip install torch torchvision matplotlib numpy
▶️ Usage
Run the script:

python main.py
📈 Future Improvements
Add Convolutional Neural Network (CNN) for better accuracy
Implement training loop with epochs and optimizer
Add accuracy and loss graphs
Deploy as a web app
🤝 Contributing
Feel free to fork this repository and improve it. Contributions are welcome!

📬 Contact
For any queries, feel free to reach out.

⭐ Acknowledgements
PyTorch Documentation
Fashion MNIST Dataset
⭐ If you like this project, don't forget to star the repo!
