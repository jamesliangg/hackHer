Starting local Redis DB

`docker run -d -p 6379:6379 -p 8001:8001 redis/redis-stack:latest`

Connection URL = `redis://localhost:6379`

Delete all keys in Redis DB `redis-cli flushall`

https://python.langchain.com/docs/integrations/vectorstores/redis
https://python.langchain.com/docs/integrations/providers/cohere
https://python.langchain.com/docs/use_cases/question_answering/quickstart
https://api.python.langchain.com/en/latest/vectorstores/langchain_community.vectorstores.redis.base.Redis.html#
https://python.langchain.com/docs/modules/data_connection/document_loaders/pdf