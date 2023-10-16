# Just ask Alice

This repo contains a simple script that allows you to ask questions of the book
Alice's Adventures in Wonderland.

This script was developed and tested using Python 3.11.6 (3.12.x did not work).
It also assumes a virtual environment (in `.python-version`) named 'vai311'.
Once you've cloned the repo and have an appropriate version of python a virtual
environment, try the following:


```bash
pip install -r requirements.txt
python alice.py -h   # see the help
```

Before it will work, however, you may need to adjust the path to your OpenAI
credentials file in the script.  Then you can start asking questions.

```bash
python alice.py "What advice did the caterpillar give to Alice?"
```

To regenerate the index for the book (uses OpenAI) use the `-c` option.

```bash
python alice.py -c "What advice did the caterpillar give to Alice?"
```

