# Case IA e Visão Computacional

---

## Descrição
Repositório do projeto desenvolvido de identificação de árvores em fotos de satélites para missão envolvendo drones. O modelo treinado busca classificar as imagens de solo e imagens de árvore.

## Instruções

Todos os algoritmos foram desenvolvidos no ambiente do [Google Colab](https://colab.research.google.com) e recomenda-se executá-los neste ambiente.

* Clone o repositório na sua máquina.

* Faça o upload do notebook a ser executado no ambiente do Google Colab.

* Executando o notebook "XmobotsPSCase_Treinamento.ipynb"

  * Execute o notebook
  
  * Para realizar o upload dos dados, o notebook irá solicitar o upload da pasta (Data.zip).
  
  * Com isto, o treinamento será realizado e terá como saída um arquivo .zip com os logs do Tensorboad e um arquivo .zip com o melhor modelo gerado ("*trees-vs-soil-CNN.h5*").

* Executando o script "XmobotsPSCase_inferencia_de_rede.ipynb"

  * Execute o notebook

  * Para realizar o upload dos dados, o notebook irá solicitar o upload da pasta (Data.zip).

  * Logo em seguida, o notebook irá solicitar o upload do modelo gerado. Deve-se realizar o upload do arquivo "trees-vs-soil-CNN.h5".

  * Com o início do script de inferência propriamente dito, será solicitado o caminho da pasta em que se encontram os dados. Executando através do google colab, o caminho da pasta será: /content/XMB/Data/.

  * Quando o script terminar de executar, as inferências estarão salvas no arquivo "predictions.csv".
