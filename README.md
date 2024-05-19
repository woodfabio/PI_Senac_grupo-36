# PI_Senac_grupo-36
Projeto Integrador - Senac EAD - Grupo 36

# Resumo
Este trabalho consiste na descrição do processo de modelagem de um software para gestão de dados de um centro universitário capaz de cadastrar diferentes tipos de pessoas. Na fase anterior o projeto consistiu em diagramas em linguagem UML descrevendo as diferentes classes utilizadas no software bem como diagramas de casos de uso descrevendo os cenários e ações contemplados por ele. Nesta fase serão apresentadas as telas dos casos de uso, o quais serão formulados em conformidade com as classes criadas, seus atributos e métodos.

# Documentação

## /diagrams
Pasta com as imagens dos diagramas UML do sistema.

### Diagrama UML classes.png
Diagrama UML de classes especificando os atributos e relacionamentos referentes às classes utilizadas no sistema.

</br>

## /screens
Pasta com as imagens das telas como são apresentadas ao usuário.

### Cadastro Aluno.png
Tela referente ao caso de uso "cadastrar aluno".
Nela é possível realizar o cadastro do usuário (instância) da classe _Aluno_ inserindo os valores de todos os atributos (identificados com um asterisco vermelho).
Também é possível cadastrar o relacionamento com instâncias das classes _Curso_ e _Turma_.

### Cadastro Fornecedor.png
Tela referente ao caso de uso "cadastrar fornecedor".
Nela é possível realizar o cadastro do usuário (instância) da classe _Fornecedor_ (na tela, referida como "empresa") inserindo os valores de todos os atributos (identificados com um asterisco vermelho).

### Cadastro Professor.png
Tela referente ao caso de uso "cadastrar professor".
Nela é possível realizar o cadastro do usuário (instância) da classe _Professor_ inserindo os valores de todos os atributos (identificados com um asterisco vermelho).
Também é possível cadastrar o relacionamento com instâncias das classes _Disciplina_ e _Turma_.

### Landing Page.png
Tela de início do programa, apresentando a instituição de ensino.
O fluxo do programa inicia-se quando o usuário seleciona o botão "Entrar" ou "Cadastrar".

### Pedidos - Lado Centro Universitário.png
Tela referente ao caso de uso "Realizar pedido", executado pelo usuário "cliente" (no caso, a própria instituição de ensino).
Nela é possível realizar o cadastro de instância da classe _Pedido_ inserindo os valores de todos os atributos (obs.: os atributos "data" e "endereço" são registrados automaticamente baseado data da operação e na sede onde a operação foi executada).
Também é possível cadastrar o relacionamento com uma instância da classe _Fornecedor_.

### Pedidos - Lado Fornecedor.png
Tela referente ao caso de uso "Receber pedido", executado pelo usuário da classe _Fornecedor_.
Nela é possível visualizar os atribtuos das instância da classe _Pedido_ que possuem relação com a instâncida do usuário _Fornecedor_.

### Sistema - Aluno_01.png
Tela referente ao caso de uso "Realizar atividade", executado pelo usuário da classe _Aluno_.
Nela é possível realizar a atividade criada pela instância de usuário da classe _Professor_ que possua relação com a mesma instância da classe _Turma_ que o usuário da classe _Aluno_.

### Sistema - Aluno_02.png
Tela referente ao caso de uso "Visualizar notas", executado pelo usuário da classe _Aluno_.
Nela é possível visualizar as notas atribuídas pela instância de usuário da classe _Professor_ que possua relação com a mesma instância da classe _Turma_ que o usuário da classe _Aluno_.

### Sistema - Login.png
Tela referente ao caso de uso onde o usuário realiza login no sistema, após já ter realizado cadastro.

### Sistema - Prof_01.png
Tela referente ao caso de uso "Criar atividade", executado pelo usuário da classe _Professor_.
Nela é possível registrar uma atividade que será atribuída a instâncias de usuário da classe _Aluno_ que possuam relação com a mesma instância da classe _Turma_ que o usuário da classe _Professor_.

### Sistema - Prof_02.png
Tela referente ao caso de uso "Registrar notas", executado pelo usuário da classe _Professor_.
Nela é possível atribuir notas a instâncias de usuário da classe _Aluno_ que possuam relação com a mesma instância da classe _Turma_ que o usuário da classe _Professor_.

### Sistema - Prof_03.png
Tela referente ao caso de uso "Acessar turmas", executado pelo usuário da classe _Professor_.
Nela é possível acessar os atributos das instâncias da classe _Turma_ que possuam relação com o usuário da classe _Professor_.

### Sistema - Prof_03.png
Tela referente ao caso de uso "Acessar turmas", executado pelo usuário da classe _Professor_.
Nela é possível acessar os atributos das instâncias da classe _Turma_ que possuam relação com o usuário da classe _Professor_.




 


