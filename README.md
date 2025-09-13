# Assinment

Task 1: Conversation Management & Summarization

    Maintains a running conversation history of user and assistant messages.

    Supports truncation of conversation history by:

        Number of turns (n last messages)

        Character limit

        Word limit

    Implements periodic summarization after every k messages (k configurable).

    Summarized history replaces older messages to keep conversation concise.

    Demonstrates functionality by:
    
    Feeding multiple conversation samples
    
    Showing truncated history under different settings
    
    Printing automatic summaries after every k-th run

    Allows clear visibility of summaries stored separately for reference.

Task 2: JSON Schema Classification & Information Extraction

    Defines a JSON schema to extract 5 key details from chats:
    
        name, email, phone, location, age
    
    Uses Groq API with OpenAI-compatible function calling to return structured JSON.
    
    Validates extracted outputs against the predefined JSON schema to ensure accuracy.
    
    Demonstrates functionality by:
    
        Parsing at least 3 sample chat messages
        
        Printing extracted JSON outputs for each chat
        
        Showing successful schema validation for all extracted data
    
    Ensures structured information extraction suitable for automated processing or downstream tasks.
          
