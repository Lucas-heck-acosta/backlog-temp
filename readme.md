# <p align="center"> Shrek Transit SJC – Monitoramento de Tráfego Inteligente</p>

Portal para consolidação de indicadores de mobilidade, atribui **níveis por região** e dispara **alertas vinculados a protocolos de ação**. Projeto proposto para atender a Prefeitura de São José dos Campos.

<p align="center"> <a href="#integrantes-da-equipe">👥 Integrantes da Equipe</a> • <a href="#descricao-do-desafio">📝 Descrição do Desafio</a> • <a href="#objetivo-do-projeto">🎯 Objetivo do Projeto</a> • <a href="#requisitos-funcionais">📋 Requisitos Funcionais</a> • <a href="#cronograma">📅 Cronograma</a> • <a href="#backlog-do-produto">🗂️ Backlog do Produto</a> • <a href="#indicadores-e-notas">📊 Indicadores & Notas</a> • <a href="#alertas-e-protocolos">🚨 Alertas & Protocolos</a> • <a href="#documentacao">📚 Documentação</a> • <a href="#tecnologias-utilizadas">🛠️ Tecnologias Utilizadas</a> </p>

<br>
<br><div style="display: flex; justify-content: center; gap: 80px; align-items: center; margin-top: 20px; margin-bottom: 20px;">
    <img src="./assets/SteamDucksLogo.png" alt="Logotipo Steam Ducks" width="40%">
    <img src="./assets/bandeira-sjc.png" alt="Bandeira São José dos Campos" width="40%">
</div>

<br>


## <a id="integrantes-da-equipe">Integrantes da Equipe</a>

| LinkedIn & GitHub | Integrantes | Função        |
|-------------------|-------------|---------------|
| <a href="https://www.linkedin.com/in/alexander-silva-lima-96a0432a6?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank"><img src="https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Linkedin"></a> <a href="https://github.com/alexttz" target="_blank"><img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>   | Alexander Silva  | Dev Team      |
| <a href="https://www.linkedin.com/in/carlos-daniel-9516952b4/" target="_blank"><img src="https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Linkedin"></a> <a href="https://github.com/darloscaniel" target="_blank"><img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a> | Carlos Daniel     | Dev Team      |
| <a href="https://www.linkedin.com/in/felipe-reiss/" target="_blank"><img src="https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Linkedin"></a> <a href="https://github.com/felpzreiz" target="_blank"><img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>   | Felipe Reis      | Dev Team      |
| <a href="https://www.linkedin.com/in/isabelly-sousa?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank"><img src="https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Linkedin"></a> <a href="https://github.com/61isabelly" target="_blank"><img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>               | Isabelly Sousa    | Dev Team      |
| <a href="https://www.linkedin.com/in/lucas-h-acosta?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app" target="_blank"><img src="https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Linkedin"></a> <a href="https://github.com/Lucas-heck-acosta" target="_blank"><img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>      | Lucas Acosta      | Product Owner |
| <a href="https://www.linkedin.com/in/luiz-henrique-rabello-ferreira-3600752ba?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank"><img src="https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Linkedin"></a> <a href="https://github.com/LuizHRFerreira" target="_blank"><img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a> | Luiz Henrique     | Dev Team      |
| <a href="https://www.linkedin.com/posts/cruz-rafaella_%C3%A9-um-prazer-compartilhar-que-finalizei-meu-activity-7212665413376081921-mEAy?utm_source=share&utm_medium=member_desktop" target="_blank"><img src="https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Linkedin"></a> <a href="https://github.com/arafaellacruz" target="_blank"><img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a> | Rafaella Cruz     | Scrum Master  |
| <a href="https://www.linkedin.com/in/samuel-prado-9142381b6?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app" target="_blank"><img src="https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Linkedin"></a> <a href="https://github.com/Samuelprado99" target="_blank"><img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>  | Samuel Prado      | Dev Team      |


---
## 📒 <a id="descricao-do-desafio">Descrição do Desafio</a>

A Prefeitura de São José dos Campos necessita de uma solução que:

* **Monitore indicadores e parâmetros** de controle previamente definidos;
* **Gere alertas automáticos** no sistema, **vinculados a protocolos de ação**;
* **Permita resposta dos gestores** aos alertas, registrando providências e encerrando o chamado.


---

## 🎯 <a id="objetivo-do-projeto">Objetivo do Projeto</a>
O objetivo do projeto é construir um sistema de monitoramento contínuo do tráfego urbano, oferecendo uma visão ampla e detalhada da situação da cidade em tempo real. A plataforma permitirá a visualização de indicadores de desempenho por região e também de um índice consolidado geral da cidade, apresentados em mapas interativos e cards informativos. Além disso, o sistema será capaz de detectar e notificar automaticamente alterações críticas no tráfego, garantindo respostas rápidas a situações emergenciais. Cada nota ou nível atribuído será transparente, permitindo ao usuário acessar o detalhamento dos indicadores que compõem a avaliação. Por fim, a solução possibilitará que gestores respondam a determinados alertas, registrando suas ações e encerrando ocorrências de forma organizada e rastreável.


---

## 📋 <a id="requisitos-funcionais">Requisitos Funcionais</a>

| **ID** | **Funcionalidade**                  | **Descrição**                                                                                          |
|:------:|:------------------------------------|:-------------------------------------------------------------------------------------------------------|
|  RF1   | **Tratamento de Dados**             | Processar os dados recebidos em planilha CSV, validando, limpando e transformando para uso no sistema. |
|  RF2   | **Indicadores de Tráfego**          | Criar métricas de acompanhamento do tráfego, como velocidade média, volume e variação por região.      |
|  RF3   | **Níveis de Monitoramento**         | Estabelecer níveis de classificação para avaliar as regiões.                                           |
|  RF4   | **Dashboard com Georreferenciado**  | Exibir o tráfego de forma simples e lúdica, com mapas interativos e cards representando as regiões.    |
|  RF5   | **Dados Externos Complementares**   | Possibilitar a integração de fontes de dados externas que enriqueçam a análise do tráfego.             |
|  RF6   | **Sistema de Alertas e Protocolos** | Disparar notificações automáticas em caso de mudanças críticas e permitir o acionamento de protocolos. |


---

## 📆 <a id="cronograma">Cronograma</a>

| Fase                     | Início     | Entrega    | Status |
|--------------------------|------------|------------|--------|
| Kick off                 | 25/08/2025 | 29/08/2025 | ✅      | 
| Sprint 1                 | 08/09/2025 | 28/09/2025 | 🔄     | 
| Sprint Review / Planning | 29/09/2025 | 03/10/2025 | ❌      | 
| Sprint 2                 | 06/10/2025 | 26/10/2025 | ❌      | 
| Sprint Review / Planning | 27/10/2025 | 31/10/2025 | ❌      | 
| Sprint 3                 | 03/11/2025 | 23/11/2025 | ❌      | 
| Sprint review            | 24/11/2025 | 28/11/2025 | ❌      | 
| Feira de Soluções        | 04/12/2025 | 04/12/2025 | ❌      | 

---

## 🗂️ <a id="backlog-do-produto">Backlog do Produto</a>

| **Rank** | **Prioridade** | **Como**                 | **User Story**                                                                                     | **Estimativa (SP)** | **Sprint** | **Dependência** | **Requisito** |
|:--------:|:--------------:|:-------------------------|:---------------------------------------------------------------------------------------------------|:-------------------:|:----------:|:---------------:|:-------------:|
|    1     |      Alta      | **Sistema**              | Importar e validar CSV, tratando os dados e registrando no banco para geração das análises         |          8          |     1      |        -        |      RF1      |
|    2     |      Alta      | **Sistema**              | Registrar e delimitar **regiões fixas** no mapa da cidade, com polígonos pré-definidos (GeoJSON)   |          5          |     1      |        1        |   RF2, RF4    |
|    3     |      Alta      | **Sistema**              | Calcular indicadores por região (velocidade média, volume, % congestão, etc.)                      |         13          |     1      |      1, 2       |   RF2, RF3    |
|    4     |      Alta      | **Gestor Geral**         | Visualizar **índice geral da cidade** em card destacado                                            |          5          |     1      |        2        |    RF2,RF3    |
|    5     |      Alta      | **Gestor Local**         | Visualizar **nível da sua(s) região(ões)** em cards                                                |          5          |     2      |        2        |    RF3,RF4    |
|    6     |      Alta      | **Gestor Geral / Local** | Visualizar **mapa simplificado** com cores por região e filtros interativos                        |         13          |     2      |      2, 3       |      RF4      |
|    7     |     Média      | **Gestor Geral**         | Criar / Configurar **Gestores locais** e **regras de alerta** por mudança de nível/indicador       |          5          |     2      |        2        |      RF6      |
|    8     |     Média      | **Gestor Geral / Local** | Acessar seção com indicadores detalhados que compõem a nota geral e local                          |          5          |     2      |      2, 3       |      RF2      |
|    9     |      Alta      | **Gestor Geral**         | Receber **alertas críticos** de mudanças de nível da cidade                                        |          8          |     3      |      3, 4       |      RF6      |
|    10    |     Média      | **Gestor Local**         | Receber **alertas críticos da sua região**                                                         |          5          |     3      |      2, 3       |      RF6      |
|    11    |     Baixa      | **Sistema**              | Permitir integração de **dados externos** para complementar análise                                |          8          |     3      |        -        |      RF5      |
|    12    |     Baixa      | **Cidadão**              | Visualizar **portal público** com mapa simplificado e índice geral da cidade (sem login)           |          3          |     3      |      5, 7       |      RF4      |


---


## 📊 <a id="indicadores-e-notas">Indicadores & Notas</a>

**Indicadores propostos :**
...
---

## 🚨 <a id="alertas-e-protocolos">Alertas & Protocolos</a>

**Gatilhos de alerta**
...

**Protocolos** (exemplo)
...

---

## 📃 <a id="documentacao">Documentação</a>

* **Manual do Usuário**
* **Dados CSV**
* **Regras de Cálculo** (fórmulas e pesos)
* **Planejamento por Sprint** (objetivos e critérios de aceite)
* **Burndown & Métricas de Entrega**

---

##  🛠️ <a id="tecnologias-utilizadas">Tecnologias Utilizadas</a>

### **Back-end**

* **Java 17**
* **Spring Boot**
* **Maven**
* **Oracle**

### **Front-end**

* **Vue.js 3**
* 
### **Infra**

* **Docker**
* **Git/GitHub**

---

<div align="center">
    <img src="assets/footer.png" alt="footer" width="100%" />
</div>
