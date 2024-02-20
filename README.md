# azure-cognitive-index

Primeiramente foram criados os seguintes recursos no portal Azure:
- Azure AI Search
- Azure AI services resources
- Storage account

Com os recursos criados e vinculados à minha conta, conforme as orientações do LAB, fora enviados para o
Storage account os documentos utilizados nesse estudo, o _zipped coffee reviews_ disponível em
https://aka.ms/mslearn-coffee-reviews. Este arquivo é composto por 9 documentos de texto contendo reviews
de cafeterias.

No passo seguinte, foi feito o processo de indexação dos documentos, utilizando as definições elencadas
pelo laboratório, afim de criar as definições de indice, incluíndo processo de enriquecimento incremental
para os campos _locations, keyphrases, sentiment, imageTags e imageCaption_.

Com o indice criado, foi possível efetuar diversas buscas na documentação apresentada.
![image](https://github.com/ToneFranca/azure-cognitive-index/assets/56046214/d7911612-dc92-44e5-bb27-3f6bf34ec716)

