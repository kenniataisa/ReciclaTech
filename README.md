# :checkered_flag: ReciclaTech

ReciclaTech - Plataforma de Economia Circular para Resíduos Eletrônicos

## :technologist: Membros da equipe

Nome: Kennia Taisa Silva Santos <br/>
Matrícula: 571798  <br/>
Curso: Ciência da Computação  <br/>

## :bulb: Objetivo Geral
ReciclaTech é uma plataforma web que conecta pessoas que desejam descartar dispositivos eletrônicos com pontos de coleta autorizados, promovendo a conscientização ambiental e o descarte correto de resíduos eletrônicos na comunidade.

## :eyes: Público-Alvo
- Comunidade acadêmica e geral que necessita descartar equipamentos eletrônicos
- Pontos de coleta de resíduos eletrônicos
- Empresas recicladoras
## :star2: Impacto Esperado
- Aumento do descarte correto de resíduos eletrônicos na comunidade
- Conscientização sobre impactos ambientais do lixo eletrônico
- Facilitação do acesso a pontos de coleta adequados

## :people_holding_hands: Papéis ou tipos de usuário da aplicação

1. Administrador
  - Gerenciamento de usuários e pontos de coleta
  - Acesso a relatórios básicos
    
2. Ponto de Coleta
  - Gerenciamento de horários
  - Registro de recebimentos
   
3. Usuário Comum
  - Registro de dispositivos
  - Agendamento de entregas
    
## :triangular_flag_on_post:	 Principais funcionalidades da aplicação

**Funcionalidades Públicas**
  - Consulta de pontos de coleta
  - Visualização de materiais aceitos
  - Informações sobre reciclagem
    
**Funcionalidades Restritas**
  - Cadastro e gestão de dispositivos
  - Agendamento de coletas
  - Gestão de pontos de coleta

## :spiral_calendar: Entidades ou tabelas do sistema

1. Usuários
    - nome
    - email
    - senha
    - tipo
    - endereço

2. Pontos de Coleta
    - nome
    - endereço
    - horário_funcionamento
    - tipos_aceitos
      
3. Agendamentos
    - usuario_id
    - ponto_coleta_id
    - data_hora
    - status
    - dispositivos
----

## :desktop_computer: Tecnologias e frameworks utilizados

**Frontend:**
  - HTML5
  - CSS3
  - TypeScript
  - Bootstrap 5

**Backend:**
  - Strapi v4
  - SQLite


## :shipit: Operações implementadas para cada entidade da aplicação


| Entidade| Criação | Leitura | Atualização | Remoção |
| --- | --- | --- | --- | --- |
| Pontos de Coleta | X |  X  | X | X |
| Agendamentos | X |  X |  X | X |
| Usuários | X |  X  | X |  |

> Lembre-se que é necessário implementar o CRUD de pelo menos duas entidades.

## :neckbeard: Rotas da API REST utilizadas

| Método HTTP | URL |
| --- | --- |
| GET | api/collection-points|
| POST | api/collection-points |
| GET | api/shedules|
| POST | api/shedules|
| PUT | /api/schedules/{id}|
| GET | api/users|
| POST | api/auth/local|
