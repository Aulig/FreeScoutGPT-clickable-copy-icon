# FreeScout ChatGPT Integration Module (HostetskiGPT)

This repository contains the FreeScout ChatGPT Integration Module, which connects FreeScout with the powerful language model ChatGPT by OpenAI. This integration enables the generation of AI-based responses for incoming messages, providing a more efficient and intelligent support system for your helpdesk.

![FreeScout ChatGPT Integration Module Example](https://my.hostetski.com/files/img/hostetskigpt.jpg "Integration Module Exapmle")
![FreeScout ChatGPT Integration Module Example](https://my.hostetski.com/files/git/gpt.gif "Integration Module Exapmle")


## Features
- Generate AI-based responses for each incoming message
- Utilize the powerful ChatGPT language model to improve support efficiency
- Customizable starting message to set the AI's role (e.g., support agent, sales manager, etc.), associate it with your brand, or provide additional context

## Requirements
To use this module, you will need an API key for ChatGPT, which can be obtained from the OpenAI platform at https://platform.openai.com/account/api-keys.

## Configuration
1. Install the FreeScout ChatGPT Integration Module
2. Add your ChatGPT API key to the module's configuration settings (Http/Controllers/HostetskiGPTController.php  - variable $token)
3. Set a starting message for the AI in the configuration settings. This message will help the AI to associate itself with a specific role, your brand, or provide additional context for generating responses (Http/Controllers/HostetskiGPTController.php - variable $startmessage).

## TODO
 - [ ] Settings via web interface
 - [x] Loader, which shows that the response is being generated and you have to wait a bit

## Contributing
This is an early version of the FreeScout ChatGPT Integration Module, and we appreciate any feedback, suggestions, or contributions to help improve the module. Please feel free to open issues or submit pull requests on GitHub, or send your messages and suggestions to our email: [support@cloudcenter.ovh](mailto:support@cloudcenter.ovh).

Together, we can make this integration a valuable addition to the FreeScout ecosystem and enhance the capabilities of helpdesk software for the entire community.
