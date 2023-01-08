# WordCloud-Ulises

Worlcloud practice based on the text of the book: 'The Odyssey'.

![Captura de pantalla_20230108_143433](https://user-images.githubusercontent.com/119113483/211198909-212cf251-e029-409f-86b7-565221be893d.png)

## Technologies 💻
* Python
* Jupyter

## Python Libraries 🗃️
* WordCloud
* Numpy
* PIL
* NLTK

* Matplotlib

## Data 📖
The entire text of the book: 'The Odyssey'.

## Text mining ⛏️
* First of all, we eliminate the "stopwords" from the abstract column, discarding irrelevant words to reduce the dimension later, facilitating the training of the model.
* We convert each word of the abstract to tokens in order to work with them.
* We eliminate the words that only appear once and the numbers, since when creating clusters they do not give us anything.
* We create the object again adding the mask

## Preview 🖼️

![Captura de pantalla_20230108_143640](https://user-images.githubusercontent.com/119113483/211198992-f8f53f4f-17d0-4a76-a43b-215e07c4ad48.png)

![Captura de pantalla_20230108_143706](https://user-images.githubusercontent.com/119113483/211199059-5e07ce3f-487a-4875-9416-7152b1bedc12.png)
