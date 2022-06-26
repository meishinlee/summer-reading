# summer-reading

## How can you try our Project

- You can either use the link [!https://meishinlee-summer-reading-main-page-6v5a2l.streamlitapp.com/] or 
- you can try it on your system

### How to run it on your system
1. Clone this repository 
2. Install all the python packages in requirements.txt using ```pip install```
3. Go to terminal and change the directory to this folder
4. run the application using the command
 ``` streamlit run main_page.py``` 

## Inspiration
Summer reading is a fun and educational activity many students and adults participate in to pass time and make their summers a little less boring. There is often the dilemma that avid readers fall into which is not knowing what book to pick up next. Writer's block is often a point of worry for many students and writers that can take up quite a chunk of time while waiting for those gears to start rotating again and fall into the flow of writing.Our tools aim to encourage reading and writing for all ages by making the process of choosing a book simple and by aiding in brainstorming for avid readers and writers!

## What it does
With the book recommendation tool, input some words and phrases for the type of novel you are interested in reading and get book recommendations personalized to your taste.
Whether it is to write a creative writing assignment, the next award winning novel, or a genius masterpiece, the Ideation and Story Generation tool is a great way to get those gears turning again. By taking in some keywords describing what you want to write about, a personalized storyline is generated for you somewhat like Tom Riddle’s Diary but instead with some NLP magic using Cohere. If you love the storyline that is generated there’s an additional feature added using Twilio to make things a little easier and get you back on track with your writing masterpiece by sending the storyline to your phone!

## How we built it
We used Github to organize and collaborate on the project. Github’s projects feature allowed us to create and assign tasks as well as keep track of progress. Github helped manage version control of the code. We used NLP with Cohere to generate storylines given keywords and topics. We used Twilio to send messages to the user. Streamlit was used for the frontend of the project and to take in input and display the results.

## Challenges we ran into
Optimizing our algorithm for preprocessing was challenging since we had a lot of records in our database. Some book descriptions were several paragraphs long, and going through thousands of records made things slow. Additionally, trying to integrate Twilio into our application was a challenge, but we were able to figure it out through reading documentation. Twilio also requires the use of an authorization key so it became difficult to collaborate whilst sharing it. 

## Accomplishments that we're proud of
We are proud of being able to complete our hack within the time frame. We are all from different parts of the word, which made it quite challenging to find times when we are all awake. Additionally, we are proud of being able to deploy our app with our secrets hidden and incorporate additional functionality using APIs we've never used before. 

## What we learned
We learned how to use Streamlit and different preprocessing techniques for language. We also learned how to integrate APIs into our application. We also learned how to use Github projects to assign tasks and keep track of our progress. 

## What's next for Bookmarked: Great Summer Reads and Ideas
We plan to optimize our recommendation algorithm even further and collect more data on books for different audiences. We also plan on expanding this list to adults and advanced readers, with a new capability to filter books by genre. 

## Domain name Submissions
- bookmarkedwith.tech
- tomriddles.tech
- GoDaddy Domain:  bookmarkto.study
