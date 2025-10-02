---
icon: object-ungroup
---

# Segmentar o Documento

{% hint style="info" %}
Não é obrigatório fazer a segmentação do documento para realizar a extração de texto.
{% endhint %}

Para abrir a interface de **Segmentação** de um documento, clique em <kbd>**⋮**</kbd> ou use o **botão direito do rato** para abrir o menu, e selecione <img src="../.gitbook/assets/image (25).png" alt="" data-size="line">

Esta interface permite:

* **limitar o reconhecimento** a algumas áreas de cada página
* **identificar imagens para extrair** do documento

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
A qualquer momento pode clicar em <img src="../.gitbook/assets/image (43).png" alt="" data-size="line"> para guardar as alterações feitas, ou em <img src="../.gitbook/assets/image (44).png" alt="" data-size="line">  para guardar e sair.
{% endhint %}

{% hint style="info" %}
Num documento já segmentado, a opção do menu é alterada para: <img src="../.gitbook/assets/image (26).png" alt="" data-size="line">
{% endhint %}

***

## Definir áreas na página

{% stepper %}
{% step %}
#### Clique na imagem e arraste para formar um retângulo

A caixa do segmento será sobreposta à imagem e adicionada à lista.

<div><figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
#### Ajuste e redimensione o segmento arrastando os quatro cantos

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### Repita os passos anteriores para as áreas desejadas

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### Termine clicando em <img src="../.gitbook/assets/image (44).png" alt="" data-size="line">
{% endstep %}
{% endstepper %}

***

## Reordenar segmentos

Na lista à direita, **arraste cada linha** usando o ícone à esquerda, colocando-as pela ordem desejada.

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

***

## Extrair imagens

Para **obter as imagens** da página durante o OCR:

{% stepper %}
{% step %}
#### Selecione a área desejada, como descrito [anteriormente](segmentar-o-documento.md#definir-areas-na-pagina)
{% endstep %}

{% step %}
#### Na lista à direita, mude o interruptor do segmento para <img src="../.gitbook/assets/image (21).png" alt="" data-size="line">

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

{% hint style="success" %}
Os segmentos definidos desta forma serão **extraídos** como ficheiros **PNG** e ficarão disponíveis num arquivo **ZIP** após a conclusão do OCR.
{% endhint %}

***

## Definir áreas a ignorar

O interruptor no canto superior direito da tabela proporciona dois modos:

* <img src="../.gitbook/assets/image (32).png" alt="" data-size="line">  - para extrair texto dos segmentos selecionados
* <img src="../.gitbook/assets/image (35).png" alt="" data-size="line"> - para ignorar os segmentos selecionados.

No modo **Ignorar**, os identificadores das caixas mudam do formato **TX.X** para **RX.X**.

<figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
No modo **Ignorar**, os segmentos de **Imagem** serão extraídos sem serem afetados pelos segmentos ignorados.
{% endhint %}

***

## Replicar segmentos

Por vezes os documentos têm uma **estrutura fixa** para todas as páginas, ou incluem **cabeçalhos** repetitivos que se pretende ignorar.

Para **replicar segmentos em todas as páginas**, selecione-os na lista e clique em <img src="../.gitbook/assets/image (37).png" alt="" data-size="line">

{% hint style="success" %}
Qualquer alteração na forma de um segmento replicado será aplicada em todas as outras páginas.
{% endhint %}

***

## Agrupar segmentos

Para **agrupar** segmentos, selecione várias linhas da lista e clique em <img src="../.gitbook/assets/image (38).png" alt="" data-size="line">

{% hint style="info" %}
Um **grupo** de segmentos é representado por uma única linha na tabela, e pode ser reordenado em conjunto, mantendo a sua ordem interna.
{% endhint %}

Para **desagrupar** os segmentos, selecione a linha do **grupo** e clique em <img src="../.gitbook/assets/image (39).png" alt="" data-size="line">

***

## Segmentar automaticamente

Para pedir ao servidor uma segmentação automática de todo o documento, clique em <img src="../.gitbook/assets/image (41).png" alt="" data-size="line"> e aguarde.

{% hint style="warning" %}
Para documentos com um grande número de páginas, o processo pode demorar vários minutos.
{% endhint %}
