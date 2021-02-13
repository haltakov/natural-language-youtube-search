# Natural Language YouTube Search

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/haltakov/natural-language-youtube-search/blob/main/natural-language-youtube-search.ipynb)

Use [OpenAI's CLIP](https://openai.com/blog/clip/) neural network to search inside YouTube videos. You can try it by running the [notebook](https://colab.research.google.com/github/haltakov/natural-language-youtube-search/blob/main/natural-language-youtube-search.ipynb) on Google Colab.

## How it works

1. Download the YouTube video
2. Extract every N-th frame
3. Encode all frames using CLIP
4. Encode a natural language search query using CLIP
5. Find the images that best match the search query

For more details see the [notebook](https://colab.research.google.com/github/haltakov/natural-language-youtube-search/blob/main/natural-language-youtube-search.ipynb).

## Examples

Here are some example searches from this [YouTube video](https://www.youtube.com/watch?v=PGMu_Z89Ao8) of a car driving around San Francisco.

### "A fire truck"

![Search results for "A fire truck"](images/fire_truck_1.jpeg)
![Search results for "A fire truck"](images/fire_truck_2.jpeg)
![Search results for "A fire truck"](images/fire_truck_3.jpeg)

### "Road works"

![Search results for "Road works"](images/road_works_1.jpeg)
![Search results for "Road works"](images/road_works_2.jpeg)
![Search results for "Road works"](images/road_works_3.jpeg)

### "People crossing the street"

![Search results for "People crossing the street"](images/people_crossing_1.jpeg)
![Search results for "People crossing the street"](images/people_crossing_2.jpeg)
![Search results for "People crossing the street"](images/people_crossing_3.jpeg)

### "The Embarcadero"

![Search results for "The Embarcadero"](images/embarcadero_1.jpeg)
![Search results for "The Embarcadero"](images/embarcadero_2.jpeg)
![Search results for "The Embarcadero"](images/embarcadero_3.jpeg)

### "Waiting at the red light"

![Search results for "Waiting at the red light"](images/waiting_red_1.jpeg)
![Search results for "Waiting at the red light"](images/waiting_red_2.jpeg)
![Search results for "Waiting at the red light"](images/waiting_red_3.jpeg)

### "Green bike lane"

![Search results for "Green bike lane"](images/bike_lane_1.jpeg)
![Search results for "Green bike lane"](images/bike_lane_2.jpeg)
![Search results for "Green bike lane"](images/bike_lane_3.jpeg)

### "A street with tram tracks"

![Search results for "A street with tram tracks"](images/tram_tracks_1.jpeg)
![Search results for "A street with tram tracks"](images/tram_tracks_2.jpeg)
![Search results for "A street with tram tracks"](images/tram_tracks_3.jpeg)

### "The Transamerica Pyramid"

![Search results for "The Transamerica Pyramid"](images/transamerica_pyramid_1.jpeg)
![Search results for "The Transamerica Pyramid"](images/transamerica_pyramid_2.jpeg)
![Search results for "The Transamerica Pyramid"](images/transamerica_pyramid_3.jpeg)

## Natural language search on Unsplah

You can also try my other project to search from 2M photos on [Unsplash](https://unsplash.com/) using natural language queries:

#### [Natural Language Image Search](https://github.com/haltakov/natural-language-image-search)
