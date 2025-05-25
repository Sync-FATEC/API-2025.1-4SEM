<h1 style="text-align: center;">📌DoR (Definition of Ready): Sprint 03</h1>

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
      <td>Como sistema, quero receber dados em tempo real das estações meteorológicas físicas, substituindo a emulação, para operar em produção.</td>
      <td>O sistema deve receber dados em tempo real das estações físicas</td>
      <td>8</td>
      <td>-</td>
      <td>Implementar conexão com estações meteorológicas físicas. Substituir endpoint de dados emulados pelos dados físicos.</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Como administrador, quero monitorar o funcionamento das estações meteorológicas em tempo real.</td>
      <td>O administrador deve visualizar em tempo real o status de operação das estações meteorológicas.</td>
      <td>8</td>
      <td>Criar um badge dinâmico que exiba em tempo real o status de conexão das estações meteorológicas.</td>
      <td>Criar endpoint para disponibilizar o status das estações.</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Como sistema, quero registrar automaticamente os dados coletados pelas estações meteorológicas em um datalogger, para garantir a persistência e integridade das informações.</td>
      <td>Todos os dados recebidos devem ser automaticamente salvos em um datalogger.</td>
      <td>5</td>
      <td>-</td>
      <td>Implementar serviço para gravar dados automaticamente no datalogger.</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Como administrador, quero gerar relatórios detalhados sobre as condições meteorológicas registradas.</td>
      <td>O sistema deve gerar e permitir download de relatórios contendo dados registrados.</td>
      <td>5</td>
      <td>Criar botão para gerar/download de relatórios.</td>
      <td>Implementar geração de relatórios em PDF.</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Como usuário, quero alterar minha senha para garantir a segurança da minha conta.</td>
      <td>O usuário deve conseguir alterar sua senha mediante autenticação.</td>
      <td>3</td>
      <td>Criar tela de alteração de senha.</td>
      <td>Criar endpoint de alteração de senha com autenticação.</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Como usuário, quero poder recuperar minha senha caso eu a esqueça, para continuar acessando o sistema.</td>
      <td>O usuário deve conseguir solicitar redefinição de senha por e-mail.</td>
      <td>3</td>
      <td>Criar tela de recuperação de senha.</td>
      <td>Criar endpoint para envio de e-mail de recuperação e redefinição de senha.</td>
      <td>Criar tabela temporária para tokens de recuperação ou adicionar campo na tabela de usuários.</td>
    </tr>
  </tbody>
</table>


<h2>Modelo de dados</h2>
<img src="https://github.com/Sync-FATEC/API-2025.1-4SEM/blob/main/sprints/sprint03/modelo-de-dados.png">

<h2>Arquitetura do sistema</h2>
<img src="https://github.com/Sync-FATEC/API-2025.1-4SEM/blob/main/sprints/sprint03/arquitetura.jpg">

<h2>DoD (Definition of Done)</h2>

<h2>Mockups</h2>
<h3>Administrador</h3>
<img src="https://github.com/Sync-FATEC/API-2025.1-4SEM/assets/fb8fb41f-c6d3-4ccc-80b9-806418bed236" 
alt="MVP">

<h3>Cliente</h3>
<img src="https://github.com/Sync-FATEC/API-2025.1-4SEM/assets/cbf1e8a0-4ced-42ec-ae87-976c3e770e8c" 
alt="MVP">

<h3>Estação</h3>
<img src="https://github.com/Sync-FATEC/API-2025.1-4SEM/assets/d57d1a6c-1d8f-4f35-ad7b-2b5ecaa3acb5" 
alt="MVP">