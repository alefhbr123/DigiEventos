<div align="center">
<img src="Logo_DigiEventos.png" alt="Logo - DigiEventos" width="200" height="200">
</div>

## Objetivo:
O objetivo principal deste projeto é desenvolver um Sistema de Gestão de Eventos e 	Reuniões para o projeto Meninas Digitais – UTFPR-CP. O foco central é otimizar a organização, a 	comunicação e o acompanhamento das atividades, que hoje são feitas de forma descentralizada. 	Essa solução vai combater a dispersão de informações, o retrabalho e a dificuldade de gerenciar o 	crescimento do projeto.

## Alunos:
- Álefh Trindade Luz de Lima - Júnior - alefhlima@alunos.utfpr.edu.br 
- Pedro Augusto da Silva Morais - Júnior - pedroaugustomorais@alunos.utfpr.edu.br 
- Fábio Massashi Suzuki - Júnior - suzukif.2023@alunos.utfpr.edu.br 
- Vitor Barbosa Hilário - Pleno - vitorhilario@alunos.utfpr.edu.br
- Gabriel Batistela da Silva - gabrielbatistela@alunos.utfpr.edu.br

## ***Requisitos funcionais***

|Identificador| Descrição| Prioridade|
| -------- | -------- | -------- |
|RF01| Permitir a criação de eventos com informações como nome, descrição, data, local.| Alta|
|RF02| Permitir a edição e exclusão de eventos por organizadores autorizados (Administrador).| Alta|
|RF03| Suportar a categorização de eventos (palestras, workshops, seminários).| Alta|
|RF04| Permitir limitar a capacidade máxima de participantes por evento.| Média|
|RF05| Permitir que usuários realizem inscrição em eventos via plataforma.| Alta|
|RF06| Permitir cancelamento de inscrição pelo participante.|Baixa|
|RF07| Permitir criação e edição de perfil do usuário com informações pessoais e profissionais.|Baixa|
|RF08| Exibir eventos inscritos, históricos e recomendações personalizadas no perfil.| Média|
|RF09| Permitir que participantes visualizem perfis de outros inscritos em eventos.| Baixa|
|RF10| Oferecer recomendações personalizadas de eventos e palestras com base no perfil e histórico do usuário.|Baixa|
|RF11| Exibir agenda personalizada com base nas inscrições do participante.|Alta|
|RF12| Permitir compartilhamento de eventos em redes sociais (Facebook, Instagram).|Média|

## ***Requisitos não funcionais***

|Identificador| Descrição| Tipo|
| -------- | -------- | -------- |
|RNF01| Autenticação por token JWT com sessão de 24 horas. Bloquear login após 5 tentativas incorretas por 15 minutos.| Segurança|
|RNF02| Design responsivo para celular, tablet e desktop. Compatível com Chrome, Firefox e Safari. | Usabilidade|
|RNF03| Compressão automática de imagens até 500KB. Carregamento sob demanda para otimizar velocidade.| Performance|
|RNF04| Suportar 500 usuários simultâneos com resposta em 3 segundos. Manter estabilidade durante picos de acesso.|Performance|
|RNF05| HTTPS obrigatório e proteção contra ataques básicos. Rate limiting de 100 requisições por minuto por usuário.|Segurança|
|RNF06| Conformidade com LGPD e termo de consentimento. Permitir exclusão e download de dados pessoais.| Privacidade|
|RNF07| Cache para consultas frequentes de eventos. Consultas SQL otimizadas em menos de 1 segundo.| Performance| 
|RNF08| Contraste mínimo 4.5:1 e navegação por teclado. Fontes legíveis e interface acessível básica.| Acessibilidade|
|RNF09| API REST documentada com autenticação. Códigos HTTP padronizados e versionamento simples. |Interoperabilidade|
