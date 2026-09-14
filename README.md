# Livraria Simples 📚 — Exercício 3.4 GitHub

Repositório criado para demonstrar na prática o **fluxo básico de colaboração com Git e GitHub**, baseado no módulo de treinamento da Microsoft ([Introdução ao GitHub](https://learn.microsoft.com/pt-br/training/modules/introduction-to-github/)).

---

## 🎯 Objetivo

Demonstrar de forma prática e limpa os conceitos essenciais do fluxo de trabalho no GitHub:
- Criação e versionamento na branch `main`
- Isolamento de novas funcionalidades em branch temática (`feature/wishlist`)
- Commits convencionais e rastreáveis
- Envio (*push*) para o GitHub
- Abertura de **Pull Request (PR)**
- Revisão e **Merge** do Pull Request
- Sincronização e preservação do histórico de colaboração

---

## 🛠️ Sobre a Aplicação

Uma aplicação estática e direta de catálogo de livraria:
- `index.html`: Interface visual contendo o catálogo de livros e a seção de lista de desejos (*wishlist*).
- `wishlist.json`: Estrutura de dados contendo os itens desejados adicionados durante a feature.

---

## 🔄 Fluxo de Colaboração Executado

O ciclo de desenvolvimento seguiu os passos recomendados de colaboração:

1. **Inicialização do Repositório (`main`)**:
   - Criação da estrutura base com o catálogo inicial de livros e documentação inicial.
   - Primeiro commit: `feat(catalogo): adicionar estrutura inicial da livraria e catalogo`.

2. **Criação da Feature Branch**:
   - Criação da ramificação `feature/wishlist` a partir da `main` para isolar o desenvolvimento da nova funcionalidade:
     ```bash
     git checkout -b feature/wishlist
     ```

3. **Desenvolvimento e Commit**:
   - Implementação da seção de *Wishlist* na interface e criação do arquivo `wishlist.json`.
   - Commit seguindo a convenção de Conventional Commits: `feat(wishlist): implementar secao e dados da lista de desejos`.

4. **Publicação da Branch**:
   - Envio da branch para o repositório remoto no GitHub:
     ```bash
     git push -u origin feature/wishlist
     ```

5. **Abertura do Pull Request**:
   - Criação do Pull Request da branch `feature/wishlist` apontando para a branch `main`, descrevendo o escopo das alterações.

6. **Merge do Pull Request**:
   - O Pull Request foi aprovado e integrado à branch `main` mantendo o histórico de commits intacto.

7. **Sincronização Local**:
   - Retorno para a branch `main` e atualização dos commits locais via `git pull`.

---

## 🔗 Links do Projeto

- **Repositório no GitHub:** [https://github.com/EduardoFdeM/eng-software-exercicio-3-4-github](https://github.com/EduardoFdeM/eng-software-exercicio-3-4-github)
- **Pull Request Mergeado:** [https://github.com/EduardoFdeM/eng-software-exercicio-3-4-github/pull/1](https://github.com/EduardoFdeM/eng-software-exercicio-3-4-github/pull/1)
