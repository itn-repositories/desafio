# Desafio ITN 2019 - Full-Stack

Este desafio tem como objetivo testar os seus conhecimentos de desenvolvedor fullstack e avaliar a sua forma de codificação e habilidades com as tecnologias propostas.

# Scheduling

![Scheduling](/assets/calendar.png)

Lucas é dentista e vai abrir um consultório odontológico e precisa de um sistema que possibilite criar agendamentos para consulta.

Como Lucas possui outro emprego, só vai estar disponível para atendimento nos dias:

#### Datas disponíveis:

Dias | Período 
:--------- | :------: 
Segunda - Quarta - Sexta | 08:00 às 12:00 Intervalo 13:01 às 18:00
Sábado | 08:00 às 12:00  Intervalo 13:01 às 16:00

O cliente poderá marcar um agendamento somente se o horário estiver disponível. 

Lucas precisa verificar todos os agendamentos marcados do dia. O sistema não deve permitir agendamentos fora do horário pré-definido. 

Lucas precisa de um relatório informando quantas consultas foram marcadas em um determinado período;

Obs: desconsiderar feriados

# Sabendo que cada consulta tem duração de 30 min, deve ser entregue:
* No backend deve ter um endpoint para receber o nome do cliente e a data do agendamento para registrar no sistema.
* No backend deve ter um endpoint para cancelar um agendamento e consequentemente torná-lo disponível para outra pessoal;
* No frontend deve ter uma tela para o cliente realizar o agendamento;
* No frontend deve possuir um calendário para mostrar os agendamentos do dia.
* No Frontend você deve desenvolver uma tela que gere o relatório de agendamentos.

Se a data estiver fora do período disponível, o sistema deve retornar uma mensagem para o cliente informando qual regra ela não se aplica. (Ex: 30/11/2019 - 17:00 Resposta : "O agendamento só está disponível até às 16hs no sábado");

# Instruções 
* [Obrigatório] disponibilizar o link do github para: contato@timeitn.com.br	
* [Obrigatório] readme.md conter as instruções para buildar e servir o aplicativo.
* [Desejavel] que disponibilize o aplicativo na plataforma [Heroku](https://www.heroku.com)

# Tecnologias Back-end (Obrigatório):
* Spring Boot;
* Banco relacional ou não relacional é de livre escolha;

# Tecnologias Front-end (Obrigatório):
#### Escolher entre os frameworks:
* Angular 6.x.x

# Diferenciais:
* Docker;
* TypeScript;
* Kubernetes;
* Organização e clareza nas ideias;
* Menos é mais, seja prático e não perca tempo com aspectos desnecessários;

Use o contato do Eduardo (eduardo.araujo@timeitn.com.br) para sanar qualquer dúvida.
