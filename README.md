# Template de Pull Request
Segue abaixo um modelo de pull request.

```markdown
## Implementação

<!-- Listar o que foi/será implementado, marcando o que já foi concluído -->

- [x] Adicionar a tela de login;
- [ ] Integrar com a API.

## Links

- Azure DevOps: [CSP-8516](https://site.com/board/items/8516)
- Protótipo: [Figma](https://figma.com/project/name)

<!-- Instruções para serem realizadas antes ou depois de testar o código, e/ou antes ou depois de realizar o deploy -->
<!-- Caso necessário -->
## Instruções

1. Instalar as novas dependências do projeto (`yarn install`);
2. Adicionar a nova variável de ambiente ao arquivo `.env`: `NEXT_PUBLIC_CUSTOMER_PAGE_ENABLED=true`.

<!-- Caso necessário -->
## Como testar?

1. Acessar a página de cadastro (`/customer/new`) clicando no botão "Criar conta", na página inicial;
2. Inserir o e-mail e senha;
3. Esperar o e-mail de confirmação de conta e clicar no link no e-mail;
4. Ao clicar no link o usuário será redirecionado para a tela de login. Caso contrário, acessar a página de login (`/sign_in`) clicando no botão "Entrar", na página inicial;
5. Preencha o e-mail e senha informado no cadastro para realizar o login;
6. O usuário deve ser redirecionado para a área do cliente.

<!-- Lista dos testes adicionados/atualizados - Caso necessário -->
## Testes

- tests/authentication/sign_in.test.ts
- tests/homepage/navbar.test.ts

<!-- Caso necessário -->
## Imagens

**Descrição da imagem**

<!-- Arquivo da imagem -->

<!-- Caso necessário -->
## Vídeos

**Descrição do vídeo**

<!-- Arquivo do vídeo -->
```
