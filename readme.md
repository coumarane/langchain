# Welcome to Chainlit! 🚀🤖

Hi there, Developer! 👋 We're excited to have you on board. Chainlit is a powerful tool designed to help you prototype, debug and share applications built on top of LLMs.

## Useful Links 🔗

- **Documentation:** Get started with our comprehensive [Chainlit Documentation](https://docs.chainlit.io) 📚
- **Discord Community:** Join our friendly [Chainlit Discord](https://discord.gg/k73SQ3FyUh) to ask questions, share your projects, and connect with other developers! 💬

We can't wait to see what you create with Chainlit! Happy coding! 💻😊

## Welcome screen

To modify the welcome screen, edit the `chainlit.md` file at the root of your project. If you do not want a welcome screen, just leave this file empty.

## TODO

- Create en environement
Python 3.11.5
$ conda create -n .venv python=3.11.5 -y && source activate .venv

$ pip install chainlit
$ pip install llama-index

- download model exemple:
https://github.com/langchain-ai/langchain/blob/master/docs/docs/modules/state_of_the_union.txt

$ pip install farm-haystack

$ pip install datasets

$ pip install torch

$ pip install langflow

```
ERROR: pip's dependency resolver does not currently take into account all the packages that are installed. This behaviour is the source of the following dependency conflicts.
chainlit 0.7.604 requires fastapi<0.101,>=0.100, but you have fastapi 0.98.0 which is incompatible.
chainlit 0.7.604 requires uvicorn<0.24.0,>=0.23.2, but you have uvicorn 0.22.0 which is incompatible.
llama-index 0.9.6.post1 requires openai>=1.1.0, but you have openai 0.27.10 which is incompatible.
llama-index 0.9.6.post1 requires SQLAlchemy[asyncio]>=1.4.49, but you have sqlalchemy 1.4.41 which is incompatible.
farm-haystack 1.22.1 requires tiktoken>=0.5.1, but you have tiktoken 0.4.0 which is incompatible.
farm-haystack 1.22.1 requires transformers==4.34.1, but you have transformers 4.33.3 which is incompatible.
datasets 2.15.0 requires huggingface-hub>=0.18.0, but you have huggingface-hub 0.15.1 which is incompatible.
```
 Run the langflow:

 $ langflow
