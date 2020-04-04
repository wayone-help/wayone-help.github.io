---
layout: page
title: Dashboard - Atender pelos agendamentos
---

### Definição

Tanto no dashboard quanto no menu lateral é listado dois casos de agendamento, os que estão **aguardando atendimento** (fila de espera) e os que estão **em atendimento**. Estas listas são formadas por todas as agendas que o usuário logado tem acesso.

<div class="text-center"> 
  <img alt="Tipos de agendamento" src="/pages/dashboard/atender-pelos-agendamentos/tipos_agendamento.png" style="width: 90%;">
</div>

Antes de mostrar como atender é necessário explicar os diferentes tipos de agendamento. Toda agenda pertence a um fluxo, e o agendamento consequentemente pertence ao mesmo fluxo. Existem quatro tipos de fluxo: Clínico, Operacional, Comercial e Financeiro. 

Além dos fluxos, a agenda pode ser global ou não. Todas as agendas criadas na página de configuração da clínica serão globais, somente as agendas adicionadas na implantação da clínica que sejam do fluxo clínico, e as agendas criadas automaticamente ao adicionar um usuário com permissão de dentista, que não serão. 

Uma agenda global significa que qualquer usuário que tenha acesso de visualizar ela, poderá atender também


### Fila em espera

Uma lista que pode ser formada por agendas dos quatro fluxos. Se a agenda for vinculada ao seu usuário, ou for uma agenda global, ao clicar no agendamento aparecerá uma popup com os dados dela, podendo iniciar atendimento (caso já não esteja com um atendimento em andamento), senão será redirecionado para a tela da área do paciente, onde poderá ver os dados dele.

Se a agenda for do fluxo clínico ou operacional, é só clicar no botão **atender**, aparecerá assim:

<div class="text-center"> 
  <img alt="Tipos de agendamento" src="/pages/dashboard/atender-pelos-agendamentos/agendamento_clinico_operacional.png" style="width: 90%;">
</div>

Se a agenda for do fluxo comercial ou financeiro, é só clicar no botão **iniciar atendimento**, aparecerá assim:

<div class="text-center"> 
  <img alt="Tipos de agendamento" src="/pages/dashboard/atender-pelos-agendamentos/agendamento_comercial_financeiro.png" style="width: 90%;">
</div>


### Em atendimento

Se o atendimento tiver sido iniciado por você, ao clicar no agendamento será redirecionado para a tela do atendimento, senão será redirecionado para a área do paciente