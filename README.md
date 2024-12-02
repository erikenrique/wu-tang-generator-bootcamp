# 🎤 Wu-Tang Name Generator

### 📖 About the Project
My Wu-Tang Name Generator is a web app that creates a unique, Wu-Tang-inspired name based on what a user's input is. That name is static based on that information. By answering five quirky survey questions, people can discover their Wu-Tang name (shoutouts to "Childish Gambino", originally a Wu-Tang name generated name)

![GIF of app](https://github.com/user-attachments/assets/f4f1cfdd-aa80-44b9-a131-c9d62321583d)

### 🛠️ How It Was Made

#### Tech Stack
* Frontend: HTML, CSS, JavaScript
* Backend: Fetch API for local file data
* Utilities: Adjective and noun files (wu_adjs.txt and wu_nouns.txt) for name generation

#### How It Works
Users input their first name, last name, date of birth, hometown, and preference for hot dogs (important, of course)

The app calculates a score based on the input data.

Using the score, the app fetches an adjective and noun from local word files to generate a Wu-Tang-style name.

### 🌱 What I Learned

Implementing asynchronous JavaScript with async and await
Handling file fetching using the Fetch API
Building a basic scoring algorithm to create dynamic, personalized outputs
