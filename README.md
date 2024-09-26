# Instruções para Clonar e Submeter Alterações em um Repositório Git

Este documento descreve os passos necessários para clonar um repositório, criar uma nova branch, realizar um commit de uma nova funcionalidade e submeter as alterações ao repositório remoto no GitHub.

## Passos

1. **Clonar o Repositório**

   Execute o seguinte comando para clonar o repositório:

   ```bash
   git clone https://github.com/pedronora/microsservicos-at-clone.git
   ```

2. **Navegar até o Diretório do Repositório Clonado**
Entre no diretório do repositório clonado:
    ```bash
    cd microsservicos-at-clone
    ```
    
3. **Criar uma Nova Branch**
    ```bash
    git checkout -b novas-funcionalidades
    ```

4. **Fazer as Alterações Necessárias**
Realize as alterações desejadas no código. Utilize seu editor de texto ou IDE para isso.

5. **Adicionar as Alterações ao Staging**
Adicione as alterações feitas ao staging:
    ```bash
    git add .
    ```
    
6. **Realizar um Commit com uma Mensagem**
Realize um commit das alterações com uma mensagem descritiva:
    ```bash
    git commit -m "Atualiza o README.md com instruções para criação de nova branch, realização de alterações e commit das mudanças"
    ```
7. **Submeter as Alterações ao Repositório Remoto**
Finalmente, submeta as alterações para o repositório remoto:
    ```bash
    git push origin novas-funcionalidades
    ```

