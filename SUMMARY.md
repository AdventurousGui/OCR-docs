# Table of contents

* [Manual de Utilizador](README.md)
  * [Site do Serviço OCR](https://iris.sysresearch.org/ocr/)
  * [Source Code](https://github.com/stjiris/OCR)

## Sobre o Serviço <a href="#sobre" id="sobre"></a>

* [Sobre o Serviço](sobre/sobre-o-servico.md)
* [Ficheiros Suportados](sobre/ficheiros-suportados.md)
* [Resultados Disponíveis](sobre/resultados-disponiveis.md)

## Usar o Serviço <a href="#tutorial" id="tutorial"></a>

* [Realizar OCR no espaço público](tutorial/realizar-ocr-no-espaco-publico.md)
* [Realizar OCR num espaço privado](tutorial/realizar-ocr-num-espaco-privado.md)
* [Configurar OCR](tutorial/configurar-ocr.md)
* [Segmentar o Documento](tutorial/segmentar-o-documento.md)
* [Editar os Resultados](tutorial/editor.md)
* [Realizar OCR de uma pasta](tutorial/realizar-ocr-de-uma-pasta.md)

## Administração <a href="#manual-admin" id="manual-admin"></a>

* [Manual do Administrador](manual-admin/manual-do-administrador.md)

## Referência da API Simplificada <a href="#api-reference" id="api-reference"></a>

* ```yaml
  type: builtin:openapi
  props:
    models: false
  dependencies:
    spec:
      ref:
        kind: openapi
        spec: ocr-api
  ```
