

## 1. Project Status  

This project was created for a Capstone course at Shepherd University in the Fall of 2025. Due to this course ending, the development of the Safe-AI Initiative is paused, and it is not likely to continue.  

We will not be requiring maintainers or contributors as there is no plan to continue development.  

--- 

## 2. Description  

Safe-AI Initiative is an educational website that provides information about some of the ethical issues that are arising due to AI usage. Because of the rapid development of different AI technologies, there are environmental, societal, mental health, and general ethical issues that aren’t often highlighted. The goal of this project is for our webpages to provide accessible and clear information on these issues, as well as provide resources and ways to get involved.  

### 2.1 Features  

- **Homepage**: hosts the projects goals, approach and a simple overview what AI is  
    

- ** Webpages** dedicated to specific ethical issues that we chose to highlight  
    

- Environmental: Highlights some of the most common environmental impacts tied to the increased development and usage of AI  
    

- Ethics: Provides a breakdown of the different levels of AI ethics and what falls under each of them.  
    

- Mental Health: Explores the mental health effects seen from consistent AI usage. This page also hosts interactive chatbot, as well as its background and methodology. 
    

- Get involved: Hosts a plethora of links to alternative resources, ways to get involved and websites that we took inspiration from.  
    

- Sources: The final page hosts the sources we gather information, methodology, and graphics from.  
    

- ** Images and graphics** that provides a simple, alternative way to view and understand the information on the webpages  
    

- ** Interactive Chatbot** A side by side interactive demonstration that highlights parasocial chatbot responses and how they may be corrected.  
    

### 2.2 Background 

Safe-AI Initiative was created because our team noticed a lack of education on ethical issues stemming from AI usage. The development of these technologies is continuing rapidly, as well as accessibility to the general public. Because of this, information on the harmful effects should be as easily obtainable as technology itself. The goal of this project is to provide this information in an accessible and understandable way.  

--- 

## 3. Installation  

To run this project locally, first clone the repository using a Github GUI application or via command line: 

```bash

git clone git@github.com:Camithilwen/Safe-AI.git 

```

To set-up and run the React website, 

- Ensure your system is running node.js v22.20.0 or greater 

- Navigate your terminal to the project's root directory and run the following commands to install the required node dependencies and run the project: 

```bash 

npm install 

npm start 

```

To set-up and run the chatbot demonstration's Streamlit application, 

- Ensure your system has an installation of Ollama v0.12.3 

- Run the following commands to install the minimum-requried Ollama dependencies for the demonstration application and start the Ollama LLM server: 

```bash 

ollama pull llama3.2 

ollama pull ALIENTELLIGENCE/sarahv2 

ollama serve 

```

- Ensure your system has an installation of Python v3.11.2 

- Navigate your terminal to the project's root directory and run the following commands to initialize a new Python virtual environment, install the required Python dependencies, and run the Streamlit project: 

```bash 

python -m venv .venv 

source ./.venv/bin/activate 

pip install -r requirements.txt 

streamlit run ./src/navigation.py --server.headless True 

```

--- 

## 5. Roadmap  

As of now, the development on this website has been completed. No further releases are planned at this time.  

--- 

## 6. Authors and Acknowledgements 

The Safe AI Initiative was created by Jamie Kemman, Alani White, and Holly White. As a team, members collaborated on research, website design, and writing.  

Jamie led the development of the chatbot feature, as well as the background research and implementation of that feature.  

Holly White and Alani White led the development and design of the website. Alani focused on conducting literature review on environmental content, and Holly focused on conducting additional survey research on perceptions of the AI industry.  

--- 

## 7. License  

MIT License 

Copyright (c) 2025 Alani White, Holly White, Jamie Kemman 

 Copyright (c) 2024 Luis Santos (TalkNexus) 

Permission is hereby granted, free of charge, to any person obtaining a copy 

of this software and associated documentation files (the "Software"), to deal 

in the Software without restriction, including without limitation the rights 

to use, copy, modify, merge, publish, distribute, sublicense, and/or sell 

copies of the Software, and to permit persons to whom the Software is 

furnished to do so, subject to the following conditions: 

The above copyright notice and this permission notice shall be included in all 

copies or substantial portions of the Software. 

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR 

IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, 

FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE 

AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER 

LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, 

OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE 

SOFTWARE.