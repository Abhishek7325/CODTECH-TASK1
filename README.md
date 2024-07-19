#### Name: ABHISHEK RAWAT 
#### Company: CODTECH IT SOLUTIONS
#### ID: CT8AI1182
#### Domain: Artificial Intelligence
#### Duration: June to August 2024

# Overview of the Project
## Project: Resume Scanner Using Natural Language processing
## Objective
This project objective to create a simple yet effective resume scanner that compares a candidate's resume against a job description using Natural Language Processing (NLP) techniques. The purpose is to determine how closely a resume matches a given job description, aiding both job seekers and recruiters in the hiring process.

## Key Steps Involved:

1.Installation of Required Libraries:
The docx2txt library is used to read text from .docx files, making it easy to process resumes and job descriptions in a common format.

2.Reading the Documents:
The job description and resume are uploaded and processed using docx2txt, extracting the text content from these documents.

3.Displaying the Resume:
For verification purposes, the content of the resume is printed to ensure it has been correctly read and processed.

4.Combining the Content:
The text content of the job description and the resume are stored in a list called content.

5.Text Vectorization:
The CountVectorizer from the sklearn.feature_extraction.text module is used to convert the text data into a matrix of token counts. This is a common technique in NLP for preparing text data for machine learning algorithms.

5.Calculating Cosine Similarity:
Cosine similarity is computed between the job description and the resume. This metric measures the cosine of the angle between two vectors in a multi-dimensional space, providing a measure of similarity between the two documents.

6.Interpreting the Results:
The similarity matrix is printed, showing the similarity scores. The specific similarity score between the job description and the resume is extracted and converted into a percentage to indicate how well the resume matches the job description.

## Result Interpretation:
In case 1, the similarity score between the resume1 file and the job description file is approximately 56.68%. This means that the resume matches the job description by 56.68%, indicating a moderate level of relevance.
