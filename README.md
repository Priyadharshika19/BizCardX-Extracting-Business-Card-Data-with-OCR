# BizCardX-Extracting-Business-Card-Data-with-OCR
  Creating application using google colab
  
**Step1:**
**Install the required packages**
!pip install -q streamlit
!npm install localtunnel
!pip install easyocr
!pip install psycopg2
!pip install streamlit-option-menu
!pip install googletrans==3.1.0a0
!pip install pymongo
**import libraries**
easyocr
streamlit
pymongo
pandas
cv2
regex
PIL
googletrans
numpy

**Step2:**
Create streamlit app to extract text from the image
1.Upload language list document
2.Create connection to database

In Streamlit App:
**Step1:** **Business card**
1. Upload image of English language business card or other language business card
2. Choose the language of uploaded card
3. Click extract button
4. Text in the card will be extract and stored in database

**Step 4:** **Others**
1. Upload image of English language text image or other language text image
2. Choose the language of uploaded file
3. Click extract button
4. Text in the card will be extract and stored in database
5. Extracted data will be translate to English language

**Step 5:** **Manage data**
1. Selectbox lists all docments in database
2. View selected document
3. Delete the document










	



  
