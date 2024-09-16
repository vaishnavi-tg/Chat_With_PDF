Initially create a environment and activate it and use it to install all the required libraries
Google Gemini pro usually works better with python greater than or equal to python 3.9
Get a google api key by going to makersuite.com and create a new api key to use it i.e put it in .env file 
Make a requirements.txt file and write all the libraries that are required to do the project 
Open the terminal and do "pip install -r requirements.txt" , so that all the libraries that are required are installed in the environment to further do the project 
Create a app.py file and import all the libraries 
The function get_pdf_text is to read all the pages of the pdf
Now make the text into chunks using get_text_chunks using text splitter and return the txt chunks
Make the embeddings i.e store the chunks using get_vector_store
Load the gemini pro model
Make the template and get the chain of prompt
Create a streamlit app to make the frontend of the app 
Deploy if necessary using streamlit free cloud to deploy it 
Now 
##Run the app.py file using the command streamlit run app.py
And then upload the file and ask for queries



