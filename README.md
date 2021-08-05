# Generating baby names

Getting a baby is probably one of the biggest life changing event in anyones life. It turns out there are many things to start thinking of. But arguably the most important thing is the name of your unborn child. When I got the news that I would be a dad by the end of the year, I knew what to do. Instead of thinking about the baby room or start researching strollers, I started looking into Recurrent Neural Networks to pick a name, because who wouldn't, right? Right?

In this repository we generate babynames (for girls) with an Recurrent Neural Network. The model is inspired by this [Github repository from Yan Gobeil](https://github.com/yangobeil/Pokemon-name-generator), who used it to generate Pokemon names. 

There are two different notebooks in this repository. 

1. `generate_babynames_complete.ipynb`: This notebook shows the process from data sources to trained RNN including generated baby names.
2. `generate_babynames_quick.ipynb`: The other notebook removes all the data processing and allows to quickly generate baby names from a pretrained model. 

## I want to generate names for a boy
Although the notebooks focus on generating girl names it would be easy to generate names for a boy. In generate_babynames_complete.ipynb you can where I found the datasets. All input datasets have two columns: `Naam` (key column) and `Aantal` (mostly for additional analyses purposes).