<h1 style="text-align: center;">📌DoR (Definition of Ready): Sprint 01</h1>

<table>
  <thead>
    <tr>
      <th>User Story</th>
      <th>Critério de aceitação</th>
      <th>Estimativa horas</th>
      <th>Tarefas Front</th>
      <th>Tarefas Back</th>
      <th>Tarefas BD</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Como administrador, quero que o sistema suporte um modelo de dados dinâmico e permita o cadastro de estações meteorológicas, garantindo flexibilidade na gestão e registro dessas informações.</td>
      <td>O sistema deve permitir o cadastro de estações meteorológicas com nome, UUID, latitude, longitude.</td>
      <td>3</td>
      <td>Criar interface de cadastro de estações.</td>
      <td>Implementar a lógica para validar e salvar os dados das estações meteorológicas no banco de dados.</td>
      <td>Criar estrutura de banco de dados adaptável para permitir futuras adições sem impacto estrutural.</td>
    </tr>
    <tr>
      <td>Como administrador, quero cadastrar novos parâmetros meteorológicos para garantir que todas as medições necessárias sejam registradas corretamente.</td>
      <td>O sistema deve permitir o cadastro de parâmetros meteorológicos com tipo json, nome, unidade, casas decimais, fator, offset.</td>
      <td>3</td>
      <td>Criar interface de cadastro de parâmetros.</td>
      <td>Implementar a lógica para validar e salvar os novos parâmetros meteorológicos no banco de dados.</td>
      <td>Criar e armazenar os parâmetros meteorológicos no banco de dados com suas unidades de medida e relações com sensores.</td>
    </tr>
    <tr>
      <td>Como administrador, quero cadastrar alertas meteorológicos para identificar condições climáticas críticas.</td>
      <td>O sistema deve permitir a configuração de alertas baseados em condições meteorológicas. Os alertas devem ser disparados automaticamente.</td>
      <td>3</td>
      <td>Criar interface de cadastro de alertas.</td>
      <td>Implementar a lógica para validar e salvar alertas meteorológicos com base em condições predefinidas.</td>
      <td>Criar estrutura no banco de dados para armazenar alertas, regras de ativação e logs de eventos disparados.</td>
    </tr>
    <tr>
      <td>Como administrador, quero cadastrar novos usuários para que possam acessar o sistema conforme suas permissões.</td>
      <td>O sistema deve permitir o cadastro de usuários com nome, CPF, e-mail, senha e permissão.</td>
      <td>3</td>
      <td>Criar interface de cadastro de usuários.</td>
      <td>Implementar a lógica para validar e salvar novos usuários no banco de dados, garantindo regras de permissões.</td>
      <td>Criar e armazenar os usuários no banco de dados com níveis de acesso e autenticação segura.</td>
    </tr>
    <tr>
      <td>Como administrador, quero editar as informações de uma estação meteorológica para manter os dados sempre atualizados.</td>
      <td>O sistema deve permitir a edição dos dados de uma estação.</td>
      <td>3</td>
      <td>Criar interface de edição de estação.</td>
      <td>Implementar a lógica para validar e salvar as edições feitas pelo administrador no banco de dados.</td>
      <td>Atualizar os registros existentes no banco de dados com as novas informações da estação meteorológica editada.</td>
    </tr>
    <tr>
      <td>Como administrador, quero editar os parâmetros meteorológicos para corrigir informações ou ajustar unidades de medida.</td>
      <td>O sistema deve permitir a edição dos parâmetros.</td>
      <td>3</td>
      <td>Criar interface para edição de parâmetros.</td>
      <td>Implementar a lógica para validar e salvar as edições feitas pelo administrador no banco de dados.</td>
      <td>Atualizar os registros existentes no banco de dados com as novas informações do parâmetro editado.</td>
    </tr>
    <tr>
      <td>Como administrador, quero editar alertas meteorológicos para ajustar suas condições de ativação e notificação.</td>
      <td>O sistema deve permitir modificar as regras dos alertas cadastrados.</td>
      <td>3</td>
      <td>Criar interface para edição de alertas.</td>
      <td>Implementar a lógica para validar e salvar as edições feitas pelo administrador no banco de dados.</td>
      <td>Atualizar os registros existentes no banco de dados com as novas informações do alerta editado.</td>
    </tr>
    <tr>
      <td>Como administrador, quero editar as informações de um usuário para corrigir ou alterar permissões.</td>
      <td>O sistema deve permitir a edição dos dados de um usuário.</td>
      <td>3</td>
      <td>Criar interface de edição de usuários.</td>
      <td>Implementar a lógica para validar e salvar as edições feitas pelo administrador no banco de dados.</td>
      <td>Atualizar os registros existentes no banco de dados com as novas informações do usuário editado.</td>
    </tr>
    <tr>
      <td>Como usuário, quero visualizar uma lista de todas as estações cadastradas no sistema.</td>
      <td>O sistema deve exibir uma lista de todas as estações cadastradas, permitindo filtros por nome e localização.</td>
      <td>3</td>
      <td>Criar interface para listagem de estações com filtros.</td>
      <td>Implementar a lógica para buscar e retornar todas as estações meteorológicas registradas no banco de dados.</td>
      <td>Realizar consultas eficientes para recuperar os dados das estações meteorológicas e apresentar na lista de forma otimizada.</td>
    </tr>
    <tr>
      <td>Como administrador, quero visualizar uma lista de parâmetros meteorológicos cadastrados para acompanhar e gerenciar as medições do sistema.</td>
      <td>O sistema deve exibir uma lista com os parâmetros meteorológicos cadastrados, permitindo filtros por nome.</td>
      <td>3</td>
      <td>Criar interface para listagem de parâmetros com filtros.</td>
      <td>Implementar a lógica para buscar e retornar todos os parâmetros meteorológicos registrados no banco de dados.</td>
      <td>Realizar consultas eficientes para recuperar os dados dos parâmetros meteorológicos e apresentar na lista de forma otimizada.</td>
    </tr>
    <tr>
      <td>Como administrador, quero visualizar uma lista de alertas meteorológicos cadastrados para gerenciar notificações de eventos climáticos críticos.</td>
      <td>O sistema deve exibir uma lista de alertas cadastrados, permitindo filtros por status.</td>
      <td>3</td>
      <td>Criar interface para listagem de alertas com filtros.</td>
      <td>Implementar a lógica para buscar e retornar todos os alertas meteorológicos registrados no banco de dados.</td>
      <td>Realizar consultas eficientes para recuperar os dados dos alertas meteorológicos e apresentar na lista de forma otimizada.</td>
    </tr>
    <tr>
      <td>Como administrador, quero visualizar uma lista de usuários cadastrados para gerenciar acessos e permissões no sistema.</td>
      <td>O sistema deve exibir a lista de usuários cadastrados, permitindo filtros por nome.</td>
      <td>3</td>
      <td>Criar interface para listagem de usuários com filtros.</td>
      <td>Implementar a lógica para buscar e retornar todos os usuários cadastrados no banco de dados.</td>
      <td>Realizar consultas eficientes para recuperar os dados dos usuários e apresentar na lista de forma otimizada.</td>
    </tr>
    <tr>
      <td>Como administrador, quero ativar e desativar estações meteorológicas conforme necessário.</td>
      <td>O administrador deve poder ativar ou desativar estações meteorológicas.</td>
      <td>3</td>
      <td>Criar botão de ativação/desativação na listagem de estações.</td>
      <td>Implementar a lógica para validar e salvar alterações de status das estações meteorológicas no banco de dados.</td>
      <td>Atualizar os registros existentes no banco de dados para refletir o novo status da estação.</td>
    </tr>
    <tr>
      <td>Como administrador, quero excluir estações meteorológicas conforme necessário.</td>
      <td>O administrador deve poder excluir uma estação sem dados históricos vinculados.</td>
      <td>3</td>
      <td>Criar botão de exclusão na listagem de estações.</td>
      <td>Implementar a lógica para validar e remover estações meteorológicas do banco de dados.</td>
      <td>Excluir registros do banco de dados apenas se não houver dependências associadas à estação.</td>
    </tr>
    <tr>
      <td>Como administrador, quero excluir parâmetros meteorológicos que não sejam mais necessários para manter o sistema organizado.</td>
      <td>O administrador deve poder excluir parâmetros não mais utilizados.</td>
      <td>3</td>
      <td>Criar botão de exclusão na listagem de parâmetros.</td>
      <td>Implementar a lógica para validar e remover parâmetros meteorológicos do banco de dados.</td>
      <td>Excluir registros do banco de dados apenas se não houver vínculos com dados históricos.</td>
    </tr>
    <tr>
      <td>Como administrador, quero excluir alertas que não sejam mais necessários para manter o sistema atualizado.</td>
      <td>O administrador deve poder remover alertas que não sejam mais relevantes.</td>
      <td>3</td>
      <td>Criar botão de exclusão na listagem de alertas.</td>
      <td>Implementar a lógica para validar e remover alertas meteorológicos do banco de dados.</td>
      <td>Excluir registros do banco de dados apenas se o alerta não estiver ativo ou em uso.</td>
    </tr>
    <tr>
      <td>Como administrador, quero excluir usuários inativos ou desnecessários para manter a base de dados organizada.</td>
      <td>O administrador deve poder remover usuários inativos.</td>
      <td>3</td>
      <td>Criar botão de exclusão na listagem de usuários.</td>
      <td>Implementar a lógica para validar e remover usuários inativos ou desnecessários do banco de dados.</td>
      <td>Excluir registros do banco de dados apenas se o usuário não tiver ações recentes registradas.</td>
    </tr>
    <tr>
      <td>Como administrador, quero controlar o acesso ao sistema definindo permissões para diferentes usuários.</td>
      <td>O sistema deve permitir definir permissões para dois níveis de usuários, tais como administrador e público.</td>
      <td>2</td>
      <td>Criar interface para gerenciamento de permissões.</td>
      <td>Implementar a lógica para validar e aplicar permissões de usuário no sistema.</td>
      <td>Gerenciar as permissões dos usuários no banco de dados de forma segura e estruturada.</td>
    </tr>
  </tbody>
</table>


<h2>Modelo de dados</h2>
<img src="https://github.com/Sync-FATEC/API-2025.1-4SEM/blob/main/sprints/sprint01/modelo-de-dados.jpeg">

<h2>DoD (Definition of Done)</h2>

<h2>Mockups</h2>

<h3>Administrador</h3>
<img src="https://github.com/Sync-FATEC/API-2025.1-4SEM/raw/main/assets/c0f23d6a-d3a3-4455-83e0-aad606994083" 
alt="MVP">

<h3>Cliente</h3>
<img src="https://github.com/Sync-FATEC/API-2025.1-4SEM/raw/main/assets/53e42ba8-88f4-4c90-a902-86c1b060c0a3" 
alt="MVP">
