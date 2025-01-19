# CLASSIFICAÇÃO DE DIFERENTES TIPOS DE USOS DE EDIFICAÇÕES URBANAS: UMA ABORDAGEM POR APRENDIZADO PROFUNDO E IMAGENS 360°


Este repositório contém os códigos, os dados e os principais resultados do TCC intitulado “CLASSIFICAÇÃO DE DIFERENTES TIPOS DE USOS DE EDIFICAÇÕES URBANAS: UMA ABORDAGEM POR APRENDIZADO PROFUNDO E IMAGENS 360°”.

* Discente: Rafael Antunes Pereira
* Orientador: Prof. Darlan Miranda Nunes

O Fluxograma seguinte ilustra o processo completo da metodologia proposta:
![medologia para classificação de diferentes tipos de edificações em imagens 360º](Figs/fluxograma_330dpi.png)


## Estrutura de pastas

1. **Extracao_Imagens.ipynb** - Este notebook realiza a extração das imagens necessárias para o treinamento e teste dos modelos. Certifique-se de executá-lo primeiro para obter os dados de imagem essenciais.

2. **Treinando_Modelos.ipynb** - Neste notebook, você usará as imagens extraídas para treinar o modelo de detecção. Ele configura e treina o modelo, utilizando as imagens processadas na etapa anterior.

3. **Testando_Modelos.ipynb** - Por último, este notebook testa o modelo treinado, avaliando seu desempenho com base nas imagens de teste.

## Ordem de Execução

1. **Executar o notebook `Extracao_Imagens.ipynb`**
2. **Executar o notebook `Treinando_Modelos.ipynb`**
3. **Executar o notebook `Testando_Modelos.ipynb`**

## Pré-requisitos

Certifique-se de que todas as bibliotecas necessárias estão instaladas. Recomenda-se o uso de um ambiente virtual para facilitar a gestão das dependências.

## Observações

Para evitar problemas com dependências no Git, lembre-se de que este repositório já possui um `.gitignore` configurado para ignorar bibliotecas instaladas localmente.

---

Esse README deve servir de guia rápido para você e outros colaboradores entenderem a estrutura do projeto e a sequência de execução dos notebooks.
