# Multilingual AI Assistant with LLMOps Implementation

Welcome to the Multilingual AI Assistant project! This project focuses on developing a multilingual AI assistant powered by Google Gimini (LLM) model API. By integrating with Streamlit for the UI and implementing LLMOps practices, we aim to create an efficient and scalable assistant for natural language interaction.

## Overview

The Multilingual AI Assistant project aims to create an AI-powered assistant capable of understanding and responding to user queries in multiple languages. Leveraging the Google Gimini model API and Streamlit for the user interface, this project demonstrates the application of LLMOps practices in developing and deploying conversational AI systems.

## Project Structure

The project is structured into several components, each serving a specific LLMOps purpose:

- **Setup**: Scripts and instructions for setting up the project environment, including creating a virtual environment, installing dependencies, and configuring the project structure.

- **Development**: Codebase for developing the AI assistant, including the main application script (`app.py`) and helper functions (`src/helper.py`).

- **API Integration**: Steps for generating and setting up the Google Gimini API key, enabling communication with the AI model.

- **Deployment**: Instructions for deploying the AI assistant to an AWS EC2 instance, ensuring accessibility and scalability.

## LLMOps Implementation Highlights

This project showcases best practices in LLMOps implementation, including:

- **Environment Management**: Creating a dedicated virtual environment (`multilingual`) for isolating project dependencies and ensuring consistency across different environments.

- **Configuration Management**: Utilizing environment variables (stored in `.env` file) for sensitive information such as API keys, ensuring secure and configurable deployments.

- **Infrastructure as Code**: Automating the setup of AWS EC2 instance and environment configuration using scripts, enabling reproducible and scalable deployments.

- **Continuous Deployment**: Enabling seamless deployment of the AI assistant to AWS EC2 using Streamlit, ensuring rapid iteration and updates.

## Usage

To get started with the project and experience the Multilingual AI Assistant, follow these steps:

1. Set up your project environment by creating a virtual environment named `multilingual` and installing dependencies from the `requirements.txt` file.

2. Obtain a Google Gimini API key from the Google DeepMind website and set it as an environment variable in the `.env` file.

3. Run the Streamlit application locally using the command: `streamlit run app.py`. Interact with the assistant using voice commands and text inputs.

4. Deploy the AI assistant to an AWS EC2 instance following the provided deployment instructions. Ensure proper configuration of security groups and port mapping.

5. Access the deployed assistant on the EC2 instance by connecting to its public IP address and interacting with the Streamlit application.

## Contributing

Contributions to the project are welcome! If you have any suggestions, bug reports, or feature requests related to LLMOps practices, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
