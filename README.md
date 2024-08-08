## BootCamp - Analista de Dados na SoulCode 

# Bibliotecas a Serem Instaladas Durante o BootCamp
- Numpy - pip install numpy
- Matplotlib - pip install matplotlib
- Pandas -  pip install pandas
- PySpark -  pip install pyspark

# Python
- Pytho Fundamentos
    - Inteiro 
    - Float
    - String
    - Boolean

- Operadores
    - Matematica (+, -, *, /, %, **)
    - Soma +
    - subtração -
    - Multiplicação *
    - Divisão /
    - Divisão Inteira //
    - Resto da Divisão %
    - Exponenciação **

- Comparação
    - <> maior e menor
    - == Igual ou is
    - != Diferente igual
    - <= Menor Igual e >= Maior Igual

-  Operadores Lógicos
    - and  - Somente sera verdadeiro se os dois for Verdadeiro
    - Or - Sera verdadeiro se um das operações for verdeiro
    - Not - inverte o valor Booleano da Variavel

- Condicionais
    - If - else -  elif

- Estrutura de Repetição
    - For  - Um loop for é usado para iterar sobre uma sequência (que pode ser uma lista, uma tupla, um dicionário, um conjunto ou uma string).
    - While - o Codigo sera executado enquanto for verdadeiro

- Métodos Comuns de Strings
    - len() - Retorna o comprimento da string 
    - lower() - Converter todos os caracteres da string para minúsculas.
    - upper() - Converter todos os caracteres da string para maiúsculas.
    - strip() - Remove espaços em branco do início e do fim de uma string.
    - split() - Divide a string em uma lista de subtrings com base em um delimitador.
    - replace() - Substitui uma substring por outra substring.
    - join() - Une todos os elementos de uma lista em uma string.
    - find() - Retorna o indice da primeira ocorrência ou -1 se não encontrar.
    - count() - Conta o número de ocorrências de uma substring.
    - startswith() - Verifica se a string começa com uma substring.
    - endswith() - Verifica se a string termina com uma substring.
    - capitalize() - Coloca a primeira letra da string em maiúscula.
    - title() - Coloca a primeira letra de cada palavra da string em maiúscula

- Tuplas
    - são estruturas de dados imutáveis

- Listas
    - Tuplas são objetos, então vamos conseguir armazenar informações dentro delas, são semelhantes às Listas com alguns detalhes de diferença quanto em Dicionários no Python.

    - Lista []
linguagens = ["Python", "Java", "PHP", "C"]

    - Tupla ()
linguagens = ("Python", "Java", "PHP", "C")
    - Set {}
linguagens = {"Python", "Java", "PHP", "C"}


- Dicionarios
    - Um dicionário em Python é uma estrutura de dados que permite armazenar dados em pares. Chamamos cada par de dados de par chave-valor.

    - Dicionário {}
optimus = {"id": 1, "nome": "Optimus Prime"}

- Jupyter
    - 

- Pandas
    - Pandas é uma biblioteca Python usada para trabalhar com conjuntos de dados.

    - Possui funções para analisar, limpar, explorar e manipular dados.
    
    -  DataFrames
        - DataFrame.index - O índice (rótulos de linha) do DataFrame.
        - DataFrame.columns - Os rótulos de coluna do DataFrame.
        - DataFrame.dtipos - Retorne os dtypes no DataFrame.
        - DataFrame.info([verbose, buf, max_cols, ...]) - Imprima um resumo conciso de um DataFrame.
        - ([incluir, excluir]) - Retorne um subconjunto das colunas do DataFrame com base nos dtypes de coluna.
        - DataFrame.values - Retorne uma representação Numpy do DataFrame.
        - DataFrame.axes - Retorne uma lista que representa os eixos do DataFrame.
        - DataFrame.ndim - Retorna um int representando o número de eixos / dimensões da matriz.
        - DataFrame.size - Retorna um int que representa o número de elementos neste objeto.
        - DataFrame.shape - Retorne uma tupla que representa a dimensionalidade do DataFrame.
        - ([índice, profundo]) - Retorne o uso de memória de cada coluna em bytes.
        - DataFrame.empty - Indicador se Series/DataFrame está vazio.
        - (*[, cópia, ...]) - Retorna um novo objeto com sinalizadores atualizados.
        - DataFrame.head([n]) - Exibe as primeiras n linhas do DataFrame.

    - Conversão
        - DataFrame.astype(dtype[, copy, errors]) - Converta um objeto pandas em um dtype especificado.dtype

        - DataFrame.convert_dtypes([infer_objects, ...]) - Converta colunas nos melhores dtypes possíveis usando dtypes que suportam .pd.NA

        - ([cópia]) - Tente inferir melhores dtypes para colunas de objeto.

        - ([profundo]) - Faça uma cópia dos índices e dados desse objeto.

        - DataFrame.bool() - (OBSOLETO) Retorna o bool de um único elemento Series ou DataFrame.

        - DataFrame.to_numpy([dtype, copy, na_value]) - Converta o DataFrame em uma matriz NumPy.

    - Indexação, iteração
        
        - DataFrame.head([n]) - Retorne as primeiras n linhas.

        - DataFrame.at - Acesse um único valor para um par de rótulos de linha/coluna.

        - DataFrame.iat - Acesse um único valor para um par de linha/coluna por posição inteira.

        - DataFrame.loc - Acesse um grupo de linhas e colunas por rótulo(s) ou uma matriz booleana.

        - DataFrame.iloc - (OBSOLETO) Indexação baseada em localização de inteiros para seleção por posição.

        - (loc, coluna, valor[, ...]) - Insira a coluna em DataFrame no local especificado.

        - DataFrame.__iter__() - Iterar sobre o eixo de informações.

        - DataFrame.items() - Iterar sobre pares (nome da coluna, Série).

        - DataFrame.keys() - Obtenha o 'eixo de informações' (consulte Indexação para obter mais informações).

        - DataFrame.iterrows() - Iterar em linhas DataFrame como pares (índice, Série).

        - ([índice, nome]) - Iterar sobre linhas DataFrame como namedtuples.

        - DataFrame.pop(item) - Devolva o item e solte do quadro.

        - DataFrame.tail([n]) - Retorne as últimas n linhas.

        - (chave[, eixo, nível, drop_level]) - Retorne a seção transversal do Series/DataFrame.

        - (chave[, padrão]) - Obter item do objeto para determinada chave (por exemplo: coluna DataFrame).

        - (valores) - Se cada elemento no DataFrame está contido em valores.

        - (cond[, outro, inplace, ...]) - Substitua os valores em que a condição é False.

        - (cond[, outro, inplace, eixo, ...]) - Substitua os valores em que a condição é True.

        - (expr, *[, no lugar]) - Consulte as colunas de um DataFrame com uma expressão booleana.

- PySpark
    - PySpark é a API Python para Apache Spark. Ele permite que você execute em tempo real, processamento de dados em larga escala em um ambiente distribuído usando Python. Ele também fornece um PySpark shell para analisar interativamente seus dados.

    - O PySpark combina a capacidade de aprendizado e a facilidade de uso do Python com o poder do Apache Spark para permitir o processamento e a análise de dados em qualquer tamanho para todos os que estão familiarizados com o Python.

    - O PySpark suporta todos os recursos do Spark, como:
    - Spark SQL
        - O Spark SQL é o módulo do Apache Spark para trabalhar com dados estruturados. Ele permite que você misture perfeitamente consultas SQL com programas Spark. Com o PySpark DataFrames, você pode ler, gravar, transformar, e analisar dados usando Python e SQL. Se você usa Python ou SQL, a mesma execução subjacente engine é usado para que você sempre aproveite todo o poder do Spark.


    - Streaming Estruturado
    - Machine Learning (MLlib) 
    -  Spark Core.

# Cloud
- Introdução a Nuvem
- Ambientes On Premise x Clound
- Gerencimento de Usuario
- Cloud Storage
- Noções dde Infraestrutura em Nuvem

# Banco de Dados
- Fundamentodes de Banco de dados (Modelagem e SGBDs)
- Limguagem SQL
- Banco de Dados NoSQL
- Big Data - Analise com Big Query
- Spark SQL

# Insigths
- Estatistica Basica
- Storytelling de Dados
- Data Visualization - looker Studio e Power BI