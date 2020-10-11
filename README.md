# Pokedex

Like a lot of people, I also was obsessed with Pokemon as a kid. I awaited for 2020 when they would become actual living creatures, however, when that failed, I decided I might as well just create the Pokedex that Ash Ketchum was always seen with. 

My Pokedex uses a multi-class classifier from FastAI and can classify the Gen One pokemon. This limitation is because of the dataset used. However, in spite of that, my model has achieved an accuracy of about 94.7%. I then connected this model to a backend using Flask and created its Frontend in JavaScript, HTML, and CSS. 

My model will take your image, and be able to classify what Pokemon it is and narrate some of its stats. 

In the future, I hope to the following:
 x Improve the dataset.
 x Make the prediction UI better.
 x Form a Multilabel classifier so that in case classify multiple pokemon in one image!
