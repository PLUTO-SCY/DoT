Our submission *Division-of-Thoughts: Harnessing Hybrid Language Model
Synergy for Efficient On-Device LLM Agents* for WWW'25!

Run: Please put your openai key in function *setOpenAi*:
```
def setOpenAi(keyid = 0):
    # set your openai key here.
    if keyid == 0:
        api_key = ""
    client = OpenAI(api_key=api_key)
    addtoken(-1)
    return client
```
You can set more than one api key for usage.

