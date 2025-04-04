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
      <td>Como sistema, quero receber dados das estações meteorológicas em tempo real.</td>
      <td>O sistema deve receber dados em tempo real, validá-los e armazená-los.</td>
      <td>5</td>
      <td>-</td>
      <td>Criar endpoint para receber dados em tempo real. Validar dados recebidos.</td>
      <td>Criar estrutura de tabela para armazenar dados em tempo real com performance.</td>
    </tr>
    <tr>
      <td>Como sistema, quero processar os dados recebidos para calcular médias horárias e diárias.</td>
      <td>O sistema deve calcular e armazenar médias horárias e diárias de forma automática a partir dos dados recebidos.</td>
      <td>8</td>
      <td>-</td>
      <td>Criar rotinas de cálculo automático.</td>
      <td>Criar tabelas específicas para armazenar médias horárias e diárias.</td>
    </tr>
    <tr>
      <td>Como sistema, quero armazenar os dados recebidos das estações meteorológicas de forma otimizada para suportar grandes volumes de informações.</td>
      <td>Os dados devem ser armazenados em uma estrutura eficiente e com índices para consultas rápidas.</td>
      <td>5</td>
      <td>-</td>
      <td>Criar processo assíncrono para armazenar os dados recebidos das estações sem travar a aplicação principal.</td>
      <td>Criar índices nos campos de data e identificador da estação para acelerar as consultas filtradas.</td>
    </tr>
    <tr>
      <td>Como administrador, quero monitorar o funcionamento das estações meteorológicas em tempo real.</td>
      <td>O sistema deve exibir, em tempo real, dados das estações e última atualização.</td>
      <td>8</td>
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
      <td>Criar endpoint para buscar os dados de sensores de determinada estação.</td>
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
      <td>Implementar rotas e lógica de leitura dos conteúdos educativos</td>
      <td>Criar estrutura de banco de dados para armazenar conteúdos de tutorial.</td>
    </tr>
  </tbody>
</table>
