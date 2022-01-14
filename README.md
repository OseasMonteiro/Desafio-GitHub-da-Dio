# Repositório sobre Desafio de Projeto Git/GitHub da Dio.
## Tudo que já aprendi na Dio.
**1 - Curso Lógica de Programação Essencial**<br>
Aprendi que a lógica de programação é contextualizada em computadores buscando a melhor sequência de ações para resolver determinado problema.<br>
Alguns conceitos fundamentais:
- Abstração (significa desenvolver a habilidade de se concentrar nos aspectos essenciais de um contexto qualquer, ignorando outros aspectos menos importantes.)
- Algoritmo (é uma sequência de passos que soluciona um determinado problema.)
- Pseudocódigo (é uma forma genérica de escrever um algoritmo, utilizando linguagem simples.)
- Fluxograma (ferramenta utilizada para representar graficamente o algoritmo, a sequência lógica e coerente dos fluxos de dados)
![!Diagrama de Blocos!](https://i.ytimg.com/vi/VX4Lmp2OTpw/maxresdefault.jpg)
- Variáveis (é um objeto - uma posição, frequentemente localizada na memória - ela é capaz de reter e representar um valor ou expressão.<br> Em outras palavras é um espaço na memória do computador destinado a um dado que é alterado durante a execução do algoritmo.) - podem ser: Numéricas; Caracteres; Alfanuméricas e/ou Lógicas.
- Constante (são valores imutáveis e não são alterados durante a vida útil do pragrama.)<br>

**2 - Curso Introdução ao Portugol**<br>
Portugol: é uma pseudolinguagem que permite ao leitor desenvolver algoritmos estruturados em português de forma simples e intuitiva, independentemente da linguagem de programação.
Nesse curso desenvolvi habilidades de metacognição (pensar como você pensa), como transmitir orientações passo a passo para que o computador reconheça as ordens e execute todo o processo.<br>
Passei a conhecer o que é:
- Estrutura de repetição (loop)(é uma estrutura que permite executar mais de uma vez o mesmo comando ou conjunto de comandos, de acordo com uma condição.)
- Linguagem de programação de Alto Nível (aquelas cuja sintaxe se aproxima mais da nossa linguagem e se distancia mais da linguagem de máquina. Ex: Linguagem C/PHP/JavaScript/C#,etc.)
- Liguagem de programação de Baixo Nível (aquelas que se aproximam da linguagem de máquina. É necessário ter conhecimento direto da arquitetura do computador para desnvolver alguma coisa. Ex: Assembly)
- Linguagem de programação Compilada (é uma linguagem em que o código fonte é executado diretamente pelo sistema operacional ou processador, após ser traduzido por meio de um processo de ccompilação. Ex: C#/Visul Basic/Delphi/C++,etc.)
- Linguagem de programação Interpretadas (é uma linguagem em que o código fonte é execcutado por um programa de computador(interpretador), em seguida é executado pelo sistema operacional ou pelo processador. Ex: JavaScript/PHP/Python,etc.)
- Desvios Condicionais: **SE**, **SE-SENÃO**, **CASO**<br>
Esses desvios chamados de booleanos levam ao raciocínio de que a condição a ser testada deve ser ou verdadeira ou falsa, não podendo ser as duas opções ao mesmo tempo. Logo (**SE**) for verdadeiro realiza-se determinado procedimento, (**SENÃO**) segue outra resolução para o procedimento. No (**CASO**) é dada similarmente aos comandos do SE,SENÃO, porém este comando não trabalhará com operadores lógicos e sim com valores definidos. Ex: é dada diversas opções a uma pessoa escolher determinado objeto caso ela não esccolha a opção 1, terá então a opção 2 e assim sucessivamente até terminarem as opções.)
- **Matrizes e Vetores**
Para Matrizes temos o conceito de que é uma coleção de variáveis de mesmo tipo, acessíveis com um único nome e armazenadas contiguamente na memória. A individualização de cada variável de um setor é feita através do uso de Índices.<br>
Para Vetores temos o seguinte conceito: são Matrizes de uma só dimensão.<br>

**3 - Curso Estrutura de Dados**<br>
É uma estrutura organizada de dados na memória (volátil) de uma computador ou em qualquer dispositivo de armazenamento, de forma que os dados possam ser utilizados de forma correta. Dessa forma é possível trabalhar com grande quantidade de dados, como aplicações em bancos de dados ou serviço de busca.<br>
Em uma estrutura de dados devemos saber como realizar um determinado conjunto de operações básicas. Ex: _Inserir dados; Excluir dados; Localizar um elemento; Percorrer todos os itens constituintes da estrutura para visualização; Classificar, que se resume em colocar os itens de dados em uma determinada ordem (numérica,alfabética,etc)._<br>
**Principais Estruturas de Dados:**<br>
1. Vetores e Matrizes (Arrays) (Vetores são estruturas de dados simples que podem auxiliar quando há muitas variáveis do mesmo tipo em um algoritmo; o vetor ou array uni-dimensional é uma variável que armazena várias varáveis do mesmo tipo, ele é uma estrutura de dados indexada, que pode armazenar uma determinada quantidade de valores do mesmo tipo.) (Matrizes ou array multi-dimensional é um vetor de vetores. Uma matriz é um vetor que possui duas ou mais dimensões.)<br>
2. Registro (É uma estrutura que fornece um formato especializado para armazenar informações em memória. Enquanto Arrays nos permitem armazenar vários dados de um único tipo de dado, o recurso de Registro nos permite armazenar mais de um tipo de dado. É composto por campos que especificam cada uma das informações que os compõem. Toda estrutura de registro tem um nome (Ex: livro), e seus campos podem ser acessados por meio do uso do operador ponto(.). Ex: Livro.preco)<br>
3. Listas (A diferença entre listas e arrays é a de que as listas possuem tamanho ajustável, enquanto arrays possuem tamanho fixo.)<br>Existem dois tipos de listas:
3.a<br> - Lista Ligada (Nesse tipo de lista os nós conhecem o valor que está sendo armazenado em seu interior além de conhecer o elemento posterior a ele, ou seja, os nós são amarrados com essa indicação de qual é o próximo nó.) <br>
3.b - Lista Duplamente Ligada (É uma variação das lista ligada, a diferença é que essas são bidirecionais, ou seja, os nós sabem quem é o próximo elemento e também quem é o elemento anterior, o que permite a navegação reversa.) <br>
4. Pilhas (É uma estrutura de dados que serve como coleção de elementos, e permite o acesso a somente um item de dados armazenado, somente um item pode ser lido ou removido por vez.) <br>Existem dois tipos de Pilhas: 
4.a<br> - Pilha LIFO _(Last in First Out)_ ou UEPS _(Último que Entra, Primeiro que Sai)_ o 1º elemento a ser retirado é o último que tiver sido inserido. <br>
4.b - Pilha FIFO _(First in First Out)_ ou PEPS _(Primeiro que Entra, Primeiro que Sai)_ o 1º elemento a ser retirado é o 1º que tiver sido inserido. <br>
5. Filas (Essa estrutura admite remoção de elementos e inserção de novos, sujeita a seguinte regra de operação: <br>
O elemento removido é o que esta na estrutura há mais tempo ou seja, o 1º objeto inserido na fila é também o 1º a ser removido seguindo o conceito FIFO.)<br>
6. Árvore (Essa é uma estrutura que organiza seus elementos de forma hierárquica, onde existe um elemento que fica no topo da árvore, chamado de raiz e existem os elementos subordinados a ele, que são cahamados de nós ou folhas.)<br>
7. Tabela Hash _(Tabela de Disperção ou Espelhamento)_ (É uma estrutura de dados especial, que associa chaves de pesquisa a valores.)<br>
Ela é uma generalização da ideia de array, porém utiliza uma função chamada _Hashing_ para espalhar os elementos, fazendo com que os mesmos fiquem de forma não ordenada dentro do "array" que define a tabela.<br> 
Nesse contexto: Valores = é a posição ou índice onde o elemento se encontra. Chave = parte da informação que compõe o elemento a ser manipulado.<br>
8. Grafos (São estruturas que permitem programar a relação entre objetos (objetos são vértices ou nós do grafo, os relacionamentos são as arestas.))<br>

**4 - Curso Git/GitHub**<br>
1. Git (Criado em 2005, pelo Linux Torvalds, é um software open source, tem como finalidade ser um sistema de versionamento de código distribuído, ele ajuda a criar e a monitorar diferentes versões do nosso código, dentro da nossa máquina. Outras tecnologias similares: Bitkeeper, CVS, Subversion, etc. )<br>
2. GitHub (É uma empresa da Microsoft, tem por objetivo armazenar repositórios online. Outras tecnologias similares: GitLab, BitBucket, etc.)<br>
**Navegação Básica no GitBash**<br>
- o Git é _CLI (Command Line Interface)_,ou seja, não possui interface gráfica para manipulá-lo, apesar de existir programas que acrescentam um _GUI (Grafic User Interface)._<br>
- **Alguns comandos**<br>
**cd** _(change directory)_ (navegar entre as pastas.)<br>
**cd ..** (voltar à pasta anterior.)<br> 
**ls** (listar.)<br> 
**clear/Ctrl+l** (limpar.)<br>
**mkdir** (criar pasta.)<br>
**mv** (mover.)<br>
**git init** (inicia um repositório.)<br>
**git add "nome arquivo"** (move/adiciona arquivos.)<br>
**git add+asterisco** (adiciona tudo que foi modificado.)<br>
**git add.** (adicicona.)<br>
**git commit** (cria um commit.)<br>
**git commit -m "msg"** (coloca uma msg no commit.)<br>
**git status** (mostra o status do arquivo = _(untracked/Unmodified/Modified/Staged.)_<br>
**git config --list** (lista todas as configurações.)<br>
**git config --global --unset user.email** (reescreve as configurações.)<br>
**git remote add origin** (adiciona repositório remoto (link GitHub).)<br>
**git remote -v** (lista os repositórios cadastrados.)<br>
**git push origin master/main** (empurra os arquivos para o repositório remoto.)<br>
**git pull origin master** (puxa os arquivos para o repositório local.)<br>
**git remote rename origin githuburl** (renomeia url do repositório remoto.)<br>
**git remote remove githuburl** (exclui url do repositório remoto.)<br>
**git clone "url"** (clona o repositório remoto para repositório local.)
3. Entendendo como o Git funciona:<br>
O Git trabalha com um conjuntos de funções _hash_ criptográficas projetadas pela NSA _(Agência de Segurança Nacional dos EUA)_, chamado de SHA1.<br>
Ele usa uma encriptação que gera um conjunto de caracteres identificador de 40 dígitos, para identificar os arquivos de forma segura e rápida, isso significa que se o arquivo é modificado por uma vírgula(,) gerará automaticamente um outro conjunto de caracteres de 40 dígitos como meio de criptografar o arquivo e manter sua integridade.
## Links Úteis:
- [Markdown](https://www.markdownguide.org/basic-syntax)
- [Markdown online](https://dillinger.io/)
- [Download Portugol](https://github.com/UNIVALI-LITE/Portugol-Studio/releases/)
