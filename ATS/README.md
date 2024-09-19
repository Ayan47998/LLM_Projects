# **ATS-like Resume Evaluation System**

## **Description**
You developed a model that simulates an Applicant Tracking System (ATS) for Data Scientist and AI/ML roles. The system takes job descriptions as input and evaluates user resumes, providing a matching score in percentage.

## **Key Components**
- **Model**: Google Gemini Pro, utilized as the underlying Generative AI model to assess resume-job description compatibility.
- **PDF Processing**: Used the `pypdf` library to convert resumes from PDF format to text, enabling analysis.
- **Frontend**: Implemented using Streamlit, allowing users to easily upload their resumes and job descriptions, and view results.

## **Workflow**
1. **Input**: Users provide a job description and upload their resume in PDF format.
2. **Processing**: The system converts the PDF resume to text and analyzes it against the job description.
3. **Evaluation**: Using the LLM, the system calculates a matching score based on keywords, skills, and experience relevant to the job description.
4. **Output**: The user receives a percentage score indicating how well their resume matches the job description.

## **Technologies Used**
- **Google Gemini Pro**: For advanced natural language understanding.
- **pypdf**: For PDF to text conversion.
- **Streamlit**: For creating an interactive web application interface.

## **Future Improvements**
- Incorporate more sophisticated scoring algorithms.
- Add features like keyword suggestions or tips for resume improvement.
- Expand to support other roles and industries.
