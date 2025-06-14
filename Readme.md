Chemistry 101: Interactive Explainer
About The Project
This project is a single-page interactive web application designed to make learning the fundamental concepts of chemistry engaging and fun. It transforms a standard Chemistry 101 lesson into an intuitive, hands-on experience. The primary goal is to help users easily explore, understand, and synthesize key information about atomic structure, chemical bonding, and reactions.

This is an educational tool and is intended for learning purposes only.

Features
Interactive Atom Explorer: Click on protons, neutrons, and electrons to learn their properties.

Animated Bonding Demonstrations: See how Ionic and Covalent bonds form with user-triggered animations.

Live Chemical Reaction Simulation: Watch a visual representation of a chemical reaction and see the Law of Conservation of Mass in action with a dynamic chart.

✨ Gemini AI Integration:

Explain Like I'm 5: Get super-simple analogies for complex atomic particles.

Molecule Suggester: Ask the AI to suggest simple molecules you can build with a given element.

Getting Started
This is a self-contained HTML file. No installation is needed. You can run it by simply opening the index.html file in any modern web browser.

Setting Up the Gemini API Key
To use the AI-powered features ("Explain Like I'm 5" and "Molecule Suggester"), you need to add your own Google Gemini API key.

Get an API Key: If you don't have one, you can get a free API key from Google AI Studio.

Add the Key to the File:

Open the HTML file in a text editor.

Find the <script> tag at the bottom of the file.

Locate the following lines of code inside the getSimpleExplanation and getMoleculeSuggestion functions:

const apiKey = "yourapikey";

Paste your API key between the double quotes:

const apiKey = "YOUR_API_KEY_HERE";

Save the file.

Reload and Enjoy: Reload the page in your browser. The AI features should now be active.

Disclaimer
This application uses a Large Language Model (LLM) for some of its features. The information generated by the AI is for educational and illustrative purposes and may not always be 100% accurate. Always cross-reference with verified scientific sources.
