# Parsing Gov Procurement Announcements
### 1. Problem Space: 
Thai Gov Procurement announcements (http://www.gprocurement.go.th/new_index.html) are made in PDFs and are hard to read for illiterate or non-thai speakers
### 2. Solution: 
Using Alibaba Qwen-turbo lightweight model we scan PDF texts and return key information

## Usage:
1. Git Clone the repository into python project folder
2. Setup environemnt and install packages"pip install -r requirements.txt"
3. Add your Qwen API Key in .env file (Find the documents here: https://www.alibabacloud.com/help/en/model-studio/developer-reference/use-qwen-by-calling-api)
4. Run the command "python pdf_parsing.py <filen_name>.pdf" or "python pdf_parsing.py <folder_containing_pdfs>"
5. Check output json file in root folder
