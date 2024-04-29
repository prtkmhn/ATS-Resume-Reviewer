# Resume and Job Application Assistant

The Resume and Job Application Assistant is an AI-powered tool that helps job seekers optimize their resumes and improve their chances of getting hired. By leveraging advanced natural language processing and computer vision techniques, this assistant provides personalized recommendations and insights based on the job description and the user's resume.

## Features

- **Resume Analysis**: Upload your resume and get instant feedback on how well it matches the job description. The assistant uses cosine similarity to calculate a matching score and identifies areas for improvement.
- **Resume Optimization**: Receive personalized suggestions on how to update your resume to better align with the job requirements. The assistant provides a revised version of your resume with enhanced content and formatting.
- **Job Description Extraction**: Simply upload an image of the job description, and the assistant will automatically extract the relevant text using optical character recognition (OCR) technology.
- **Intelligent Chatbot**: Engage in a conversation with the AI-powered chatbot to get answers to your questions and receive guidance throughout the job application process. The chatbot is trained on the job description and your resume to provide context-aware responses.
- **Image Upload**: Enhance your interaction with the chatbot by uploading images related to your questions or the job application. The assistant can analyze the images and provide relevant insights.

## Technologies Used

- Python
- Gradio: A Python library for building web-based user interfaces
- Google Generative AI: A suite of powerful language models and vision models
- pytesseract: An optical character recognition (OCR) engine
- scikit-learn: A machine learning library for Python
- Pillow: A Python imaging library

## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/your-username/resume-job-assistant.git
   ```

2. Install the required dependencies:

3. Set up the Google API key:
   - Obtain an API key from the Google Cloud Console.
   - Set the `GOOGLE_API_KEY` environment variable with your API key.

4. Run the application:

5. Access the application in your web browser using Gradio

## Usage

1. Upload an image of the job description and your resume in text format.
2. Click the "Process Application" button to analyze your resume and get a matching score.
3. Review the extracted job information, similarity score, and the updated version of your resume.
4. Use the chatbot to ask questions and get guidance related to the job application.
5. Upload images to provide additional context or to receive insights from the assistant.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request. Make sure to follow the existing code style and guidelines.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- [Gradio](https://gradio.app/) for providing an easy-to-use interface for building web applications.
- [Google Generative AI](https://cloud.google.com/ai/generative-ai) for their powerful language models and vision models.
- [pytesseract](https://github.com/madmaze/pytesseract) for enabling optical character recognition capabilities.
- [scikit-learn](https://scikit-learn.org/) for the machine learning functionalities.
- [Pillow](https://pillow.readthedocs.io/) for image processing support.



