# Submitted to [FarmWise](https://listedinc.notion.site/About-Us-Listed-Inc-c158f2e78d7948a2abae6033e56920e8)

Chat application that allows users to have interactive conversations with the content of five research papers. The application should utilize the GPT 3.5 model for retrieval augmented generation (RAG).

## Chat with PDF
This application is an LLM-powered chatbot that allows users to interact with PDF files using natural language queries. The chatbot is built using the following technologies:

- [Streamlit](https://streamlit.io/): A Python library for creating web apps for data science and machine learning projects.
- [LangChain](https://python.langchain.com/): A library for natural language processing tasks.
- [OpenAI](https://platform.openai.com/docs/models): An LLM (Language Model) model used for question answering.

Crafted by: [Murali Manoharan](https://github.com/MURALIMANOHARAN1)

## Usage
1. Install the required dependencies by running `pip install streamlit dotenv PyPDF2 streamlit_extras langchain`
2. Create an environment file (`.env`) and set your OpenAI API key as `openai_api_key=YOUR_API_KEY`.
3. Run the app by executing `streamlit run your_script.py`.
4. In the app's sidebar, you'll find information about the Farmwise Ai chatbot and its components.
5. Upload a PDF file by clicking the "Upload your PDF" button.
6. Once the PDF is uploaded, the app will extract the text and split it into chunks for processing.
7. The chatbot will then prompt you to ask questions about the PDF content using the text input field.
8. Enter your question, and the chatbot will provide answers based on the content of the PDF using the OpenAI LLM model.

## Dependencies
- `streamlit`: 0.89.0
- `dotenv`: 0.19.0
- `PyPDF2`: 1.26.0
- `streamlit_extras`: 0.31.1
- `langchain`: 1.1.0

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Please note that the above information is just a template, and you should modify it to fit the specific details of your project. The README file serves as documentation to help users understand and use your Python script effectively. Include installation instructions, usage guidelines, dependencies, and any other relevant information that would assist users in working with your application.
