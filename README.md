<div align="center">
<img src="Logo_DigiEventos.png" alt="Logo - DigiEventos" width="200" height="200">
</div>

## Objetivo:
O objetivo principal deste projeto é desenvolver um Sistema de Gestão de Eventos e 	Reuniões para o projeto Meninas Digitais – UTFPR-CP. O foco central é otimizar a organização, a 	comunicação e o acompanhamento das atividades, que hoje são feitas de forma descentralizada. 	Essa solução vai combater a dispersão de informações, o retrabalho e a dificuldade de gerenciar o 	crescimento do projeto.

## Alunos:
- Álefh Trindade Luz de Lima - alefhlima@alunos.utfpr.edu.br 
- Pedro Augusto da Silva Morais - pedroaugustomorais@alunos.utfpr.edu.br 
- Fábio Massashi Suzuki - suzukif.2023@alunos.utfpr.edu.br 
- Vitor Barbosa Hilário - vitorhilario@alunos.utfpr.edu.br
- Gabriel Batistela da Silva - gabrielbatistela@alunos.utfpr.edu.br

## ***Requisitos funcionais***

| Código   | Requisito Funcional                                                                                                                                               | Prioridade |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| **RF01** | O sistema deve permitir que o **Administrador cadastre eventos**, incluindo nome, descrição, data, horário e local.                                               | Alta       |
| **RF02** | O sistema deve permitir que o **Administrador edite e exclua eventos** existentes, garantindo que apenas organizadores autorizados realizem essas ações.          | Alta       |
| **RF03** | O sistema deve permitir que o **Administrador gerencie usuários**, incluindo cadastro, edição, ativação e desativação de contas.                                  | Alta       |
| **RF04** | O sistema deve permitir que o **Administrador defina a capacidade máxima de participantes por evento**, bloqueando novas inscrições quando o limite for atingido. | Média      |
| **RF05** | O sistema deve permitir que **usuários realizem inscrições em eventos** diretamente pela plataforma.                                                              | Alta       |
| **RF06** | O sistema deve permitir que **participantes cancelem suas inscrições** em eventos antes da data de realização.                                                    | Baixa      |
| **RF07** | O sistema deve permitir que o **usuário atualize seu perfil**, informando dados pessoais e profissionais relevantes.                                              | Baixa      |
| **RF08** | O sistema deve **exibir ao usuário seus eventos inscritos, histórico de participação e recomendações personalizadas** com base em seu perfil.                     | Média      |
| **RF09** | O sistema deve permitir que **participantes visualizem o perfil básico de outros inscritos** em um mesmo evento.                                                  | Baixa      |
| **RF10** | O sistema deve exibir uma **agenda personalizada ao participante**, consolidando os eventos nos quais está inscrito.                                              | Alta       |
| **RF11** | O sistema deve permitir a **categorização de eventos** em tipos como palestras, workshops e seminários.                                                           | Alta       |


## ***Requisitos não funcionais***

| Identificador | Requisito Não Funcional                                                                                                                                               | Categoria          |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ |
| **RNF01**     | O sistema deve usar **login com token JWT** válido por 24h. Após 5 tentativas erradas, o usuário fica bloqueado por 15 minutos.                                       | Segurança          |
| **RNF02**     | O sistema deve ter **design responsivo**, funcionando bem em celular, tablet e computador. Deve ser compatível com os navegadores Chrome, Firefox e Safari.           | Usabilidade        |
| **RNF03**     | O sistema deve **comprimir imagens automaticamente** até 500KB e usar **carregamento sob demanda** para não deixar a navegação lenta.                                 | Performance        |
| **RNF04**     | O sistema deve suportar **até 500 usuários ao mesmo tempo**, com resposta em até 3 segundos, mesmo em horários de pico.                                               | Performance        |
| **RNF05**     | O sistema deve usar **HTTPS obrigatório** e proteger contra ataques básicos (SQL Injection, XSS, CSRF). Cada usuário pode fazer no máximo 100 requisições por minuto. | Segurança          |
| **RNF06**     | O sistema deve estar de acordo com a **LGPD**, pedindo consentimento de uso de dados e permitindo que o usuário **baixe ou exclua suas informações**.                 | Privacidade        |
| **RNF07**     | O sistema deve ter **cache para consultas repetidas** e consultas no banco de dados devem levar **menos de 1 segundo**.                                               | Performance        |
| **RNF08**     | O sistema deve ser **acessível**, com contraste mínimo de 4.5:1, suporte à navegação por teclado e fontes fáceis de ler.                                              | Acessibilidade     |
| **RNF09**     | O sistema deve ter uma **API REST documentada**, com autenticação, uso correto de códigos HTTP e versionamento simples.                                               | Interoperabilidade |

