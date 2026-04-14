# English Assistant AI 🤖
​A lightweight, single-page web application designed to help users improve their English language skills using AI. This tool provides instant feedback, grammar corrections, and language assistance through a clean, offline-capable interface.
​
🚀 Features
​Real-time AI Interaction: Get instant answers to grammar and vocabulary questions.
​Minimalist UI: A distraction-free interface built with clean HTML, CSS, and JavaScript.
​Secure API Integration: Utilizes GitHub Actions to handle API credentials securely, preventing key leakage.
​Mobile Responsive: Fully functional on Android and iOS devices.

​🛠️ Tech Stack
​Frontend: HTML5, CSS3, JavaScript (ES6+)
​AI Engine: Google Gemini API
​CI/CD: GitHub Actions (for secure deployment and secret injection)
​

🔒 Security & Deployment
​This project is hosted on GitHub Pages. To protect the API credentials, it uses a Secret Injection workflow.
​The API key is never stored in the source code. Instead:
​The code uses a placeholder: const apiKey = "REPLACE_WITH_API_KEY";
​A GitHub Action (.github/workflows/deploy.yml) triggers on every push.
​The Action securely retrieves the API_KEY from GitHub Secrets and injects it into the production build before deployment.

​⚙️ How to Set Up Your Own
​If you want to fork this project and use your own API key:
​Generate an API Key: Get a key from Google AI Studio.
​Add Secret: * Go to your Repo Settings > Secrets and variables > Actions.
​Create a new secret named API_KEY.
​Paste your key there.
​Configure Pages:
​Go to Settings > Pages.
​Set the Source to GitHub Actions.
​Deploy: Push any change to the main branch, and the Action will handle the rest.

​👤 Author
​Pratik Rajesh Jain IT Engineer | Technical Support Expert LinkedIn | GitHub
