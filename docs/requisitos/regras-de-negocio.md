Regras de Negócio 

RN01 – Unicidade de Cadastro: Cada usuário deve ser identificado por um e-mail único. Não é permitido criar mais de uma conta com o mesmo e-mail.

RN02 – Perfil de Acesso: O sistema deve distinguir entre Cidadão (acesso ao mapa, ranking e perfil) e Administrador (acesso aos logs e gestão de denúncias).

RN03 – Persistência de Sessão: A sessão do usuário deve permanecer ativa por até 7 dias, a menos que o usuário solicite explicitamente o "Logout".

RN04 – Disponibilidade do Mapa: O mapa interativo só exibirá pontos de coleta se o usuário permitir o acesso à localização do navegador ou informar um endereço/CEP válido.

RN05 – Raio de Busca: Por padrão, o sistema deve sugerir os pontos de coleta num raio de até 10km da posição atual do usuário, permitindo a expansão manual desse filtro.

RN06 – Cadastro de Novos Pontos: Qualquer cidadão pode sugerir um novo ponto de coleta, mas este só ficará visível para os demais usuários após a aprovação de um Administrador.

RN07 – Atribuição de Pontos: O usuário ganhará pontos ao:

- Realizar check-in em um ponto de coleta (10 pts).

- Sugerir um novo ponto que venha a ser aprovado (50 pts).

- Reportar um erro ou denúncia que seja verídica (10 pts).

RN08 – Limite de Check-in: Para evitar fraudes, um usuário só pode realizar 1 check-in por dia no mesmo ponto de coleta.

RN09 – Atualização do Ranking: O ranking global deve ser processado e atualizado semanalmente.

RN10 – Suspensão de Pontos: Se um ponto de coleta receber 3 ou mais denúncias de "insalubridade" ou "inexistência" em um período de 48h, ele deve ser ocultado automaticamente do mapa até a revisão administrativa.

RN11 – Prova Visual: Toda denúncia ou sugestão de novo ponto deve obrigatoriamente conter pelo menos uma foto anexada para fins de auditoria.

RN12 – Conexão Obrigatória: O sistema não deve permitir o carregamento de novas rotas ou busca de pontos sem conexão ativa com a internet.

RN13 – Natureza do Serviço: O sistema não realiza agendamento de coletas domiciliares nem processa pagamentos financeiros (recompensa apenas via pontos virtuais).