## TERM_CHAT
- Chat with GPT-3.5 in the terminal.
- Chats are saved locally in `~/.chat/` by default.
- You can select any previous chats to continue.
- You can list all the saved chats.

## Setup
1. clone this repo and `cd` into it.
2. replace the `API_KEY` with your own in the `chat` file.
3. run `chmod +x ./chat`
4. run `./chat would you tell me a joke?`

## Usage
start a new chat:
```
./chat which country won the world cup in 2014?
```

continue last chat:
```
./chat -c where was it held?
```

continue an old chat:
```
./chat -s <chat_file_path/chat_file_name> what did I ask?
```

list all chats:
```
./chat -l
```

