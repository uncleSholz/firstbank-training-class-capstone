# Training Capstone

There are two criteria for this project:

1. You are able to utlize prompt engineering in this codebase so that the GPT model is able to generate better image prompts for DALL-E
2. You are able to improve the User Experience of the Dash app so that a user can see:\
    i. The generated prompt\
    ii. The loading time\
    iii. Better UI elements

You can be as creative as you can and even generate more than one image. Tho this does not count to your score. Only the first two criteria count towards your score.

## Running this project

After cloning the repo do the following:

1. Create a .env file from the .env.example file. You can choose to duplicate the .env.example file and then rename it to .env or run the following command:

```
cp .env.example .env
```

2. Install the dependencies using the command below:

```
pip install -r requirements.txt
```

3. Set the environment variables from the Azure OpenAI resource and Azure OpenAI studio

4. Run the app.py file using the command below:

```
python app.py
```


## Note

1. The main.py file does not have anything to do with the app. It's just a file you can use to quickly check that your API keys are working
2. You should create a .env file from your .env.example file to ensure that the environment variables are obtained
3. If you are on your local machine, you should create a new virtual environment for your project. But if you are on Codespaces, you don't have to.

