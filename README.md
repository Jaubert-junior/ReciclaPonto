# Recicle +
# 1.Identificação do projeto
## Equipe: 
- Chrislley Emylly
- Francisco Flávio
- Jaubert Junior
- Thiario Lima

## Disciplina
Projeto Integrador
## Professor
Ely Miranda

-----
# 2. Problema a ser Resolvido
O descarte inadequado de resíduos sólidos é um dos principais desafios ambientais no Brasil. Apesar da existência da Política Nacional de Resíduos Sólidos (Lei nº 12.305/2010), grande parte da população não possui acesso facilitado às informações sobre locais corretos para descarte de materiais recicláveis. 

# 3. Objetivo do Projeto
O projeto Recicle+ tem como objetivo facilitar a logística reversa de resíduos recicláveis, reduzir o descarte inadequado em aterros sanitários e promover a conscientização ambiental da população. A proposta busca oferecer uma solução tecnológica acessível que conecte cidadãos a pontos de coleta seletiva, incentivando práticas sustentáveis e contribuindo para a preservação ambiental e melhoria da qualidade de vida.

# 4. Público-Alvo
- Cidadãos

# 5. Tecnologias Utilizadas
| Área | Tecnologia |
|------|------------|
| Front-end | HTML / CSS / JS |
| Back-end | Flask |
| Banco | MySQL|
| Prototipação | Canva |
| Gestão | Trello |


# 6. Requisitos do Sistema
## Atores
- Administrador
- Cidadão
- Google Maps API

## Regras de Negócio
- Unicidade de Cadastro: Cada usuário deve ser identificado por um e-mail único. Não é permitido criar mais de uma conta com o mesmo e-mail.
-  Perfil de Acesso: O sistema deve distinguir entre Cidadão (acesso ao mapa, ranking e perfil) e Administrador (acesso aos logs e gestão de denúncias).
- Persistência de Sessão: A sessão do usuário deve permanecer ativa por até 7 dias, a menos que o usuário solicite explicitamente o "Logout".
- Disponibilidade do Mapa: O mapa interativo só exibirá pontos de coleta se o usuário permitir o acesso à localização do navegador ou informar um endereço/CEP válido.
- Raio de Busca: Por padrão, o sistema deve sugerir os pontos de coleta num raio de até 10km da posição atual do usuário, permitindo a expansão manual desse filtro.
- Cadastro de Novos Pontos: Qualquer cidadão pode sugerir um novo ponto de coleta, mas este só ficará visível para os demais usuários após a aprovação de um Administrador.
- Atribuição de Pontos: O usuário ganhará pontos ao:
1.Realizar check-in em um ponto de coleta (10 pts).
2.Sugerir um novo ponto que venha a ser aprovado (50 pts).
3.Reportar um erro ou denúncia que seja verídica (10 pts).
- Limite de Check-in: Para evitar fraudes, um usuário só pode realizar 1 check-in por dia no mesmo ponto de coleta.
- Atualização do Ranking: O ranking global deve ser processado e atualizado semanalmente.
- Suspensão de Pontos: Se um ponto de coleta receber 3 ou mais denúncias de "insalubridade" ou "inexistência" em um período de 48h, ele deve ser ocultado automaticamente do mapa até a revisão administrativa.
- Prova Visual: Toda denúncia ou sugestão de novo ponto deve obrigatoriamente conter pelo menos uma foto anexada para fins de auditoria.
- Conexão Obrigatória: O sistema não deve permitir o carregamento de novas rotas ou busca de pontos sem conexão ativa com a internet.
- Natureza do Serviço: O sistema não realiza agendamento de coletas domiciliares nem processa pagamentos financeiros (recompensa apenas via pontos virtuais).

## Backlog
| ID | Item | Prioridade | Status |
|----|------|------------|--------|
| 1 |Login de Usuário| Alta|Em desenvolvimento
| 2 |Busca de Pontos|Alta|Pendente
| 3 |Filtro de Resíduos|Média|Pendente
| 4 |Ranking|Média|Pendente
| 5 |Denúncia de Pontos|Baixa|Pendente
| 6 |Informações Educativas|Baixa|Pendente
| 7 |Perfil do Usuario|Baixa|Pendente
| 8 |Compartilhamento Social|Baixa|Pendente
| 9 |Reportar Erros|Baixa|Pendente
| 10 |Controle de sessões|Baixa|Pendente

## Histórias de Usuário
- Como usuário quero fazer login com minhas credenciais para acessar o sistema.
- Como cidadão eu quero buscar por pontos de coleta seletiva mais próximos de minha residência ou de outro lugar selecionado.
- Como cidadão quero filtrar os locais por um tipo específico de resíduos.
- Como cidadão quero visualizar o ranking de usuários, para que possa comparar meu engajamento com o de outros.
- Como cidadão eu quero realizar denúncias de pontos de coleta insalubres para manter a integridade do sistema.
- Como cidadão eu quero acessar informações educativas sobre reciclagem.
- Como cidadão quero visualizar meu perfil para adicionar ou alterar uma foto de perfil.
- Como cidadão, quero compartilhar meu progresso no ranking em redes sociais, para que eu incentive meus amigos a também reciclarem.
- Como cidadão quero Reportar Erros no sistema.
- Como administrador eu quero conseguir  um registro com os acessos do sistema para manter um controle de sessões. 

# 7. Modelagem do Sistema
## Diagrama de Casos de Uso
- motivo da ausência: Ainda em desenvolvimento
- etapa em que será produzido: Planejamento de sprints;
- Previsão de entrega: 07/04/26;
- Responsável: equipe
## Fluxo de Telas
- motivo da ausência: Ainda em desenvolvimento
- etapa em que será produzido: Planejamento de sprints;
- Previsão de entrega: 07/04/26;
- Responsável: equipe
## Arquitetura
- motivo da ausência: Ainda em desenvolvimento
- etapa em que será produzido: Planejamento de sprints;
- Previsão de entrega: 07/04/26;
- Responsável: equipe
## Modelo Entidade-Relacionamento
- motivo da ausência: Ainda em desenvolvimento
- etapa em que será produzido: Implementação;
- Previsão de entrega: 07/04/26;
- Responsável: equipe
## Diagrama de Classes
- motivo da ausência: Ainda em desenvolvimento
- etapa em que será produzido: Implementação;
- Previsão de entrega: 07/04/26;
- Responsável: equipe

# 8. Protótipos
## Tela de Login
[Login](docs/prototipos/login_e_cadastro.jpg)
## Cadastro
[Cadastro](docs/prototipos/cadastro.png)
## Ranking
[ranking](ranking.jpg)
## Mapa
[mapa](visualizar_pontos.jpg)
---
# 9. Planejamento do Projeto
## Cronograma
| Etapa | Período |
|------|---------|
| Levantamento | 17/02 a 08/04 |
| Protótipos | 08/04 a 30/04 |
| Implementação | 04/05 a 15/06 |
## Sprints
| Sprint | Entregas |
|-------|----------|
| Sprint 1 | Login de Usuário + banco |
| Sprint 2 | Busca de Pontos |
| Sprint 3 | Filtro de Resíduos |
| Sprint 4 | Ranking |
| Sprint 5 | Denúncia de Pontos |
| Sprint 6 | Informações Educativas |
| Sprint 7 | Perfil do Usuario |
| Sprint 8 | Compartilhamento Social |
| Sprint 9 | Reportar Erros |
| Sprint 10 | Controle de sessões |
## Gestão das Tarefas
Pendente
## Histórico de Entregas
Entrega 1: Documento de Briefing; Pesquisa de Mercado; Visão de produto; ENFN
Entrega 2: Análise de requisitos básica, definição de atores, definição de interfaces, definição de dados, backlog
Entrega 3: Historias de usuario, Protótipos

---
# 10. Banco de Dados
## Estrutura
- motivo da ausência: Ainda em desenvolvimento
- etapa em que será produzido: Implementação;
- Previsão de entrega: 07/04/26;
- Responsável: equipe
## Modelo Visual
- motivo da ausência: Ainda em desenvolvimento
- etapa em que será produzido: Implementação;
- Previsão de entrega: 07/04/26;
- Responsável: equipe
## Observações
- motivo da ausência: Ainda em desenvolvimento
- etapa em que será produzido: Implementação;
- Previsão de entrega: 07/04/26;
- Responsável: equipe
---
# 11. Implementação

## Backend
- motivo da ausência: ainda não iniciamos o processo de implementção;
- etapa em que será produzido: implementação;
- Previsão de entrega: 07/04/26;
- Responsável: equipe
## Frontend
- motivo da ausência: ainda não iniciamos o processo de implementção;
- etapa em que será produzido: implementação;
- Previsão de entrega: 07/04/26;
- Responsável: equipe
## Funcionalidades Concluídas
- motivo da ausência: ainda não iniciamos o processo de implementção;
- etapa em que será produzido: implementação;
- Previsão de entrega: 07/04/26;
- Responsável: equipe
## Funcionalidades em Desenvolvimento
- Login 
- Cadastro
--
# 12. Evidências do Projeto
- motivo da ausência: ainda não iniciamos o processo de implementção;
- etapa em que será produzido: implementação;
- Previsão de entrega: 07/04/26;
- Responsável: equipe
---
# 13. Itens Ainda Não Produzidos
- motivo da ausência: ainda não iniciamos o processo de implementção;
- etapa em que será produzido: implementação;
- Previsão de entrega: 07/04/26;
- Responsável: equipe
---
# 14. Como Executar o Projeto
- motivo da ausência: ainda não iniciamos o processo de implementção;
- etapa em que será produzido: implementação;
- Previsão de entrega: 07/04/26;
- Responsável: equipe
