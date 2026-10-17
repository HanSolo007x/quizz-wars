# 🎮 Quizz Wars

![Status](https://img.shields.io/badge/Status-Concluído-success)
![Tecnologias](https://img.shields.io/badge/Tecnologias-JavaScript_|_CSS_|_Firebase-blue)
![Deploy](https://img.shields.io/badge/Deploy-Netlify-informational)

## 📌 Sobre o Projeto
O **Quizz Wars** é uma aplicação web interativa de perguntas e respostas focada em raciocínio rápido. O grande diferencial do projeto é o seu **placar global em tempo real (Leaderboard)**, estruturado e integrado na nuvem.

Este projeto foi desenvolvido para colocar em prática conceitos fundamentais de engenharia de *software* no front-end, lógica de programação (JavaScript Vanilla), manipulação do DOM e integração de dados em tempo real utilizando serviços BaaS (Backend as a Service).

🔗 **(https://quizzwars.netlify.app)

## ⚙️ Funcionalidades Principais
- **Mecânica de Jogo Dinâmica:** Interface fluida construída para reatividade imediata aos comandos do utilizador.
- **Integração na Nuvem:** Ligação direta com o **Firebase Realtime Database** para leitura e gravação assíncrona de dados.
- **Leaderboard Global:** Sistema de ranking atualizado em tempo real, onde as pontuações são guardadas, ordenadas (algoritmo de *sorting*) e exibidas para todos os jogadores.
- **Design Responsivo:** Layout estruturado com CSS para se adaptar a diferentes ecrãs.

## 🛠️ Tecnologias Utilizadas
- **JavaScript (ES6+)**: Lógica central de negócio, manipulação do DOM e consumo da API do Firebase.
- **CSS3 / HTML5**: Estruturação semântica e estilização da interface de utilizador.
- **Firebase Realtime Database**: Base de dados NoSQL utilizada para guardar e sincronizar a pontuação dos utilizadores de forma assíncrona.
- **Netlify**: Plataforma utilizada para o *deploy* e alojamento em produção.

## 🧠 Lógica e Raciocínio (Por trás do código)
A principal complexidade resolvida neste projeto foi garantir que as requisições assíncronas ao Firebase fossem tratadas de forma eficiente, para não travar a interface do utilizador enquanto o placar é atualizado. Além disso, a lógica de ordenação do ranking exige um controlo preciso dos dados JSON retornados pela base de dados antes de serem renderizados no ecrã.

## 👨‍💻 Como executar localmente
Se quiser testar a aplicação na sua própria máquina, siga os passos:

1. Clone este repositório:
   ```bash
   git clone [https://github.com/SEU_USUARIO/quizz-wars.git](https://github.com/SEU_USUARIO/quizz-wars.git)