# Generative AI Script with Google Gemini  

This project demonstrates how to use Google's Gemini AI model to generate AI-driven content. It includes the installation steps, prerequisites, and usage instructions for the provided Python script.  

---

## Prerequisites  

1. **Python Version**  
   Ensure you have Python 3.7 or higher installed on your system. You can check your version by running:  
   ```bash
   python --version
   ```  

2. **API Key**  
   - Obtain an API key for Google Generative AI services (Gemini AI).  
   - Store the key securely. You'll need it during the setup.  

3. **Environment File**  
   - Create a `.env` file in the project directory.  
   - Add the following line to store your API key:  
     ```env
     GEMINI_API_KEY=your_actual_api_key
     ```  

---

## Installation  

Follow these steps to set up and run the script:  

1. **Clone or Download the Repository**  
   Download the project files to your local machine.  

2. **Set Up a Virtual Environment**  
   Create and activate a virtual environment to manage dependencies.  
   ```bash
   python -m venv env  
   source env/bin/activate    # On Windows, use `env\Scripts\activate`
   ```  

3. **Install Dependencies**  
   Install the required Python libraries:  
   ```bash
   pip install python-dotenv google-generativeai
   ```  

4. **Configure the `.env` File**  
   - Create a `.env` file in the root directory of the project.  
   - Add your Gemini API key as shown in the prerequisites section.  

5. **Run the Script**  
   Execute the script to generate content using the AI model:  
   ```bash
   python generate_ai.py
   ```  

---

## Script Explanation  

The script performs the following tasks:  

1. **Loads Environment Variables**: Reads the API key from the `.env` file.  
2. **Configures Google Generative AI**: Sets up the client with the provided API key.  
3. **Initializes the Gemini AI Model**: Uses the "gemini-1.5-flash" model for generating content.  
4. **Generates AI Content**: Sends a prompt to the AI model and prints the response.  

---

## Example Output  

When running the script with the prompt `Explain how AI works`, you should see output similar to:  
```
AI works by simulating human-like intelligence through algorithms and computational models. These models are trained on large datasets to perform tasks such as...
```  

---

## License  

This project is open-source and can be modified for personal or educational use.  
