AI Chat Console Application
A simple, interactive console-based chatbot application built with C# that leverages GitHub's AI models inference API to provide real-time conversational AI capabilities.
Features

Streaming Responses: Real-time word-by-word response streaming for enhanced interactivity
Conversation History: Maintains full chat context throughout the session
Color-Coded Interface: Distinct colors for user input, bot responses, and system messages
Persistent Sessions: Continue conversations with full context retention

Prerequisites

.NET 9.0 or higher
NuGet packages:
Microsoft.Extensions.AI.OpenAI
Configuration
Important: Before running the application, you must configure your own API credentials:

Obtain a GitHub Personal Access Token with appropriate permissions
Replace the placeholder token in the code:

csharp   new ApiKeyCredential("YOUR_GITHUB_PAT_HERE")

Usage

Run the application:

bash   dotnet run

Interact with the chatbot:

Type your message and press Enter
The AI will respond in real-time with streaming text
Type exit to quit the application


The conversation history is maintained throughout the session, allowing for contextual multi-turn conversations.


Sameer IBS 
Senior Software Engineer 



