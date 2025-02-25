Neural Network Model Comparison on Genome Sequence Detection data: AlexNet vs. NiNNet

Overview

This project compares the performance of two deep learning architectures, AlexNet and NiNNet, using different optimization techniques. The models are trained and evaluated on a given genome sequence dataset to analyze their accuracy and classification performance. The results are visualized using accuracy curves and confusion matrices.

Project Features
✔️ Implementation of AlexNet and NiNNet architectures.
✔️ Training with multiple optimizers: SGD, Adam, and RMSprop.
✔️ Comparison of model performance across different configurations.
✔️ Visualization of accuracy trends over epochs.
✔️ Generation of confusion matrices for error analysis.

Experiment Configurations
The project runs experiments with the following configurations:

Model	Optimizer	Batch Size	Learning Rate	Epochs
AlexNet	 SGD	      256	       0.001	      10
AlexNet	 Adam	     1032	      0.0001	      10
NiNNet	 RMSprop	  516	      0.0005	      10
NiNNet	 Adam	     1032	      0.0001	      10

Results & Analysis
📈 Accuracy Curves: The accuracy of each configuration is plotted across epochs to visualize model performance.
📊 Confusion Matrices: Heatmaps are generated to analyze model predictions and misclassifications.


How to Run

1.Clone the repository:
git clone https://github.com/venkateshbollineni/Genome-Sequence-Detection-pytorchframework-DeepLearning.git
cd cd Genome-Sequence-Detection-pytorchframework-DeepLearning

2.Install dependencies:
pip install -r requirements.txt

3.Launch Jupyter Notebook
jupyter notebook

4.Open the notebook and run the experiment:
GenomeSeqDetection.ipynb

5.View the generated plots for accuracy trends and confusion matrices.

Technologies Used
🔹 PyTorch – For model implementation and training
🔹 Matplotlib & Seaborn – For result visualization
🔹 Scikit-learn – For evaluation metrics

NOTE: You would need your own Genome Sequence Dataset to execute the file.