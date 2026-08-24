 Sistema de Controle de Estoque em Python

Aplicação desenvolvida em Python para gerenciamento de produtos, quantidades e operações de estoque, rodando diretamente no terminal com suporte a salvamento automático dos dados.

---

Sobre o Projeto

O **Sistema de Controle de Estoque** permite que um usuário realize o gerenciamento completo de mercadorias. Ele possui persistência de dados em formato **JSON**, garantindo que as alterações (cadastros, remoções e edições) não sejam perdidas ao fechar o programa.

 Funcionalidades

- **1. Cadastrar produto:** Registra novos itens informando nome, quantidade inicial e preço unitário.
- **2. Remover produto:** Exclui permanentemente um item do estoque.
- **3. Alterar quantidade:** Atualiza o saldo de estoque de um produto existente.
- **4. Listar produtos:** Exibe uma tabela com todos os produtos, quantidades e preços cadastrados.
- **5. Consultar produto:** Busca um item específico mostrando seus detalhes e o valor total acumulado.
- **0. Sair:** Encerra a aplicação com segurança.

 Tecnologias e Conceitos Utilizados

- **Python 3**
- **Dicionários e Listas:** Para estruturar e manipular os produtos em memória.
- **Funções (`def`):** Para modularizar e organizar as responsabilidades do código.
- **Módulo `json`:** Para carregar e salvar automaticamente os dados no arquivo `estoque.json`.
- **Tratamento de Exceções (`try/except`):** Evita que o programa feche caso o usuário digite valores numéricos inválidos.


 Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/controle-de-estoque-python.git](https://github.com/seu-usuario/controle-de-estoque-python.git)
