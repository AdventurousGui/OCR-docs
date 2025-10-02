---
icon: gear
---

# Configurar OCR

{% hint style="info" %}
Não é obrigatório definir uma configuração para realizar a extração de texto.

Os parâmetros predefinidos são aceitáveis para a maioria dos documentos.
{% endhint %}

Para abrir a interface de **Configuração de OCR** de um documento, clique em <kbd>**⋮**</kbd> ou use o **botão direito do rato** para abrir o menu, e selecione <img src="../.gitbook/assets/image (22).png" alt="" data-size="line">

* escolher os **formatos de** **ficheiros de resultados**
* obter resultados com **maior qualidade**

<figure><img src="../.gitbook/assets/image (3) (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
A qualquer momento pode clicar em <img src="../.gitbook/assets/image (43).png" alt="" data-size="line"> para guardar as alterações feitas, ou em <img src="../.gitbook/assets/image (44).png" alt="" data-size="line">  para guardar e sair.
{% endhint %}

{% hint style="info" %}
Num documento com uma configuração de OCR personalizada, a opção do menu é alterada para:<img src="../.gitbook/assets/image (24).png" alt="" data-size="line">
{% endhint %}

***

## Formatos de Resultados

Na coluna da esquerda pode escolher um ou mais formatos de resultado. Os formatos avançados **hOCR** e **ALTO** apenas são produzidos para documentos de uma página.

***

## Línguas

Para **obter melhores resultados**, Na coluna central pode escolher uma ou mais línguas, de acordo com o conteúdo do documento.

{% hint style="warning" %}
Selecione as línguas por ordem de **maior** para **menor importância**.

Por exemplo, num documento em Português com algum texto em Inglês, certifique-se que a seleção é:&#x20;

<kbd>2º Inglês</kbd>

<kbd>1º Português</kbd>
{% endhint %}

***

## Configurações Predefinidas

Os administradores do sistema poderão fornecer **conjuntos predefinidos** de parâmetros. Estes poderão ser escolhidos ao clicar em **Escolher configuração predefinida.**

<figure><img src="../.gitbook/assets/image (49).png" alt="" width="303"><figcaption></figcaption></figure>

***

## Opções Avançadas

Na coluna da direita, um utilizador com conhecimentos do processo de OCR pode ajustar parâmetros avançados.&#x20;

Em particular, é possível escolher entre dois módulos de Tesseract para Python: **TesserOCR** e **Pytesseract.**

{% hint style="danger" %}
O **Pytesseract** é mais lento e, por isso, desaconselhado. Poderá ser removido numa versão futura.
{% endhint %}

Para mais informações sobre estes parâmetros, consultar as seguintes páginas:

{% embed url="https://tesseract-ocr.github.io/tessdoc/" %}

{% embed url="https://muthu.co/all-tesseract-ocr-options/" %}
