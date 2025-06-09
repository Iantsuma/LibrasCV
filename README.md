# LibrasCV

## Pré-requisitos
1. Ter um sistema de Python Notebook/Google Colab.
2. Contar com uma webcam.
3. Executar as primeiras duas células do notebook.
  
## Funcionalidades básicas
- Leitura de Gestos:
  - Executar a célula que irá carregar o modelo (penúltima do notebook) abaixo de 
  - Executar a célula "Leitura de Sinais propriamente dita"
- Treinar o modelo:
  - Caso deseje treinar o modelo em si, altere a célula "Definição de Sinais (actions)", execute-a e execute a célula "Criação de pastas (se não existirem)"
  - Execute então a célula "Capturando Keypoints para Treinamento". O programa irá iterar sobre cada sinal 30x, coletando suas informações.
  - Finalmente, execute a célula "Pre-processamento e treino do modelo" para treinar o modelo em si. Caso haja necessidade, sinta-se livre para interromper o treinamento em caso de acurácia suficiente.
