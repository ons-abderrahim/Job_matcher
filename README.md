# **Job Matcher**

This is a tool that uses cosine similarity and the scikit-learn library to match job seekers with job openings. The tool takes in job descriptions for job seekers and job openings and calculates the cosine similarity between them. The job with the highest similarity score is recommended to the job seeker.

## **Usage**

1. Run the following command to start the program:

```
Copy code
python job_matcher.ipynb

```

1. Input the job description for the job seeker and the job openings in the format specified in the prompt.
2. The program will output the job opening with the highest similarity score to the job seeker's description.

## **Data**

The data used in this program is expected to be in a txt file containing the columns "job_title" and "job_description" for both the job seekers and job openings.

## **Note**

The program uses Cosine Similarity to compare the job descriptions, Cosine Similarity is a measure of similarity between two non-zero vectors of an inner product space that measures the cosine of the angle between them.

The program uses scikit-learn library for calculating the Cosine Similarity, scikit-learn is a Python library for machine learning built on top of NumPy and SciPy.

## **Contact**

If you have any questions or issues, please contact me at ons.abderrahim@ieee.org
