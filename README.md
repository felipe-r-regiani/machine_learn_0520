# machine_learn_0520

Este repositório é focado no estudo e implementação do **Perceptron**, a unidade fundamental das Redes Neurais Artificiais, explorando o treinamento supervisionado para problemas de classificação linearmente separáveis.

## 📂 Conteúdo

* **train_dataset[1-3].csv**: Conjuntos de dados utilizados para o treinamento do modelo em diferentes cenários de complexidade.
* **test_dataset[1-3].csv**: Dados reservados para a validação e teste da capacidade de generalização do Perceptron.
* **perceptron.ipynb**: Notebook que contém a implementação da arquitetura do Perceptron e a análise de convergência. O projeto abrange:
    - **Inicialização de Pesos**: Configuração aleatória ou zerada dos parâmetros do modelo.
    - **Regra de Aprendizagem**: Implementação do ajuste de pesos baseado no erro e na taxa de aprendizagem (Learning Rate).
    - **Análise de Cenários**: Comparação de desempenho variando o número de épocas e taxas de aprendizado (0.01 a 0.0001).
    - **Visualização do Erro**: Gráficos que demonstram a evolução do erro médio ao longo das iterações de treinamento.

## 🛠️ Tecnologias e Bibliotecas

As ferramentas centrais utilizadas neste projeto são:

* **Python 3**: Linguagem base.
* **NumPy**: Operações vetoriais e matriciais para o cálculo do somatório e atualização de pesos.
* **Matplotlib**: Plotagem de gráficos de evolução do erro e visualização das classes.
* **CSV**: Manipulação dos datasets de treino e teste.
* **Jupyter Notebook**: Ambiente para execução dos testes e análise dos cenários.

## 🚀 Como começar

1.  Clone este repositório:
    ```bash
    git clone https://github.com/felipe-r-regiani/machine_learn_0520.git
    ```
2.  Instale as bibliotecas necessárias:
    ```bash
    pip install numpy matplotlib
    ```
3.  Execute o notebook:
    - Abra o `perceptron.ipynb`.
    - Analise os diferentes cenários de treinamento para observar como a **Taxa de Aprendizagem** influencia a velocidade e a estabilidade da convergência do modelo.
