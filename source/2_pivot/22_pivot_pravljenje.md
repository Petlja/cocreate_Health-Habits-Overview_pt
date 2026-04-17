# Como criar uma tabela dinâmica?

```{infonote}
**Os quatro elementos básicos de uma tabela dinâmica**

- **Linhas (*Rows*)** - Categorias apresentadas no lado esquerdo da tabela.
- **Colunas (*Columns*)** - Categorias apresentadas na parte superior da tabela.
- **Valores (*Values*)** - Números calculados (soma, contagem, média…).
- **Filtros (*Filters*)** - Permitem mostrar apenas uma parte dos dados.
```

## Criar uma tabela dinâmica — passo a passo

### Passo 1: Selecione a tabela com os dados
Clique em qualquer célula da tabela e prima a combinação de teclas *Ctrl + A*

![Passo 1](images/pivot1_sr.png)

### Passo 2: Inicie a criação da tabela dinâmica
Clique em *Insert* (1), *PivotTable* (2) e selecione a opção *From Table/Range* (3)

![Passo 2](images/pivot2_sr.png)

### Passo 3: Escolha onde pretende colocar a sua tabela dinâmica
Pode escolher uma nova folha de cálculo (*New Worksheet*) ou uma localização na mesma folha (*Existing Worksheet*) (4) (nesse caso, clique na célula que corresponderá ao canto superior esquerdo da sua tabela dinâmica) (5). Confirme clicando em *Ok*. (6)

![Passo 3](images/pivot3_sr.png)

### Passo 4: Conheça o editor de tabelas dinâmicas
As configurações da tabela dinâmica são feitas arrastando campos (7) para as zonas desejadas (8).

![Passo 4](images/pivot4_sr.png)

### Passo 5: Adicione linhas (*Rows*) e valores (*Values*)
Para o primeiro exemplo da introdução, arrastámos o campo *fruta* para a zona *Rows*. Para a zona *Values* arrastámos o campo *quantidade [kg]*

![Passo 5](images/pivot5_sr.png)


```{infonote}
O método de cálculo na área Values pode ser alterado através da opção Value Field Settings. Para além da soma predefinida (Sum), estão também disponíveis Average (média), Count (número de entradas), Min e Max. É importante saber que, se um campo de texto for colocado na área Values, a tabela dinâmica irá mostrar automaticamente o número de ocorrências desse texto (Count) em vez da soma.
```

### Passo 6: Adicione colunas (opcional)
A tabela que mostra também o método de pagamento dos clientes foi obtida adicionando o campo *método de pagamento* à zona Colunas (*Columns*) (10)

![Passo 6](images/pivot6_sr.png)

```{infonote}
Se o painel do lado direito que permite configurar a apresentação da tabela dinâmica for fechado, pode reabri-lo clicando em qualquer célula da tabela dinâmica e selecionando a opção Show field list.
```
### Passo 7: Adicione filtros (opcional)
A adição de filtros permite extrair e apresentar rapidamente, a partir de uma grande quantidade de dados, apenas os valores necessários num dado momento, sem alterar a tabela original nem fazer cálculos adicionais.

```{infonote}
Embora a tabela dinâmica esteja ligada à tabela original, as alterações nesta não são atualizadas automaticamente. Após cada alteração, é necessário clicar com o botão direito na tabela dinâmica e selecionar a opção Refresh, para que todos os resultados sejam atualizados.
```
## Gráfico dinâmico

Os dados de uma tabela dinâmica também podem ser apresentados graficamente. Desta forma, os resultados tornam-se mais legíveis e as diferenças e relações são mais facilmente identificadas.

O gráfico dinâmico é criado da seguinte forma:

Clique dentro da tabela dinâmica e selecione a opção *PivotChart* no menu. Escolha o tipo de gráfico e confirme a seleção.

![Gráfico dinâmico](images/chart1_sr.png)

```{infonote}
O gráfico está ligado à tabela dinâmica, o que significa que qualquer alteração na tabela é automaticamente refletida no gráfico. Na apresentação gráfica, as vantagens da utilização de filtros tornam-se especialmente evidentes.
```

![Gráfico dinâmico](images/chart2_sr.png)