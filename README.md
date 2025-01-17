# Cybersecurity and AI Project Repository

Welcome to the **Cybersecurity and AI Project Repository**, a collection of projects leveraging machine learning to solve real-world cybersecurity and anomaly detection challenges. This repository showcases work in phishing detection, fake news classification, and poisoned image anomaly detection.

These projects were completed during the Fall 2024 semester as part of my Cybersecurity and AI class at Boise State University, where I am a junior studying computer science, cybersecurity and AI. As a student learning about the intersection of artificial intelligence and cybersecurity, this work reflects both academic exploration and hands-on application of machine learning techniques to solve complex problems.

---

## Repository Structure

- **Root Directory**  
  **Project:** *AI-based Cyber Attack Detection*  
  Machine learning models applied to cybersecurity datasets to detect phishing attempts, network intrusions, and Android malware.  
  - **Key Highlights:**
    - Prepared data by analyzing and removing outliers and handling missing values to improve model accuracy.
    - Trained models using 10-fold cross-validation and an 80/20 train/test split while avoiding overfitting.
    - Fine-tuned parameters like tree depth, kernel types (Linear, Polynomial, RBF), and network architectures (ANN) to
      maximize performance across datasets.
    - Compared algorithm performance across precision, recall, and F1-score, presenting results with clear visualizations. 
  - **Tools Used:** Python, Anaconda, JupyterLab, ML Libraries  
  - **GitHub:** [AI-based Cyber Attack Detection](https://github.com/GraceLytle/CS597-CyberAI)

- **`project2/` Directory**  
  **Project:** *TruthSeeker Fake News Detection*  
  A pipeline to detect fake news on Twitter using the TruthSeeker dataset. Includes both 2-class and 4-class classification models.  
  - **Key Highlights:**
    - Processed data to group tweets by statement, ensuring no overlap between training and validation sets for accurate
      model evaluation and used an 80/20 train/test split.
    - Implemented label mapping for binary and 4-way classification, converting string labels into numerical values to
      support model training.
    - Applied both traditional machine learning techniques and fine-tuned BERT-based architecture.
    - Optimized training by experimenting with hyperparameters such as learning rates, batch sizes, weight decay, and
      warm up steps to enhance performance.  
  - **Tools Used:** Python, Anaconda, PyTorch, Hugging Face Transformers, BERT based model, JupyterLab, ML Libraries
  - **GitHub:** [TruthSeeker Fake News Detection](https://github.com/GraceLytle/CS597-CyberAI/tree/main/Project2)

- **`project3/` Directory**  
  **Project:** *Anomaly Detection for Poisoned Images*  
  Detecting poisoned images in the CIFAR-10 dataset using a fine-tuned ResNet18 model and ASPARaGUS-generated samples.  
  - **Key Highlights:**
    - Fine-tuned a ResNet18 model, pre-trained on CIFAR-10, to classify poisoned versus clean images with a training set
      of balanced samples and tested on unseen data for validation.
    - Adjusted early convolutional layers in ResNet18 to improve the model’s ability to recognize low-level patterns in
      poisoned image data.
    - Trained with subsets of balanced data, applying techniques like batch size tuning and early stopping to prevent
      overfitting.
    - Exported the fine-tuned model for reusability in future anomaly detection workflows using Python’s pickle module.
    - Processed a large dataset of images (5,000 clean 500 poisoned) using the saved fine-tuned model, logging the results
      to validate the detection of anomalies with high accuracy.
  - **Tools Used:** Python, PyTorch, ASPARaGUS, ResNet18, CIFAR-10 Dataset  
  - **GitHub:** [Anomaly Detection for Poisoned Images](https://github.com/GraceLytle/CS597-CyberAI/tree/main/Project3) 

---
