# Desafio de Reducao de Dimensionalidade em Imagens para Redes Neurais

## Contexto
Este projeto fez parte do desafio proposto no **Bootcamp BairesDev - Machine Learning Practitioner**, cujo objetivo foi aplicar tecnicas de reducao de dimensionalidade em imagens para utilizacao em redes neurais. A tarefa consistia em transformar imagens em diferentes formatos para exploracao de metodos de pre-processamento, tornando-as mais eficientes para treinamento de modelos de aprendizado profundo.

## Objetivo
O desafio envolveu a manipulacao e transformacao de imagens, explorando as seguintes tecnicas:
- Conversao para tons de cinza
- Binarizacao de imagens
- Visualizacao dos resultados no Colab

## Tecnologias e Bibliotecas Utilizadas
- Python
- Numpy (Manipulacao de arrays)
- Matplotlib (Visualizacao de imagens)
- Imageio (Carregamento e salvamento de imagens)

## Como Funciona
1. **Carregamento da Imagem**: A imagem e carregada a partir do arquivo utilizando a biblioteca `imageio`.
2. **Conversao para Tons de Cinza**: Aplicacao da formula de ponderacao dos canais RGB para transformacao da imagem em escala de cinza.
3. **Binarizacao da Imagem**: Aplicacao de um limiar para converter a imagem em uma representacao binaria.
4. **Visualizacao**: Utilizacao do Matplotlib para exibir a imagem original, em tons de cinza e binarizada.

## Como Executar o Codigo
1. Instale as dependencias necessarias:
   ```bash
   pip install imageio numpy matplotlib
   ```
2. Carregue a imagem no ambiente desejado.
3. Execute o script para processar e visualizar as transformacoes.

## Exemplo de Uso
1. O codigo carrega uma imagem chamada `Martinha.jpeg`.
2. Converte a imagem para tons de cinza e posteriormente para formato binario.
3. Salva os resultados como `Tons de cinza.jpg` e `Imagem binaria.jpg`.
4. Exibe graficamente as imagens processadas.

## Melhorias Futuras
- Aplicacao de tecnicas mais avancadas de reducao de dimensionalidade, como PCA.
- Implementacao de compressao de imagens para otimizacao do armazenamento.
- Integracao com redes neurais para testes diretos com modelos pre-treinados.

## Documentacao das Bibliotecas
- Numpy: https://numpy.org/doc/
- Matplotlib: https://matplotlib.org/stable/contents.html
- Imageio: https://imageio.readthedocs.io/en/stable/
