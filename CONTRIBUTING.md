# Diretrizes para Contribuição

Bem-vindo(a) ao projeto Web-Scraping-Intelligence-Tool! Agradecemos o seu interesse em contribuir.

Para garantir um processo de colaboração suave e eficaz, por favor, siga estas diretrizes:

## Como Contribuir

1.  **Faça um Fork do Repositório**: Comece fazendo um fork do repositório para a sua conta GitHub.

2.  **Clone o Repositório Forkado**: Clone o seu fork para a sua máquina local:

    ```bash
    git clone https://github.com/SEU_USUARIO/Web-Scraping-Intelligence-Tool.git
    cd Web-Scraping-Intelligence-Tool
    ```

3.  **Crie um Branch**: Crie um novo branch para a sua feature ou correção de bug:

    ```bash
    git checkout -b feature/sua-feature-nova
    # ou
    git checkout -b bugfix/correcao-de-bug
    ```

4.  **Faça Suas Alterações**: Implemente suas alterações, adicione novos recursos ou corrija bugs. Certifique-se de seguir as melhores práticas de codificação e manter o código limpo e legível.

5.  **Escreva Testes**: Se você estiver adicionando novos recursos ou corrigindo bugs, por favor, inclua testes unitários e/ou de integração para garantir que suas alterações funcionem conforme o esperado e não introduzam regressões.

6.  **Execute os Testes**: Antes de fazer o commit, execute todos os testes para garantir que tudo está funcionando corretamente:

    ```bash
    python3.11 -m unittest discover tests
    ```

7.  **Faça o Commit das Suas Alterações**: Faça o commit das suas alterações com uma mensagem clara e concisa:

    ```bash
    git commit -m "feat: Adiciona nova funcionalidade X" # para novas funcionalidades
    # ou
    git commit -m "fix: Corrige bug Y" # para correções de bugs
    ```

8.  **Envie para o Seu Fork**: Envie suas alterações para o seu repositório forkado no GitHub:

    ```bash
    git push origin feature/sua-feature-nova
    ```

9.  **Abra um Pull Request**: Vá para o repositório original no GitHub e abra um Pull Request (PR). Forneça uma descrição detalhada das suas alterações, o problema que elas resolvem e quaisquer outras informações relevantes.

## Padrões de Código

-   Siga o estilo de código [PEP 8](https://www.python.org/dev/peps/pep-0008/).
-   Use nomes de variáveis e funções descritivos.
-   Comente seu código onde for necessário para explicar a lógica complexa.

## Relatando Bugs

Se você encontrar um bug, por favor, abra uma issue no GitHub e forneça o máximo de detalhes possível, incluindo:

-   Uma descrição clara e concisa do bug.
-   Passos para reproduzir o comportamento.
-   O comportamento esperado.
-   O comportamento real.
-   Sua versão do Python e das dependências.

## Sugerindo Novas Funcionalidades

Se você tiver uma ideia para uma nova funcionalidade, por favor, abra uma issue no GitHub para discutir a sua proposta. Isso nos ajuda a coordenar esforços e evitar trabalho duplicado.

Obrigado por sua contribuição!
