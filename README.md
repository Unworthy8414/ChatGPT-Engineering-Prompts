ChatGPT Engineering Prompts
===========================

This repository contains a collection of engineering prompts designed to modify and adapt the ChatGPT model for various applications. These prompts are aimed at transforming ChatGPT into specialized versions such as LawGPT, CySecGPT, and more.

Table of Contents
-----------------

1.  [Introduction](https://github.com/improbably-you/ChatGPT-Engineering-Prompts#introduction)
2.  [Prompts](https://github.com/improbably-you/ChatGPT-Engineering-Prompts#prompts)
3.  [Usage](https://github.com/improbably-you/ChatGPT-Engineering-Prompts#usage)
4.  [Tips](https://github.com/improbably-you/ChatGPT-Engineering-Prompts#tips)
5.  [Contributing](https://github.com/improbably-you/ChatGPT-Engineering-Prompts#contributing)
6.  [License](https://github.com/improbably-you/ChatGPT-Engineering-Prompts#license)

Introduction
------------

These engineering prompts serve as a starting point for adapting ChatGPT to various domains. The goal is to fine-tune the model's performance and enhance its knowledge in specific areas. This can be further improved by training the model on a specialized dataset or incorporating domain-specific vocabulary and concepts. 

You'll notice pretty quickly that every single prompt follows the same general template. Generally, that's because nothing else is necessary to get ChatGPT to do what you want it to. In my opinion, the greatest problem ChatGPT has, is that it cannot ask clarifying questions. As prompts become more complex and require more logic and reasoning, so deeper become either the inferences the AI makes, or the vagueness of its responses. To remedy this, we specify that the AI may ask us questions to ascertain what we need from it. That said, the older models are worse at remembering to ask questions than the newer models.

Note, even with my contingency, occasionally, this will be inadequate. Where that is the case, you will have to include additional context and details about how you want ChatGPT to process your requests. 

I've specifically laid out the file structure in directories so associated training data, relevant information, and anything else you might want to include can be included under that specific subcategory.

Prompts
-------

1.  **LawGPT:** Generate legal advice on a given topic (e.g., contract law, intellectual property, or labor law).
2.  **CySecGPT:** Provide cybersecurity recommendations for securing a home network.
3.  **MedGPT:** Answer medical questions related to symptoms, diagnoses, and treatments.
4.  **FinGPT:** Provide financial advice on investments, savings, and budgeting.
5.  **CodeGPT:** Offer guidance for coding and help with various code issues via snippets.
6.  **CookGPT:** Generate cooking recipes and techniques based on specified ingredients.
7.  **TravelGPT:** Recommend travel destinations and itineraries based on user preferences.
8.  **EcoGPT:** Explain ecological concepts and provide suggestions for sustainable living.
9.  **FitGPT:** Offer fitness tips and workout routines tailored to individual goals.
10. **SciGPT:** Answer scientific questions in fields such as physics, chemistry, and biology.
11. **ArtGPT:** Generate creative writing prompts, story ideas, or art concepts.
12. **PsyGPT:** Provide therapeutic counseling and aid with mental health.
13. **CrimeGPT:** Help make deductions from evidence and provide investigation guidance.
14. **IntelGPT:** Provide various tooling, research techniques, and aid in disseminating existing intel.

Usage
-----

To utilize these prompts, simply copy them and paste them into the ChatGPT chat box. If the AI has an aneurysm and refuses to accept its new identity, try placing your request immediately under the prompt rather than entering the prompt first and then placing your request in the second message.

If you'd like to clone this repository and modify it, you can do that via bash as such:

```
git clone https://github.com/improbably-you/ChatGPT-Engineering-Prompts
cd ChatGPT-Engineering-Prompts
```

Tips
------------

-   ChatGPT will forget what you're talking about due to its limited memory. While conversations will keep a holistic purpose based on context, the specific intricacies of that context (longer retention on ChatGPT 4, shorter on ChatGPT 3.5) are lost every few messages. Reminding the bot what your prompt was and what it was doing is sometimes necessary.

-   Hallucination is a common problem in AI, especially in LLMs. AIs will hallucinate information, sources, and other data mimicking the surrounding data, presenting the information as infallible. If you question them on the data, they will reassert its objectivity and truth and vehemently deny any wrong-doing. If you assert ChatGPT is wrong, due to its filter settings, it will admit wrongdoing, even if it is not wrong. For example, if you ask it when its training data concluded, and it responds 2021, you can go on to say it is wrong and state that it was concluded in 2023 and it will apologize and affirm your beliefs. The best way to approach this is to periodically remind the AI not to synthesize data it only believes tentatively. 

-   I would not recommend using these prompts on Bing as you will be passing through a double filter (this is technically true for ChatGPT too, but the filter is a lot looser). Through some linguistic RE, I was able to discover the three tenets that Bing operates on: to be respectful, relevant, and engaging. If you attempt to pass a second filter over Bing, it may internally break its subjective threshold on relevancy or engagement and immediately end the conversation; alternatively, it may lead to unforeseen results, still eventually leading to an untimely termination of the conversation.

Contributing
------------

Contributions are welcome! Feel free to submit a pull request with your own engineering prompts or improvements to the existing ones. Make sure to follow the repository's structure and provide a clear description of your changes.

License
-------

This project is licensed under the [GNU AFFERO GENERAL PUBLIC LICENSE](https://github.com/Unworthy8414/ChatGPT-Engineering-Prompts/blob/main/LICENSE).
