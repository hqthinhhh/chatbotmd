# Running the Chat Application

This guide will help you run the chat application contained in the `index.html` file.

## Start the app

1. **Download model**

Create a folder named `models`, then download `ggml-vistral-7B-chat-q4_0.gguf` from here <https://huggingface.co/uonlp/Vistral-7B-Chat-gguf> and put into the `models` folder

2. **Install llama_cpp Python**

Follow the guide here to install llama_cpp Python <https://github.com/abetlen/llama-cpp-python>

3. **Run local OpenAI server**

Run the following script to run an OpenAI API server locally. The server should run at port 8000

```bash
./server.sh
```

4. **Run chat application**

```
python3 -m http.server 9000