# Novidades da versão

## Flit web manager 4.2.1 (13/07/2022)

### 🔧 Correções

- `Ajuste de jornadas [FM-1050]` - Ajuste interno para voltar a confirmar as jornadas automaticamente de acordo com as configurações.

- `Lançamento simplificado [FM-1039]` - Ajuste interno para melhorar o lançamento retroativo de férias.

- `Lançamento simplificado [FM-1044]` - Ajuste interno no status programado do usuário para que fique com o status correto.

- `Lançamento simplificado [FM-1056]` - Ajuste interno na data final do lançamento simplificado para auto preencher de acordo com a data inicial informada.

- `Folha de ponto [FM-1072]` - Ajuste interno para que o totalizador de horas acumuladas apareça na impressão.

- `Feriado [FM-997]` - Ajuste interno na configuração de feriado para que aplique nas empresas corretas.

- `Reconhecimento facial [FM-1094]` - Ajuste interno para deixar de contar o reconhecimento facial em usuários desligados.

---

## Flit Web Manager 4.2.0 (30/06/2022)

### 🚀 Novo

- `Busca/Pesquisa [FM-793]` - Habilitamos um campo de busca nos filtros da plataforma, para permitir pesquisar funcionários, departamentos, cargos e empresas, apenas digitando a descrição de cada.

- `Lançamento simplificado [FM-739]` - Criado novo recurso para ser possível efetuar lançamentos em bloco, onde o gestor conseguirá por exemplo, lançar um atestado para vários dias de uma única vez e ainda para vários funcionários, assim como, afastamento, férias, abonos. Inclusive é possível efetuar abonos parciais, quando o funcionário se ausenta por um período da empresa, mas será abonado e não descontado pela ausência.

- `Status do usuário [FM-726]` - Agora o status do usuário será modificado apenas pela tela de Lançamentos, alterando para férias, afastado e contrato suspenso. Antes poderia ser modificado no cadastro de usuários, mas agora ficou pela tela de lançamentos.

- `Comprovante de ponto [FM-725]` - Criado nova tela para consulta do comprovante de ponto. O colaborador pode consultar através de um navegador, mesmo pelo celular, o seguinte link: https://comprovante.flitapp.com.br/#/login.

- `Listagem de usuários [FM-857]` - Criado filtro no cadastro de usuários, para que na listagem exiba apenas os ativos. Caso queira analisar os desligados, pode-se utilizar o filtro para a pesquisa.

- `Listagem de usuários [FM-856]` - Criado no cadastro de usuários um ícone ao lado do contador de usuários ativos, exibindo que na contagem de licenças não conta com os usuários desligados.

- `Listagem de marcação [FM-777]` - Adicionado CNPJ ao lado do nome fantasia em todas as buscas de empresas na plataforma.

- `Ajustar jornadas [FM-779]` - Criado nova opção no ajuste de jornadas para permitir visualizar e selecionar tipo do período.

- `Filtros [FM-913]` - Ajuste interno em todos os filtros, para ser possível remover apenas um filtro selecionado na hora de pesquisar.

### 🌟 Melhorias

- `Parâmetros gerais [FM-844]` - Melhoria interna na exibição dos parâmetros para quem utiliza a plataforma no pacote único (apenas marcação de ponto).

- `Importação AFD [FM-865]` - Ajuste interno no tempo de resposta na importação do arquivo AFD.

- `Folha de ponto [FM-752]` - Ajuste interno para que a folha de ponto seja exibida de forma mais ampla na tela de visualização.

- `Cadastro de escalas [FM-770]` - Melhoria para que o gestor consiga alterar a escala e informar a partir de qual data deseja aplicar essa nova escala no funcionário.

### 🔧 Correções

- `Hora extra [FM-943]` - Ajuste interno para que as horas extras noturnas do ajustar jornadas apareça corretamente no resumo da jornada.

- `Ajustar jornadas [FM-873]` - Ajuste interno para que não exiba usuários indevidos para o gestor no ajustar jornadas.

- `E-mail de boas-vindas [FM-920]` - Ajuste interno no e-mail de boas-vindas.

---

## Flit App 4.6.1 (17/05/2022)

### 🌟 Melhorias

- `Melhoria na ressincronização das marcações [FA-168]` - Ajuste interno para ressincronizações das marcações off-line.

### 🔧 Correções

- `Gráfico de horas trabalhadas [FA-157]` - Foi otimizado o tempo do primeiro processamento do gráfico de horas.

- `Login/ Recuperação de senha [FA-156]` - Ajuste interno para quando usuário inserir o e-mail através do preenchimento automático, não apareça a mensagem de “usuário inválido”.

- `Marcação [FA-167]` - Ajuste interno para quando o Gestor estiver realizando alterações cadastrais e o usuário estiver marcando ponto, a marcação ocorra normalmente.

---

## Flit App 4.6.0 (22/04/2022)

### 🌟 Melhorias

- `Login [FA-104]` - Adicionado proteção para quando ocorrer bloqueio de conexão, o aplicativo informe que se trata de um bloqueio de rede.

- `Reconhecimento facial [FA-114]` - Ajuste interno para quando utilizar o reconhecimento facial, o sistema identifique o usuário de acordo com a empresa vinculada.

- `E-mail de boas-vindas [FA-117]` - Melhoria na cor do e-mail de boas-vindas e no primeiros a passos.

- `Comprovante [FA-125]` - Agora o comprovante da marcação de ponto, apresenta a origem do registro, ou seja, qual aplicativo foi utilizado.

- `Marcação por exceção [FA-127]` - Ajuste interno nas marcações por exceção, para que sejam feitas apenas com o horário original do servidor.

- `Notas [FA-129]` - Adicionado nova forma de visualização/edição de notas na aplicativo web.

- `Notificações [FA-128]` - Adicionado notificações de exceções no aplicativo web.

- `Menu lateral [FA-130]` - Criado menu lateral para o aplicativo web.

- `Recuperação de acesso [FA-143]` - Melhoria para quando o usuário não lembrar o e-mail cadastrado, poderá recuperar a senha utilizando o CPF.

### 🔧 Correções

- `Gráfico de horas trabalhadas [FA-117]` - Ajuste interno na exibição das informações, para ficarem alinhadas.

- `Cadastro de feriado [FA-119]` - Ajuste interno no percentual do gráfico para que mostre corretamente quando há horas extras.

- `Seleção de horário [FA-140]` - Ajuste visual na seleção de horários das exceções.

- `Gráfico de horas trabalhadas [FA-135]` - Ajuste interno para quando a jornada for folga, férias ou qualquer outra que não tenha período previsto de trabalho o gráfico ficará oculto.

---

## Flit Web 4.1.2 (19/04/2022)

### 🔧 Correções

- `Proteção marcação sem foto [FW-10]` - Ajuste interno para permitir marcar o ponto sem foto, apenas se a opção "Fotografar colaborador ao marcar ponto no Flit Web" estiver desmarcada no cadastro de empresas da plataforma de gestão.

---

## Flit Manager 4.1.1 (08/03/2022)

### 🚀 Novo

- `Layout [FM-820]` - Foi criada uma opção na aba superior direita onde mostrará os links dos aplicativos e também as recomendações mínimas/recomendadas.

### 🌟 Melhorias

- `Página inicial do blog [FM-799]` - Ajuste interno na aba "início" para exibir as novidades da versão.

- `Cadastro de empresas [FM-836]` - Ajuste interno para permitir inserir até 200 caracteres nos campos de razão social e nome fantasia.

- `Cadastro de usuários [FM-802]` - Realizada melhoria para que usuários cadastrados já como demitidos tenham suas jornadas recentes criadas.

- `E-mail de boas-vindas [FM-860]` - A cor do e-mail de boas-vindas foi alterada e o passo a passo também foi melhorado.

- `Mapas [FM-800]` - Realizada melhoria nos mapas do Flit. Agora também mostrará os negócios locais e pontos de referência.

- `Cadastro de feriado [FM-795]` - Ajuste interno na opção "Válido para todas as empresas do município/estado”, para ser habilitada somente após a seleção do município/estado.

- `Listagem de marcações [FM-810]` - Agora a foto do colaborador se adapta de acordo com o tamanho da câmera na área de identificação da marcação e quando passa o mouse sobre fica possível expandir.

### 🔧 Correções

- `Parâmetros gerais [FM-844]` - Ajuste interno para quando utilizar o Flit apenas como marcação de ponto, as opções de parâmetros gerais sejam bloqueadas.

- `Cadastro de feriado [FM-833]` - Ajuste interno na mensagem que aparece ao criar um feriado já existente.

- `Cadastro de usuários [FM-848]` - Ajuste interno na hora de cadastrar usuários sem categoria.

- `Cadastro de feriados [FM-798]` - Ajuste interno na escrita do modal de informações do feriado.

---

## Flit Manager 4.1.0 (24/02/2022)

### 🚀 Novo

- `Interface nova [FM-592]` - A interface principal do manager está de cara nova! :)

### 🌟 Melhorias

- `Cadastro de feriados [FM-705]` - Criado novo cadastro de feriados, no qual será possível selecionar se o feriado é nacional, estadual ou municipal separando por empresas.

- `Feriados nacionais [FM-658/703]` - Os feriados nacionais serão adicionados automaticamente todos os anos pela equipe Flit.

- `Cadastro de feriados [FM-696]` - Ajuste interno para quando um feriado for cadastrado na data atual ou posterior, as jornadas anteriores serem atualizadas e recalculadas com base nas empresas afetadas. Exemplo: Se hoje é dia 24/02 e o feriado aconteceu dia 20/02 e esse não estava cadastrado antes, ao cadastrar esse feriado no sistema, o Flit Manager vai atribuir nas jornadas do dia 20/02 feriado para todos da(s) empresa(s).

- `Exportação MOV.DP [FM-717]` - Ajuste interno na exportação MOV.DP para que os campos de HE Seg. a Sáb. e Feriado/Domingo fiquem separados.

- `Envio de e-mails [FM-579]` - Melhoria interna no layout do envio de e-mail de marcações, recuperação de senha. O usuário também receberá um e-mail de ativação/recuperação assim que o gestor cadastrá-lo no manager.

### 🔧 Correções

- `Integração Alterdata [FM-619]` - Ajuste visual nos campos de integração com a Alterdata em parâmetros gerais.

- `Marcação ignorada [FM-597]` - Ajuste interno para que a marcação de ponto seja ignorada apenas para aquelas realizadas no mesmo minuto.

- `Reconhecimento facial [FM-598]` - Ajuste interno para quando o usuário estiver com a opção "utiliza reconhecimento facial" marcada e ao desligá-lo, o sistema desmarque automaticamente essa opção.

- `Endereço (Usuários/Empresas) [FM-561]` - Ajuste interno nos campos de endereço para que seja possível cadastrar o número como "S/N".

- `Ajustar jornadas [FM-699]` - Ajuste interno no cálculo da jornada, para quando editar a saída do primeiro período.

---

## Flit Manager 4.0.12 (24/01/2022)

### 🌟 Melhorias

- `Folha de ponto [FM-682]` - Otimização na geração da folha de ponto.

- `Processamento de jornadas [FM-653]` - Ajuste interno no processamento de jornadas para ignorar as jornadas antigas que ficam em memória.

### 🔧 Correções

- `Status do usuário [FM-682]` - Quando o usuário estiver de **férias, afastado ou suspensão de contrato**, o status somente voltará para **ativo de forma automática** quando a data final for menor que a data atual.

---

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
