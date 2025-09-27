# Projeto - Base de Dados de Streaming de Música

**Requisitos Funcionais:**

O que precisa de fazer? / Que ações deve suportar / A Base de Dados suporta ou não os requisitos?

- Criar playlists.

- Pesquisar álbuns

- Suportar múltiplos utilizador

- Tempo de música ouvido no ano

- Analisar dados (fazer consultas às várias tabelas)

- Download de músicas (gerenciar reprodução das músicas baixadas)

- Pesquisar música

- Pesquisar artista

- Criar playlists recomendada com base no hisórico de audição

- Estatísticas (artistas mais ouvidos e géneros favoritos)

- Gerenciar o perfil (dados pessoais)

- Tempo de audição por música de cada artista

- Selecionar músicas favoritas (dar like/dislike)

- A partir de likes em cada género recomendar músicas desse género

- Notificações sobre lançamentos de albuns dos artistas favoritos.

- Inserir músicas por artista

- Atualizar Tempo de Audição Semanal

- Suporta podcasts

- Cross-sync entre dispositivos

- Acesso de várias pessoas à mesma playlists

- Jam session entre utilizadores

- Suporte a vários níveis de qualidade de áudio

- Controlos da fila de reprodução

- Suporte a letras de músicas

- Gerenciamento de assinaturas pagas

**Requisitos Não-Fucnionais**

Que Desempenho deve ter o sistema? / Qual a sua Usabilidade e Segurança? / Serão mais difíceis de verificar que os Requisitos Funcionais?

_Desempenho_

- Tempo de resposta para pesquisas inferior a 0.5

- Buffer de reprodução impede interrupções em conexões com velocidade mínima de 1.5 Mbps

_Escalabilidade_

- O sistema deve suportar um aumento de até 25% por mês na base dos utilizadores sem compromissos de desempenho

- A base de dados deve estar preparada para suportar um catáçogo de pelo menos 50 milhões de faixas

- Tem de ter a capacidade de lidar com picos de acesso de até 80% dos utilizadores simultâneos durante lançamentos de artistas populares

_Confiabilidade_

- O sistema deve estar disponível 99.9% do tempo com downtime máximo de 8.75 horas por ano para eventuais manutenções de qualidade

- Em caso de falha do sistema não poderá haver qualquer perda ou fuga de dados

_Segurança_

- Proteção contra reprodução não autorizada que coloque em causa os direitos de autor (DRM)

- Armazenamento dos dados biométricos na Base de Dados

- Apenas assinantes poderão modificar a sua informação sobre o planto que utilizam

_Usabilidade_

- O tempo de carregamento entre páginas ou secções deve ser inferior a 2 segundos

- Acessibilidade deve seguir os padrões mais reentes (WCAG ou W3C)

- O design deve ser responsivo para adaptação aos mais variados tamanhos de ecrã

- Interrupção contextual: pausar automaticamente a reprodução quando outras fontes de áudio/vídeo são ativadas no dispositivo

_Manutenção_

- Atualizações do sistema não devem interromper o serviço por mais de 10 minutos

- A documentação do código e da arquitetura da Base de Dados tem de ser completa e descritiva o suficiente

- Tem de ter modularidade, ou seja, possibilitar a substituição de partes do sistema sem o afetar como um todo

_Compatibilidade_

- Todas as APIs deverão estar documentadas para a integração com sistemas de terceiros

_Privacidade e Conformidade Legal_

- A Base de Dados tem de estar em total conformidade com GPDR, LGPD e outras legislações de proteção de dados

- O utilizador deve ser capaz de exportar ou eliminar inteiramente os seus dados pessoais sempre que o solicitar

- A Base de Dados não deve guardar dados sem o registo do consentimento para recolha e uso dos dados por parte de quem utilizar o serviço

- Diariamente deve ser solicitado um backup dos dados com retenção de 30 dias

- O tempo de recuperação dos dados em caso de falha deve ser inferior a 2 horas

- Os procedimentos de recuperação de falhas do sistema tem de estar documentado

_Eficiência_

- Os recursos do servidor devem ser otimizados

- Deve ser realizada a compressão dos dados para reduzir o uso de largura de banda
