# TransferLearning_Muilti-Channel_Imagery
<img src="https://www.gov.br/cbpf/pt-br/assuntos/noticias/inscricao-para-duas-bolsas-pibic-ate-terca-09/cbpf-1.png"  width="500" />

<font size="50"> Implementing Transfer Learning to N>3 Channels Imagery and Removing Pre-processing Layers from Tensorflow.applications

    
<font size="1">
This is a tutorial Notebook of how to solve two problems:
    
    1.) How to implemente transfer Learning, using the weights of IMAGENET to images with N>3 channels.
    
    2.) How to Remove the peprocessing layers loaded with Tensorflow models
    

*Neste Notebook iremos focar em dois problemas:*
  
*1) As redes neurais Convolucionais pré carregadas do tensorflow, com os pesos da imagenet, só aceitam imagens com 3 canais (RGB).*

*2) As CNN carregadas do **TF** vêm com camadas de pré processamento embutidas.*

*Objetivo: Um tutorial de como podemos retirar essa camada de pré* 
*processamento, e adaptar a rede para que ela possa ser usada com N canais.*
*Os pesos associados aos canais extras serão a média dos valores dos pesos da Imagenet para os canais originais.*


    
***Este código funciona em qualquer rede disponível no TensorFlow.applications 2.8.0***
    
This code was developed by Phelipe Darc.

