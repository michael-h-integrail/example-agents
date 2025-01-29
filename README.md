# example-agents
A public repository of example integrail.ai agents

## Repository URL
This repository is hosted on GitHub at:  
[https://github.com/michael-h-integrail/example-agents](https://github.com/michael-h-integrail/example-agents)

## How to Clone This Repository
If you're new to Git and want to download this repository to your local machine, follow these steps:

### **Option 1: Using Git (Recommended)**
1. **Install Git** (if you haven’t already):
    - [Download and install Git](https://git-scm.com/downloads) for your operating system.
2. **Open a Terminal or Command Prompt**
    - On Windows, you can use **Git Bash**, **Command Prompt**, or **PowerShell**.
    - On macOS or Linux, use the **Terminal**.
3. **Navigate to the folder where you want to clone the repository**
   ```sh
   cd /path/to/your/directory
   ```
   (Replace /path/to/your/directory with your desired location.) 
4. **Run the following command to clone the repository  
   ```sh
   git clone https://github.com/michael-h-integrail/example-agents.git
   ```
   Navigate into the cloned repository

   ```sh
   cd example-agents
   ``` 
You now have a local copy of the repository and can start exploring the files.

### **Option 2: Download as a ZIP (No Git Required)**
If you don’t want to use Git, you can download the repository as a ZIP file:

1. Go to the repository page:  
   [https://github.com/michael-h-integrail/example-agents](https://github.com/michael-h-integrail/example-agents)
2. Click the **Code** button (green dropdown).
3. Select **Download ZIP**.
4. Extract the ZIP file to a folder on your computer.

Now you have access to the files without needing Git.

## Using the Examples
Once you have the example files, to try them in Integrail's Agent Studio yourself, follow these steps:
1. Login or Sign up for a FREE Integrail Studio account at [studio.integrail.ai](https://studio.integrail.ai/) 
2. Once Logged In, Click 'Create New Agent'
3. Click "..." menu, next to the file dropdown in the top/middle section of the window.
4. Click the upload icon:  
      ![Upload Icon](doc/img/upload.png)
5. Click **"Choose File"**
6. Browse to the example you wish to try in Integrail's Agent Studio and select it

7. [View the `simple-node-examples` folder](https://github.com/michael-h-integrail/example-agents/tree/main/simple-node-examples)

You have a couple of options for how to run the Agents:

### Chat with the Agent
If you simply want to try chatting with an agent without worrying about what's under the hood, just follow these steps:
1. Click **"Chat with Agents"** item in the left navigation bar
2. Select the agent with which you wish to chat.
3. Chat away (type text inputs, input files, etc. using the simple chat interface)

### View or Tweak in the Agent Designer
If you are curious about how the agent was build, and you want to experiment with it, follow these steps: 

1. If you are already in the **"Chat with Agents"** screen, click the edit icon in the top right section of that window.  This opens the Design View for the agent you're using.

Otherwise, follow these steps:
1. Click **"Design Agents"** on the left navigation bar
2. In the top/center of the window, click the Agent selector dropdown
3. Select the agent you want to view/change

You will see the Agent inputs on the left (you can try specific inputs by selecting this node and viewing its properties).  Similarly, you can see the Agent outputs on the right. 

You will also see intermediate nodes in the middle.  You can configure various parameters (for instance try changing the **System Prompt** of an LLM node to change it's behavior)

**Be sure to check out the Readme.md file in each folder for more information and detailed notes the agents in that folder**
