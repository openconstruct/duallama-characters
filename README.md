# duallama-characters


To use get llamacpp https://github.com/ggml-org/llama.cpp. use llama-server to load two different models on two different ports
example

    llama-server -m model.gguf --port 8080

  then

    llama-server -m model2.gguf --port 8000

  Use any ports, you can change them in duallama characters.
  There are two included character cards, Pinocchio and Captain Jean Luc Picard.
  To create character cards, open dlcmaker.html
  Once you're done, open dlchars.html

  Assign the name you want the bot to use in chat, it should be the same as the character card for continuity sake.

  Happy chatting, please open a github issue if you have any problems.

  Tested with gemma 1 and 4b, and llama 1 and 3b. I got the best results using 2 gemma 4
