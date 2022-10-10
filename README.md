### LabeX

### Descrição
Plataforma para a LabeX, empresa fictícia de gerenciamento de viagens espaciais, que permite ao usuário se candidatar a viagens pré-existentes ou ainda administrar suas viagens já cadastradas e criar novas viagens.

### Funcionalidades
- Divisão entre parte pública e parte privada do _site_: a parte pública pode ser acessada por todos (Telas inicial, de lista de viagens e de formulário de inscrição), a parte privada necessita de _login_ (Telas inicial da área administrativa, de detalhes de viagem, de criação de nova viagem). Se o usuário não estiver _logado_, será redirecionado para a Tela de _login_;

#### Parte Pública
- Tela de lista de viagens: visualização da lista de viagens existentes e de seus detalhes (nome, descrição, planeta, duração, data);
- Tela de formulário de inscrição: formulário para se inscrever para uma viagem existente. Todos os campos do formulário são obrigatórios;
- Tela de _login_: formulário para fazer o _login_.Todos os campos do formulário são obrigatórios, o _e-mail_ deve ser válido e a senha deve possuir ao menos 6 caracteres.

#### Parte Privada
- Tela inicial da área administrativa: visualização da lista de todas as viagens e seus detalhes (nome, descrição, planeta, duração, data) com a possibilidade de deletá-las, ou de seguir para a página de detalhes da viagem;
    - Ao clicar para deletar uma viagem, o usuário deve confirmar se realmente deseja prosseguir com a ação.
- Tela de criação de nova viagem: formulário para criar novas viagens. Todos os campos do formulário são obrigatórios;
- Tela de detalhes da viagem: visualização dos detalhes de uma viagem (nome, descrição, planeta, duração, data) e dos candidatos, separados em duas categorias (aprovados e inscritos);
    - Os nomes dos candidatos aprovados para a viagem aparecem em lista;
    - Visualização dos detalhes dos candidatos inscritos que não foram aprovados nem rejeitados (nome, idade, profissão, mensagem);
    - Possibilidade de aprovar ou reprovar os candidatos para a viagem. Em caso de aprovação, o nome do candidato aparece na lista dos aprovados, em caso de rejeição, o candidato é descartado. Em ambos os casos, a tela é atualizada.
- Botão com função de _logout_ na parte inferior da Tela inicial da área administrativa.

### Link Surge 
<https://cagey-hammer.surge.sh/>

### Imagens
![labex-home](https://user-images.githubusercontent.com/104588339/179419879-7e064e20-7357-4a41-956c-78d402b4c2f9.png)
![labex-login](https://user-images.githubusercontent.com/104588339/179419898-10f29604-0603-4c5a-9866-c8a0fd7eaab8.png)
![labex-lista-viagens](https://user-images.githubusercontent.com/104588339/179420502-f92274dc-9a07-4a44-a30e-bb3c70d09a20.png)
![labex-inscricao](https://user-images.githubusercontent.com/104588339/179419910-59c87cfd-0f80-4b7b-9438-43496e5df798.png)
![labex-admin-home](https://user-images.githubusercontent.com/104588339/179420507-71c38c5c-ff17-4a13-a73b-86d07afe912b.png)
![labex-detalhes-viagem](https://user-images.githubusercontent.com/104588339/179420510-2eead7a6-24ce-4c39-ae54-9d8754ccd4b9.png)
![labex-cadastrar-viagem](https://user-images.githubusercontent.com/104588339/179420116-b1dc82f4-5494-4422-91c8-561dc7f1db0a.png)
