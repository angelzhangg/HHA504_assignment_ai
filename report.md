## Objective
The objective of this assignment is to introduce you to the use of pre-trained machine learning models in Azure and Google Cloud Platform (GCP). You will use cloud-based notebooks to interact with these models, focusing on speech and vision capabilities.

## Instructions

### 1. Work with Pre-trained Speech Models
- **GCP Speech-to-Text:**
  - Navigate to GCP and access the Vertex AI Notebooks.
  - Use a pre-configured notebook to interact with the GCP Speech-to-Text API.
  - Upload a sample audio file and transcribe it using the pre-trained speech model.
  - Document the results and the steps you took to achieve them.
    
![gcp](https://github.com/user-attachments/assets/23dedb5d-ef32-4695-85db-b57852b04a61)

Go into Collab Enterprise notebook, install the necessary libraries for using the Speech-to-Text API:
  
![code](https://github.com/user-attachments/assets/20b617aa-987a-42ce-9c5d-946892ad91ea)

Ensure the speech to text api is enabled otherwised during the authenticate user, we would get error
  
![error](https://github.com/user-attachments/assets/fc0bfb9c-4325-4c2a-a6cd-16a737b1a69c)

Could not get this code to work





### 2. Work with Pre-trained Vision Models
- **GCP Vision API:**
  - In the same or a new notebook, interact with the GCP Vision API.
  - Upload an image and use the Vision API to detect objects or text within the image.
  - Document the results and provide a brief analysis of the model's accuracy.

![vision_api](https://github.com/user-attachments/assets/975b1217-0f61-4dad-88b2-4474d1739123)
Ensure vision api is enabled otherwised during the authenticate user, we would get error

![error](https://github.com/user-attachments/assets/b4677fe1-5965-45be-a360-ce295ade56ab)
Could not get this code to work


  
- **Azure AI Vision:**
  - Switch to Azure and access Azure Machine Learning (AML) Notebooks.
  - Use a pre-trained vision model in AML to perform a similar task as with GCP, such as object detection or text recognition.
  - Compare the results with those from GCP and document your findings.

### 3. Submit Your Work
- Create a Markdown document that includes:
  - Screenshots or outputs from the GCP Speech-to-Text and Vision API interactions.
  - Screenshots or outputs from the Azure AI Vision model interactions.
  - A comparison of the results from GCP and Azure, including reflections on model accuracy and ease of use.
  - Any challenges faced and how you resolved them.
