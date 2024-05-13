# MongoDB-basics
## How to Install MongoDB along with mongosh on GitHub Codespaces

1. **Set Up Your GitHub Codespace:**
   - If you haven't already, create a GitHub repository for your project.
   - Set up a GitHub Codespace for your repository. You can do this by clicking on the "Code" button in your repository and selecting "Open with Codespaces."

2. **Access Your Codespace:**
   - Once your Codespace is ready, access it by clicking on the "Open Codespace" button.

3. **Install MongoDB:**
   - Inside your Codespace, open a terminal.
   - You can install MongoDB using the package manager available in the Codespace's environment. For example, if it's based on Ubuntu, you can use `apt`:
     ```bash
     sudo apt update
     sudo apt install -y mongodb
     ```

4. **Start MongoDB:**
   - After installation, start the MongoDB service:
     ```bash
     sudo service mongodb start
     ```
   - Make sure MongoDB is running by checking its status:
     ```bash
     sudo service mongodb status
     ```

5. **Install mongosh:**
   - You can install mongosh using npm (Node.js Package Manager):
     ```bash
     npm install -g mongosh
     ```

6. **Connect to MongoDB:**
   - Once MongoDB and mongosh are installed, you can connect to your MongoDB instance using mongosh:
     ```bash
     mongosh
     ```

7. **Verify Connection:**
   - After connecting, you should see the mongosh prompt (`mongosh>`). You can then run MongoDB commands to interact with your MongoDB database.

These are general steps and might vary depending on the specific environment and configurations of your GitHub Codespace. Make sure to check the documentation or guidelines specific to GitHub Codespaces if you encounter any issues.
