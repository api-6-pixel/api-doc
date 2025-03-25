<h1 align="center"> Sistema Inteligente de Planejamento e Monitoramento de Reflorestamento (SIPMR) </h1>

## :page_facing_up: Desafio Proposto
Este projeto visa desenvolver um sistema inteligente para planejamento e monitoramento de reflorestamento, utilizando uma base de dados de plantio para prever padrões de crescimento, 
sugerir melhores estratégias de recuperação ambiental e monitorar a evolução das áreas reflorestadas.


## :books: Solução
Nosso sistema proporcionará um controle eficiente de dados agrícolas, abrangendo informações sobre plantio, espécies cultivadas, condições ambientais e lotes. Com uma interface intuitiva, os usuários poderão acompanhar esses dados em tempo real, garantindo maior organização e precisão no gerenciamento dos lotes. 

O principal objetivo é permitir a projeção detalhada do crescimento da colheita mês a mês, facilitando o planejamento estratégico e a tomada de decisões. Além disso, o sistema oferecerá estimativas do custo projetado para o tratamento de cada lote e tipo de solo, auxiliando no controle financeiro e na otimização dos recursos disponíveis


## :clipboard: Backlog
<details>  
<summary> Confira o backlog do produto: </summary>
<br>
<table>
  <tr>
    <th>Prioridade</th>
    <th>Feature</th>
    <th>Sprint</th>
    <th>Requisitos</th>
  </tr>
  <tr>
    <td>Alta</td>
    <td>Dashboard Projeção de crescimento da colheita do lote informado</td>
    <td>1</td>
    <td></td>
  </tr>
  
  <tr>
    <td>Alta</td>
    <td>Dashboard Projeção de desempenho (R$) da espécie com base nas condições de cada lote</td>
    <td>1</td>
    <td></td>
  </tr>
  
  
  <tr>
    <td>Alta</td>
    <td>Dashboard Projeção de gastos com tratamento do solo</td>
    <td>1</td>
    <td></td>
  </tr>
  
  
  <tr>
    <td>Alta</td>
    <td>Tela de dashboards</td>
    <td>1</td>
    <td></td>
  </tr>
  
  
  <tr>
    <td>Alta</td>
    <td>Tela de atualização diária de plantios</td>
    <td>1</td>
    <td></td>
  </tr>
  
  
  <tr>
    <td>Alta</td>
    <td>Tela de cadastro de plantios</td>
    <td>1</td>
    <td></td>
  </tr>
  
  
  <tr>
    <td>Alta</td>
    <td>Autenticação de Usuário</td>
    <td>2</td>
    <td></td>
  </tr>
  
  
  <tr>
    <td>Alta</td>
    <td>Cadastro de Usuário</td>
    <td>2</td>
    <td></td>
  </tr>
  
  
  <tr>
    <td>Alta</td>
    <td>Deleção de Conta</td>
    <td>2</td>
    <td></td>
  </tr>
  
  
  <tr>
    <td>Alta</td>
    <td>Permissionamento da tela de Usuário</td>
    <td>2</td>
    <td></td>
  </tr>
  
  
  <tr>
    <td>Alta</td>
    <td>Notificação de vazamento de dados do usuários</td>
    <td>2</td>
    <td></td>
  </tr>
  
  
  <tr>
    <td>Alta</td>
    <td>Visualização de Informações Pessoais</td>
    <td>2</td>
    <td></td>
  </tr>
  
  
  <tr>
    <td>Alta</td>
    <td>Atualização de dados Pessoais</td>
    <td>2</td>
    <td></td>
  </tr>
  
  
  <tr>
    <td>Alta</td>
    <td>Cadastro de Lotes</td>
    <td>3</td>
    <td></td>
  </tr>
  
  
  <tr>
    <td>Alta</td>
    <td>Visualização de Lotes</td>
    <td>3</td>
    <td></td>
  </tr>
  
  
  <tr>
    <td>Alta</td>
    <td>Deleção de Lotes</td>
    <td>3</td>
    <td></td>
  </tr>
  
  
  <tr>
    <td>Alta</td>
    <td>Portabilidade de Dados</td>
    <td>3</td>
    <td></td>
  </tr>
</table>
</details>

## Requisitos Funcionais
<details>
  <table>
    <tr>
      <td>RF-1</td>
      <td>O sistema deve permitir o gerenciamento de usuários, garantindo que exista dois tipos de acesso: Operador com permissão de gerir os dados da plataforma e Usuário com permissão de visualização dos gráficos.</td>
    </tr>
    <tr>
      <td>RF-2</td>
      <td>O sistema deve permitir gerenciar um plantio, permitindo listá-lo, excluí-lo e cadastrá-lo.</td>
    </tr>
    <tr>
      <td>RF-3</td>
      <td>O sistema deve permitir gerenciar espécies, permitindo listá-las, excluí-las e cadastrá-las.</td>
    </tr>
    <tr>
      <td>RF-4</td>
      <td>O sistema deve permitir gerenciar condições ambientais, permitindo listá-las, excluí-las e cadastrá-las.</td>
    </tr>
    <tr>
      <td>RF-5</td>
      <td>O sistema deve permitir gerenciar lotes, permitindo listá-los, excluí-los e cadastrá-los.</td>
    </tr>
    <tr>
      <td>RF-6</td>
      <td>O sistema deve fornecer um dashboard detalhado aos usuários que permita realizar as seguintes projeções:
          <ul>
            <li>Projeção de crescimento da colheita do lote informado (mês)</li>
            <li>Projeção de desempenho (R$) da espécie com base nas condições de cada lote</li>
            <li>Projeção de gastos com tratamento do solo</li>
          </ul>
      </td>
    </tr>
    <tr>
      <td>RF-7</td>
      <td>O sistema deve solicitar autorização explícita do usuário antes de coletar seus dados pessoais.</td>
    </tr>
    <tr>
      <td>RF-8</td>
      <td>O sistema deve permitir que os usuários solicitem a modificação ou exclusão de seus dados pessoais a qualquer momento.</td>
    </tr>
    <tr>
      <td>RF-9</td>
      <td>O sistema deve disparar e-mails para todos os usuários em caso de vazamento de dados notificando os dados expostos.</td>
    </tr>
  </table>
</details>

## Requisitos não funcionais
<details>
  <table>
    <tr>
      <td>RNF-1</td>
      <td>O sistema deve utilizar modelos de aprendizado de máquina para prever dados relevantes ao plantio.</td>
    </tr>
    <tr>
      <td>RNF-2</td>
      <td>O sistema deve fornecer uma política de privacidade clara, informando aos usuários como seus dados serão utilizados, por quanto tempo serão armazenados, e quais dados específicos serão coletados.</td>
    </tr>
    <tr>
      <td>RNF-3</td>
      <td>O sistema deve permitir que seja realizada a portabilidade dos dados do usuário do sistema para qualquer outro, mantendo os dados seguros durante todo o processo.</td>
    </tr>
    <tr>
      <td>RNF-4</td>
      <td>O sistema deve ser otimizado para exibição em telas de desktop.</td>
    </tr>
    <tr>
      <td>RNF-5</td>
      <td>O sistema deve implementar autenticação e autorização usando tokens JWT.</td>
    </tr>
    <tr>
      <td>RNF-6</td>
      <td>O sistema deve ser compatível com os navegadores mais utilizados (Edge, Chrome e Firefox).</td>
    </tr>
  </table>
</details>

## :calendar: Entregas

| Sprint | Periodo | Status |
| :---: | :---: | :---: |
| 1 | 30/03/25 - 30/03/25 |:white_check_mark:  |
| 2 | 30/09/25 - 20/10/25 |:white_check_mark:  |
| 3 | 21/10/25 - 10/11/25 |  |


## :busts_in_silhouette: Equipe de desenvolvimento

| Função | Nome |
| :---: | :---: |
| Product Owner | [Matheus Cruz Fiebig](https://github.com/matheus-fiebig) |
| Scrum Master | [Luciano do Nascimento Pamplona da Silva](https://github.com/lucianonps) |
| Dev | [Alisson dos Santos Pereira](https://github.com/41issonm) |
| Dev | [Beatrice Lopes Correa](https://github.com/beatricelopes) |
| Dev | [Danillo Wesley da Costa Silva](https://github.com/xxzidanilloxx) |
| Dev | [Wagner de Deus da Silva Júnior](https://github.com/wdeus) |
