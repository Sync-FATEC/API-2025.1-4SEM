<h1 style="text-align: center;">📌DoR (Definition of Ready): Sprint 02</h1>

<table>
  <thead>
    <tr>
      <th>User Story</th>
      <th>Critério de Aceitação</th>
      <th>Estimativa Horas</th>
      <th>Tarefas Front</th>
      <th>Tarefas Back</th>
      <th>Tarefas BD</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Como sistema, quero emular o recebimento de dados das estações meteorológicas, para que o projeto possa ser desenvolvidos e testados sem equipamentos reais.</td>
<td>O sistema deve gerar automaticamente dados simulados dos sensores, com variações realistas em intervalos configuráveis, permitindo que outras funcionalidades operem normalmente mesmo sem conexão com estações reais.</td>
      <td>5</td>
      <td>-</td>
      <td>Criar um serviço que gere dados simulados dos sensores meteorológicos. Implementar intervalo automático de envio dos dados.</td>
      <td>Armazenar os dados simulados na mesma estrutura/tabela que os dados reais.</td>
    </tr>
    <tr>
      <td>Como sistema, quero processar os dados recebidos para calcular médias horárias e diárias.</td>
      <td>O sistema deve calcular e armazenar médias horárias e diárias de forma automática a partir dos dados recebidos.</td>
      <td>8</td>
      <td>Criar filtros por tipo de média horária ou diária.</td>
      <td>Criar endpoints para retornar as médias horárias e diárias com filtros por data e estação.</td>
      <td>Criar tabelas específicas para armazenar médias horárias e diárias.</td>
    </tr>
    <tr>
      <td>Como sistema, quero armazenar os dados recebidos de forma otimizada para suportar grandes volumes de informações.</td>
      <td>Os dados devem ser armazenados em uma estrutura eficiente e com índices para consultas rápidas.</td>
      <td>5</td>
      <td>-</td>
      <td>Criar processo assíncrono para armazenar os dados recebidos sem travar a aplicação principal.</td>
      <td>Criar índices nos campos de data e identificador da estação para acelerar as consultas filtradas.</td>
    </tr>
    <tr>
      <td>Como administrador, quero acompanhar em tempo real o estado operacional das unidades de coleta, para garantir a continuidade do serviço.</td>
      <td>O sistema deve exibir, em tempo real, o status operacional das unidades de coleta e o horário da última verificação.</td>
      <td>5</td>
      <td>-</td>
      <td>Implementar serviço de atualização contínua para enviar dados atualizados.</td>
      <td>Realizar consultas em tempo real para verificar status e última transmissão de cada estação.</td>
    </tr>
    <tr>
      <td>Como usuário, quero receber notificações em caso de eventos meteorológicos extremos.</td>
      <td>O sistema deve enviar notificações quando condições críticas forem atingidas.
      O sistema deve enviar notificações por e-mail quando condições críticas forem atingidas.</td>
      <td>3</td>
      <td>-</td>
      <td>Criar lógica para monitorar e disparar alertas.</td>
      <td>Registrar notificações e condições que as dispararam.</td>
    </tr>
    <tr>
      <td>Como usuário, quero acessar dashboards interativos com os dados coletados pelas estações.</td>
      <td>O usuário deve visualizar um painel com gráficos com os dados meteorológicos coletados.</td>
      <td>8</td>
      <td>Criar layout do dashboard com componentes gráficos.</td>
      <td>Criar endpoint para retornar os dados dos gráficos da dashboard</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Como usuário, quero filtrar os dados exibidos no dashboard por data, para visualizar informações específicas de um período determinado.</td>
      <td>O usuário deve conseguir selecionar uma data ou intervalo de datas.</td>
      <td>3</td>
      <td>Implementar campos de seleção de data/início e fim.</td>
      <td>Implementar lógica de consulta otimizada por intervalo de datas.</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Como usuário, quero acessar um tutorial sobre os conceitos meteorológicos apresentados.</td>
      <td>O sistema deve disponibilizar tutoriais com explicações sobre medições e sensores.</td>
      <td>8</td>
      <td>Criar página interativa com tutoriais em texto e imagem.</td>
      <td>-</td>
      <td>-</td>
    </tr>
  </tbody>
</table>
