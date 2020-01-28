# Challenge | Pipeline of Book Evaluations

![pipeline](/data/screenshot.png)

## Introduction

I have an opinion: every Data Scientist should be an avid reader. Even if the topic is not exact science, reading widens our world view, make us prone to different subjects and perspectives. 
With the actual volume of published content, we need some filtering. That can mean sailing by target subject, and looking for well-stablished authors and books.
I digged into that through some authors from the exact sciences (mainly logic, finance, math and programming), but the actual work would recquire time to process, and would risk crashing the API key.


## The steps

- Find viable API for (somehow) reliable book evaluations.
- Extract data from API (xml and json), and also travel through its html to find key features.
- Explore the obtained data, retrieving some quality reading content.


## Hardships along the way

- APIs have limitations, and they tend to crash if there are too many queries.
- Had to exlore XML, which was not on the study plan. Luckily, that's not far from a HTML.
- Somehow the response obtained for the authors IDs did not retrieve everything. Had to find those instances, and redo it for them.
- The API crashed without giving further notice, and way before the informed maximum throttling.
- Not enough data and scrubbing to retrieve useful information about quality tendencies.


## Deliverables

A presentation on 'Google Slides'.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRv5ixIDMijHlA85onwSU1dgwT3JjgLABp5cE-K33XcEmL5FP01XwWoVnbwWUs5WA60i13aiyM9LwlW/embed?start=false&loop=true&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

A csv with the filtered dataset.


## Sources

[API/Scrapping - Book evaluations](https://www.goodreads.com/api)

[Scrapping (incipient) - Book exchange](https://www.skoob.com.br/)

[Multiple intelligences - Wikipedia](https://en.wikipedia.org/wiki/Theory_of_multiple_intelligences)