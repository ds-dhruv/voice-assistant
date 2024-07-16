# Voice Assistant Using Python

Project Overview :-->
The AI Voice Assistant is a Python-based application designed to facilitate user interaction through voice commands. Leveraging advanced speech recognition and text-to-speech capabilities, this assistant can perform various tasks, such as web browsing, fetching news, and responding to user queries using the OpenAI API.

Features :-->
1. Speech Recognition : Convert spoken language into text using the speech_recognition library, enabling seamless interaction.
2. Text-to-Speech : Utilize pyttsx3 and gtts for vocal responses, providing a natural conversational experience.
3. Web Browsing : Launch web pages and perform searches using webbrowser based on user requests.
4. News Retrieval : Access the latest news articles via the NewsAPI to keep users informed about current events.
5. OpenAI Integration : Use the OpenAI API to generate intelligent responses and engage users in conversation.

Modules Used :-->
1. speech_recognition : For capturing and recognizing voice commands.
2. webbrowser : To open URLs and perform searches.
3. pyttsx3 : A text-to-speech conversion library for offline capabilities.
4. requests : To make API calls to OpenAI and NewsAPI.
5. openai : For accessing advanced language model features.
6. gtts : Google Text-to-Speech for generating spoken responses in different languages.
7. pygame : To handle audio playback for a more interactive experience.
8. os : For interacting with the operating system, such as managing files or executing commands.
9. pocketsphinx : For offline speech recognition, allowing basic commands without an internet connection.

API Keys Used :-->
1. OpenAI API : Enables the assistant to generate intelligent and context-aware responses.
2. NewsAPI : Provides access to a wide range of news articles and headlines.

How It Works :-->
1. The user activates the assistant with a wake word or phrase.
2. The assistant listens for voice commands, which are then processed using the speech_recognition module.
3. Based on the recognized command, the assistant can:
   Search the web for information and open results in a browser.
   Retrieve the latest news headlines using the NewsAPI.
   Generate responses or engage in conversation using the OpenAI API.
4. The assistant provides vocal feedback using the pyttsx3 and gtts modules, allowing for interactive communication.
5. Optional offline capabilities using pocketsphinx ensure basic functionality without internet access.
