# Natural Language YouTube Search

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/haltakov/natural-language-youtube-search/blob/main/natural-language-youtube-search.ipynb)

Use [OpenAI's CLIP](https://openai.com/blog/clip/) neural network to search inside YouTube videos. You can try it by running the [notebook](https://colab.research.google.com/github/haltakov/natural-language-youtube-search/blob/main/natural-language-youtube-search.ipynb) on Google Colab.

## How it works

1. Download the YouTube video
2. Extract every N-th frame
3. Encode all frames using using CLIP
4. Encode a natural language search query using CLIP
5. Find the images that best match the search query

For more details see the [notebook](https://colab.research.google.com/github/haltakov/natural-language-youtube-search/blob/main/natural-language-youtube-search.ipynb).

## Natural language search on Unsplah

You can also try my other project to search from 2M photos on [Unsplash](https://unsplash.com/) using natural language queries:

#### [Natural Language Image Search](https://github.com/haltakov/natural-language-image-search)
