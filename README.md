Project Title
Text Extraction and Summarization

Description
This project features a Python script that extracts relevant information from a paragraph based on a query and summarizes it using natural language processing (NLP). The script utilizes spaCy for sentence segmentation and the Transformers library for text summarization.

Features
Sentence Extraction: Segments a paragraph into individual sentences.
Query Filtering: Identifies and extracts sentences containing the specified query.
Text Summarization: Summarizes the extracted or full paragraph using a transformer model.
Technologies Used
spaCy: For sentence segmentation and processing.
Transformers: For text summarization.
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/kundankumar95/text-extraction-summarization.git
Navigate to the project directory:
bash
Copy code
cd text-extraction-summarization
Install required libraries:
bash
Copy code
pip install spacy transformers
Download the spaCy model:
bash
Copy code
python -m spacy download en_core_web_sm
Usage
Run the script:
bash
Copy code
python extract_relevant_info.py
Input Prompts:
Paragraph: Enter the text from which you want to extract information.
Query: Enter the keyword or phrase you want to search for in the paragraph.
Output: The script will print the summarized relevant information based on the query.
Example
bash
Copy code
Enter your paragraph: The power outage affected several areas in the city. Water leaks were reported in multiple locations. Security cameras were down in some areas.
Enter your query: electricity

Response:
The power outage affected several areas in the city.
Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your proposed changes. Ensure to follow the coding guidelines and include tests for new features.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
For any questions or support, please reach out to:

Email: kundanburnwal32434@gmail.com
GitHub: kundankumar95
