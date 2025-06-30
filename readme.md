# 🤖 Vasuki.AI Conversational Engine

Vasuki.AI is a modular JavaScript conversational engine that combines smart NLP pipelines, API integrations, text generation, and intent detection to handle a wide range of user queries contextually and dynamically.

---

## 🚀 Features

✅ **Predefined Intent Matching**  
Detects greetings, farewells, math, weather, help requests, and more using keyword lists.

✅ **Bigram Markov Chain Text Generator**  
Generates contextually relevant text expansions from a trained word map.

✅ **Fuzzy Autocorrect**  
Uses Levenshtein distance and trigram similarity for typo correction.

✅ **Dynamic API Calls**
- **Wikipedia Summaries** — Fetches page summaries from Wikipedia’s REST API.
- **Weather** — Geocodes city names and fetches real-time weather using OpenStreetMap + Open-Meteo.
- **News** — Pulls the latest geo-based news headlines via NewsData.io.
- **Postal Code Lookup** — Uses Zippopotam.us to resolve zip/post codes to places.
- **Image Search** — Fetches images from Unsplash based on user queries.

✅ **Mathematical Expression Solver**  
Parses and safely evaluates simple math expressions in user queries.

✅ **Summarization & Expansion**  
- Compress text with extractive summarization.
- Expand text creatively using bigram-based NLG.

✅ **Top-k Sampling**  
Implements probabilistic word choice to make generated text more natural and less repetitive.

✅ **Conversation History**  
Stores user inputs and bot responses to maintain context.

---

## 🔗 External APIs Used

- [Wikipedia REST API](https://www.mediawiki.org/wiki/API:REST_API)
- [OpenStreetMap Nominatim](https://nominatim.org/release-docs/latest/api/Search/)
- [Open-Meteo](https://open-meteo.com/)
- [Zippopotam.us](http://www.zippopotam.us/)
- [Unsplash API](https://unsplash.com/documentation)
- [NewsData.io](https://newsdata.io/)

---

## 📌 Example Queries

- *"What's the weather in Paris?"*
- *"solve 12 / (3 + 1)"*
- *"generate image of sunset beach"*
- *"summarize: Artificial intelligence is transforming the world by..."*
- *"What's the news today?"*
- *"What is the post code 110001?"*

---

## 💬 Feedback

> **⭐ Vasuki.AI on npmjs.com:**  
> “Vasuki.AI is an experimental conversational context engine that brings powerful intent detection and response handling into your JavaScript projects. It helps you prototype bots, virtual assistants, and smart chat systems quickly. Feedback is always welcome — your ideas and issues will help improve Vasuki.AI!”

Feel free to share ideas, improvements, or bugs by opening an issue or a pull request.
Mail Me
[here](mailto:codeclutch.adamyarao@gmail.com?subject=Feedback For VasukiAI Github)
---

## 🏷️ License

Open-source. Use it, fork it, and adapt it to your own AI chat apps, smart assistants, or research bots. Contributions are welcome!

---

## ✨ Credits

Crafted with ❤️ using JavaScript, open APIs, and a bit of NLP magic.
