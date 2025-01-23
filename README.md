# Visual-Question-Answering-With-Multimodal-Transformers

**Introduction:**
 
Understanding visuals and natural language inquiries relating to those images is a difficult problem known as Visual Question Answering (VQA). The multimodal transformer-based technique used in this research addresses the VQA issue. The model integrates data from text and image modalities to generate precise responses to image-related queries.

**Solution Outline:**

**Problem Statement:** Given an image and a natural language question related to the image, the goal is to generate a natural language answer.

**Approach:**

	•	Featurization of Image and Question
 
	•	Feature Fusion using Late Fusion
 
	•	Answer Generation
 
**Implementation Steps:**

	•	Data Preparation: Preprocess the DAQUAR dataset.
 
	•	Model Architecture: Define a multimodal transformer model architecture.
 
	•	Training: Train the model using the processed dataset.
 
	•	Evaluation: Evaluate the model's performance using established metrics for VQA.
 
**Evaluation Metrics:**

	•	Accuracy
 
	•	Macro F1 Score
 
	•	Wu and Palmer Similarity (WUPS) Score
 
**Example Input and Output**

Input:

	•	Image: 
	•	Question: "What is on the desk and behind the black cup?"

Output:

	•	Answer: "Bottle"
 
**Setup and Running Instructions**
**Environment Setup:**
 
	•	Create a virtual environment.
 
	•	Install required packages listed in requirements.txt.
 
**Data Preparation:**
 
	•	Download the DAQUAR dataset from link.
 
	•	Preprocess the dataset using the provided scripts.
 
**Training:**
 
	•	Run the training script, providing necessary hyperparameters.
 
**Evaluation:**
 
	•	Run the evaluation script to assess the model's performance.
 
 **Inference:**
 
	•	Use the trained model to make predictions on new image-question pairs.
 
**Dataset**

	•	The full DAQUAR dataset can be found In the following link.
 
	•	https://www.kaggle.com/datasets/priya1506/daquar-processed

**References:**

Couto, J. (2018, March 1). Introduction to visual question answering: Datasets, approaches and evaluation. Tryolabs. https://tryolabs.com/blog/2018/03/01/introduction-to-visual-question-answering 

Daquar. Kaggle. (2023, April 16). https://www.kaggle.com/datasets/dotran0101/daquar?select=test.csv 

Koluguri, N. R. (2019, April 30). Visual question answering - attention and fusion based approaches. Medium. https://medium.com/@nithinraok_/visual-question-answering-attention-and-fusion-based-approaches-ebef62fa55aa 

Sahu, T. (2022, March 8). Visual question answering with Multimodal Transformers. Medium. https://medium.com/data-science-at-microsoft/visual-question-answering-with-multimodal-transformers-d4f57950c867 
