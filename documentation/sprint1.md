# Via Livre SJC - Monitoramento de Tráfego Inteligente

# Documentação - Sprint 1

<p align="center">
      <img src="../assets/SteamDucksLogo.png" alt="logo da Steam Ducks" width="200">
      <h2 align="center"> Steam Ducks</h2></p>

<p align="center">
  | <a href ="#desafio"> Desafio</a>  |
  <a href ="#us"> User Stories</a>  |   
  <a href ="#dor">DoR</a>  |
  <a href ="#dod">DoD</a>  |
  <a href ="#equipe"> Equipe</a> |
</p>


## 🏅 Desafio <a id="desafio"></a>

Implementar a base do sistema de monitoramento de tráfego, estabelecendo a fundação para ingestão de dados CSV, cadastro de regiões geográficas e cálculo inicial de indicadores. Foi necessário criar a estrutura do banco de dados, implementar o ETL para processamento dos dados de tráfego e estabelecer as regiões fixas da cidade com seus respectivos polígonos GeoJSON, consolidando a base para o dashboard de monitoramento nas próximas sprints.

## 📋 User Stories <a id="us"></a>

| Rank | Prioridade | User Story                                                                                                                                                   | Story Points | Sprint | Requisito do Cliente | Status |
| :--: | :--------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | :----------: | :----: | :------------------: | :----: |
|  1   |    Alta    | Como Administrador, quero importar e validar CSV, tratando os dados e registrando no banco para que seja possível gerar análises precisas de tráfego                                             |      8       |   1    |         RF1          |   🔄   |
|  2   |    Alta    | Como Administrador, quero registrar e delimitar regiões fixas no mapa da cidade, com polígonos pré-definidos (GeoJSON) para organizar o monitoramento por áreas específicas                                          |      5       |   1    |      RF2, RF4        |   🔄   |
|  3   |    Alta    | Como Administrador, quero calcular indicadores por região (velocidade média, volume, % congestão, etc.) para fornecer métricas objetivas de desempenho                                                          |     13       |   1    |      RF2, RF3        |   🔄   |
|  4   |    Alta    | Como Gestor Geral, quero visualizar índice geral da cidade em card destacado para ter uma visão consolidada da situação do tráfego municipal                                                                               |      5       |   1    |      RF2, RF3        |   🔄   |

## 🏅 DoR - Definition of Ready <a id="dor"></a>

|             Critério             | Descrição                                                                                         |
| :------------------------------: | ------------------------------------------------------------------------------------------------- |
|       Clareza na Descrição       | A User Story está escrita no formato "Como [persona], quero [ação] para que [objetivo]"           |
| Critérios de Aceitação Definidos | A história possui critérios objetivos que indicam o que é necessário para considerá-la concluída. |
| Cenários de Teste Especificados  | A história tem pelo menos 1 cenário de teste estruturado (Dado, Quando, Então).                   |
|           Independente           | A história pode ser implementada sem depender de outra tarefa da mesma Sprint.                    |
|    Compreensão Compartilhada     | Toda a equipe (incluindo PO e devs) compreende o propósito da história.                           |
|            Estimável             | A história foi pontuada no Planning Poker ou tem uma estimativa clara.                            |
|       Documentos de Apoio        | Se necessário, mockups, fluxos ou modelos de dados estão anexados ou referenciados.               |
|   Critérios técnicos acordados   | As necessidades de Frontend e Backend foram claramente separadas (quando aplicável).              |

## 🏅 DoD - Definition of Done <a id="dod"></a>

|                 Critério                 | Descrição                                                                            |
| :--------------------------------------: | ------------------------------------------------------------------------------------ |
|     Critérios de Aceitação atendidos     | Todos os cenários de teste da história foram executados e aprovados.                 |
|        Testes manuais realizados         | Onde aplicável, os dados são corretamente armazenados e recuperáveis.               |
|             Código revisado              | O código foi revisado por pelo menos um colega de equipe.                            |
|     Documentação interna atualizada      | Foi atualizado o que for necessário: API, estrutura de dados, endpoints, etc.        |
|  Integração com outras partes testadas   | As interfaces entre Frontend e Backend foram validadas.                              |
| Build/Testes automatizados (se aplicável) | A funcionalidade não quebra a aplicação e passa nos testes automatizados existentes. |
|             Validação do PO              | O Product Owner validou a entrega com base nos critérios definidos.                  |
|            Pronto para deploy            | O item está testado, validado e pode ser integrado ao produto final.                 |

## 👥 Equipe <a id="equipe"></a>

| LinkedIn & GitHub | Integrantes | Função        |
|-------------------|-------------|---------------|
| <a href="https://www.linkedin.com/in/lucas-h-acosta?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app" target="_blank"><img src="https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Linkedin"></a> <a href="https://github.com/Lucas-heck-acosta" target="_blank"><img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>      | Lucas Acosta      | Product Owner |
| <a href="https://www.linkedin.com/posts/cruz-rafaella_%C3%A9-um-prazer-compartilhar-que-finalizei-meu-activity-7212665413376081921-mEAy?utm_source=share&utm_medium=member_desktop" target="_blank"><img src="https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Linkedin"></a> <a href="https://github.com/arafaellacruz" target="_blank"><img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a> | Rafaella Cruz     | Scrum Master  |
| <a href="https://www.linkedin.com/in/alexander-silva-lima-96a0432a6?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank"><img src="https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Linkedin"></a> <a href="https://github.com/alexttz" target="_blank"><img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>   | Alexander Silva  | Dev Team      |
| <a href="https://www.linkedin.com/in/carlos-daniel-9516952b4/" target="_blank"><img src="https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Linkedin"></a> <a href="https://github.com/darloscaniel" target="_blank"><img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a> | Carlos Daniel     | Dev Team      |
| <a href="https://www.linkedin.com/in/felipe-reiss/" target="_blank"><img src="https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Linkedin"></a> <a href="https://github.com/felpzreiz" target="_blank"><img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>   | Felipe Reis      | Dev Team      |
| <a href="https://www.linkedin.com/in/isabelly-sousa?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank"><img src="https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Linkedin"></a> <a href="https://github.com/61isabelly" target="_blank"><img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>               | Isabelly Sousa    | Dev Team      |
| <a href="https://www.linkedin.com/in/luiz-henrique-rabello-ferreira-3600752ba?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank"><img src="https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Linkedin"></a> <a href="https://github.com/LuizHRFerreira" target="_blank"><img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a> | Luiz Henrique     | Dev Team      |
| <a href="https://www.linkedin.com/in/samuel-prado-9142381b6?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app" target="_blank"><img src="https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Linkedin"></a> <a href="https://github.com/Samuelprado99" target="_blank"><img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>  | Samuel Prado      | Dev Team      |

## 🎯 MVP 

O MVP da Sprint 1 concentra-se na **estrutura fundamental** e na **inteligência** para o monitoramento de tráfego.


---

<div align="center">
    <img src="../assets/footer.png" alt="footer" width="100%" />
</div>
