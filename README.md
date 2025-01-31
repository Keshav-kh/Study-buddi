
# Study Buddi 📚

## Project Description

The PDF Analyzer App is a web-based application that allows users to upload a PDF file and ask questions about its content. Additionally, the app includes two distinct features: 
- Topic-based Quiz Generator: Users can enter a specific topic, and the app generates a 10-question quiz with multiple-choice options.
- Summary-based Q&A: Users can ask questions about the content of the uploaded PDF, and the app will provide relevant answers.

## 🏆 Award

This project won the **"Best Integration for Streamlit and AI"** at HackPSU.

## 🚀 Features

1. **PDF Upload**: Users can upload a PDF document to the app.
2. **Topic-based Quiz Generator**: Users can toggle to 'Topic' mode and enter a word. The app will generate a 10-question quiz related to the word with multiple-choice questions.
3. **Summary-based Q&A**: When the toggle is set to 'Summary,' users can ask questions about the PDF content and receive answers.
4. **User-friendly Interface**: Simple and interactive web interface using Streamlit.
5. **Instant Feedback**: For quizzes, the app provides explanations for correct and incorrect answers.

## 🛠️ Technologies Used

- **Streamlit**: For building the web interface.
- **Langchain**: For processing and managing the AI workflows.
- **FAISS**: For vector storage and similarity search.
- **Google Generative AI**: For embeddings and conversational AI.
- **OCR.space**: For extracting text from images.
- **PyPDF2**: For reading and processing PDFs.
- **PIL**: For handling image files.
- **dotenv**: For managing environment variables.

## 📦 Setup and Installation

1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```bash
    cd pdf-analyzer-app
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the app:
    ```bash
    streamlit run app.py
    ```

## 📝 Usage

1. Launch the application by running the above command.
2. Upload a PDF file using the provided interface.
3. Toggle between 'Topic' and 'Summary' mode based on your requirement:
    - In 'Topic' mode, enter a keyword to generate a quiz.
    - In 'Summary' mode, ask questions related to the PDF content.
4. View results, feedback, and answers directly on the app.

## 📚 Example

**PDF Analyzer**
- Upload a PDF file using the sidebar.
- Type a question related to the PDF content.
- Receive contextual answers powered by Google Generative AI.
  
**Quiz Generator**
- Process a PDF to extract content.
- Generate a 10-question quiz and attempt it.
- Get instant feedback on your answers with explanations.|

**Screenshot Analyzer**
- Upload a screenshot containing a question.
- Let the app analyze and provide the answer using OCR and AI.

## 🤝 Contribution

Contributions are welcome! Please fork the repository and submit a pull request for any features or improvements.

## 📝 License

This project is licensed under the MIT License.

## 👨‍💻 Author

Keshav Khandelwal & Viraj Mishra
