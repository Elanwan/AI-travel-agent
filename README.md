# AI Travel Agent

## Overview
This project is an **AI-powered travel assistant** built with **.NET 8**, **Azure OpenAI**, and **Semantic Kernel SDK**. It assists users in planning their trips by providing:
- Destination recommendations
- Currency conversion
- Flight booking assistance
- Travel itinerary generation

## Features
- **Natural Language Processing**: Uses OpenAI's GPT-3.5 Turbo model for interaction.
- **Customizable Prompts**: Uses Handlebars template for structured prompts.
- **Context-aware Conversations**: Maintains chat history to offer relevant suggestions.
- **Plugin-based Architecture**: Easily extendable for additional functionalities like hotel booking.

## Installation
### Prerequisites
- .NET 8.0 or later
- An **Azure OpenAI** subscription with **gpt-35-turbo-16k** deployed
- **Visual Studio Code** or any C#-compatible IDE
- A **GitHub account** (for cloning the repository)

## How It Works
1. **User Input**: The user initiates a conversation by providing travel details.
2. **Kernel Processing**:
   - Calls Azure OpenAI's GPT model.
   - Retrieves relevant travel suggestions.
3. **Chat Completion Service**:
   - Maintains chat history.
   - Adapts responses based on previous interactions.
4. **Function Plugins**:
   - `CurrencyConverterPlugin`: Converts currencies.
   - `FlightBookingPlugin`: Suggests and books flights.
   - `TravelItineraryPlugin`: Generates customized travel plans.

## Usage Example
```
Assistant: How may I help you?
User: I am going to Paris. Can you create an itinerary for me?
Assistant: Sure, how many days is your trip?
User: 5 days.
Assistant: Here’s a suggested 5-day itinerary for Paris...
```

## Future Enhancements
- 🌍 **Integration with real-time APIs** (for flight and hotel bookings)
- 🎤 **Voice Command Support**
- 📅 **Calendar Integration**
- 📍 **Map-based Recommendations**

## License
This project is open-source and available under the [MIT License](LICENSE).

## Contributing
We welcome contributions! Feel free to submit issues or pull requests.

🚀 **Start Planning Smarter Trips with AI!**

