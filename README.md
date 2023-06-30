# A Zoo for Chat Data for Training LLM

- Human-bot conversation: e.g. ShareGPT
- Bot-bot conversation: e.g. UltraChat
- human-human conversation: see everewhere

## Multilingual ShareGPT
###  Translated ShareGPT  using ChatGPT.

ShareGPT is a collection of chat logs between real users and the AI model ChatGPT. What sets this dataset apart is the fact that these interactions have been selected by users themselves, which generally implies a higher level of quality and relevance. This corpus played a key role in the success of the well-known Vicuna model, as it allowed for the training of large-scale pre-trained language models capable of engaging in smooth multi-turn conversations.

Despite the global nature of the interactions within ShareGPT, it's important to acknowledge that the distribution of languages in the corpus is still skewed, with a predominance of English and fewer instances of other languages. To rectify this imbalance and extend the utility of the model, we have made an effort to translate the ShareGPT corpus into other languages, such as Chinese, Japanese, Korean, German, French, Italian, and Arabic. This initiative is intended to assist in the construction of large-scale language models akin to Vicuna in these other languages.

The translation data currently covers utterances of <2048 length, which are constrained by the input length of ChatGPT-3.5. The translated corpus does not yet include data from the ShareGPT corpus that's already in the target language. Moreover, manual verification of the translations has not been carried out to ensure higher quality, and this is one thing we want to do in the future.

### Dataset link
|Target Language|Link for Alpaca-gpt4|Link for Evol-instruct|
| ------ | ------ | ------ |
| Chinese |[Alpaca-gpt4](https://huggingface.co/datasets/FreedomIntelligence/alpaca-gpt4-chinese)|[Evol-instruct](https://huggingface.co/datasets/FreedomIntelligence/evol-instruct-chinese)
| Japanese |[Alpaca-gpt4](https://huggingface.co/datasets/FreedomIntelligence/alpaca-gpt4-japanese)|[Evol-instruct](https://huggingface.co/datasets/FreedomIntelligence/evol-instruct-japanese)|
| Korean |[Alpaca-gpt4](https://huggingface.co/datasets/FreedomIntelligence/alpaca-gpt4-korean)|[Evol-instruct](https://huggingface.co/datasets/FreedomIntelligence/evol-instruct-korean)|
| German |[Alpaca-gpt4](https://huggingface.co/datasets/FreedomIntelligence/alpaca-gpt4-deutsch)|[Evol-instruct](https://huggingface.co/datasets/FreedomIntelligence/evol-instruct-deutsch)|
| French |[Alpaca-gpt4](https://huggingface.co/datasets/FreedomIntelligence/alpaca-gpt4-french)|[Evol-instruct](https://huggingface.co/datasets/FreedomIntelligence/evol-instruct-french)|
| Italian |[Alpaca-gpt4](https://huggingface.co/datasets/FreedomIntelligence/alpaca-gpt4-italian)|[Evol-instruct](https://huggingface.co/datasets/FreedomIntelligence/evol-instruct-italian)|
| Arabic |[Alpaca-gpt4](https://huggingface.co/datasets/FreedomIntelligence/alpaca-gpt4-arabic)|[Evol-instruct](https://huggingface.co/datasets/FreedomIntelligence/evol-instruct-arabic)|
| Portuguese |[Alpaca-gpt4](https://huggingface.co/datasets/FreedomIntelligence/alpaca-gpt4-portuguese)|[Evol-instruct](https://huggingface.co/datasets/FreedomIntelligence/evol-instruct-portuguese)|
| Spanish |[Alpaca-gpt4](https://huggingface.co/datasets/FreedomIntelligence/alpaca-gpt4-spanish)|[Evol-instruct](https://huggingface.co/datasets/FreedomIntelligence/evol-instruct-spanish)|
| Hindi |[Alpaca-gpt4](https://huggingface.co/datasets/FreedomIntelligence/alpaca-gpt4-hindi)|[Evol-instruct](https://huggingface.co/datasets/FreedomIntelligence/evol-instruct-hindi)|
| Indonesian |[Alpaca-gpt4](https://huggingface.co/datasets/FreedomIntelligence/alpaca-gpt4-indonesian)|[Evol-instruct](https://huggingface.co/datasets/FreedomIntelligence/evol-instruct-indonesian)|

As an open-source project, we are open to contributions.

## Bot-bot Conversation
https://github.com/thunlp/UltraChat

https://github.com/radi-cho/botbots


## Citation
This project is also a part of [LLMZoo](https://github.com/FreedomIntelligence/LLMZoo) and if this dataset has been helpful to you, please feel free to cite it using the following format:

```angular2
@article{phoenix-2023,
  title={Phoenix: Democratizing ChatGPT across Languages},
  author={Zhihong Chen and Feng Jiang and Junying Chen and Tiannan Wang and Fei Yu and Guiming Chen and Hongbo Zhang and Juhao Liang and Chen Zhang and Zhiyi Zhang and Jianquan Li and Xiang Wan and Benyou Wang and Haizhou Li},
  journal={arXiv preprint arXiv:2304.10453},
  year={2023}
}
```

```angular2
@misc{llm-zoo-2023,
  title={LLM Zoo: democratizing ChatGPT},
  author={Zhihong Chen and Junying Chen and Hongbo Zhang and Feng Jiang and Guiming Chen and Fei Yu and Tiannan Wang and Juhao Liang and Chen Zhang and Zhiyi Zhang and Jianquan Li and Xiang Wan and Haizhou Li and Benyou Wang},
  year = {2023},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/FreedomIntelligence/LLMZoo}},
}
```

