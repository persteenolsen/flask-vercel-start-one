# Python and Flask Tutorial

A Web Application with Python version 3.12 and Flask version 3.0.0 

# Installing

- Download Python from the official website [Python](https://python.org/)
- Download the the Python extension for Visual Studio Code which automatically include the Pylance extionsion
- Download / fork this Flask Starter Web App from my GitHub
- Create the virtual envirement ".venv" for the Flask Web App by Powershell or by VS Code
- Virtual Envirment by VS Code: "View - Command Palette - Python Create Enviroment"

# Run the Flask Web App without Debug

- Right click the local folder with the Flask Web App and open Powershell
- Run "flask run" and type "http://127.0.0.1:5000/" in your Browser and check the site is loaded
- If ".flaskenv" is not found run "pip install python-dotenv" and run "flask run" again
- You can also run the Flask Web App by run "flask --app api/index run" which point directly at your Flask entry file 
 
# Local development / debug / hot reload / refresh:

- Make sure that you have installed Python and Flask by the commands in Powershell: "python --version" or "flask --version"
- The folder ".vscode" include the launch file for local development / debug by VS Code  
- To debug from outside VS Code use powershell at the rootfolder with the repository forked from GitHub and type: "flask run --debug" which use the settings in the .flaskenv file. 
- By using "flask run --debug" you may get promted to do: "pip install python-dotenv" for make things work
- Open a Browser and type "http://127.0.0.1:5000/" to see the site
- Make a change in a file and type f5 or refresh the Browser to see the change

# Deployment:

- Make sure to have both a GitHub and a Vercel Account
- Create a ropository with the Web App Starter at GitHub
- Log in to Vercel and select the GitHub repository with your Web App Starter and follow the instructions
- The vercel.json file will be used at Vercel Serverless Functions
- Commit and sync your changes to GitHub which will create an automated Deployment to Vercel
- Check that your site is online at Vercel "your-repository-name.vercel.app"

# Features / Usefull links

- [Python](https://python.org/)
- [Flask](https://flask.palletsprojects.com/)
- [Vercel](https://vercel.com/)
- [GitHub](https://github.com/)
- [VS Code](https://code.visualstudio.com/)



# Author

- Per Olsen

# License

This project is open source and available under the [MIT License](LICENSE).



