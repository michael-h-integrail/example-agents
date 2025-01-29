# Readability Node Examples 
This folder contains examples for the Readability Node


## [ex-Readability](https://github.com/michael-h-integrail/example-agents/simple-node-examples/ex-Readability.json)
This is a basic example of using the Readability node.  Things to try:

### Chat with the Agent
1. In the left navigation bar select **Chat with Agents**
2. Select this Agent
3. Type in a valid URL (for example: https://integrail.ai)

   Notice how the Agent extracts the text from the URL and displays it in simple markdown format.
   
   Markdown used by chatbots and LLMs. It is easier to handle in an agent workflow than HTML

4. Enter some text that is NOT a valid URL (i.e. "not a url")

   Observe that the agent response with an error message (this message is configurable as you'll see)

### View the Agent in the Designer
1. On the left navigation bar, select **Design Agents**
2. On the top of the window, click the agent selector dropdown and select this agent
### Run the Agent
1. Click the Run icon at the top/center of the window
2. Click the 'Agent outputs' node on the right

   Notice that the agent shows the progress as it runs, and records the runtime of each node 
3. In the right panel, scroll down to see the Agent's output.

   This is the text in markdown format that was extracted from the URL (the default URL is https://intgrail.ai)

### Change the Input URL
1. Click the "Agent inputs (URL)" node on the left
2. In the right panel, under the ('urlString') parameter, type another URL into the text box

### Change the Output Format

1. Click the "Extract Text (Readability)" node
2. In right panel, Look at the settings and find the **Format** setting
   2. Select one of the other formats and re-run the agent

   NOTE: for rich formats like markdown, you might want togo over to **Chat With Agents** on the left navbar, 
 
   so you can chat with the agent, and see its output fully formatted instead of viewing the raw text output

### Change the Fallback Output
1. Click the "Extract Text (Readability)" node
2. In right panel, find the **Fallback Outputs** setting, near the bottom

   This setting controls how the node behaves when it fails to complete (when you input an invalid URL for example).
3. Delete the Fallback Output value


If there is no Fallback Output value, when a node fails, instead of continuing to execute the rest of the workflow passing along a fallback output, the workflow will stop exectuting and issue an error message


NOTE: If you wan to create a custom fallback output message, use the below JSON array format **exactly**.  Only change the value inside the quotes "Custom Fallback message"
```json
[ { "name" : "content, "value" : "Custom Fallback Message"} ]
```

### Have a Question or Need Help?
Email us at [support@intgegrail.ai](email://support@integrail.ai)