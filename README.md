# Gerador de Cachorros com Autoencoder Variacional

Este repositório contém a documentação para geração de um modelo do tipo autoencoder variacional, treinado na tarefa de codificar/decodificar imagens de cachorros, a ser depois utilizado para a geração de imagens de novos cachorros a partir da amostragem aleatória de valores normalmente distribuídos do espaço latente correspondente.

O código utiliza o dataset [Dog Breed Identification](https://www.kaggle.com/c/dog-breed-identification). O [modelo ResNet50 implementado no Keras](https://www.tensorflow.org/api_docs/python/tf/keras/applications/ResNet50) foi utilizado para pré-processamento das imagens. A estrutura da rede variacional é baseada em um [tutorial do Keras](https://keras.io/examples/generative/vae).
