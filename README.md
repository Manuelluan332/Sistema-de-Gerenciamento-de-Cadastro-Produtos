
#  🔍 Sistema de Gerenciamento de Cadastro de Produtos com SQLite 🎲📊

# Descrição do Projeto
Projeto desenvolvido durante  curso da Udemy [Engenharia de Dados com Python](https://www.udemy.com/course/engenharia-de-dados-com-python/?kw=engenharia+de+dados+com+python&src=sac&couponCode=ACCAGE0923), pelo Professor Edmilson Alves .O objetivo desse projeto foi desenvolver um sistema para gerenciar  produtos,no qual criar uma interface visual interativa, via python com a biblioteca **tkinter** para que o usuário possa se interagir inserindo os dados  e os cadastrando na janela para que possam ser salvos no banco de dados  **SQLite** , a partir de uma  conexão **jupyter python**.Além do  mais, com os dados armazendos no banco , também podemos gerar um arquivo feito em excel com as mesmas informações.


## 🧾Pré-Requistos, Instalações e Configurações do Banco de dados

### 1.Pré-Requisto:
* Python3x.
* SQLite.
* Visual Studio Code.
* Dbeaver(Opcional, caso queria gerar uma conxão com o banco)
### 2.Instalações:

### 2.1 Instalações das  depedências:
```
#01.Criando  o ambiente virtual:

pip install virtualenv #ou pip3 install virtualenv

#02.Ativando o ambiente Virtual:

mome_do_ambiente \Scripts\activate
Ex: Sgbds\Scripts\activate


#03.Se der erro ao criar ou ativar rodar  o comando ative esse codigo  no Shell como ADm para liberar.

#Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
```

### 2.2 Instalação das  bibliotecas(pyslite3/Pandas/Tkinter/Arquivo xlsx)
```
#01.Biblioteca  pysqlite3:
pip install pysqlite3
pip install --upgrade pysqlite3 # Caso esteja instalado no seu ambiente Virtual.

#02.Biblioteca pandas:
pip install pandas

#03.Biblioteca  Tkinter:
python -m tkinter

#04.Biblioteca OpePyXl para arquivos .xlsx: 
pip install openpyxl

```
### 3.Configurações do Banco de dados:

#### 3.1 Abra o Visual Studio Code, no segundo arquivo  **02.Projects** , logo no primeiro código clique nele, no qual vai criar e gerar um banco dados  no projeto.**Somente rode ele uma vez**.

#### 3.2 Logo em seguinda, vai direto no banco de dados **SQLite** .Clique em banco de dados, vai na aba adicionar banco de dados  ou (CTR + O ).Após isso, vai  na pasta que criou o banco de dados e exporte o arquivo e clique nele para ficar salvo no projeto.

#### 3.3 Por fim, clique um banco de dados que vai ser gerado com o mesmo  foi criado no Visual Studio Code. Clique no icone de duas tomadas, para gerar conexão e pronto a tabela vai está criada e inserida no banco. Assim ,você pode rodar o código logo abaixo e se interagir com a interface visual conectada pelo banco pelo jupyter python.

#### 3.4 Tabela gerada no banco:

```
CREATE TABLE produto (
    id,
    nome,
    valor,
    fornecedor,
    categoria,
    responsavel_cadastro
);

```
## 🛠 Ferramentas Utilizadas:
 * Linguagem:**Python.**
 * Biblioteca: **Pandas,jupyter Python,openpyxl, Tkinter e Sqlite3.**
 * Banco de dados: **SQlite.**
 * Ferramentas Sql: **DBeaver/Sqlite.**

## 💼 Arquitetura do Sistema:
```
SQLite-Project/
├──Referencias/
|Ambiente Virtual.ipynb
|Referencias Sqlite.ipynb
├──Scripts/
|01.Comando.ipynb
|02.Projeto Cadastro Produto
|Cadastrar_produto.db
|Produto.xlsx
├── Sgbds   


```

## 🖼️ Visulumbre da janela Tkinter:
<img width="1890" height="997" alt="Captura de tela 2026-01-23 200400" src="https://github.com/user-attachments/assets/325b72b2-d09b-4117-ae87-3718d1428e18" />


## 📃Referências da Web:



#### SQLiteStudio: 
https://sqlitestudio.pl/

#### wikipedia:
https://pt.wikipedia.org/wiki/SQLite

#### SQLite Site Oficial:
https://www.sqlite.org/


#### Documentação Python:
https://docs.python.org/pt-br/3/library/sqlite3.html

#### Manual do usuario:
https://github.com/pawelsalawa/sqlitestudio/wiki/User_Manual

#### Documentação SQLite:
https://sqlite.org/lang.html

#### Documentação tkinter:

 https://docs.python.org/pt-br/3/library/tk.html

 https://docs.python.org/pt-br/3/library/tkinter.html
