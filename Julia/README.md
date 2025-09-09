
Ideias para o museu do Git

° Inicio do museu na sala principal, cada sala tera uma explicação e alguns codigos iniciais sobre o git. ° Logo depois vc ira poder fazer perguntas, pré programadas por nós e tirar as dúvidas. ° Quiz de perguntas nas salas ou no final do museu. °

no final podemos fazer um quiz geral sobre cada sala e ver oq aprendemos no museu.

SALA HISTORIA DO GIT

O Início: O Kernel do Linux e o BitKeeper Desenvolvimento colaborativo: Entre 1991 e 2002, o desenvolvimento do kernel do Linux, projeto de código aberto, dependia de um sistema para compartilhar arquivos e tarefas entre desenvolvedores.

A ascensão do BitKeeper: A partir de 2002, a comunidade Linux começou a utilizar o BitKeeper, um sistema de controle de versão distribuído.

A quebra de relação: Em 2005, a relação com a BitKeeper tornou-se tensa devido a restrições e custos impostos pelo software proprietário, que antes era gratuito para a comunidade Linux.

A CRIAÇÃO DO GIT

A solução de Torvalds: Linus Torvalds, vendo a necessidade de uma nova ferramenta, decidiu criar o seu próprio sistema de controle de versão.

Desenvolvimento rápido: Em abril de 2005, Torvalds criou o Git em um curto espaço de tempo, buscando uma solução mais eficiente e flexível.

Características principais: O Git foi projetado para ser distribuído, rápido, capaz de lidar com grandes projetos e com um eficiente sistema de ramificação (branches) para o desenvolvimento não linear.

A EVOLUÇÃO E O SUCESSO

Manutenção e maturidade: A manutenção do Git foi passada para Junio Hamano, um dos principais colaboradores do projeto.

Popularização: O Git se tornou uma ferramenta padrão para o controle de código-fonte, sendo a base para várias plataformas de hospedagem de código, como o GitHub e o GitLab, que foram essenciais para a colaboração em larga escala entre desenvolvedores.

SALA CODIGOS PRINCIPAIS

° Configuração Inicial (Opcional, mas recomendado)

Antes de começar a usar o Git, é uma boa prática configurar o nome e e-mail que serão associados aos seus commits.

git config --global user.name "Seu Nome" : Define o nome do usuário. git config --global user.email "seuemail@exemplo.com" : Define o e-mail do usuário.

Inicializar um Repositório

Para iniciar um novo projeto rastreado pelo Git em um diretório local: git init : Cria um novo repositório Git na pasta atua

Clonar um Repositório Existente

Se você precisa copiar um repositório já existente de um servidor (como o GitHub) para o seu computador: git clone <URL_DO_REPOSITORIO> : Baixa o repositório remoto para a sua máquina.

Adicionar e Confirmar Alterações

Após fazer alterações nos seus arquivos, você precisa adicioná-las ao "staging area" e depois confirmá-las em um commit. git status : Mostra o estado atual dos arquivos (quais foram modificados, adicionados, etc.). git add . (ou git add <nome_do_arquivo>): Adiciona os arquivos modificados à área de staging, preparando-os para o commit. git commit -m "Sua mensagem do commit" : Salva as alterações que estão na área de staging no histórico do repositório, com uma mensagem descritiva.

SALA CODIGO AVANÇADO
