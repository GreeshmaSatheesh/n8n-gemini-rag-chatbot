
# Project Requirements

## Software Requirements
- n8n account
- Google Gemini API access
- Web browser
- Internet connection

## AI Models
- Google Gemini Chat Model
- Google Gemini Embeddings

## Technologies
- n8n Workflow Automation
- Retrieval-Augmented Generation (RAG)
- Large Language Models (LLMs)
- Text Embeddings
- Vector Database

## Configuration Requirements
1. Configure Google Gemini credentials in n8n.
2. Configure the PDF source.
3. Configure the document loader and text splitter.
4. Configure the embedding model.
5. Configure the vector store.
6. Import both workflow JSON files.

## Execution
1. Run the PDF Loader workflow.
2. Verify that document embeddings are stored.
3. Activate the RAG Chatbot workflow.
4. Ask questions through the n8n chat interface.

## Important Note
The project uses an in-memory vector store.
Depending on the n8n environment, stored vectors may be lost after a restart. The PDF Loader may need to be executed again.
