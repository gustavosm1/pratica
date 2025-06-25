
# Projeto Final - Processamento de Imagens

## Aluno
- Gustavo Machado

## Descrição do Projeto
Esse projeto tem como objetivo classificar imagens de grãos de café em duas categorias: arábica e robusta. Para isso, foi utilizada uma abordagem clássica com extração de características usando o descritor HOG e classificação com SVM.

## Descritor Utilizado
O HOG (Histogram of Oriented Gradients) foi escolhido porque é eficiente para capturar bordas e formatos. Ele transforma a imagem em um vetor que representa os padrões de direção dos gradientes.

## Classificador
Utilizei o classificador SVM (Support Vector Machine) com kernel linear. Esse classificador foi escolhido por ser eficaz em tarefas de separação de classes com dados em alta dimensão (como os vetores do HOG).

## Resultados
O modelo foi treinado e testado, e os resultados mostraram boa acurácia. Também foram geradas métricas como matriz de confusão, precisão, recall e F1-score.

## Como Executar
1. Acesse o notebook no Google Colab ou abra o arquivo `Projeto_HOG_SVM_OK_FINAL.ipynb`.
2. Execute todas as células.
3. As imagens são carregadas automaticamente do dataset (duas pastas: arábica e robusta).
4. O modelo é treinado e os resultados são mostrados no final.

## Link do Repositório
[https://github.com/gustavosm1/pratica](https://github.com/gustavosm1/pratica)

## Observação
Todos os arquivos estão no repositório, inclusive o notebook e o dataset corrigido. O vídeo de apresentação também pode ser incluído lá.
