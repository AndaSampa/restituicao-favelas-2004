# Restituição de Favelas MDC 2004

Repositório para desenvolvimento de método para restituição de favelas 2004

## Introdução

No aero levantamento realizado na cidade de São Paulo em 2004, que deu origem ao MDC (Modelo Digital da Cidade), não foram realizadas as restituições cartográficas de alguns assentamentos informais e favelas. Diferentemente do aerolevantamento a Laser (LiDAR 3D) realizado em 2017 que classifica toda e qualquer edificação, possibilitando assim um Modelo de altura das edificações.

## Objetivo

Para comparar o uso de solo das ZEIS entre 2004 e 2017 seria necessário desenvolver um método de restituir as edificações que não foram restituidas no aerolevantamento de 2004. Portanto o objetivo desse repositório é desenvolver, testar, documentar e validar um método para poder restituir as edificações faltantes nas áreas de ZEIS

## Materiais e método

Temos a disposição as ortofotos de 2004 com resolução espacial de 12cm, assim como as geometrias das edificações à disposição no GeoSampa. Para comparar as regiões, vamos utilizar aprendizagem por redes neurais produndas U-Net a partir das edificações restituidas em 2004 em áreas que são consideradas favelas e então identificar as áreas faltantes podendo assim comparar com o Modelo de altura das edificações das mesmas áreas levantadas em 2017.

## Resultados

Os resultados, assim que processados ficarão à disposição na pasta resultados

## Referências

* https://geoscripting-wur.github.io/PythonRaster/
* 
