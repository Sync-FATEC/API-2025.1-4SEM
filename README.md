<h2 id='topo'><img src="media/banner_apresentacao.png"></h2>

<div align="center">
<a href="#objetivo"> 🎯 Objetivo </a> |
<a href="#proposta"> 📧 Proposta de Solução </a> |
<a href="#requisitos-funcionais"> 📚 Requisitos Funcionais </a> |
<a href="#requisitos-nao-funcionais"> 📚 Requisitos Não Funcionais </a> |
<a href="#product-backlog"> 📖 Product Backlog </a> |
<a href="#dor"> DoR </a> |
<a href="#dod"> DoD </a> |
<a href="#sprints"> 📌 Sprints </a> |
<a href="#tecnologias"> 💻 Tecnologias </a> |
<a href="#padroes-de-commit"> 📨 Padrões de Commit </a> |
<a href="#membros"> 👥 Membros </a> 
</div>

<br>

<h2 id='objetivo'> 🎯 Objetivo </h2>
Este projeto tem como objetivo desenvolver um sistema de monitoramento ambiental para a Tecsus, permitindo a coleta, processamento e visualização de dados meteorológicos em tempo real. A plataforma facilitará a análise de informações como temperatura, umidade, pressão, velocidade do vento e índice pluviométrico, promovendo a conscientização ambiental e auxiliando na prevenção de desastres naturais.

<br>

<h2 id='proposta'> 📧 Proposta de Solução </h2>

Nossa proposta é criar um sistema eficiente e acessível, integrando sensores IoT a uma plataforma moderna para exibição e análise de dados.

✅ Arquitetura Escalável: Utilizaremos uma estrutura robusta para garantir a recepção e o processamento eficiente dos dados enviados pelas estações meteorológicas.

📊 Dashboards Interativos: O sistema apresentará gráficos e relatórios em tempo real, permitindo a análise detalhada dos dados coletados.

🚨 Geração de Alertas: Implementaremos um sistema de notificações automáticas para eventos meteorológicos críticos, auxiliando na tomada de decisões.

🎓 Engajamento Educacional: A plataforma contará com materiais explicativos sobre os conceitos meteorológicos, incentivando a aprendizagem baseada em problemas para estudantes do ensino médio.

<br>

<h2 id='requisitos-funcionais'> 📚 Requisitos Funcionais </h2>

| Número | Descrição |
|--------|-----------|
| RF1 | Permitir o registro de estações meteorológicas com sensores variados, adaptando-se a diferentes tipos de medições. |
| RF2 | Permitir o cadastro, edição, visualização e remoção de estações meteorológicas. |
| RF3 | Permitir o cadastro, edição, visualização e remoção dos parâmetros meteorológicos. |
| RF4 | Permitir o cadastro, edição, visualização e remoção dos alertas de condições críticas. |
| RF5 | Permitir o cadastro, edição, visualização e remoção de usuários com diferentes permissões. |
| RF6 | Receber e armazenar dados enviados em tempo real pelas estações meteorológicas. |
| RF7 | Apresentar os dados coletados por meio de painéis gráficos interativos. |
| RF8 | Gerar alertas automaticamente com base em condições climáticas específicas. |
| RF9 | Implementar um sistema que registre automaticamente os dados lidos pelos sensores (datalogger). |
| RF10 | Construir fisicamente uma estação meteorológica utilizando sensores e componentes eletrônicos. |
| RF11 | Disponibilizar um guia educativo explicando o que significa cada medição feita pela estação. |
| RF12 | Controlar os níveis de acesso ao sistema, permitindo que administradores tenham acesso completo, funcionários tenham acesso às funcionalidades operacionais, e usuários públicos visualizem apenas informações liberadas. |


<br>

<h2 id='requisitos-nao-funcionais'> 📚 Requisitos Não Funcionais </h2>

| Número | Descrição |
|--------|-----------|
| RNF1 | O sistema deve ser fácil de usar e visualmente agradável, especialmente nos painéis com os dados das estações. |
| RNF2 | O sistema deve envolver estudantes do ensino médio com conteúdos educativos claros e interessantes, facilitando o aprendizado. |
| RNF3 | Toda a comunicação entre a plataforma e as aplicações deve ser bem documentada, com exemplos claros para facilitar futuras integrações. |
| RNF4 | O sistema deve ter um processo automático que verifique se tudo está funcionando corretamente antes de publicar uma nova versão. |
| RNF5 | Sempre que houver uma atualização no sistema, ela deve ser publicada automaticamente para que o cliente sempre tenha acesso à versão mais recente, sem precisar esperar ou atualizar manualmente. |

<br>

<h2 id='product-backlog'> 📖 Product Backlog </h2>

<table>
  <thead>
    <tr align="center">
      <th>Rank</th>
      <th>Prioridade</th>
      <th>User Story</th>
      <th>Planning Poker</th>
      <th>Sprint</th>
      <th>Requisito</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>1</td><td>ALTA</td><td>Como administrador, quero que o sistema suporte um modelo de dados dinâmico e permita o cadastro de estações meteorológicas, garantindo flexibilidade na gestão e registro dessas informações.</td><td>3</td><td>1</td><td>RF1</td></tr>
    <tr><td>2</td><td>ALTA</td><td>Como administrador, quero cadastrar novos parâmetros meteorológicos para garantir que todas as medições necessárias sejam registradas corretamente.</td><td>3</td><td>1</td><td>RF3</td></tr>
    <tr><td>3</td><td>ALTA</td><td>Como administrador, quero cadastrar alertas meteorológicos para identificar condições climáticas críticas.</td><td>3</td><td>1</td><td>RF4</td></tr>
    <tr><td>4</td><td>ALTA</td><td>Como administrador, quero cadastrar novos usuários para que possam acessar o sistema conforme suas permissões.</td><td>3</td><td>1</td><td>RF5</td></tr>
    <tr><td>5</td><td>ALTA</td><td>Como administrador, quero editar as informações de uma estação meteorológica para manter os dados sempre atualizados.</td><td>3</td><td>1</td><td>RF2</td></tr>
    <tr><td>6</td><td>ALTA</td><td>Como administrador, quero editar os parâmetros meteorológicos para corrigir informações ou ajustar unidades de medida.</td><td>3</td><td>1</td><td>RF3</td></tr>
    <tr><td>7</td><td>ALTA</td><td>Como administrador, quero editar alertas meteorológicos para ajustar suas condições de ativação e notificação.</td><td>3</td><td>1</td><td>RF4</td></tr>
    <tr><td>8</td><td>ALTA</td><td>Como administrador, quero editar as informações de um usuário para corrigir ou alterar permissões.</td><td>3</td><td>1</td><td>RF5</td></tr>
    <tr><td>9</td><td>ALTA</td><td>Como usuário, quero visualizar uma lista de todas as estações cadastradas no sistema.</td><td>3</td><td>1</td><td>RF2</td></tr>
    <tr><td>10</td><td>ALTA</td><td>Como administrador, quero visualizar uma lista de parâmetros meteorológicos cadastrados para acompanhar e gerenciar as medições do sistema.</td><td>3</td><td>1</td><td>RF3</td></tr>
    <tr><td>11</td><td>ALTA</td><td>Como administrador, quero visualizar uma lista de alertas meteorológicos cadastrados para gerenciar notificações de eventos climáticos críticos.</td><td>3</td><td>1</td><td>RF4</td></tr>
    <tr><td>12</td><td>ALTA</td><td>Como administrador, quero visualizar uma lista de usuários cadastrados para gerenciar acessos e permissões no sistema.</td><td>3</td><td>1</td><td>RF5</td></tr>
    <tr><td>14</td><td>ALTA</td><td>Como administrador, quero excluir estações meteorológicas conforme necessário.</td><td>3</td><td>1</td><td>RF2</td></tr>
    <tr><td>15</td><td>ALTA</td><td>Como administrador, quero excluir parâmetros meteorológicos que não sejam mais necessários para manter o sistema organizado.</td><td>3</td><td>1</td><td>RF3</td></tr>
    <tr><td>16</td><td>ALTA</td><td>Como administrador, quero excluir alertas que não sejam mais necessários para manter o sistema atualizado.</td><td>3</td><td>1</td><td>RF4</td></tr>
    <tr><td>17</td><td>ALTA</td><td>Como administrador, quero excluir usuários inativos ou desnecessários para manter a base de dados organizada.</td><td>3</td><td>1</td><td>RF5</td></tr>
    <tr><td>18</td><td>ALTA</td><td>Como administrador, quero controlar o acesso ao sistema definindo permissões para diferentes usuários.</td><td>2</td><td>1</td><td>RF12</td></tr>
    <tr><td>19</td><td>MÉDIA</td><td>Como sistema, quero emular o recebimento de dados das estações meteorológicas, para que o projeto possa ser desenvolvidos e testados sem equipamentos reais.</td><td>5</td><td>2</td><td>RF6</td></tr>
    <tr><td>20</td><td>MÉDIA</td><td>Como sistema, quero processar os dados recebidos para calcular médias horárias e diárias.</td><td>8</td><td>2</td><td>RF6</td></tr>
    <tr><td>21</td><td>MÉDIA</td><td>Como sistema, quero armazenar os dados recebidos de forma otimizada para suportar grandes volumes de informações.</td><td>5</td><td>2</td><td>RF6</td></tr>
    <tr><td>22</td><td>MÉDIA</td><td>Como administrador, quero acompanhar em tempo real o estado operacional das unidades de coleta, para garantir a continuidade do serviço.</td><td>5</td><td>2</td><td>RF6</td></tr>
    <tr><td>23</td><td>MÉDIA</td><td>Como usuário, quero receber notificações em caso de eventos meteorológicos extremos.</td><td>3</td><td>2</td><td>RF8</td></tr>
    <tr><td>24</td><td>MÉDIA</td><td>Como usuário, quero acessar dashboards interativos com os dados coletados pelas estações.</td><td>8</td><td>2</td><td>RF7</td></tr>
    <tr><td>25</td><td>MÉDIA</td><td>Como usuário, quero filtrar os dados exibidos no dashboard por data, para visualizar informações específicas de um período determinado.</td><td>3</td><td>2</td><td>RF7</td></tr>
    <tr><td>26</td><td>MÉDIA</td><td>Como usuário, quero acessar um tutorial sobre os conceitos meteorológicos apresentados.</td><td>8</td><td>2</td><td>RF11</td></tr>
    <tr><td>27</td><td>BAIXA</td><td>Como sistema, quero receber dados em tempo real das estações meteorológicas físicas, substituindo a emulação, para operar em produção.</td><td>8</td><td>3</td><td>RF6</td></tr>
    <tr><td>28</td><td>BAIXA</td><td>Como administrador, quero monitorar o funcionamento das estações meteorológicas em tempo real.</td><td>8</td><td>3</td><td>RF6</td></tr>
    <tr><td>29</td><td>BAIXA</td><td>Como sistema, quero registrar automaticamente os dados coletados pelas estações meteorológicas em um datalogger, para garantir a persistência e integridade das informações.</td><td>5</td><td>3</td><td>RF9</td></tr>
    <tr><td>30</td><td>BAIXA</td><td>Como administrador, quero gerar relatórios detalhados sobre as condições meteorológicas registradas.</td><td>5</td><td>3</td><td>RF7</td></tr>
    <tr><td>31</td><td>BAIXA</td><td>Como usuário, quero alterar minha senha para garantir a segurança da minha conta.</td><td>3</td><td>3</td><td>RF5</td></tr>
    <tr><td>32</td><td>BAIXA</td><td>Como usuário, quero poder recuperar minha senha caso eu a esqueça, para continuar acessando o sistema.</td><td>3</td><td>3</td><td>RF5</td></tr>


  </tbody>
</table>



<br>

<h2 id='dor'> DoR (Definitions of Ready) </h2>

### User Stories
- Definidas e compreendidas por todos.
- Pequenas o suficiente para serem feitas em uma sprint.

### Critério de Aceitação
- Mensurável e testável.
- Descreve claramente quando a funcionalidade está completa.

### Tarefas
- Identificadas e documentadas para cada User Story.
- Cada tarefa possui um responsável designado.

### Modelo de Dados
- Definido e documentado.
- Campos, tipos de dados e relações claramente especificados.

### Arquitetura do Sistema
- Definida e validada pela equipe técnica.
- Diagramas e decisões arquiteturais documentadas.

<br>

<h2 id='dod'> DoD (Definition of Done) </h2>

### Código
- Implementa todos os critérios de aceitação.
- Todos os testes implementados e executados com sucesso.

### Commit
- Documentados com mensagens claras e descritivas.
- Seguem o padrão de nomenclatura acordado pela equipe.

### Mockups
- Mockups na interface funcionam conforme esperado.
- Experiência do usuário corresponde aos critérios definidos.

### Guia de Instalação
- Detalha todos os passos para configuração e instalação.
- Inclui requisitos de sistema, dependências e configurações de software/hardware.

<br> 

<h2 id='sprints'> 📌 Sprints </h2>

<table>
  <thead>
    <tr align="center">
      <th>Sprints</th>
      <th>Data de Início</th>
      <th>Data de Término</th>
      <th>Documentos</th>
      <th>Status</th>
    </tr>
  </thead>
 <tbody>
  <tr align="center">
    <td>01</td>
    <td>10/03/2025</td>
    <td>30/03/2025</td>
    <td><a href="https://github.com/Sync-FATEC/API-2025.1-4SEM/tree/main/sprints/sprint01/sprint01.md">Relatório</a></td> 
    <td>✅</td>
  </tr>
  <tr align="center">
    <td>02</td>
    <td>07/04/2025</td>
    <td>27/04/2025</td>
    <td><a href="https://github.com/Sync-FATEC/API-2025.1-4SEM/tree/main/sprints/sprint02/sprint02.md">Relatório</a></td> 
    <td>✅</td>
  </tr>
  <tr align="center">
    <td>03</td>
    <td>05/05/2025</td>
    <td>25/05/2025</td>
    <td><a href="https://github.com/Sync-FATEC/API-2025.1-4SEM/tree/main/sprints/sprint03/sprint03.md">Relatório</a></td> 
    <td>🔄</td>
  </tr>
</tbody>
</table>

<h2>:movie_camera: MVP </h2>

<h3>Administrador</h3>
<img src="https://github.com/Sync-FATEC/API-2025.1-4SEM/assets/fb8fb41f-c6d3-4ccc-80b9-806418bed236" 
alt="MVP">

<h3>Cliente</h3>
<img src="https://github.com/Sync-FATEC/API-2025.1-4SEM/assets/cbf1e8a0-4ced-42ec-ae87-976c3e770e8c" 
alt="MVP">

<h3>Estação</h3>
<img src="https://github.com/Sync-FATEC/API-2025.1-4SEM/assets/68cc2987-b201-4e56-a8fb-4a09136bbd8d" 
alt="MVP">

<br>

<h2 id='tecnologias'> 💻 Tecnologias </h2>
<img src="media/tecnologias.png">

<br>

<h2 id='padroes-de-commit'> 📨 Padrões de Commit </h2>
<img src="media/padroes.png">

<br>

<h2 id='membros'> 👥 Membros </h2>

| Foto | Nome | Função | Github | Linkedin |
| :---------: | :---------: | :---------------------: | :-----------------: | :-------: |
| <img src="https://github.com/joaogabgr.png?size=50" width=50px> | João Gabriel Solis | Scrum Master | <a href="https://github.com/joaogabgr"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/joaoggbs/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
| <img src="https://github.com/Ana-Laura-Moratelli.png?size=50" width=50px> | Ana Laura Moratelli | Product Owner | <a href="https://github.com/Ana-Laura-Moratelli"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/anamoratelli/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
| <img src="https://github.com/Karnas01.png?size=50" width=50px> | Arthur Karnas | Desenvolvedor | <a href="https://github.com/Karnas01"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/arthur-karnas-da-rocha-b90433271/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
| <img src="https://github.com/yokotaerik.png?size=50" width=50px> | Erik Yokota | Desenvolvedor | <a href="https://github.com/yokotaerik"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/erik-camara-yokota-685439233/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
| <img src="https://github.com/collafilipe.png?size=50" width=50px> | Filipe Colla | Desenvolvedor | <a href="https://github.com/collafilipe"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/filipe-colla?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
| <img src="https://github.com/ZduardoPereira.png?size=50" width=50px> | José Eduardo Fernandes | Desenvolvedor | <a href="https://github.com/ZduardoPereira"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/jos%C3%A9-eduardo-fernandes-pereira-b26517284/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
| <img src="https://github.com/Kaue-Francisco.png?size=50" width=50px> | Kauê Francisco | Desenvolvedor | <a href="https://github.com/Kaue-Francisco"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/kau%C3%AA-francisco-3b13aa255/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> |

<a href='#topo'> Voltar ao topo </a>
