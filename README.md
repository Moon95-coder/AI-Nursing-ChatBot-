## 👩‍⚕️A.I. Nursing ChatBot
This is an A.I. Nursing ChatBot that allows users to ask basic healthcare questions.
This chatbot does not replace a qualified medical professional, but it does provide very helpful information to users.
It can provide ICD-10 codes for a variety of conditions and it can provide suggestions on what something may be based on it symptoms.
The UI for this chatbot is user-friendly and is very similar to most modern chatbots. This is the link to the chatbot: http://localhost:8501.

---

### Tech Stack 🖥️

* Visual Studio Code
* Python
* Streamlit
* Groq API

---

### Thought-Process 🧐

I wanted to create an interactive chatbot that could be helpful to both patients and healthcare workers. So, I started off by considering how my chatbot was going to accomplish this goal. It was clear to me that I had to use A.I., so I needed to get an API key and intergrate it into my python program so that my program could have the intellectence it needs to be a helpful nursing chatbot. I then started working on the backend of my chatbot. This included writing the code for the response generator, the title of the chatbot, chat history, user input, and the statements that allow both the chatbot's messages and the user's messages to be displayed in the chat message container. Once, I finished with the backend of my chatbot, I tested the program in the visual studio code terminal. Once everything was working right, I then worked on encrypting my API key. I encrypted my API key by putting it in a .env file. I added the .env file to the gitignore file so that GitHub would not upload my API Key to the repository. Once, my API key was properly encrypted, I worked on the front-end of my ChatBot. I decided to use Streamlit for the front-end of my chatbot, because I loved the result it produced.  









