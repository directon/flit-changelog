# Novidades da versão
## Flit web manager 4.0.9
 
### 🚀 Novo
 
- `Cadastro de (Usuários/Perímetros)` - Agora podemos vincular até 5 perímetros diferentes no cadastro de usuários, desta forma o usuário não fica mais limitado a marcar apenas em um perímetro fixo.
 
- `Cadastro de empresas` - Agora existe uma opção nos parâmetros para **Permitir marcar ponto fora do perímetro** caso o dispositivo não conseguir obter a localização ou se passarem 30 segundos da abertura da tela de marcação.
 
- `Cadastro de empresas` - Agora nos parâmetros podemos informar até 5 IPS externos, para restringir as marcações do flit web, desta forma caso o gestor opte por utilizar este recurso ele pode ter o controle se o usuário está marcando ponto por dentro da rede da empresa por exemplo, e caso esteja fora da rede não permite marcar.
 
- `Exportação Alterdata` - Agora podemos informar em parâmetros gerais o código do evento de **horas noturnas totais**, e exportar o mesmo na tela de exportações.
 
### 🌟 Melhorias
- `Cadastro de usuários` - Os códigos externos do domínio agora são validados se são únicos por empresa e não por conta.
 
- `Cadastro de usuários` - Não permitir excluir usuários que já realizaram marcações em qualquer um dos apps.
 
- `Ajuste de jornadas` - Inserido log de exclusão manual de período.
 
- `Ajuste de jornadas` - Ocultar jornadas após a data de demissão dos usuários.
 
- `Cadastro de dispositivos` - Melhorias de UI e UX, a fonte do PIN foi melhorada para não confundir as letras minúsculas com maiúsculas, e também agora o CPF/CNPJ da empresa fica perto do PIN no modal de detalhes do dispositivo para facilitar a inserção de dados no formulário de login.
 
### 🔧 Correções
- `Folha de ponto` - Períodos trabalhados consideravam o fuso do local do navegador, agora assim como no ajuste de jornadas consideram o fuso do período que está no servidor para exibir os horários.
 
- `Folha de ponto` - Antes eram geradas duas páginas de folha de ponto quando o colaborador fazia aniversário naquele mês, agora é gerada apenas uma como esperado.
 
- `Ajuste de jornadas` - Ao abrir a jornada de um usuário que foi excluído, ela ficava carregando em loop e não abria.
 
- `Ajuste de jornadas` - Ao atualizar a escala na jornada de um usuário que foi importado e está sem escala, ele joga como folga, antes ficava carregando em loop.
 
- `Criação de jornadas` - Ao editar o cadastro do usuário em cenários que era necessário criar as jornadas daquele período em aberto, as marcações já realizadas anteriormente não eram inseridas na jornada.
