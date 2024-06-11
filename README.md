# Chatboi

ChatBoi is a simple chatbot built using the Rasa framework for conversational AI. It can engage in casual conversations, express feelings, bid farewell, respond to requests, and more.

## Features

- **Greeting**: Responds to various forms of greetings like "Hello", "Hi", "Hey there", etc.
- **Expressing Feelings**: Engages in conversations about feelings, whether happy, sad, excited, or stressed.
- **Farewell**: Provides polite farewells when ending conversations.
- **Request Handling**: Assists with user requests related to booking flights, hotel reservations, weather information, restaurant recommendations, etc.
- **Casual Conversation**: Engages in light-hearted and casual discussions on various topics.

## Usage

To interact with ChatBoi, follow these steps:

1. **Installation**: Clone this repository to your local machine.

- `git clone https://github.com/ShivgunGaming/chatboi.git`


2. **Setup Environment**: Install the necessary dependencies.

- `cd chatboi`

- `pip install -r requirements.txt`


3. **Training**: Train the Rasa model using the provided training data.

- `rasa train`


4. **Run the Bot**: Start the Rasa server to interact with the bot via REST API.

- `rasa run --cors "*"`

or

- `rasa shell`


5. **Interact**: You can now interact with the bot through a REST API client like cURL or Postman, or integrate it with your own applications.

## Training Data

The training data for ChatBoi includes:

- **Domain**: Defines the intents, responses, actions, and policies.
- **NLU Data**: Contains examples of user messages mapped to intents.
- **Stories**: Defines conversational flows and user-bot interactions.
- **Config**: Configuration file specifying the NLU pipeline and policies.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
