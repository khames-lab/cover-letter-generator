# Cover Letter Generator with Llama 2

This application allows you to generate a cover letter for a job application using the Llama 2 language model. 

The Llama 2 model used in this tutorial is hosted on the Replicate platform

Simply provide the necessary details, such as your name, company name, job title, and a job description, and let the AI generate a cover letter for you.

## Getting Started

To use this Cover Letter Generator, follow these steps:

1. Make sure you have the required libraries installed, including `replicate` and `streamlit`.
   
2. Set your Replicate API token by modifying the `os.environ["REPLICATE_API_TOKEN"]` line with your API token. Check https://replicate.com/docs/reference/http#authentication

3. Run the application using Streamlit by executing the script.

```bash
streamlit run your_script_name.py
```

## How does this work

1. Fill in the necessary details in the provided form, including your name, company name, hiring manager's name, job title, referral source, and paste the job description.

2. Adjust the AI temperature, which reflects the model's creativity (a value between 0 and 1).

3. Click the "Generate Cover Letter" button.

4. The AI will generate a cover letter based on your inputs and display it on the screen.

5. You can download the generated cover letter as a text file using the "Download Cover Letter as TXT" button.

## Credits
This Cover Letter Generator utilizes the Llama 2 language model from Replicate.
