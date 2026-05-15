# Esteira de Machine Learning — Poker Hand Dataset

Este projeto foi desenvolvido para a disciplina de Inteligência Artificial do curso de Análise e Desenvolvimento de Sistemas. O objetivo é implementar uma esteira (pipeline) completa de aprendizado de máquina, desde a preparação dos dados até a avaliação e predição de um modelo de classificação.

## 🃏 Sobre o Dataset
O **Poker Hand Dataset** (UCI Machine Learning Repository) consiste em classificar mãos de poker com base em 5 cartas. Cada carta possui um naipe (1-4) e um valor (1-13). O objetivo é prever a classe da mão (de 0 a 9, onde 9 é um Royal Flush).

## 🚀 Requisitos do Projeto
A esteira de dados cumpre os seguintes requisitos:
1. **Estatísticas Descritivas:** Análise geral da base de dados.
2. **Transformação de Colunas:** Engenharia de atributos (7 novas features criadas).
3. **Transformação de Linhas:** Remoção de duplicatas para limpeza da base.
4. **Divisão de Dados:** Separação em Treino (70%), Validação (15%) e Teste (15%) com técnica de hold-out estratificado.
5. **Treinamento e Avaliação:** Uso do algoritmo **Random Forest** com avaliação via Acurácia e Matriz de Confusão.
6. **Predição:** Demonstração do modelo em funcionamento com novos dados.

## 🛠️ Tecnologias Utilizadas
* Python 3.12+
* Pandas e NumPy (Manipulação de dados)
* Scikit-Learn (Machine Learning)
* Matplotlib e Seaborn (Visualização)
* Google Colab (Ambiente de execução)

## 📋 Como Reproduzir (Passo a Passo)

Como o projeto utiliza arquivos de dados externos, siga estas etapas no **Google Colab**:

1.  **Acesse o Colab:** Abra o arquivo `poker_hand_ml_pipeline.ipynb` no Google Colab.
2.  **Upload dos Dados:** No menu lateral (ícone de pasta), faça o upload dos arquivos:
    * `poker-hand-training-true.data`
    * `poker-hand-testing.data`
3.  **Execução:** Clique em `Ambiente de Execução` > `Executar tudo`.
4.  **Resultados:** As estatísticas, a matriz de confusão e as predições serão geradas automaticamente ao final do notebook.

## 📊 Resultados Obtidos
* **Acurácia no Teste:** ~98.68%
* **Total de Exemplos Únicos:** 238,535
* **Modelo:** RandomForestClassifier (ajustado para classes desbalanceadas).

---
**Autor:** Adalberto  
**Data:** Maio de 2026
