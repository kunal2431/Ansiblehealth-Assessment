# Markdown to Google Docs Converter

## Brief Description
This project converts structured **markdown meeting notes** into a **fully formatted Google Doc** using the **Google Docs API**.  
It supports headings, nested bullet points, checkboxes, @mentions styling, and footer formatting.  
The solution is designed to run in **Google Colab** and demonstrates API integration, text parsing, and document formatting.

---

## Setup Instructions

1. Open **Google Colab**:  
   https://colab.research.google.com/

2. Ensure you are logged into the **Google account** where the document should be created.

3. Open **Full_Stack_Software_Engineer_Assessment_Task_Kunal.ipynb**.

4. Run the notebook cell and approve Google authorization when prompted.

---

## Required Dependencies

The following Python packages are required (automatically installed in Colab):

- `google-api-python-client`
- `google-auth`
- `google-auth-httplib2`
- `google-auth-oauthlib`

They are installed in the notebook using:

```bash
pip install google-api-python-client google-auth google-auth-httplib2 google-auth-oauthlib
