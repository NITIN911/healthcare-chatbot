# healthcare-chatbot
Bot tha give you health suggestions on the bases of responses provided by user. 
It is based on Dialogflow platform provided by google.
# Quick Start With Dialogflow
This guide shows you how to use the Dialogflow Console to build and test a simple agent.
Before you begin

You should do the following before reading this guide:

    Read Dialogflow basics.
    Perform setup steps.

Create an agent

If you have not already created an agent, create one now:

    Go to the Dialogflow ES Console.
    If requested, sign in to the Dialogflow Console. See Dialogflow console overview for more information.
    Click Create Agent in the left sidebar menu. (If you already have other agents, click the agent name, scroll to the bottom and click Create new agent.)
    Enter your agent's name, default language, and default time zone.
    If you have already created a project, enter that project. If you want to allow the Dialogflow Console to create the project, select Create a new Google project.
    Click the Create button.

Import the example file to your agent

The steps in this guide make assumptions about your agent, so you need to import an agent prepared for this guide. When importing, these steps use the restore option, which overwrites all agent settings, intents, and entities.

The agent prepared for this guide is a new agent, with no user-defined intents or entities.

To import the file, follow these steps:

    Download the new-agent.zip file.
    Go to the Dialogflow ES Console.
    Select your agent.
    Click the settings settings button next to the agent name.
    Select the Export and Import tab.
    Select Restore From Zip and follow instructions to restore the zip file that you downloaded.

Intents

Intents categorize an end-user's intention for one conversation turn. For each agent, you define many intents, where your combined intents can handle a complete conversation.
Default intents

When you create an agent, two default intents are created for you:

    Default Welcome Intent: This intent is matched when the end-user begins a conversation with your agent. This intent should return a response that lets the end-user know what your agent does or what they can say to begin a conversation.
    Default Fallback Intent: This intent is matched when the agent cannot match the end-user expression to any other intent.

To see these intents, go to the intent list for your agent:

    Go to the Dialogflow ES Console.
    Select the agent you just created.
    Click Intents in the left sidebar menu.

The middle of the console shows the list of intents for the agent.
# For More checkout the documentation (https://cloud.google.com/dialogflow/es/docs)
