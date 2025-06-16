# TravelDash Mobile App

A React Native travel companion app with budget management and AI assistance features.

## Features

### Budget Management
- Track trip-specific budgets with category-wise allocation
- Real-time expense tracking with visual progress bars
- Default budget categories with customizable allocations:
  - Accommodation (40%)
  - Transportation (20%)
  - Food & Dining (20%)
  - Activities (15%)
  - Miscellaneous (5%)
- Color-coded budget indicators

### AI Travel Assistant
- Chat interface for travel-related queries
- Powered by OpenAI GPT-3.5
- Suggested travel questions
- Real-time responses with loading states
- Message history persistence

## Setup

1. Install dependencies:
```bash
npm install
```

2. Environment Setup:
- Create a `.env` file in the root directory
- Add your OpenAI API key:
```
OPENAI_API_KEY=your_api_key_here
```

3. Run the app:
```bash
# iOS
npm run ios

# Android
npm run android
```

## Tech Stack

- React Native with Expo
- TypeScript
- Firebase (Authentication & Firestore)
- OpenAI API
- React Navigation
- React Native Paper
- Async Storage

## Development

### Adding a New Budget
1. Navigate to a trip detail screen
2. Click on "Add Budget"
3. Enter the total budget amount
4. The app will automatically allocate the budget across categories

### Using the AI Assistant
1. Navigate to the AI Assistant screen
2. Type your travel-related question or select a suggested one
3. Wait for the AI to respond
4. Your chat history will be preserved between sessions

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request


# Troubleshooting

If you're having issues getting the above steps to work, see the [Troubleshooting](https://reactnative.dev/docs/troubleshooting) page.

# Learn More

To learn more about React Native, take a look at the following resources:

- [React Native Website](https://reactnative.dev) - learn more about React Native.
- [Getting Started](https://reactnative.dev/docs/environment-setup) - an **overview** of React Native and how setup your environment.
- [Learn the Basics](https://reactnative.dev/docs/getting-started) - a **guided tour** of the React Native **basics**.
- [Blog](https://reactnative.dev/blog) - read the latest official React Native **Blog** posts.
- [`@facebook/react-native`](https://github.com/facebook/react-native) - the Open Source; GitHub **repository** for React Native.
