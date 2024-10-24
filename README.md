# GitUploadTerminal
Script simples que você pode usar para automatizar o processo de commit e push para o GitHub no final das suas tarefas.

## Automação de Commits Diários para o GitHub

### Descrição
Este script automatiza o processo de commit e push de alterações para um repositório Git ao final de cada dia. A ferramenta é especialmente útil para desenvolvedores que desejam manter um histórico preciso das modificações em seus projetos e garantir que o código esteja sempre atualizado no repositório remoto.

### Funcionamento
1. **Configuração:** O script requer a configuração do diretório do projeto e, opcionalmente, uma mensagem de commit personalizada.
2. **Verificação de Status:** Antes de realizar o commit, o script verifica o status do repositório para identificar quais arquivos foram modificados.
3. **Commit e Push:** Em seguida, todos os arquivos modificados são adicionados ao índice do Git, um commit é criado com a mensagem especificada e as alterações são enviadas para o repositório remoto.

### Tecnologias Utilizadas
* **Python:** Para a primeira versão do script, foi utilizado Python para criar uma solução mais flexível e fácil de manter.
* **Bash:** A segunda versão, implementada em Bash, oferece uma alternativa mais leve e integrada ao ambiente Linux.

## Instruções para Instalação e Execução

**Pré-requisitos:**

* **Git:** Certifique-se de ter o Git instalado e configurado em seu sistema. Para instalação, consulte a documentação oficial do Git para sua distribuição Linux.
* **Python** (opcional): Se você optar pela versão Python, instale o Python e quaisquer dependências adicionais (normalmente, não há dependências extras para este script simples).
* **Um editor de texto:** Para modificar os scripts e o arquivo README.md.

**Clonando o Repositório:**

1. **Crie um novo diretório:** Abra o terminal e navegue até o local onde deseja salvar o projeto.
2. **Clone o repositório:** Execute o seguinte comando, substituindo `https://seu-usuario/seu-repositorio.git` pela URL do seu repositório GitHub:

   ```bash
   git clone https://seu-usuario/seu-repositorio.git

### Contribuições
Contribuições são bem-vindas! Se você encontrar algum bug ou tiver sugestões de melhoria, por favor, abra um issue ou faça um pull request.
