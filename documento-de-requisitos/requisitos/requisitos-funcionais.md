### 3. Requisitos Funcionais

* RF. 01: Cadastrar  Usuário.

**Descrição:** Qualquer pessoa poderá efetuar  seu cadastro no aplicativo.  
**Entrada:** Nome de usuário, E-mail e senha.  
**Processo:** O cadastro será incluído em nossa base de dados.  
**Saída:** Mensagem de confirmação de cadastro bem sucedido caso tenha sido efetuado com sucesso, senão, mensagem de erro.  
**Prioridade: **Essencial

* RF. 02: Alterar Usuário

**Descrição:** O usuário acessa seu perfil e encontra o\(s\) campo onde ele deseja modificar e o modifica.  
**Entrada:** Campo desejado e o novo dado.  
**Processo:** Atualização na base de dados.  
**Saída:** Mensagem de confirmação bem sucedido da modificação do cadastro caso tenha sido efetuado com sucesso, senão, mensagem de erro.  
**Prioridade: **Essencial

* RF 03: Excluir  Usuário

**Descrição:** O próprio usuário do aplicativo poderá excluir sua conta.  
**Entrada:** Nome de usuário.  
**Processo:** O sistema verifica se o usuário é cadastrado, se for o usuário é excluído.  
**Saída:** Mensagem de confirmação bem sucedido da exclusão do cadastro caso tenha sido efetuado com sucesso, senão, mensagem de erro.  
**Prioridade: **Essencial

* RF. 04: Consultar Usuário

**Descrição:** O usuário administrador pode buscar um determinado usuário cadastrado  
**Entrada: N**ome ou código do usuasrio  
**Processo:** O sistema busca as informações do cadastro do usuário e retorna ao administrador.  
**Saída:** O sistema devolve as infomações do usuário ou uma mensagem de usuário não encontrado.  
**Prioridade: **Importante

* RF. 05: Cadastrar Produto

**Descrição:** Os usuários cadastrados podem inserir novos produtos com suas descrições.  
**Entrada:** Dados do produto, indetificação do usuário, PV e data de inserção.  
**Processo:** O sistema insere todos esses dados na base de dados.  
**Saída:** Mensagem de confirmação bem sucedido da inserção do produto caso tenha sido efetuado com sucesso, senão, mensagem de erro.  
**Prioridade: **Essencia

* RF. 06: Alterar Produto

**Descrição: **Somente um usuário administrador poderá realizar a auteração dos dados cadastrais de um poduto  
**Entrada:** Campo desejado e o novos dados a ser inserido.  
**Processo:** Atualização da base de dados de do produto.  
**Saída:** Mensagem de confirmação bem sucedido da modificação caso tenha  
sido efetuado com sucesso, senão, mensagem de erro.  
**Prioridade: **Essencial

* RF. 07: Excluir Produto

**Descrição**: Somente um usuário  administrador poderá efetuar a exclusão de produtos.  
**Entrada:** Nome do Produto ou código do produto  
**Processo:** O sistema busca o produto na base de dados, caso ele encontre  
ele exclui.  
**Saída:** Mensagem de confirmação bem sucedido da exclusão do produto caso tenha sido efetuado com sucesso, senão, mensagem de erro.  
**Prioridade: **Importante

* RF. 08: Consultar Produto

**Descrição:** O usuário pode buscar um determinado produto de sua escolha  
através de campos determinados.  
**Entrada: **Campo \(nome, marca, categoria\) ao qual o usuário deseja fazer a busca e o parâmetro de busca.  
**Processo:** O sistema busca os produtos referentes ao parâmetro de busca e retorna ao usuário.  
**Saída:** Os produtos referentes à busca para que possa fazer qualquer ação previamente prevista no sistema, senão mensagem de que não foi encontrado nenhum produto.  
**Prioridade: **Essencial

* RF. 09: Cadastrar  LC.

**Descrição: **O usuário poderá criar sua LC.  
**Entrada:** nome da LC.  
**Processo:** O sistema cadastrar uma LC vinculada aquele usuários.  
**Saída:**  Mensagem de confirmação bem sucedido da criação da LC caso tenha sido efetuado com sucesso, senão, mensagem de erro.

* RF.10: Alterar  LC.

**Descrição: **O usuário poderá fazer alteração nos dados da LC.  
**Entrada:** Campo desejado e o novo dado.  
**Processo: **Atualização nos dados da LC na base de dados.  
**Saída:** Mensagem de confirmação bem sucedido da modificação caso tenha  
sido efetuado com sucesso, senão, mensagem de erro.  
**Prioridade: **Essencial

* RF.11: Excluir LC.

**Descrição:** O usuário poderá excluir qualquer LC.  
**Entrada:** LC\(s\) desejada.  
**Processo:** Exclusão da\(s\) LC na base de dados.  
**Saída:** Mensagem de confirmação bem sucedido da\(s\) exclusão caso tenha  
sido efetuado com sucesso, senão, mensagem de erro.  
**Prioridade: **Essencial

* RF. 12: Consultar LC.

**Descrição:** O usuário pode buscar uma lista de compra.  
**Entrada:** Nome da lista ou nome de produto nela comtido.  
**Processo:** O sistema exibe as listas de acordo com os parâmetros informados.  
**Saída:** As listas filtradas ou uma mensagem de lista não encontrada  
**Prioridade: **Importante

* RF. 13: Cadastrar Produtos na LC.

**Descrição**: Os usuários cadastrados podem inserir novos produtos em sua\(s\) LC.  
**Entrada:** Nome do Produto, nome da\(s\) LC.  
**Processo:** O sistema insere todos os produtos selecionados na\(s\) LC alterando na base de dados.  
**Saída:** Mensagem de confirmação bem sucedido da inserção do\(s\) produto caso tenha sido efetuado com sucesso, senão, mensagem de erro.  
**Prioridade: **Essencial

* RF. 14: Excluir de Produtos da LC. 

**Descrição:** Os usuários cadastrados podem excluir os produtos de sua\(s\) respectiva LC.  
**Entrada:** Nome do Produto, nome da\(s\) LC.  
**Processo: **O sistema exclui  todos os produtos selecionados na\(s\) LC alterando na base de dados.  
**Saída:** Mensagem de confirmação bem sucedido da\(s\) exclusão do produto caso tenha sido efetuado com sucesso, senão, mensagem de erro.  
**Prioridade: **Essencial

* RF. 15: Cadastar  PV 

**Descrição:** Os usuários cadastrados podem inserir novos PV com suas descrições.  
**Entrada:** Nome do PV, nome de usuário, dados do PV, data de inserção.  
**Processo:** O sistema insere todos os dados do PV na base de dados.  
**Saída:** Mensagem de confirmação bem sucedido da inserção do PV caso tenha sido efetuado com sucesso, senão, mensagem de erro.  
**Prioridade: **Essencial

* RF.16: Alterar PV

**Descrição:** O usuário poderá fazer alteração nos dados do PV.  
**Entrada:** Campo desejado e o novo dado.  
**Processo:** Atualização nos dados do PV na base de dados.  
**Saída:** Mensagem de confirmação bem sucedido da modificação caso tenha  
sido efetuado com sucesso, senão, mensagem de erro.  
**Prioridade: **Essencial

* RF. 17: Excluir PV

**Descrição:** O administrador poderá efetuar a exclusão do PV.  
**Entrada:** Nome do PV  
**Processo:** O sistema busca o PV na base de dados, caso ele encontre  
ele exclui.  
**Saída:** Mensagem de confirmação bem sucedido da exclusão do PV caso tenha sido efetuado com sucesso, senão, mensagem de erro.  
**Prioridade: **Essencial

* RF. 18: Comparar Preço de Produto

**Descrição:** O usuário poderá comparar preços de produtos que estejam ou não na sua LC.  
**Entrada:** Nome do Produto  
**Processo:** O sistema busca os preços do produto em seus respectivos PV.  
ele exclui.  
**Saída:** Exibição do produto com seus vários preços do menor para o maior caso tenha sido efetuado com sucesso, senão, mensagem de erro.  
**Prioridade: **Essencial

* RF. 19: Consultar Melhor PV

**Descrição:** O usuário poderá buscar o melhor PV para efetuar sua compra baseado em sua LC.  
**Entrada:** LC.  
**Processo:** O sistema busca o melhor PV baseado na LC vinculada ao usuário.  
**Saída:** Exibição do PV que o sistema julgou ser o melhor para que o usuário faça sua compra caso tenha sido efetuado com sucesso, senão, mensagem de erro.  
**Prioridade: **Desejável

* RF. 20: Cadastrar Preço de Produto 

**Descrição: **O usuário cadastro o preço dos produtos num determinado ponto de venda.  
**Entrada:** Buscar produto e preço do produto em um ponto de venda  
**Processo:** O sistema atualiza o preço do produto para aquele ponto de venda.  
**Saída:** Confirmar a atuliazação do preço do produto ou  mensagem de erro.  
**Prioridade:** Essencial

RF. 21: Leitor de Código de Barras

**Descrição: **O usuário poderá fazer a consulta de um produto utilizando a câmera de seu dispositivo móvel  para fazer leitura do código de barras do produto informado na embalagem. Durante o preenchimento do cadastro de produto o usuário também poderá fazer a coleta do codigo de barras através da leitora eletronica. Esta funcionalidade só deve estar disponível na versão para dispositivo movel.  
**Entrada:** Fotográfia do código de barras do produto existente na embalagem  
**Processo:** O sistema faz a leitura do codigo utilizando um interpretador de imagem e retorna o número do código  que poderá ser usado no cadastro de novos produtos ou numa requesisção de busca do mesm.  
**Saída:** Retorna os dados de um produto cadastrado ou  a mensagem de produto não encontrado.  
**Prioridade:** Desejavel



