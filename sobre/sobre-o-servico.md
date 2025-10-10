# Sobre o Serviço

## Objetivos

O **serviço de OCR (Reconhecimento Ótico de Caracteres)** permite extrair o texto de digitalizações de documentos.

A aplicação _web_ está atualmente acessível em [https://iris.sysresearch.org/ocr/](https://iris.sysresearch.org/ocr/) e tem como objetivo disponibilizar um serviço de OCR:

* **anónimo** (sem registo de utilizador);
* de uso **expedito e intuitivo**;
* com um **foco em ficheiros de grandes dimensões**;
* com **armazenamento remoto**;
* e com **ferramentas para melhorar a qualidade dos resultados.**

***

A aplicação ser utilizada de duas formas:

* **Espaço público** – acessível a todos os visitantes da página, para OCR de documentos sem requisitos de confidencialidade.
* **Espaços privados** – acessíveis através de um _link_ único, para documentos sensíveis.

{% hint style="danger" %}
Os **espaços privados** criados há mais de **1 dia** são diariamente apagados de forma automática.
{% endhint %}

## Ficheiros Suportados

Atualmente, o serviço permite processar documentos digitalizados nos seguintes formatos:

* PDF
* JPEG
* PNG
* TIFF
* BMP
* GIF
* WebP
* PNM
* JPEG 2000
* ZIP contendo qualquer combinação de formatos aceites, exceto PDF

## Resultados Disponíveis

Para cada documento, é possível obter um ou mais ficheiros de resultados, nos seguintes formatos:

* Ficheiro de texto
* Ficheiro de texto com separadores de página
* PDF com o texto extraído numa camada transparente e pesquisável
* PDF com a camada transparente de texto e um apêndice de índice dos termos extraídos
* CSV com índice e contagem dos termos extraídos
* JSON com as entidades encontradas no texto (obtidas do serviço NER)
* Ficheiro hOCR (apenas para documentos de uma página)
* Ficheiro XML ALTO (apenas para documentos de uma página)
