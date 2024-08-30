Important files to note are chroma-create-v1.py and ou-chatbot-chroma-final-v1.py, rest are for test purpose

Steps to run:
1. Install libraries in dependencies.yml
2. create a folder to store all the required pdf's using "mkdir docs/"
3. Creates Chroma Vector Store using chroma-create-v1.py (based on your doc present in folder 'docs/' will create vector store)
4. Running chroma server using "chroma run --path /path-to-chroma-db/"
5. Running StreamLit Application using "streamlit run ou-chatbot-chroma-final-v1.py"
6. Test the application at localhost:8501 
