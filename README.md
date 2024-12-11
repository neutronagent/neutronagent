# NeutronAgent

NeutronAgent is a flexible and powerful Python-based AI assistant framework that leverages OpenAI's GPT models. Designed for developers, researchers, and enthusiasts, NeutronAgent makes it easy to integrate AI capabilities into your applications or workflows.

## Features

- **Chat Interface**: Engage in real-time conversations with the AI.
- **Custom Logic Integration**: Extend functionality with task-specific logic (e.g., summarization, sentiment analysis).
- **Module Support**: Import and use external Python modules to expand capabilities.

## Installation

Clone the repository:

```bash
git clone https://github.com/neutronagent/neutronagent.git
cd neutronagent
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

> **Note**: Ensure you have an OpenAI API key to use the GPT models.

## Usage

### Running the Chat Interface

Launch the interactive chat session:

```bash
python neutron_agent.py
```

### Example Custom Tasks

NeutronAgent includes support for task-specific functionalities like text summarization and sentiment analysis. You can call these directly in your code:

```python
# Summarization example
text = "Neutron Agent is a powerful AI assistant that can handle multiple tasks."
print(neutron.custom_logic(task_type="summarize", text=text))
```

## Configuration

Replace `your-openai-api-key-here` with your OpenAI API key in the `__main__` section of `neutron_agent.py`:

```python
API_KEY = "your-openai-api-key-here"
neutron = NeutronAgent(openai_api_key=API_KEY)
```

## Contributing

We welcome contributions! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Open a Pull Request

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- [OpenAI](https://openai.com) for providing the GPT models.
- The AI developer community for inspiration and support.

