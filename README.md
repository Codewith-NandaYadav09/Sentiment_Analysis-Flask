
![WhatsApp Image 2024-12-20 at 3 57 56 PM](https://github.com/user-attachments/assets/a6deaa48-6748-4518-a215-b5206ee5cfad)


To run the app.py Flask application  on your local machine, follow these steps:

1. *Clone the Repository*:
   - Open your terminal or command prompt.
   - Navigate to the directory where you want to clone the repository.
   - Execute the following command:
     bash
     git clone https://github.com/Codewith-NandaYadav09/Sentiment-Analysis-Flask.git
     
   - Change to the repository's directory:
     bash
     cd Sentiment-Analysis-Flask
     

2. *Set Up a Virtual Environment*:
   - It's recommended to use a virtual environment to manage dependencies.
   - Create a virtual environment:
     bash
     python -m venv venv
     
   - Activate the virtual environment:
     - On Unix or macOS:
       bash
       source venv/bin/activate
       
     - On Windows:
       bash
       venv\Scripts\activate
       

3. *Install Dependencies*:
   - Ensure that all required Python packages are installed.
   - If a requirements.txt file is present in the repository, run:
     bash
     pip install -r requirements.txt
     
   - If there's no requirements.txt, you may need to manually install the necessary packages. Common dependencies for a Flask application might include Flask, pandas, scikit-learn, and xgboost. Install them using:
     bash
     pip install Flask pandas scikit-learn xgboost nltk matplotlib
     

4. *Set Environment Variables*:
   - Flask requires the FLASK_APP environment variable to point to your application file.
   - On Unix or macOS:
     bash
     export FLASK_APP=app.py
     
   - On Windows (Command Prompt):
     bash
     set FLASK_APP=app.py
     
   - On Windows (PowerShell):
     bash
     $env:FLASK_APP = "app.py"
     

5. *Run the Flask Application*:
   - Start the Flask development server by executing:
     bash
     flask run
     
   - By default, the application will be accessible at http://127.0.0.1:5000/.

6. *Test the API Endpoints*:
   - Use tools like curl, Postman, or a web browser to interact with the API endpoints defined in app.py.
   - For example, to test a GET endpoint, you might use:
     bash
     curl http://127.0.0.1:5000/your-endpoint
     


For more detailed information on running a Flask application, refer to the official Flask documentation: 

By following these steps, you should be able to successfully run the app.py Flask application on your local machine.
