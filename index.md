
# Novidades da versão

## Flit web manager 4.0.9 (11/10/2021)

### 🚀 Novo

-  `Cadastro de (Usuários/Perímetros) [FM-373]` - Agora podemos vincular até 5 perímetros diferentes no cadastro de usuários, desta forma o usuário não fica mais limitado a marcar apenas em um perímetro fixo.

-  `Cadastro de empresas [FM-374]` - Agora existe uma opção nos parâmetros para **Permitir marcar ponto fora do perímetro** caso o dispositivo não conseguir obter a localização ou se passarem 30 segundos da abertura da tela de marcação.

-  `Cadastro de empresas [FM-108]` - Agora nos parâmetros podemos informar até 5 IPS externos, para restringir as marcações do flit web, desta forma caso o gestor opte por utilizar este recurso ele pode ter o controle se o usuário está marcando ponto por dentro da rede da empresa por exemplo, e caso esteja fora da rede não permite marcar.

-  `Exportação Alterdata [FM-400]` - Agora podemos informar em parâmetros gerais o código do evento de **horas noturnas totais**, e exportar o mesmo na tela de exportações.

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