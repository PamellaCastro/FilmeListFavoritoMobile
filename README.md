# FilmeListFavoritoMobile

# Minha Lista de Filmes e Livros
Este é um aplicativo móvel híbrido simples, desenvolvido com Ionic e Angular, para gerenciar e organizar sua lista pessoal de filmes e livros favoritos. Ele permite que você adicione, visualize, edite e remova itens da sua lista de forma intuitiva e os persiste no armazenamento local do dispositivo.

✨ Funcionalidades
Adicionar Item: Cadastre novos filmes ou livros informando título e descrição.
Visualizar Lista: Exiba todos os itens cadastrados em uma lista clara e organizada.
Editar Item: Modifique o título e a descrição de filmes/livros já existentes.
Excluir Item: Remova itens da sua lista com uma confirmação para evitar exclusões acidentais.
Persistência de Dados: Todos os dados são salvos localmente no dispositivo, garantindo que suas listas não sejam perdidas ao fechar o aplicativo.
Navegação Detalhada: Clique em um item para ver seus detalhes em uma tela separada.
🚀 Tecnologias Utilizadas
Ionic Framework: Kit de ferramentas de UI de código aberto para criar aplicativos móveis de alta qualidade em frameworks web populares como Angular.
Angular: Framework JavaScript para a construção de interfaces de usuário dinâmicas e Single Page Applications (SPAs).
Capacitor: Uma plataforma de código aberto para construir aplicativos web que rodam nativamente em iOS, Android, Electron e na web, permitindo acesso a funcionalidades nativas do dispositivo.
TypeScript: Superset do JavaScript que adiciona tipagem estática, melhorando a robustez e a manutenção do código.
HTML5: Linguagem de marcação para estruturar o conteúdo.
CSS / SCSS: Linguagem de folha de estilos para estilizar a interface do usuário.
Capacitor Preferences API: Utilizado para armazenamento persistente de dados chave-valor no dispositivo.
⚙️ Como Rodar o Projeto (Desenvolvimento)
Para clonar e rodar este projeto em seu ambiente de desenvolvimento, siga os passos abaixo:

Clone o Repositório:

Bash

git clone https://github.com/PamellaCastro/FilmeListFavoritoMobile.git
cd SEU_REPOSITORIO
(Lembre-se de substituir SEU_USUARIO e SEU_REPOSITORIO pelos seus dados reais do GitHub)

Instale as Dependências:

Bash

npm install
Execute o Aplicativo no Navegador:

Bash

ionic serve
Isso abrirá o aplicativo no seu navegador padrão (http://localhost:8100/).

📱 Como Rodar em Dispositivos Nativos (iOS/Android)
Para testar o aplicativo em emuladores ou dispositivos reais, você precisará ter o ambiente de desenvolvimento nativo configurado (Android Studio para Android, Xcode para iOS).

Adicione a Plataforma:

Bash

ionic capacitor add android
# OU
ionic capacitor add ios
Construa o Aplicativo Web (se fez alterações):

Bash

ionic build
Copie os Recursos Web para a Plataforma Nativa:

Bash

ionic capacitor copy android
# OU
ionic capacitor copy ios
Abra o Projeto na IDE Nativa:

Bash

ionic capacitor open android
# OU
ionic capacitor open ios
Isso abrirá o projeto no Android Studio ou Xcode, de onde você poderá rodar em um emulador ou dispositivo.

🤝 Contribuição
Contribuições são bem-vindas! Se você encontrar um bug ou tiver uma ideia para uma nova funcionalidade, sinta-se à vontade para abrir uma issue ou enviar um pull request.
