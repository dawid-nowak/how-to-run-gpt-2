# how-to-run-gpt-2
```
git clone git://github.com/openai/gpt-2.git && cd gpt-2
docker build . -f Dockerfile.cpu --tag gpt-2
docker run -ti gpt-2 src/interactive_conditional_samples.py
```
