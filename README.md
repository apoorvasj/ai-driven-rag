<h1> Getting Started </h1>
<h4>1. Create a new folder where you want this repository. </h4>
Create a new folder from file explorer or <code>mkdir new_folder</code> and 
<code>cd new_folder </code>. <br>Open the folder in a IDE of your choice such as VSCode.

<h4>2. Clone the repository locally. </h4>
<code>git clone https://github.com/apoorvasj/ai-driven-rag.git</code>

<h4>3. Create and activate a virtual environment</h4>
Create the virtual environment.<br>
<code>python -m venv myenv</code><br>
Activate the environment.<br>
<code>myenv/Scripts/activate</code>

<h4>4. Install dependencies</h4>
Navigate into your folder.<br>
<code>cd ai-driven-rag</code><br>
Install dependencies.<br>
<code>pip install -r requirements.txt</code>

<h4>5. Set environment variables.</h4>
This project requires you to create two environment variables for LLM and embedding access.<br>
Create a <code>.env</code> file.
<code>
GROQ_API_KEY="your key"
COHERE_API_KEY = "your key"
</code>
To create both the API keys, visit 
<li><a href="https://console.groq.com/keys"> Groq </a>
<li><a href="https://cohere.com/"> Cohere </a>
<h4>6. Your code is ready to run!</h4>
