# Cloud Edge
A repository for Unimi project focused on cloud development.

## Development guide
### Runing the code on the local machine
**Prerequisites**:
1. **Python**: Ensure that Python is installed on your system. You can download and install Python from the official Python website. https://www.python.org/downloads/
2. **Pipenv**: Install Pipenv if you haven't already. You can do this via pip, Python's package installer. https://pipenv.pypa.io/en/latest/installation.html

**Steps**:
1. **Clone Repository:** Clone your Streamlit application repository to your local machine if you haven't already. ```git clone https://github.com/dr-leto/cloud_edge.git```
2. **Navigate to Repository:** Change your current directory to the root directory of your cloned repository. ```cd cloud_edge```
3. **Install Dependencies:** Use Pipenv to install the required dependencies specified in the Pipfile. This command will create a virtual environment and install all dependencies specified in the Pipfile. ```pipenv install```
4. **Activate Virtual Environment:** Activate the virtual environment created by Pipenv. ```pipenv shell```
5. **Run Streamlit Application:** Now, you can run your Streamlit application using the streamlit run command followed by the main Python script (main.py). ```streamlit run main.py```
6. **Access Application:** Once the Streamlit server starts, you will see a message indicating that your app is running and provide a local URL (usually http://localhost:8501). Open this URL in your web browser to access your Streamlit application.

### Making Changes to the Code:
1. **Modify the Code**: Make the desired changes to your Streamlit application code in the main.py file or any other relevant files in your project.
2. **Test Locally:** After making the changes, it's a good practice to test your application locally to ensure that the changes work as expected. Follow the steps mentioned earlier to run your application locally using Pipenv.

### Deploying the App to Streamlit Cloud:
1. **Commit and push the changes:** Before deploying, ensure that all your changes are committed to your version control system (Git). This ensures that you have a clean snapshot of your code.
2. **Login to Streamlit Cloud:** If you haven't already, log in to the Streamlit Cloud dashboard using your Streamlit account credentials.
3. **Create a New App:** In the Streamlit Cloud dashboard, click on the "New app" button.
4. **Configure App Settings:** Fill in the necessary details such as the name of your app, description, and any other required configurations.
5. **Specify GitHub Repository:** Connect your Streamlit app to your GitHub repository. Streamlit Cloud allows you to deploy apps directly from GitHub repositories.
6. **Select Branch:** Choose the branch from which you want to deploy your application (e.g., master branch).
7. **Deploy**: Once configured, initiate the deployment process. Streamlit Cloud will pull your code from the specified GitHub repository and deploy your application.
8. **Monitor Deployment:** Streamlit Cloud will provide feedback on the deployment process. You can monitor the progress and check for any errors or warnings.
9. **Access Deployed App:** Once deployed successfully, Streamlit Cloud will provide a URL where your application is hosted. You can share this URL with others to access your deployed Streamlit application.
