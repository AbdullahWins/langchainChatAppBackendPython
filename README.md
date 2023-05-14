Create and activate a virtual environment:

```
python3 -m venv myenv
```

For MacOS/Linux:

```
source myenv/bin/activate
```

For Windows:

```
myenv\Scripts\activate
```

Install the necessary libraries:

```
pip install -r requirements.txt
```

Run the backend server:

```
daphne project.asgi:application
```

If your backend server is running correctly, you should see something like this:

```
"WSCONNECTING /ws/chat/" - -
"WSCONNECT /ws/chat/" - -
```

**Important**: In order to run the LLM, set your Open AI API key [here](https://github.com/AbdullahWins/langchainChatAppBackendPython/project/settings.py#L146).