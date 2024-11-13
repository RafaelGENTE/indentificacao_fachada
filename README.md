# Projeto de Detecção de Fachadas

Este repositório contém notebooks para um projeto de detecção e classificação de fachadas em imagens. O projeto envolve três etapas principais: extração das imagens, treinamento de modelos e teste dos modelos. Siga a ordem abaixo para garantir o funcionamento adequado do pipeline.

## Estrutura do Projeto

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
