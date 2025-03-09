
# SignUpForm
O **SignUpForm** é um projeto que simula uma página de cadastro e login, desenvolvido em **HTML** e **CSS**. O objetivo principal é criar uma interface intuitiva e responsiva para cadastro de usuários, com campos para informações pessoais, escolha de gênero, upload de foto de perfil e aceitação de termos de uso e privacidade. O projeto foi desenvolvido para praticar e aprimorar habilidades em formulários web e design responsivo.

---

## Funcionalidades

- **Formulário de Cadastro**: Inclui campos para nome completo, email, nome de usuário, senha, confirmação de senha, gênero, data de nascimento, foto de perfil e uma breve biografia.
- **Validação de Senha**: A senha deve conter pelo menos 8 caracteres, incluindo letras maiúsculas, minúsculas e números.
- **Escolha de Gênero**: Opções para selecionar o gênero (Homem Cis, Mulher Cis, Outro).
- **Upload de Foto**: Permite ao usuário enviar uma foto de perfil.
- **Termos de Uso e Privacidade**: Checkboxes para aceitar os termos de uso e privacidade.
- **Design Responsivo**: Layout adaptável para diferentes tamanhos de tela.

---

## Tecnologias Utilizadas

- **HTML**: Estruturação do formulário e conteúdo.
- **CSS**: Estilização da interface, incluindo layout, cores e espaçamento.
- **Validação de Formulário**: Uso de atributos HTML como `required` e `pattern` para validação básica.

---

## Como Executar o Projeto

### Pré-requisitos
- Navegador web moderno (Google Chrome, Firefox, Edge, etc.).
- Editor de código (VS Code, Sublime Text, etc.) para visualizar ou editar o código.

### Passos para Execução

1. Clone o repositório:
   ```bash
   git clone https://github.com/Boudenzin/SignUpForm.git
   ```

2. Navegue até o diretório do projeto:
   ```bash
   cd SignUpForm
   ```

3. Abra o arquivo `index.html` no navegador:
   - Clique duas vezes no arquivo `index.html` ou arraste-o para o navegador.

4. Interaja com o formulário:
   - Preencha os campos do formulário.
   - Clique em "Enviar" para simular o cadastro (o formulário redireciona para o GitHub do autor).

---

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

```
SignUp-LogInPage/
├── index.html            # Arquivo HTML principal.
├── style.css             # Arquivo CSS para estilização.
└── README.md             # Este arquivo.
```

### Detalhes do Código

- **HTML (`index.html`)**:
  - Estrutura do formulário com campos para nome, email, senha, gênero, foto de perfil, data de nascimento e biografia.
  - Uso de `fieldset` para agrupar campos relacionados.
  - Validação de senha com o atributo `pattern`.

- **CSS (`style.css`)**:
  - Estilização do formulário com layout centralizado e espaçamento adequado.
  - Design limpo e moderno, com bordas arredondadas e cores suaves.
  - Estilo para os botões de rádio e checkboxes.

---

## Próximos Objetivos

1. **Integração com Backend**:
   - Adicionar funcionalidades de backend usando JavaScript, Node.js ou Spring Boot para processar o cadastro e login.

2. **Validação Avançada**:
   - Implementar validação em tempo real com JavaScript para fornecer feedback imediato ao usuário.

3. **Página de Login**:
   - Criar uma página de login separada para complementar o cadastro.

4. **Responsividade Avançada**:
   - Melhorar a adaptação do formulário para dispositivos móveis e tablets.

5. **Testes de Usabilidade**:
   - Implementar testes para garantir que o formulário seja intuitivo e funcional em diferentes cenários.

6. **Deploy**:
   - Publicar o projeto em uma plataforma como GitHub Pages, Netlify ou Vercel.

7. **Mais Estilos**:
   - Adicionar temas claros e escuros ou personalização de cores.

---

## Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
