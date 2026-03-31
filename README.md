# ShopAI Mate

Your private AI shopping assistant — chat, search products, compare prices, and get personalized recommendations, all running on-device with no data sent to the cloud.

This is a private, on-device AI assistant built for smart shopping. Powered by Apple's MLX framework, it runs advanced language models entirely on your iPhone — your conversations never leave your device.

Ask for product recommendations, compare options, search the web for reviews, and get tailored suggestions through an interactive preference questionnaire — all within a single chat.

KEY FEATURES

- On-device AI: Models run locally using Apple MLX. No server, no subscriptions, no data collection.

- Product Search: Find and compare products with prices, descriptions, and direct links.

- Web Search: Get up-to-date information and reviews powered by Brave Search.

- Smart Questionnaires: Interactive UI to capture your budget, brand preferences, and must-have features for personalized recommendations.

- Vision Support: Attach photos from your camera or library and ask the AI about them.

- Thinking Mode: Toggle reasoning visibility to see how the model arrives at its answers.

- Model Management: Download, switch, and manage MLX models directly from the app.

## Privacy Policy

Privacy Policy

This app uses two third-party search APIs, Brave Search and Channel3, to process user queries and return lists of products.

When you enter a search query, the query is sent to these external services in order to retrieve relevant results.

The app itself does not collect, store, or retain any personal data. No user information is saved on our servers.

However, the third-party services (Brave Search and Channel3) may process requests in accordance with their own privacy policies. We recommend reviewing their policies to understand how your data may be handled.


## Publishing Checklist

Before publishing or sharing builds:

1. confirm the app icon and bundle identifier are correct
2. confirm location, camera, and photo permission strings are intentional
3. verify the selected deployment target is what you want to support
4. test one plain chat, one image turn, and one tool-backed turn on a real device
5. remove any private API keys from local settings before screenshots or demos

## GitHub

This repository is prepared to be committed as a normal Xcode project with the app, assets, and `ToolTest` harness checked in.

Typical flow:

```bash
git add -A
git commit -m "Initial commit for MLXChat"
git remote add origin <your-repo-url>
git push -u origin main
```
