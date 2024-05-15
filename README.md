# MongoDB-basics
## How to Install MongoDB along with mongosh on GitHub Codespaces

1. **Install MongoDB:**
   - Inside your Codespace, open a terminal.
   - You can install MongoDB using the package manager available in the Codespace's environment. For example, if it's based on Ubuntu, you can use `apt`:
     ```bash
     sudo apt update
     sudo apt install -y mongodb
     ```

2. **Start MongoDB:**
   - After installation, start the MongoDB service:
     ```bash
     sudo service mongodb start
     ```
   - Make sure MongoDB is running by checking its status:
     ```bash
     sudo service mongodb status
     ```

3. **Install mongosh:**
   - You can install mongosh using npm (Node.js Package Manager):
     ```bash
     npm install -g mongosh
     ```

4. **Connect to MongoDB:**
   - Once MongoDB and mongosh are installed, you can connect to your MongoDB instance using mongosh:
     ```bash
     mongosh
     ```

7. **Verify Connection:**
   - After connecting, you should see the mongosh prompt (`mongosh>`). You can then run MongoDB commands to interact with your MongoDB database.
