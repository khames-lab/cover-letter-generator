# Cover letter generator using Llama2 and streamlit

![Capture d’écran 2023-09-30 164959](https://github.com/khames-lab/cover_letter_generator/assets/77197337/c93415a2-9433-4e89-bbd2-8e07e4f9514a)


This application allows you to generate a cover letter for a job application using the Llama 2 language model. 

The Llama 2 model used in this tutorial is hosted on the Replicate platform

Simply provide the necessary details, such as your name, company name, job title, and a job description, and let the AI generate a cover letter for you.


![Capture d’écran 2023-09-30 165320](https://github.com/khames-lab/cover_letter_generator/assets/77197337/d70849e8-91f5-443f-8f91-8de3c472cc58)

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
