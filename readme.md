

# Chat with PDF - AI-Powered Document Interaction

## Overview

"Chat with PDF" is a revolutionary AI-powered tool that enables real-time interaction with PDF documents. It allows users to upload PDFs and instantly extract key insights, ask questions about the document, summarize lengthy reports, and search for specific content—all driven by AI and natural language processing (NLP).

With this tool, handling documents like reports, research papers, or legal contracts becomes effortless. Whether you're a student, researcher, or professional, this AI solution transforms how you engage with documents.

## Features

- **Instant PDF Upload & Processing**: Upload your PDFs and get key insights instantly.
- **AI-driven Question Answering**: Ask questions about the content of the document and receive intelligent responses.
- **Summarization**: Quickly summarize lengthy reports, papers, or contracts.
- **Advanced Search**: Search for specific content within the PDF using AI-powered search functionality.

## Technologies Used

- **LangChain**: Framework for building applications with LLMs (Large Language Models) and external data sources.
- **FAISS**: Fast Approximate Nearest Neighbor search for efficient vector search and document retrieval.
- **LLMs (Large Language Models)**: For natural language understanding and providing intelligent responses.
- **Document Embeddings**: Contextual embeddings that allow for relevant and accurate document retrieval.

## How It Works

1. **Upload your PDF**: Simply upload any PDF document.
2. **Ask Questions**: Type your questions about the content of the PDF, and the AI chatbot will respond with accurate information.
3. **Summarize**: Request a summary of the document to get a brief overview of the key points.
4. **Search**: Search for specific content or sections within the document.

## How to Get Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/Chat-with-PDF.git
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Get an API Key for Gemini**:
   To create a similar project, you will need an API key from Gemini. Follow these steps:
   - Go to [AI Studio](https://aistudio.google.com/app/apikey).
   - Create a new project and generate the API key.
   - Store the key in the `.env` file of the project.

4. **Set up the API Key in the `.env` file**:
   - Create a `.env` file in the project root and add the following line:
     ```
     GEMINI_API_KEY=your_api_key_here
     ```

5. **Run the Application**:
   ```bash
   python app.py
   ```

6. Open your browser and navigate to `http://localhost:5000` to start interacting with PDFs.


## Demo Video

Watch a demo of "Chat with PDF" in action:

[![Watch the demo video](https://img.youtube.com/vi/RIWbalZ7sTo/0.jpg)]([https://github.com/prathameshatkare/chat_with_pdf/blob/main/assests/chat_with_pdf.mp4](https://youtu.be/8UyFEZzidOw))

> Click the image above to watch the video on YouTube.



## Contributing

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-name`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request to the main repository with a description of your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Let me know if you'd like any further adjustments!
