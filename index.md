# Novidades da versão

## Flit web manager 4.0.10 (29/10/2021)


### 🌟 Melhorias

-  `Listagem de marcação [FM-443]` - Adicionado campo de matricula do usuário em listagem de marcação, levando também essa informação para o Excel.

-  `Banner topo [FM-432]` - Criado recurso para quando o cliente estiver inadimplente, exibir um banner em vermelho com um contador de dias que faltam para que o sistema seja bloqueado (prazo de 5 dias). Dessa forma não será bloqueado de imediato quando entrar em inadimplência.


### 🔧 Correções

-  `Empresas x Jornadas [FM-445]` - Ajuste interno para não permitir a exclusão de empresas que possuem marcações, jornadas ou usuários.

-  `Hora noturna [FM-447]` -  Ajuste interno no cálculo de jornadas para quando as horas extras estiverem dentro da tolerância, serem descontadas na jornada diurna.

-  `Dashboard [FM-464]`  - Ajuste interno para exibir no Dashboard o usuário no seu status corretamente, depois de marcar o ponto estando com um atraso.

-  `Cadastro de usuários [FM-467]` - Ajuste interno para não remover o perímetro do usuário após alterar qualquer informação no seu cadastro.

---

## Flit web manager 4.0.9 (11/10/2021)

### 🚀 Novo

-  `Cadastro de (Usuários/Perímetros) [FM-373]` - Agora é possível **vincular até 5 perímetros** diferentes no cadastro de usuários, desta forma o usuário não fica  limitado a marcar apenas em um único perímetro.

-  `Cadastro de empresas [FM-374]` - Na aba parâmetros foi criado uma opção para **permitir marcar ponto fora do perímetro** caso o dispositivo não consiga obter a localização e tenha passado de 30 segundos na com a tela de marcação aberta.

-  `Cadastro de empresas [FM-108]` - Também na aba parâmetros será possível **informar até 5 IPS externos, para restringir as marcações do flit web**, desta forma, caso o gestor opte por utilizar este recurso ele pode ter o controle se o usuário está marcando ponto por dentro da rede da empresa por exemplo, caso esteja fora da rede não permitirá a marcação.

-  `Exportação Alterdata [FM-400]` - Em parâmetros gerais foi **criado o campo de horas noturnas totais**, também é possível exportar o mesmo na tela de exportações.

### 🌟 Melhorias

-  `Cadastro de usuários [FM-360]` - Os códigos externos do domínio agora são validados se são únicos por empresa e não por conta.

-  `Cadastro de usuários [FM-375]` - Não permitir excluir usuários que já realizaram marcações em qualquer um dos apps.

-  `Ajuste de jornadas [FM-392]` - Inserido log de exclusão manual de período.

-  `Ajuste de jornadas [FM-376]` - Ocultar jornadas após a data de demissão dos usuários.

-  `Cadastro de dispositivos [FM-363]` - Melhorias de UI e UX, a fonte do PIN foi melhorada para não confundir as letras minúsculas com maiúsculas, e também agora o CPF/CNPJ da empresa fica perto do PIN no modal de detalhes do dispositivo para facilitar a inserção de dados no formulário de login.

### 🔧 Correções

-  `Folha de ponto [FM-365]` - Períodos trabalhados consideravam o fuso do local do navegador, agora assim como no ajuste de jornadas consideram o fuso do período que está no servidor para exibir os horários.

-  `Folha de ponto [FM-357]` - Antes eram geradas duas páginas de folha de ponto quando o colaborador fazia aniversário naquele mês, agora é gerada apenas uma como esperado.

-  `Ajuste de jornadas [FM-358]` - Ao abrir a jornada de um usuário que foi excluído, ela ficava carregando em loop e não abria.

-  `Ajuste de jornadas [FM-413]` - Ao atualizar a escala na jornada de um usuário que foi importado e está sem escala, ele joga como folga, antes ficava carregando em loop.

-  `Criação de jornadas [FM-417]` - Ao editar o cadastro do usuário em cenários que era necessário criar as jornadas daquele período em aberto, as marcações já realizadas anteriormente não eram inseridas na jornada.

---