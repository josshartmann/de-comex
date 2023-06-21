# Transformação e Estilização de Dados de Comércio Exterior

Este repositório contém um código em Python e um script VBA que permitem a transformação e estilização de dados de comércio exterior obtidos a partir da base de dados detalhada por NCM (Nomenclatura Comum do Mercosul).

## Passos para a Transformação dos Dados

1. Faça o download dos arquivos de dados de importação e exportação no formato CSV a partir do seguinte link: [Base de dados detalhada por NCM](https://www.gov.br/produtividade-e-comercio-exterior/pt-br/assuntos/comercio-exterior/estatisticas/base-de-dados-bruta).

2. Utilize o código em Python disponível no arquivo `transform_data.py` para processar os arquivos CSV e gerar análises agregadas por estado, mês e NCM. Certifique-se de ter as bibliotecas Pandas e Collections instaladas. O código irá gerar arquivos CSV separados por estado, contendo os dados processados.

3. Siga as instruções abaixo para estilizar as tabelas geradas a partir dos arquivos CSV:

   - Abra o Microsoft Excel, substitua o valor da célula C2 na planilha ativa com o caminho da pasta onde os arquivos CSV processados estão localizados.
   - Execute o script VBA `AdicionarSheetsIE` para adicionar as planilhas dos arquivos CSV na pasta especificada, estilizando as tabelas conforme descrito no código VBA.

4. As planilhas com as tabelas estilizadas serão criadas em um novo arquivo do Excel. Cada planilha corresponderá a um arquivo CSV processado. As tabelas terão as células mescladas corretamente, valores formatados, cabeçalhos ajustados e estilos aplicados.

## Observações

- Certifique-se de ajustar o código Python fornecido no arquivo `script.ipynb com os caminhos corretos para os arquivos CSV de importação e exportação.
- Os arquivos CSV de importação e exportação devem estar no formato esperado pelo código Python, com as colunas relevantes para a análise.
- O código Python irá processar os dados e gerar arquivos CSV separados por estado na pasta de saída especificada.
- O script VBA irá adicionar as planilhas dos arquivos CSV na pasta especificada, estilizando as tabelas criadas.
- Certifique-se de ajustar o valor da célula C2 no script VBA com o caminho correto da pasta onde os arquivos CSV processados estão localizados.

Divirta-se explorando e estilizando os dados de comércio exterior!
