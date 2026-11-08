# Sizwe: Multilingual Mental Health Chatbot

Sizwe is a multilingual chatbot that supports mental health conversations for African-language speakers. It was built in three days at the **MAISH Hackathon 2024**, where it won **3rd place**: two days of building and a presentation day, with no budget and no paid NLP or AI APIs.

**Live demo:** [add your GitHub Pages link here]

> **Important:** Sizwe is a student prototype. It is not a therapist and does not give medical advice or diagnoses. If you or someone you know is in crisis, please contact a qualified professional or a local helpline.
>
> **South African crisis contacts:** [add verified helpline details from an official source, such as SADAG]

## Screenshots

<!-- HOW TO ADD: save each image in an "images" folder with the file name shown, then delete the "Screenshot to add" line and remove the comment markers around the image line. -->

**Welcome page**

<!-- ![Welcome page](images/welcome.png) -->
> 📸 Screenshot to add: `images/welcome.png`

**A conversation in English**

<!-- ![Conversation in English](images/chat-english.png) -->
> 📸 Screenshot to add: `images/chat-english.png`

**Switching language to isiZulu mid-conversation**

<!-- ![Switching to isiZulu](images/chat-zulu.png) -->
> 📸 Screenshot to add: `images/chat-zulu.png`

## Features

- **Multiple languages:** replies in the language the user writes in (currently English and isiZulu: [update this list to match your code]).
- **Switch languages mid-conversation:** the chatbot notices when the user changes language and answers in the new one.
- **Rule-based language detection:** a custom JavaScript engine detects the language and maps it to responses. It uses no paid NLP or AI services.
- **Structured conversation flows:** supportive, mental-health-focused conversation paths.
- **Fallback replies:** a graceful response when the chatbot does not recognise the input.
- **Simple interface:** built with plain HTML, CSS and JavaScript.

## How it works

1. The user types a message.
2. The language detection logic checks the message against known words and phrases for each supported language.
3. The chatbot picks the matching conversation flow and replies in the detected language.
4. If nothing matches, it uses a fallback reply and invites the user to try again.

## Run it locally

No installation is needed.

1. Clone the repository:
   ```bash
   git clone https://github.com/NeoMudau/Sizwe-Mental-health-chatbot.git
   ```
2. Open `index.html` in your browser.

The prototype files are in the `Sizwe - Mental Health Chatbot Prototype` folder.

## Built with

- **HTML:** structure
- **CSS:** styling
- **JavaScript:** language detection, conversation logic and interface behaviour

## Project status

This is a hackathon prototype. It is not a finished product, but it works end to end and you are welcome to explore it and learn from it.

## Possible next steps

- [ ] Add more African languages
- [ ] Improve language detection accuracy
- [ ] Add more conversation flows
- [ ] Explore optional AI-assisted replies, with proper safety checks for mental health topics

## Contributing

Feedback and suggestions are welcome. Open an issue or a pull request.

## License

This project is licensed under the **MIT License**.
