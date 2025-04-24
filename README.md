### 1- Criar Projeto Python - Poetry / UV
### 1.1- Como instalar pyenv no Ubuntu -> https://gist.github.com/luzfcb/ef29561ff81e81e348ab7d6824e14404

### 2- Estrutura de Pastas 
### 2.1- Material da Aula

### 3- Configuração do Spark com Delta e Iceberg 
### 3.1- Como Configurar o Pyspark e Jupyter Lab com Poetry -> https://www.youtube.com/watch?v=EEH2LTNZoEg
### 3.2- Como Usar Python com Apache Spark? -> https://www.youtube.com/watch?v=WwrX1YVmOyA
### 3.3- Como Configurar o Pyspark e Delta Lake com Poetry -> https://www.youtube.com/watch?v=2ubkqLY-cbE
### 3.4- Como Sair do Zero no Delta Lake e PySpark -> https://www.youtube.com/watch?v=eOrWEsZIfKU

### 4- Documentação com MKDocs (Celta e Iceberg)
### 4.1- Documentado projetos com MkDocs -> https://www.youtube.com/watch?v=GW6nAJ1NHUQ


1. Pyenv (gerenciador de versões do Python)

1.1 Baixar versões do Python para trabalhar em projetos com "Pyenv":
    Comando: pyenv install <version> (ex.: pyenv install 3.12.3)

1.2 Selecionar a versão para o projeto
    Comando: pyenv local <version> (ex.: pyenv local 3.12.3) -- Para definar dentro do projeto que ele irá com a versão informada (local).
                OU
    Comando: pyenv global <version>  -- Para definir que todos novos projetos receberão a versão global quando criados.

2. Poetry (gerenciador de pacotes para Python)

2.1 Configurar o Poetry para criar automaticamente o ambiente virtual dentro de cada repositório.
    Comando: poetry config virtualenvs.in-project true

2.2 Iniciar o poetry dentro de um repositório
    Comando: poetry init

3. Apache Spark (camada de processamento) e Jupyter Labs (camada interativa para visualizar e maniputar dados)

3.1 Instalar as bibliotecas
    Comando: Poetry add pyspark jupyterlab

4. Delta Lake e Iceberg

4.1 Delta lake (verificar biblioteca ou método para rodar na aplicação!!)

4.2 Instalação da biblioteca pyiceberg
    Comando: poetry add pyiceberg

