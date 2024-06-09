# ChatGPT-access
A little code to access ChatGPT 3.5 Turbo.

This repository contains a project to interact with OpenAI's GPT models using the latest OpenAI API. The project includes a Python script that reads an API key from a file and interacts with the GPT-4-turbo model to generate responses based on user input.

## Requirements

- Python 3.6+
- OpenAI Python client (`openai`)

## Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/galenwilkerson/ChatGPT-access.git
   cd ChatGPT-access
   ```

2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

3. **Generate an API Key:**

   You need to generate an API key from the OpenAI website. Follow these steps:

   - Go to the [OpenAI API page](https://beta.openai.com/signup/).
   - Sign up or log in.
   - Generate a new API key.

4. **Save the API Key:**

   Save the generated API key in a file named `api_key.txt` in the project directory. The script will read this file to authenticate requests to the OpenAI API.

   ```sh
   echo "your-api-key" > api_key.txt
   ```

## Usage

Run the script to start interacting with the ChatGPT model:

```sh
python chatgpt_project.py
```

When you run the script, it will prompt you to enter text, which will be sent to the GPT-4-turbo model. The model's response will be printed to the console. To exit, type "exit", "quit", or "stop".

## Notebook

The project also includes a Jupyter Notebook (`OpenAI ChatGPT project.ipynb`) that demonstrates the same functionality. You can open and run the notebook using Jupyter:

```sh
jupyter notebook "OpenAI ChatGPT project.ipynb"
```

## Example

Here is an example of how the interaction might look:

```
Welcome to the ChatGPT project!
You: hi
ChatGPT: Hello! How can I assist you today?
```

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Issues

If you encounter any issues, please open an issue on this repository.
