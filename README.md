# LangChainBot

LangChain Question / Answer Bot for CoStar Benefits Information for Company Tech Talk

Website: https://www.mercerhrs.com/microsite/costar/index.shtml

Langchain Documentation: https://langchain.readthedocs.io/en/latest/index.html

## curl example
curl --location 'http://localhost:5000/get-bot-response' \
--header 'Content-Type: application/json' \
--data '{"question": "what are my 401k contribution limits"}'
