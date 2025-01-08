# OpenAI API Pricing


https://openai.com/api/pricing/

Multiple models, each with different capabilities and price points. Prices can be viewed in units of either per 1M or 1K tokens. You can think of tokens as pieces of words, where 1,000 tokens is about 750 words.

Language models are also available in the Batch API⁠(opens in a new window) that returns completions within 24 hours for a 50% discount.

## API Price Calculator

`track_costs.ipynb` provides a basic example of how to calculate the cost.

**Limitations:** Only input tokens and output tokens are supported yet.
Do not support audio models, batch and cached tokens.




## Pricing
> The data is updated to January 8, 2025.

| Model                                | Input Tokens ($/1K) | Batch Input Tokens ($/1K) | Cached Input Tokens ($/1K) | Output Tokens ($/1K) | Batch Output Tokens ($/1K) | Text Input Tokens ($/1K) | Text Output Tokens ($/1K) | Audio Input Tokens ($/1K) | Audio Output Tokens ($/1K) |
| ------------------------------------ | ------------------- | ------------------------- | -------------------------- | -------------------- | -------------------------- | ------------------------ | ------------------------- | ------------------------- | -------------------------- |
| gpt-4o                               | 0.00250             | 0.00125                   | 0.00125                    | 0.01000              | 0.00500                    |                          |                           |                           |                            |
| gpt-4o-2024-11-20                    | 0.00250             | 0.00125                   | 0.00125                    | 0.01000              | 0.00500                    |                          |                           |                           |                            |
| gpt-4o-2024-08-06                    | 0.00250             | 0.00125                   | 0.00125                    | 0.01000              | 0.00500                    |                          |                           |                           |                            |
| gpt-4o-audio-preview                 |                     |                           |                            |                      |                            | 0.00250                  | 0.01000                   | 0.10000                   | 0.20000                    |
| gpt-4o-audio-preview-2024-12-17      |                     |                           |                            |                      |                            | 0.00250                  | 0.01000                   | 0.04000                   | 0.08000                    |
| gpt-4o-audio-preview-2024-10-01      |                     |                           |                            |                      |                            | 0.00250                  | 0.01000                   | 0.10000                   | 0.20000                    |
| gpt-4o-2024-05-13                    | 0.00500             | 0.00250                   |                            | 0.01500              | 0.00750                    |                          |                           |                           |                            |
| gpt-4o-mini                          | 0.000150            | 0.000075                  | 0.000075                   | 0.000600             | 0.000300                   |                          |                           |                           |                            |
| gpt-4o-mini-2024-07-18               | 0.000150            | 0.000075                  | 0.000075                   | 0.000600             | 0.000300                   |                          |                           |                           |                            |
| gpt-4o-mini-audio-preview            |                     |                           |                            |                      |                            | 0.000150                 | 0.000600                  | 0.010000                  | 0.020000                   |
| gpt-4o-mini-audio-preview-2024-12-17 |                     |                           |                            |                      |                            | 0.000150                 | 0.000600                  | 0.010000                  | 0.020000                   |
| o1                                   | 0.0150              |                           | 0.0075                     | 0.0600               |                            |                          |                           |                           |                            |
| o1-2024-12-17                        | 0.0150              |                           | 0.0075                     | 0.0600               |                            |                          |                           |                           |                            |
| o1-preview                           | 0.0150              |                           | 0.0075                     | 0.0600               |                            |                          |                           |                           |                            |
| o1-preview-2024-09-12                | 0.0150              |                           | 0.0075                     | 0.0600               |                            |                          |                           |                           |                            |
| o1-mini                              | 0.0030              |                           | 0.0015                     | 0.0120               |                            |                          |                           |                           |                            |
| o1-mini-2024-09-12                   | 0.0030              |                           | 0.0015                     | 0.0120               |                            |                          |                           |                           |                            |
| chatgpt-4o-latest                    | 0.0050              |                           |                            | 0.0150               |                            |                          |                           |                           |                            |
| gpt-4-turbo                          | 0.0100              |                           |                            | 0.0300               |                            |                          |                           |                           |                            |
| gpt-4-turbo-2024-04-09               | 0.0100              |                           |                            | 0.0300               |                            |                          |                           |                           |                            |
| gpt-4                                | 0.0300              |                           |                            | 0.0600               |                            |                          |                           |                           |                            |
| gpt-4-32k                            | 0.0600              |                           |                            | 0.1200               |                            |                          |                           |                           |                            |
| gpt-4-0125-preview                   | 0.0100              |                           |                            | 0.0300               |                            |                          |                           |                           |                            |
| gpt-4-1106-preview                   | 0.0100              |                           |                            | 0.0300               |                            |                          |                           |                           |                            |
| gpt-4-vision-preview                 | 0.0100              |                           |                            | 0.0300               |                            |                          |                           |                           |                            |
| gpt-3.5-turbo-0125                   | 0.0005              |                           |                            | 0.0015               |                            |                          |                           |                           |                            |
| gpt-3.5-turbo-instruct               | 0.0015              |                           |                            | 0.0020               |                            |                          |                           |                           |                            |
| gpt-3.5-turbo-1106                   | 0.0010              |                           |                            | 0.0020               |                            |                          |                           |                           |                            |
| gpt-3.5-turbo-0613                   | 0.0015              |                           |                            | 0.0020               |                            |                          |                           |                           |                            |
| gpt-3.5-turbo-16k-0613               | 0.0030              |                           |                            | 0.0040               |                            |                          |                           |                           |                            |
| gpt-3.5-turbo-0301                   | 0.0015              |                           |                            | 0.0020               |                            |                          |                           |                           |                            |
| davinci-002                          | 0.0020              |                           |                            | 0.0020               |                            |                          |                           |                           |                            |
| babbage-002                          | 0.0004              |                           |                            | 0.0004               |                            |                          |                           |                           |                            |


