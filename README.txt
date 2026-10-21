JASYS AI PHOTO — ZIP PACKAGE

Files:
- index.html: the JASYS AI Photo chat website.

How to use:
1. Extract the ZIP file.
2. Open index.html in a modern browser with an internet connection.
3. Paste your Groq API key into the top field and press Save.
4. Type a question and press Send, or select a photo using the camera button and ask about it.

Important security note:
This is a browser-only demo. The API key is stored in this browser's localStorage and is sent from the browser to Groq. It is NOT hidden or protected inside the ZIP. Do not publish this version with a private API key for other people to use. For a public website, put the key on a backend server and have the website call that server.

Model availability:
The app uses meta-llama/llama-4-scout-17b-16e-instruct for photo questions and openai/gpt-oss-120b for text-only questions. Model availability can change in your Groq account; if a model is unavailable, update the model name to one currently enabled for your account.
