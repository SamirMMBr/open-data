Fonte dos Dados:
- http://geogeral.com

Descrição do Dados:
- Dados obtidos do site http://geogeral.com que é um site de estudos e pode não representar os dados oficiais do país e/ou mais atuais.

Estrutura dos dados:
- As primeiras oito linhas são informações da origem dos dados copiadas do próprio site. Importante para saber quando atualizou os dados.
- A partir da nova linha temos a Cidade ( município ) ou Localidade, depois o Nome do Departamento entre colchetes separado com hífen o País e por fim a população.
- Atenção! Não foi colocado o "título" de cada coluna dos dados de propósito. Com o objetivo de tratar isso no Power Query / Excel / Power BI

Método usado para estudo:
- No Power Query tentei usar fonte de dados = WEB para buscar direto no site.
- Porém, a estrutura do site acima não possui uma tag html de tabela e este método não funcionou.
- Solução foi criar os arquivos TXT manualmente, usando Copiar (CTRL+L) e Colar(CRTL+V) do site para o bloco de notas.
- Já no Power Query, usadas primeiras 8 linhas para entender os dados e criar a etapas de tratamento dos dados
- Depois de criado a rotina para o primeiro arquivo / consulta, foi duplicada a consulta e trocado o caminho da fonte para outro arquivo TXT
- Por fim, unificar o resultado de todas consultas em uma "bolivia-todos-municipio-populacao"

Ferramentas necessárias para Estudo:
- PC ou Notebook com Microsoft Windows
- Microsoft Excel versões: 2013, 2016, 2019, Microsoft 365
- Microsoft Silverlight (descontinuado) obrigatório instalar para usar Power View dentro de Microsoft Excel.
- Power BI Desktop
- Atenção! Caso usar apenas o Power BI Desktop. NÃO é necessário instalar o Silverlight.

Downloads:
- Silverlight https://1drv.ms/f/s!AP_YqGmkzL8ah9Bn
- Power BI Desktop https://powerbi.microsoft.com/pt-br/downloads/