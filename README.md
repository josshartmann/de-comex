# Data Transformation and for Foreign Trade

This repository contains Python code and a VBA script that enable the transformation and styling of foreign trade data obtained from the database detailed by NCM (Mercosur Common Nomenclature).

## Passos para a Transformação dos Dados

1. Download the import and export data files in CSV format from the following link: [Detailed database by NCM](https://www.gov.br/produtividade-e-comercio-exterior/pt-br/assuntos/comercio-exterior/estatisticas/base-de-dados-bruta).

2. Use the Python code available in the `transform_data.py` file to process the CSV files and generate aggregated analyses by state, month, and NCM. Make sure you have the Pandas and Collections libraries installed. The code will generate separate CSV files by state containing the processed data.

3. Follow the instructions below to style the tables generated from the CSV files:

   - Open Microsoft Excel, replace the value in cell C2 in the active worksheet with the path to the folder where the processed CSV files are located.
   - Run the VBA script `AdicionarSheetsIE` to add worksheets for the CSV files in the specified folder, styling the tables as described in the VBA code.

4. Worksheets with styled tables will be created in a new Excel file. Each worksheet corresponds to a processed CSV file. The tables will have correctly merged cells, formatted values, adjusted headers, and applied styles.

## Notes

- Be sure to adjust the Python code provided in the `script.ipynb` file with the correct paths to the import and export CSV files.
- The import and export CSV files must be in the expected format for the Python code, with relevant columns for analysis.
- The Python code will process the data and generate separate CSV files by state in the specified output folder.
- The VBA script will add worksheets for the CSV files in the specified folder, styling the created tables.
- Make sure to adjust the value in cell C2 in the VBA script with the correct path to the folder where the processed CSV files are located.

## Conclusion

I trust that this repository and its accompanying documentation will assist you in effectively transforming and styling foreign trade data. Should you require any further assistance or have inquiries, please do not hesitate to reach out. I appreciate your interest and hope you find this resource valuable for your data-related endeavors.
