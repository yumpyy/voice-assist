# voice assist
voice assistant/chat bot (?) dunno why I made this

![gui-preview](./gui-preview.png)

## installation
1. run this in terminal
```
git clone https://github.com/yumpyy/school-proj.git && pip install -r requirements.txt
```

2. install extra depedencies from below and place them in `models` directory.

3. then run `python main-qt-gui.py`

## extra dependencies (required)
1. [megumin voice model](https://huggingface.co/DogeLord/megumin/tree/main) for tts
2. [gpt4all model](https://huggingface.co/TheBloke/orca_mini_3B-GGML/resolve/main/orca-mini-3b.ggmlv3.q4_0.bin)

## todo
- [ ] test on windows
- [ ] install script
- [ ] better logs 
- [x] add mysql-connector for logging chat history
- [x] memory for gpt model
- [x] add gui
- [x] use gpt3.5 api for queries
    | couldnt get openai api key, instead im using gpt4all orca mini model
