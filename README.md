# City Name Generation with RNN Model: Latin script and Non-latin Script

Two notebooks shared the same database which consists of 3094 cities in the US and China respectively, but the text processing differs according to the libraries. The benchmark models in `Cityname_generator_Pytorch_NN_Model.ipynb` are simple NN models using *PyTorch*, while the models from `Cityname_generator_Tensorflow_RNN_model.ipynb` used GRU units from *TensorFlow*. 


## Notes
Though we had some experience with Transformers throughout the course, RNNs have been something that were not quite expolred in all the exercises. So on top of modifying the models from the last session with a bigger dataset, I assembled a sequence model with GRU layer juxtaposed to the simple NN that we had in class.


## Credits 
`uscities.csv` was downloaded from https://simplemaps.com/data/us-cities.

`china_cities.csv` is from https://github.com/public-wheels/china-cities

`Cityname_generator_Tensorflow_RNN_model.ipynb` is modified based on codes from two tutorials:
https://github.com/antonio-f/Generating-names-with-RNN/blob/master/Generating%20names%20with%20recurrent%20neural%20networks/RNN-task.ipynb,
https://github.com/susantabiswas/Name-Gen-RNN/blob/master/Name_Generator.ipynb, and *Dinosaur Island-Character-Level Language Modeling* in the course ["Sequence Models" on Coursera](https://www.coursera.org/learn/nlp-sequence-models).

`Cityname_generator_Pytorch_NN_Model.ipynb` adopted codes from https://github.com/karpathy/nn-zero-to-hero/blob/master/lectures/makemore/makemore_part2_mlp.ipynb.
