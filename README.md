# ihcux-racha-ai-blazor



# Implementação Blazor

A interface foi desenvolvida utilizando componentes Blazor para melhorar a reutilização e organização do código.

O dashboard principal foi criado no arquivo:

```plaintext
Pages/Dashboard.razor
```

A hierarquia visual do wireframe foi aplicada utilizando cards Bootstrap, organização em grid responsivo e separação de componentes.

Os cards de resumo financeiro foram posicionados no topo da página para destacar as informações mais importantes do sistema, facilitando a visualização do saldo do usuário.

A lista de grupos foi componentizada utilizando o componente:

```plaintext
Shared/GrupoCard.razor
```

Esse componente foi reutilizado para exibir os grupos financeiros de forma padronizada e organizada.

Também foram utilizadas cores visuais para melhorar a experiência do usuário:

* Verde para valores positivos
* Vermelho para valores negativos

---

# Dificuldade Técnica

A maior dificuldade técnica foi realizar a componentização do `GrupoCard`, principalmente no momento de passar os dados do objeto `Grupo` como parâmetro dentro do Blazor.

Também houve dificuldade na organização das pastas e na estruturação correta dos componentes dentro do projeto.

Pages/Dashboard.razor
