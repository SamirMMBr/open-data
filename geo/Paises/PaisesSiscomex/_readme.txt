Fonte dos Dados:
- http://www.siscomex.gov.br

Descrição do Dados:
- Dados obtidos do site http://www.siscomex.gov.br/informacoes/tratamento-administrativo-de-exportacao/ que é um site do Governo do Brasil.
- Os arquivos disponibilizado aqui no GitHub, são cópias do SISCOMEX e podem não ser atuais.
- Você pode obter os dados diretamente no site da SISCOMEX entrando em "Países - códigos para uso na NF-e (atulizado em dd/mm/yyyy)" 
- Link direto para o arquivo http://siscomex.gov.br/wp-content/uploads/2021/01/PAISES.xlsx

Estrutura dos dados:
- O arquivo original PAISES.xlsx no site da SISCOMEX foi renomeado aqui no GitHub para PaisesSiscomexYYYYMMDD.xlsx
- Nas primeiras linhas, são encontradas a logamarca do SISCOMEX e outras informações.
- Em seguida, temos a tabela de dados que é composta pelas colunas e significado:
++ CÓDIGO SPED (uso na NF-e) = "Código do País para uso durante a Emissão da Nota Fiscal Eletrônica - NFe, este é código interno do sistema do SPED"
++ NO_PAIS_POR = "Nome do País em Português - SEM acentos"
++ NO_POR_MIN = "Nome do País em Português - COM acentos"
++ NO_PAIS_ING = "Nome do País em Inglês"
++ NO_PAIS_ESP = "Nome do País em Espanhol"
++ NO_PAIS_FRA = "Nome do País em Francês"
++ SISCOMEX = "Código do País, este é código interno do sistema do SISCOMEX"
++ A2 = "Sigla do País, com 2 dígitos alfanumérico"
++ A3 = "Sigla do País, com 3 dígitos alfanumérico"
++ N3 = "Sigla do País, com 3 dígitos numérico"
++ SITUAÇÃO = "Status do País, indica se foi incluído / excluído no SISCOMEX"
++ DATA INÍCIO = "Data de inclusão no SISCOMEX""
++ DATA FIM = "Data de Exclusão no SISCOMEX""
++ Filiação na OMC = "Data de Filiação na OMC - Organização Mundial do Comércio"
++ CAPITAL = "Nome da Capital do País"
++ Continente/Região = "Nome do Continente ou Região Geográfica do País"
++ População 2012 (1.000.000) = "População do País em Milhões"
++ ÁREA (KM2) = "Aréa do País em Quilômetros Quadrados"
++ IDIOMA = "Idiômas do País"
++ FORMA DE GOVERNO (2013) = "Regime Governamental do País"
++ MOEDA (2013) = "Moeda do País"
- Atenção! 
- A estrutura do "arquivo.xlsx" NÃO FOI MODIFICADA e NUNCA SERÁ.
- O objetivo é usar este arquivo como base para tratamento de ETL no Power Query / Excel / Power BI ou outra ferramenta de BI.

Método usado para estudo:
- Salvar o arquivo PaisesSiscomexYYYYMMDD.xlsx localmente no seu computador ( C:\ )
- No Excel usar o Power Query para o ETL tratamento dos dados e Power View para criar os relatórios
- No Power Desktop usar o Power Query para o ETL para o ETL tratamento dos dados e depois criar os relatórios
- Já no Power Query, usadas primeiras 8 linhas para entender os dados e criar a etapas de tratamento dos dados
- Observação: Também, é possível salvar o arquivo no OnDrive - Pessoal ou OnDrive Business
- Leia: Como usar URL de arquivos no OnDrive para carregar dados no Power Query

Ferramentas necessárias para Estudo:
- PC ou Notebook com Microsoft Windows
- Microsoft Excel versões: 2013, 2016, 2019, Microsoft 365
- Microsoft Silverlight (descontinuado) obrigatório instalar para usar Power View dentro de Microsoft Excel.
- Power BI Desktop
- Atenção! Caso usar apenas o Power BI Desktop. NÃO é necessário instalar o Silverlight.

Downloads:
- Silverlight https://1drv.ms/f/s!AP_YqGmkzL8ah9Bn
- Power BI Desktop https://powerbi.microsoft.com/pt-br/downloads/