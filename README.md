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
    <td>RF-6, RNF-1</td>
  </tr>
  <tr>
    <td>Alta</td>
    <td>Dashboard Projeção de desempenho (R$) da espécie com base nas condições de cada lote</td>
    <td>1</td>
    <td>RF-6, RNF-1</td>
  </tr>
  <tr>
    <td>Alta</td>
    <td>Dashboard Projeção de gastos com tratamento do solo</td>
    <td>1</td>
    <td>RF-6, RNF-1</td>
  </tr>
  <tr>
    <td>Alta</td>
    <td>Tela de dashboards</td>
    <td>1</td>
    <td>RF-6, RNF-1, RNF-4, RNF-6</td>
  </tr>
  <tr>
    <td>Alta</td>
    <td>Tela de atualização diária de plantios</td>
    <td>1</td>
    <td>RF-3, RNF-4, RNF-6</td>
  </tr>
  <tr>
    <td>Alta</td>
    <td>Tela de cadastro de plantios</td>
    <td>1</td>
    <td>RF-2, RNF-4, RNF-6</td>
  </tr>
  <tr>
    <td>Alta</td>
    <td>Autenticação de Usuário</td>
    <td>2</td>
    <td>RF-1, RNF-4, RNF-6, RNF-5</td>
  </tr>
  <tr>
    <td>Alta</td>
    <td>Criação de Conta</td>
    <td>2</td>
    <td>RF-1, RNF-4, RNF-6, RF-7, RNF-2</td>
  </tr>
  <tr>
    <td>Media</td>
    <td>Deleção de Conta</td>
    <td>2</td>
    <td>RF-8, RNF-4, RNF-6</td>
  </tr>
  <tr>
    <td>Media</td>
    <td>Permissionamento da tela de Usuário</td>
    <td>2</td>
    <td>RF-1, RNF-4, RNF-6</td>
  </tr>
  <tr>
    <td>Alta</td>
    <td>Notificação de vazamento de dados do usuários</td>
    <td>2</td>
    <td>RF-09, RNF-02</td>
  </tr>
  <tr>
    <td>Baixa</td>
    <td>Visualização de Informações Pessoais</td>
    <td>2</td>
    <td>RF-5, RNF-2</td>
  </tr>
  <tr>
    <td>Baixa</td>
    <td>Atualização de dados Pessoais</td>
    <td>2</td>
    <td>RNF-2, RF-5, RF-1 </td>
  </tr>
  <tr>
    <td>Media</td>
    <td>Cadastro de Lotes</td>
    <td>3</td>
    <td>RF-4, RNF-4, RNF-6</td>
  </tr>
  
  
  <tr>
    <td>Media</td>
    <td>Visualização de Lotes</td>
    <td>3</td>
    <td>RF-4, RNF-4, RNF-6</td>
  </tr>
  
  
  <tr>
    <td>Media</td>
    <td>Deleção de Lotes</td>
    <td>3</td>
    <td>RF-4, RNF-4, RNF-6</td>
  </tr>
  
  
  <tr>
    <td>Baixa</td>
    <td>Portabilidade de Dados</td>
    <td>3</td>
    <td>RF-7, RNF-3, RNF-02</td>
  </tr>
</table>
</details>

#### Requisitos Funcionais
<details>
  <table>
  <thead>
    <tr>
      <th>RF-id</th>
      <th>Requisito</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>RF-01</td>
      <td>Gerenciamento de Usuários</td>
      <td>O sistema deve permitir o gerenciamento de usuários, com dois tipos de acesso: <strong>Operador</strong> (gestão de dados) e <strong>Usuário</strong> (visualização de gráficos e dados do plantio). O objetivo é garantir a segurança e evitar acesso não autorizado aos dados sensíveis.</td>
    </tr>
    <tr>
      <td>RF-02</td>
      <td>Cadastro de Plantio</td>
      <td>O sistema deve permitir ao usuário inserir dados iniciais da colheita e criar vários lotes atrelados ao plantio. Cada lote deve incluir informações sobre <strong>espécie</strong>, <strong>quadrante</strong>, <strong>condição ambiental</strong> do dia e <strong>dados do solo</strong>.</td>
    </tr>
    <tr>
      <td>RF-03</td>
      <td>Atualização de Plantio Diário</td>
      <td>O sistema deve permitir que o usuário atualize todas as informações do plantio, exceto a <strong>espécie plantada</strong>. Além disso, o usuário poderá <strong>finalizar o plantio</strong> após a colheita, liberando o espaço para novos plantios.</td>
    </tr>
    <tr>
      <td>RF-04</td>
      <td>Gerenciamento de Lotes</td>
      <td>O sistema deve permitir ao usuário cadastrar, visualizar, deletar e gerenciar os lotes. Esses lotes podem ser utilizados nas funcionalidades do sistema, como projeção gráfica e atualização de dados.</td>
    </tr>
    <tr>
      <td>RF-05</td>
      <td>Disponibilização de Dados do Usuário</td>
      <td>O sistema deve permitir que os usuários visualizem e gerenciem seus próprios dados pessoais cadastrados, garantindo a conformidade com a LGPD (Lei Geral de Proteção de Dados).</td>
    </tr>
    <tr>
      <td>RF-06</td>
      <td>Projeção Gráfica dos Lotes</td>
      <td>O sistema deve oferecer um <strong>dashboard</strong> com projeções gráficas detalhadas para o usuário, incluindo: <strong>crescimento da colheita</strong>, <strong>desempenho financeiro (R$)</strong> da espécie, e <strong>gastos com tratamento do solo</strong> para cada lote.</td>
    </tr>
    <tr>
      <td>RF-07</td>
      <td>Autorização dos Termos de Uso</td>
      <td>O sistema deve solicitar <strong>autorização explícita</strong> do usuário em relação aos termos de uso</td>
    </tr>
    <tr>
      <td>RF-08</td>
      <td>Modificação ou Exclusão de Dados Pessoais</td>
      <td>O sistema deve permitir que o usuário solicite a <strong>modificação</strong> ou <strong>exclusão</strong> de seus dados pessoais a qualquer momento, proporcionando controle total sobre seus dados.</td>
    </tr>
    <tr>
      <td>RF-09</td>
      <td>Notificação de Vazamento de Dados</td>
      <td>O sistema deve enviar <strong>e-mails de notificação</strong> a todos os usuários em caso de <strong>vazamento de dados</strong>, informando quais dados foram expostos, conforme necessário pela LGPD.</td>
    </tr>
  </tbody>
</table>
</details>

#### Requisitos não funcionais
<details>
  <table>
  <thead>
    <tr>
      <th>RNF-id</th>
      <th>Requisito</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>RNF-01</td>
      <td>Aprendizado de Máquina</td>
      <td>O sistema deve utilizar <strong>modelos de aprendizado de máquina</strong> para prever dados importantes para o plantio, como crescimento, desempenho financeiro e necessidade de tratamentos do solo.</td>
    </tr>
    <tr>
      <td>RNF-02</td>
      <td>Transparência no Uso de Dados</td>
      <td>O sistema deve fornecer uma <strong>política de privacidade</strong> clara, informando como os dados dos usuários serão utilizados, por quanto tempo serão armazenados e quais dados específicos serão coletados, garantindo transparência e confiança.</td>
    </tr>
    <tr>
      <td>RNF-03</td>
      <td>Portabilidade de Dados</td>
      <td>O sistema deve permitir que os <strong>dados do usuário</strong> possam ser exportados e transferidos para <strong>outros sistemas</strong>, mantendo a segurança durante o processo de portabilidade, conforme exigido pela LGPD.</td>
    </tr>
    <tr>
      <td>RNF-04</td>
      <td>Compatibilidade com Resolução de Tela Desktop</td>
      <td>O sistema deve ser <strong>otimizado para telas de desktop</strong>, garantindo uma boa visualização e experiência de uso em dispositivos de tela maior.</td>
    </tr>
    <tr>
      <td>RNF-05</td>
      <td>Autenticação com JWT</td>
      <td>O sistema deve implementar <strong>autenticação e autorização utilizando tokens JWT</strong> (JSON Web Tokens), garantindo segurança nas interações do sistema e no acesso aos dados dos usuários.</td>
    </tr>
    <tr>
      <td>RNF-06</td>
      <td>Compatibilidade com Navegadores Principais</td>
      <td>O sistema deve ser <strong>compatível com os principais navegadores</strong> da web, como <strong>Edge</strong>, <strong>Chrome</strong> e <strong>Firefox</strong>, para garantir que todos os usuários possam acessar a plataforma de maneira funcional e sem problemas de compatibilidade.</td>
    </tr>
  </tbody>
</table>
</details>


#### DOR
<details>
  • A história esta testável(com BDD definido). <br>
  • Prioridades da história esta alinhada com cliente. <br>
  • Quebra da história realizada e pontuada. <br>
  • Requisitos estão definidos na história. <br>
</details>

#### DOD
<details>
  • Testes foram realizados na branch de develop. <br>
  • Projetos afetados descritos no JIRA. <br>
  • Todas histórias movidas para CONCLUÍDO. <br>
</details>

#### Dicionario de dados
<details>

##### tb_atualizacao
| Nome | Tipo | Constraint | Observação |
|------|------|------------|------------|
| atualizacao_indice_uv | double precision | NOT NULL | Índice U.V. do solo em % |
| atualizacao_ph_solo | double precision | NOT NULL | PH do solo em % |
| atualizacao_temperatura_ambiente | double precision | NOT NULL | Temperatura ambiente em Celsius |
| atualizacao_temperatura_solo | double precision | NOT NULL | Temperatura do solo em Celsius |
| atualizacao_umidade_ambiente | double precision | NOT NULL | Umidade do ambiente |
| atualizacao_umidade_solo | double precision | NOT NULL | Umidade o solo |
| atualizacao_id | bigint | PRIMARY KEY (IDENTITY) | Identificador único |
| atualizacao_registro | timestamp | NOT NULL | Data hora da criação do registro |
| plantacao_id | bigint | NOT NULL, FK | Campo de relacionamento com a tabela de tb_plantacao |

##### tb_cad_termo
| Nome | Tipo | Constraint | Observação |
|------|------|------------|------------|
| codigo | bigint | PRIMARY KEY (IDENTITY) | Identificador único |
| data_criacao | timestamp | NULLABLE | Data hora da criação do registro |
| descricao | character varying(255) | NULLABLE | Descrição o termo |
| titulo | character varying(255) | NULLABLE | Titulo do termo |
| versao | character varying(255) | NULLABLE | Qual a versão eu o termo se encontra |

##### tb_cad_termo_item
| Nome | Tipo | Constraint | Observação |
|------|------|------------|------------|
| obrigatorio | boolean | NOT NULL | Obrigatoriedade deste termo |
| codigo | bigint | PRIMARY KEY (IDENTITY) | Identificador único |
| termo_codigo | bigint | NOT NULL, FK | Campo de relacionamento com a tabela de tb_cad_termo |
| descricao | character varying(255) | NULLABLE | Descrição o item do termo |

##### tb_cad_termo_item_aceite
| Nome | Tipo | Constraint | Observação |
|------|------|------------|------------|
| aceito | boolean | NOT NULL | Se o termo foi aceito ou não |
| codigo | bigint | PRIMARY KEY (IDENTITY) | Identificador único |
| termo_aceite_codigo | bigint | NOT NULL | Campo de relacionamento com a tabela de tb_cad_termo_item_aceite_usuario_historico |
| termo_item_codigo | bigint | NOT NULL, FK | Campo de relacionamento com a tabela de tb_cad_termo_item |

##### tb_cad_termo_item_aceite_usuario_historico
| Nome | Tipo | Constraint | Observação |
|------|------|------------|------------|
| codigo | bigint | PRIMARY KEY (IDENTITY) | Identificador único |
| data_aceite | timestamp | NULLABLE | Data hora de aceite |
| data_alteracao | timestamp | NULLABLE | Data hora de alteração do termo |
| termo_codigo | bigint | NOT NULL FK | Campo de relacionamento com a tabela de tb_cad_termo |
| usuario_codigo | bigint | NOT NULL FK | Campo de relacionamento com a tabela de tb_usuario |

##### tb_fazenda
| Nome | Tipo | Constraint | Observação |
|------|------|------------|------------|
| fazenda_area | double precision | NOT NULL | Area de plantio da fazenda |
| fazenda_criacao | timestamp | NOT NULL | Data hora de criação do registro |
| fazenda_id | bigint | PRIMARY KEY (IDENTITY) | Identificador único |
| fazenda_localizacao | character varying(255) | NOT NULL | Localização da fazenda |
| fazenda_nome | character varying(255) | NOT NULL | Nome da fazenda |

##### tb_plantacao
| Nome | Tipo | Constraint | Observação |
|------|------|------------|------------|
| plantacao_area | double precision | NOT NULL | Area de plantação |
| plantacao_custo | double precision | NOT NULL | Custo estimado |
| plantacao_data | timestamp | NOT NULL | Data hora da criação do registro |
| plantacao_id | bigint | PRIMARY KEY (IDENTITY) | Identificador único |
| usuario_id | bigint | NOT NULL, FK | Campo de relacionamento com a tabela de tb_usuario |
| plantacao_especie | character varying(255) | NOT NULL | Espécie plantada |
| plantacao_fazenda | character varying(255) | NOT NULL | Nome do lote |

##### tb_usuario
| Nome | Tipo | Constraint | Observação |
|------|------|------------|------------|
| usuario_dt_criacao | timestamp | NOT NULL | Data hora da criação do registro |
| usuario_id | bigint | PRIMARY KEY (IDENTITY) | Identificador único |
| usuario_documento | character varying(255) | NOT NULL | CPF/CNPJ (criptografada) |
| usuario_email | character varying(255) | NOT NULL | Email do usuário |
| usuario_funcao | character varying(255) | NOT NULL | Funaro do usuário no sistema (criptografada) |
| usuario_nome | character varying(255) | NOT NULL | Nome do usuário (criptografada) |
| usuario_senha | character varying(255) | NOT NULL | Senha o usuário (criptografada) |
  
</details>

## Sprint 1

<details>
<summary>Dashboard de Projeções</summary>

**Requisitos:**
- Projeção de crescimento da colheita do lote informado (mensal)
- Projeção de desempenho (R$) da espécie com base nas condições de cada lote
- Projeção de gastos com tratamento do solo

</details>

<details>
<summary>Cadastro de Plantio</summary>

**Requisitos:**
- Cada lote deve conter:
  - Espécie plantada
  - Quadrante
  - Condição ambiental do dia
  - Dados relacionados ao solo

</details>

<details>
<summary>Atualização Diária de Plantio</summary>

**Requisitos:**
- Permitir atualização de todas as informações, exceto a espécie plantada
- Possibilitar finalização do plantio após a colheita
- Liberar o quadrante para novo plantio após colheita

</details>

---

## Sprint 2

<details>
<summary>[PX-41] Autenticação de Usuários</summary>

**Requisitos:**
- Gerenciamento de Usuário
- Compatibilidade com Resolução de Tela Desktop
- Autenticação com JWT
- Compatibilidade com Navegadores Principais

</details>

<details>
<summary>[PX-42] Cadastro de Usuário</summary>

**Requisitos:**
- Gerenciamento de Usuários
- Aceite dos termos de uso
- Transparência no Uso de Dados
- Compatibilidade com Resolução de Tela Desktop
- Compatibilidade com Navegadores Principais

</details>

<details>
<summary>[PX-47] Visualização de Dados Pessoais</summary>

**Requisitos:**
- Gerenciamento de Usuários
- Transparência no Uso de Dados
- Compatibilidade com Resolução de Tela Desktop
- Compatibilidade com Navegadores Principais

</details>

<details>
<summary>[PX-43] Deleção de Conta</summary>

**Requisitos:**
- Gerenciamento de Usuários
- Modificação ou Exclusão de Dados Pessoais
- Compatibilidade com Resolução de Tela Desktop
- Compatibilidade com Navegadores Principais

</details>

<details>
<summary>[PX-48] Atualização de Dados Pessoais</summary>

**Requisitos:**
- Gerenciamento de Usuários
- Modificação ou Exclusão de Dados Pessoais
- Compatibilidade com Resolução de Tela Desktop
- Compatibilidade com Navegadores Principais

</details>

<details>
<summary>[PX-46] Notificação de Vazamento de Dados</summary>

**Requisitos:**
- Permissionamento de Usuário
- Transparência no Uso de Dados

</details>

---

## Sprint 3

<details>
<summary>[PX-110] Uso Administrativo do Sistema</summary>

**Requisitos:**
- Permissionamento do sistema
- Visibilidade de Lotes do Usuário
- Compatibilidade com Navegadores Principais
- Compatibilidade com Resolução Desktop

</details>

<details>
<summary>[PX-111] Portabilidade de Dados</summary>

**Requisitos:**
- Portabilidade dos dados

</details>

<details>
<summary>[PX-113] Como Melhorar a Sua Colheita</summary>

**Requisitos:**
- Projeção gráfica dos lotes
- Melhoria de Lotes do Usuário

</details>

<details>
<summary>[PX-145] Extração de Dados de Lote do Usuário</summary>

**Requisitos:**
- Extração de dados do plantio via Excel
- Disponibilização dos dados offline
- Compatibilidade com Navegadores Principais
- Compatibilidade com Resolução Desktop

</details>

<details>
<summary>[PX-146] Extração de Dados de Projeção do Usuário</summary>

**Requisitos:**
- Extração de dados de previsibilidade do lote via Excel

</details>


## :calendar: Entregas

| Sprint | Periodo | Status |
| :---: | :---: | :---: |
| 1 | 10/03/25 - 30/03/25 |:white_check_mark:  |
| 2 | 07/04/25 - 27/04/25 |:white_check_mark: |
| 3 | 05/05/25 - 25/05/25 |:white_check_mark: |


## :busts_in_silhouette: Equipe de desenvolvimento

| Função | Nome |
| :---: | :---: |
| Product Owner | [Matheus Cruz Fiebig](https://github.com/matheus-fiebig) |
| Scrum Master | [Luciano do Nascimento Pamplona da Silva](https://github.com/lucianonps) |
| Dev | [Alisson dos Santos Pereira](https://github.com/41issonm) |
| Dev | [Beatrice Lopes Correa](https://github.com/beatricelopes) |
| Dev | [Danillo Wesley da Costa Silva](https://github.com/xxzidanilloxx) |
| Dev | [Wagner de Deus da Silva Júnior](https://github.com/wdeus) |
