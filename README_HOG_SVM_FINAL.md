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
- Acurácia: 100%
- Precisão: 1.00
- Recall: 1.00
- F1-score: 1.00
- Matriz de Confusão:
  [[2, 0],
   [0, 2]]

## Como Executar
1. Faça upload do notebook `Projeto_HOG_SVM_FINAL_COLAB_OK.ipynb` no Google Colab.
2. Faça upload do arquivo `Projeto_HOG_SVM_ENTREGA.zip` e extraia com o código inicial.
3. Execute todas as células do notebook.
4. O dataset está localizado em `coffee_dataset_corrigido/train/arabica` e `robusta`.

## Link do Repositório
Você pode compactar tudo e subir para seu Google Drive ou GitHub. Exemplo:
https://drive.google.com/drive/folder/SEU-LINK-AQUI

