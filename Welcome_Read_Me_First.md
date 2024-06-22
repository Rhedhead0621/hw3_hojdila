<span style="color: #FFF; background-color: #232323; text-shadow: 0 0 5px #FFF, 0 0 10px #FFF, 0 0 15px #FFF, 0 0 20px #49ff18, 0 0 30px #49FF18, 0 0 40px #49FF18, 0 0 55px #49FF18, 0 0 75px #49ff18; ">Welcome!!!</span>

<span style="color: green;">Welcome!!!</span>

<span style="color: purple; font-size:18px; line-height:35px; font-family: Calibri;">Welcome!!!</span>

<span style="color: #FFFFFF; background: #333333; text-shadow: #FFF 0px 0px 5px, #FFF 0px 0px 10px, #FFF 0px 0px 15px, #FF2D95 0px 0px 20px, #FF2D95 0px 0px 30px, #FF2D95 0px 0px 40px, #FF2D95 0px 0px 50px, #FF2D95 0px 0px 75px; color: #FFFFFF; background: #333333; ">Advanced Analytics with Python – Final Project</span>

Team Member
------------
Anna Hojdila

Project Title
-------------
ChatBot Development through web and PDF scraping

Type of Final Project
---------------------
Based on Module 5 - Data wrangling / visualizations / analysis

Executive Summary of the Project
-----------------------------------------
This project has morphed from the original plan, however the problem-solving of roadblocks led to discovering other options and work-arounds just as interesting.

Initial Primary Goals:

- Use Python to Webscrape data to use with a chatbot
- Develop a chatbot that interacts with information from the data

Right click to open link in new tab:

[Why use chatbots?](https://datasciencedojo.com/blog/what-are-chatbots/)

Data Needs and Sources
-----------------------
- Python
- Chatbot platform such as Landbot - decided to remain within Python and use NLTK package

Challenges and Reality Checks
-----------------------------
- Webscraping data requiring login information is challenging, especially when I'm finally successful entering my email address and selecting the "Next" button through the code, only to get to a Google login requirement needing to text my cell phone and enter a random texted number

- Another idea was taking information from a PDF, and using the text information for the chatbot - this requires OCR (Optical Character Recognition) within Python (I thought Python would magically know an A was an A, not a picture of an A...)

- The text data would be used to build the intents (user inputs) and responses (chatbot output) within a chatbot

- Learn something more about these "intents" and "responses" everyone keeps mentioning

- What does it take to build a chatbot??

- Landbot looks interesting...wait, they want me to load a question and response one at a time?? Ok, I can use DialogFlow but that's not free...

- Need free, *Now* what chatbot platform should I use?? Let's just look at Python options

- Why did the Python Chatterbot crash my Anaconda?? Now I have to learn how to uncrash Anaconda...

- Let's not use Python Chatterbot...

Accomplishments and Personal Learning
-------------------------------------
Main chatbot source, I started with their code and ideas, and modified it along the way:

[Analytics Vidhya Simple Chatbot](https://www.analyticsvidhya.com/blog/2021/07/build-a-simple-chatbot-using-python-and-nltk/)

Basic project process flow:

- 1_Selenium_Plus_BS_Final.ipynb: access a webpage and scrape the html data

- 2_Selenium_Final.ipynb: access a webpage and scrape the clean text off the page

- 3_OCR_Final.ipynb: scrape text off a PDF using OCR

- 4_NLTK_aap_troubleshooting.ipynb: this is the first time I've experienced issues installing packages. I also am not able to create a virtual environment, so I will need to work on troubleshooting that. This file shows which packages I had to install using %pip install. These packages need to be installed before working on the rest of the notebooks.

- 5_Cleaning_keywordExtraction_Final.ipynb: clean a text document and extract keywords

- 6_NLTK_Basic_Rule_Chatbot_Final.ipynb: runs a very basic, pop up chatbot

- 7_GUI_chatbox_Final.ipynb: runs the very basic intents/responses, in a GUI pop up chatbot

- 8_md_to_html.ipynb: converts .md file to .html file

- Resources.md: documented most of the websites used or read through

- The plan was to scrape text from the web or PDF, to use for the final intents/reponses - this is much harder than I thought it would be, but I still think it's possible and I'm still going to pursue options to implement a chatbot at work. I am going to build the landbot version, but it may not involve using Python.

- The final chatbot was going to have the paired responses from a json file - the json file repeatedly imported as a list instead of a dictionary, I'm moving on and putting that on my to do list.

- The project doesn't focus on one website or PDF for a final example, however the basic steps to begin are included, after much trial and error.

- I also would like to launch the chatbot from an html document

[Using Pyscript](https://www.linkedin.com/pulse/pyscript-way-run-python-your-html-page-balayogi-g#:~:text=With%20PyScript%2C%20Python%20code%20can,this%20package%20for%20web%20development.&text=PyScript%20offers%20a%20wide%20range%20of%20features%20to%20develop%20interactive%20web%20applications)

- Chatbots can also store the "conversations" for further learning and analyzing topics for enhanced customer service (what are the highest ranking questions, issues, topics, etc.) 

- Learned more about markdown and html formatting - very cool site! 

[CSS / HTML Interactive Cheat Sheet](https://htmlcheatsheet.com/css/)

I learned a lot from the course modules, however this final project immersed and reinforced the content we covered:

- Importance of knowing the data - is it string, number, list, dictionary?
- Defining functions
- Looking at a starting template and knowing what to change along with how to change it
- I've needed a way to manipulate text from a PDF invoice we have to manually reference monthly; I should be able to scrape the VIN, item and dollar amount into a table, which is a process we have needed for a few years - very excited about that

<span style="font-size:20px; color: #333333; background: #CE5937; border: 1px solid #02090D;">Folders</span>

- chromedriver: chromedriver was necessary for connecting Selenium with Chrome

- data: data files

- docs: text and PDF files

- images: image files

- notebook_trials: all the trials used along the way

    -- ForProfOnly: copy of the notebook that works through the required email step, stops and doesn't complete the Google login portion. It's not highly sensitive, but it references a corporate site
    