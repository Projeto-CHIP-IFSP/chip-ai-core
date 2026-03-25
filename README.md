# 🧠 Projeto CHIP | Core AI & Lógica

> Repositório oficial do Cérebro (IA) do ecossistema CHIP. Desenvolvido para o 3º semestre de Ciência da Computação (IFSP).

## 📖 Sobre o Projeto CHIP
O CHIP é um ecossistema de assistência ao estudo focado em produtividade e bem-estar digital. O diferencial do projeto é a hibridez: o sistema opera tanto como um robô físico de companhia (IoT) quanto como um aplicativo autônomo (Mobile), unificados por uma inteligência artificial compartilhada e gamificação.

## 🎯 O que este repositório faz?
Este repositório contém o backend lógico e os modelos de Visão Computacional. 
**Responsabilidades da Squad:**
* Coleta de dataset de faces.
* Treinamento do modelo de detecção de emoções (TensorFlow/Keras).
* Otimização e exportação para `.tflite` (para uso no Mobile e no Robô).
* Criação do script Python principal ("Máquina de Estados").

## 👥 A Equipe (Squad 1 - IA)
* Gustavo Ferreira 
* Murilo Rodrigues 
* Rafaella Ribeiro
* Vinicius Kenji 

## 🛠️ Stack Tecnológica
* **Linguagem:** Python 
* **Bibliotecas Principais:** OpenCV, TensorFlow, Jupyter 

## 🚦 Padrões de Desenvolvimento (Git & Jira)
Para manter nosso código limpo e integrado com o Jira, siga estas regras:

1. **Nunca faça commits direto na `main`.** Todo código deve vir de um Pull Request.
2. **Nomenclatura de Branches:** Use o código da tarefa do Jira + um breve descritivo.
   * *Exemplo:* `feat/SCRUM-12-treinamento-modelo` ou `fix/SCRUM-5-erro-opencv`
3. **Nomenclatura de Commits:** Use *Conventional Commits*.
   * `feat: adiciona detecção de olhos`
   * `fix: corrige crash na captura de vídeo`
   * `docs: atualiza dependências do python`
