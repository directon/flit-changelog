# Novidades da versão
___
## Flit Manager 4.0.12 (24/01/2022)

### 🌟 Melhorias

- `Folha de ponto [FM-682]` - Otimização na geração da folha de ponto.

- `Processamento de jornadas [FM-653]` - Ajuste interno no processamento de jornadas para ignorar as jornadas antigas que ficam em memória.

### 🔧 Correções

- `Status do usuário [FM-682]` - Quando o usuário estiver de **férias, afastado ou suspensão de contrato**, o status somente voltará para **ativo de forma automática** quando a data final for menor que a data atual.
___
## Flit App 4.5.0 (21/01/2022)

### 🌟 Melhorias

- `Escala prevista [FA-77]` - Realizada melhoria na tela principal do aplicativo para exibir a escala prevista do funcionário para o dia atual.

- `Previsão de saída [FA-79]` - Na tela principal também será mostrada a previsão de saída do funcionário caso tenha marcação na jornada atual.

  ![mobile-previsao-saida](assets/images/mobile-previsao-saida.png)

### 🔧 Correções

- `Status do usuário [FA-75]` - Agora quando o usuário estiver com um status de: Férias, afastamento ou suspensão de contrato configurado para uma data futura, ele conseguirá marcar o ponto, bloqueando a marcação só durante o período do afastamento.
 
---
## Flit Multi 1.2.1 (25/11/2021)
 
 
### 🔧 Correções
 
- `Configuração - Câmera [MUL-22]` - Botão de voltar na configuração da câmera está mais visível.
 
- `Login [MUL-21]` - Ao colocar um terminal inválido na hora de fazer o login, aparecerá uma mensagem de falha na tela.
 
- `Logout [MUL-42]` - Quando houver um logout automático aparecerá na tela em qual dispositivo ocorreu o novo acesso.
 
---
 
## Flit web manager 4.0.11 (25/11/2021)
 
### 🚀 Novo
 
- `Listagem de marcação [FM-540]` - Foi criada uma nova coluna que mostra os dias da semana na listagem de marcação.
 
- `Listagem de marcação [FM-511]` - Foi criada uma nova coluna que mostra a hora da marcação do usuário.
 
- `Exportação MOV.DP [FM-405]` - Agora é possível fazer a exportação das horas extras intrajornada no arquivo, o campo fica na aba de "Parâmetros gerais".
 
### 🌟 Melhorias
 
- `Reconhecimento facial [FM-532]` - Proteção para que só seja possível subir imagens que tenham um rosto identificado. Caso o reconhecimento facial obrigatório esteja marcado.
 
- `Proteção para a exceção [FM-551]` - Caso o usuário tenha feito marcação por exceção alguma vez, o gestor não conseguirá excluir o cadastro do mesmo.
 
### 🔧 Correções
 
- `Criação de jornadas [FM-504]` - Antes, quando fazíamos a criação interna de jornadas em massa e o usuário possuía marcação de um dia para o outro, algumas jornadas não eram criadas e isso foi corrigido.
 
- `Recálculo de acumulados [FM-509]` - As jornadas vão permanecer com a configuração de horário noturno do momento da criação da jornada. Caso o usuário queira atualizar as configurações de redução de horário noturno terá que acessar a jornada e clicar no botão de "Atualizar" que só aparecerá caso a configuração da jornada esteja diferente da conta.
 
- `Criação de jornadas [FM-509]` - Jornadas só serão criadas após a data de admissão do usuário.
 
- `Jornada de usuário demitido [FM-537]` - As jornadas devem ser criadas até a data de demissão do usuário.
 
- `Horas noturnas [FM-522]` - Ajuste feito para que a redução de hora noturna calcule da mesma forma na jornada prevista e na jornada realizada.
 
---
 
## Flit web manager 4.0.10 (29/10/2021)
 
### 🌟 Melhorias
 
- `Listagem de marcações [FM-443]` - Adicionado campo de **matrícula (PIN)** do usuário, levando também essa informação na exportação para Planilha (Excel).
 
- `Banner topo [FM-432]` - Criado recurso para quando o cliente estiver inadimplente, exibir um banner em vermelho com um contador de dias que faltam para que o sistema seja bloqueado (prazo de 5 dias). Dessa forma não será bloqueado de imediato quando entrar em inadimplência.
 
### 🔧 Correções
 
- `Empresas x Jornadas [FM-445]` - Ajuste interno para não permitir a exclusão de empresas que possuem marcações, jornadas ou usuários.
 
- `Hora noturna [FM-447]` - Ajuste interno no cálculo de jornadas para quando as horas extras estiverem dentro da tolerância, serem descontadas apenas da jornada horas diurnas.
 
- `Dashboard [FM-464]` - Ajuste interno para exibir status correto do usuário no Dashboard, depois de marcar o ponto estando com um atraso.
 
- `Cadastro de usuários [FM-467]` - Ajuste interno para não remover o perímetro do usuário após alterar qualquer informação no seu cadastro.
 
---
 
## Flit Multi 1.2.0 (27/10/2021)
 
### 🌟 Melhorias
 
- `Nova orientação vertical [MUL-18]` - Agora é possível utilizar a marcação de ponto no Flit Multi na forma vertical do dispositivo.
 
  ![flit-multi-vertical](assets/images/multi-vertical.png)
 
---
 
## Flit web manager 4.0.9 (11/10/2021)
 
### 🚀 Novo
 
- `Cadastro de (Usuários/Perímetros) [FM-373]` - Agora é possível **vincular até 5 perímetros** diferentes no cadastro de usuários, desta forma o usuário não fica limitado a marcar apenas em um único perímetro.
 
- `Cadastro de empresas [FM-374]` - Na aba parâmetros foi criado uma opção para **permitir marcar ponto fora do perímetro** caso o dispositivo não consiga obter a localização e tenha passado de 30 segundos na com a tela de marcação aberta.
 
- `Cadastro de empresas [FM-108]` - Também na aba parâmetros será possível **informar até 5 IPS externos, para restringir as marcações do flit web**, desta forma, caso o gestor opte por utilizar este recurso ele pode ter o controle se o usuário está marcando ponto por dentro da rede da empresa por exemplo, caso esteja fora da rede não permitirá a marcação.
 
- `Exportação Alterdata [FM-400]` - Em parâmetros gerais foi **criado o campo de horas noturnas totais**, também é possível exportar o mesmo na tela de exportações.
 
### 🌟 Melhorias
 
- `Cadastro de usuários [FM-360]` - Os códigos externos do domínio agora são validados se são únicos por empresa e não por conta.
 
- `Cadastro de usuários [FM-375]` - Não permitir excluir usuários que já realizaram marcações em qualquer um dos apps.
 
- `Ajuste de jornadas [FM-392]` - Inserido log de exclusão manual de período.
 
- `Ajuste de jornadas [FM-376]` - Ocultar jornadas após a data de demissão dos usuários.
 
- `Cadastro de dispositivos [FM-363]` - Melhorias de UI e UX, a fonte do PIN foi melhorada para não confundir as letras minúsculas com maiúsculas, e também agora o CPF/CNPJ da empresa fica perto do PIN no modal de detalhes do dispositivo para facilitar a inserção de dados no formulário de login.
 
### 🔧 Correções
 
- `Folha de ponto [FM-365]` - Períodos trabalhados consideravam o fuso do local do navegador, agora assim como no ajuste de jornadas consideram o fuso do período que está no servidor para exibir os horários.
 
- `Folha de ponto [FM-357]` - Antes eram geradas duas páginas de folha de ponto quando o colaborador fazia aniversário naquele mês, agora é gerada apenas uma como esperado.
 
- `Ajuste de jornadas [FM-358]` - Ao abrir a jornada de um usuário que foi excluído, ela ficava carregando em loop e não abria.
 
- `Ajuste de jornadas [FM-413]` - Ao atualizar a escala na jornada de um usuário que foi importado e está sem escala, ele joga como folga, antes ficava carregando em loop.
 
- `Criação de jornadas [FM-417]` - Ao editar o cadastro do usuário em cenários que era necessário criar as jornadas daquele período em aberto, as marcações já realizadas anteriormente não eram inseridas na jornada.
 
---