### 3. Requisitos Funcionais

* RF. 1: Cadastrar  Usuário.

**Descrição:** Qualquer pessoa poderá efetuar  seu cadastro no aplicativo.  
**Entrada:** Nome de usuário, E-mail e senha.  
**Processo:** O cadastro será incluído em nossa base de dados.  
**Saída:** Mensagem de confirmação de cadastro bem sucedido caso tenha sido efetuado com sucesso, senão, mensagem de erro.  
**Prioridade: **Essencial

* RF. 2: Alterar Cadastrado de Usuário

**Descrição:** O usuário acessa seu perfil e encontra o\(s\) campo onde ele deseja modificar e o modifica.  
**Entrada:** Campo desejado e o novo dado.  
**Processo:** Atualização na base de dados.  
**Saída:** Mensagem de confirmação bem sucedido da modificação do cadastro caso tenha sido efetuado com sucesso, senão, mensagem de erro.  
**Prioridade: **Essencial

* RF 3: Excluir  Cadastro de Usuário

**Descrição:** O próprio usuário do aplicativo poderá excluir sua conta.  
**Entrada:** Nome de usuário.  
**Processo:** O sistema verifica se o usuário é cadastrado, se for o usuário é excluído.  
**Saída:** Mensagem de confirmação bem sucedido da exclusão do cadastro caso tenha sido efetuado com sucesso, senão, mensagem de erro.  
**Prioridade: **Essencial

* RF. 4: Cadastrar Produto

**Descrição:** Os usuários cadastrados podem inserir novos produtos com suas descrições.  
**Entrada:** Dados do produto, indetificação do usuário, PV e data de inserção.  
**Processo:** O sistema insere todos esses dados na base de dados.  
**Saída:** Mensagem de confirmação bem sucedido da inserção do produto caso tenha sido efetuado com sucesso, senão, mensagem de erro.  
**Prioridade: **Essencial

* RF. 5: Moderar Cadastro de Produto

**Descrição:** Toda os podutos cadastrado pelos usuário comum passará por uma revisão por um moderador  
**Entrada: **Os dados do produto cadastrados pelos usuários comum  
**Processo: **Caso o cadastro tenha ocorrido corretamente  o produto e inserido na tabela de produto, outro caso será descartado.  
**Saída:** Mensagem de confirmação bem sucedido da inserção do produto caso tenha sido efetuado com sucesso, senão, mensagem de erro.  
**Prioridade: **Essencial

* RF.5: Alterar do Produto

**Descrição: Somente um usuário administrador poderá realizar a auteração dos dados cadastrais de um poduto**  
**Entrada:** Campo desejado e o novos dados a ser inserido.  
**Processo:** Atualização da base de dados de do produto.  
**Saída:** Mensagem de confirmação bem sucedido da modificação caso tenha  
sido efetuado com sucesso, senão, mensagem de erro.

* RF. 6: Exclusão de Produto

**Descrição**: O administrador poderá efetuar a exclusão de produtos.  
**Entrada:** Nome do Produto  
**Processo:** O sistema busca o produto na base de dados, caso ele encontre  
ele exclui.  
**Saída:** Mensagem de confirmação bem sucedido da exclusão do produto caso tenha sido efetuado com sucesso, senão, mensagem de erro.

* RF. 7: Consulta e Resgate de Documentos

**Descrição:** O usuário pode buscar um determinado produto de sua escolha  
através de campos determinados.  
**Entrada: **Campo \(nome, marca, categoria\) ao qual o usuário deseja fazer a busca e o parâmetro de busca.  
**Processo:** O sistema busca os produtos referentes ao parâmetro de busca e retorna ao usuário.  
**Saída:** Os produtos referentes à busca para que possa fazer qualquer ação previamente prevista no sistema, senão mensagem de que não foi encontrado nenhum produto.

* RF. 8: Criação da\(s\) LC.

**Descrição: **O usuário poderá criar sua LC.  
**Entrada:** nome da LC.  
**Processo:** O sistema cadastrar uma LC vinculada aquele usuários.  
**Saída:**  Mensagem de confirmação bem sucedido da criação da LC caso tenha sido efetuado com sucesso, senão, mensagem de erro.

* RF.9: Modificação da\(s\) LC.

**Descrição: **O usuário poderá fazer alteração nos dados da LC.  
**Entrada:** Campo desejado e o novo dado.  
**Processo: **Atualização nos dados da LC na base de dados.  
**Saída:** Mensagem de confirmação bem sucedido da modificação caso tenha  
sido efetuado com sucesso, senão, mensagem de erro.

* RF.10: Exclusão da\(s\) LC.

**Descrição:** O usuário poderá excluir qualquer LC.  
**Entrada:** LC\(s\) desejada.  
**Processo:** Exclusão da\(s\) LC na base de dados.  
**Saída:** Mensagem de confirmação bem sucedido da\(s\) exclusão caso tenha  
sido efetuado com sucesso, senão, mensagem de erro.

* RF. 11: Inserção de Produtos na\(s\) LC.

**Descrição**: Os usuários cadastrados podem inserir novos produtos em sua\(s\) LC.  
**Entrada:** Nome do Produto, nome da\(s\) LC.  
**Processo:** O sistema insere todos os produtos selecionados na\(s\) LC alterando na base de dados.  
**Saída:** Mensagem de confirmação bem sucedido da inserção do\(s\) produto caso tenha sido efetuado com sucesso, senão, mensagem de erro.

* RF. 12: Exclusão de Produtos da\(s\) LC. 

**Descrição:** Os usuários cadastrados podem excluir os produtos de sua\(s\) respectiva LC.  
**Entrada:** Nome do Produto, nome da\(s\) LC.  
**Processo: **O sistema exclui  todos os produtos selecionados na\(s\) LC alterando na base de dados.  
**Saída:** Mensagem de confirmação bem sucedido da\(s\) exclusão do produto caso tenha sido efetuado com sucesso, senão, mensagem de erro.

* RF. 13: Inserção de PV 

**Descrição:** Os usuários cadastrados podem inserir novos PV com suas descrições.  
**Entrada:** Nome do PV, nome de usuário, dados do PV, data de inserção.  
**Processo:** O sistema insere todos os dados do PV na base de dados.  
**Saída:** Mensagem de confirmação bem sucedido da inserção do PV caso tenha sido efetuado com sucesso, senão, mensagem de erro.

* RF.14: Modificação do PV

**Descrição:** O usuário poderá fazer alteração nos dados do PV.  
**Entrada:** Campo desejado e o novo dado.  
**Processo:** Atualização nos dados do PV na base de dados.  
**Saída:** Mensagem de confirmação bem sucedido da modificação caso tenha  
sido efetuado com sucesso, senão, mensagem de erro.

* RF. 15: Exclusão do PV

**Descrição:** O administrador poderá efetuar a exclusão do PV.  
**Entrada:** Nome do PV  
**Processo:** O sistema busca o PV na base de dados, caso ele encontre  
ele exclui.  
**Saída:** Mensagem de confirmação bem sucedido da exclusão do PV caso tenha sido efetuado com sucesso, senão, mensagem de erro.

* RF. 16: Comparar preço do\(s\) Produtos

**Descrição:** O usuário poderá comparar preços de produtos que estejam ou não na sua LC.  
**Entrada:** Nome do Produto  
**Processo:** O sistema busca os preços do produto em seus respectivos PV.  
ele exclui.  
**Saída:** Exibição do produto com seus vários preços do menor para o maior caso tenha sido efetuado com sucesso, senão, mensagem de erro.

* RF. 17: Buscar melhor PV para compra

**Descrição:** O usuário poderá buscar o melhor PV para efetuar sua compra baseado em sua LC.  
**Entrada:** LC.  
**Processo:** O sistema busca o melhor PV baseado na LC vinculada ao usuário.  
**Saída:** Exibição do PV que o sistema julgou ser o melhor para que o usuário faça sua compra caso tenha sido efetuado com sucesso, senão, mensagem de erro.

