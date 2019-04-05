# how-to-run-gpt-2
```
git clone git://github.com/openai/gpt-2.git && cd gpt-2
docker build . -f Dockerfile.cpu --tag gpt-2
docker run -ti gpt-2 src/interactive_conditional_samples.py
```
Test text
```
Even if it’s not literally true that British politics is drowning in its own effluent, the idea carries an unpleasant whiff of reality. Perhaps it’s fairer to talk of the political system undergoing a nervous breakdown. It has certainly seemed that way these past few days, when you merely had to bump into an MP to release an outpouring of “total despair”, as one Tory minister described his state of mind to me on Wednesday.
```
