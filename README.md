TP01 - Integração de Sistemas de Informação (ISI)

Author: Aime Bruce Ishimwe Student 
number: 51224 Institutional
email: a51224@alunos.ipca.pt 
Course: Licenciatura em Engenharia de Sistemas Informáticos(Information Systems Integration ), 2026/27
Git repository: https://github.com/bruceaime/ISI_Project1_Population

Demonstration video:

http://youtu.be/BaqE4xc-2oE

Project description

ETL process built with Pentaho Data Integration (Kettle) that consolidates the historical population data of two countries from heterogeneous sources:

France: JSON file
Portugal: CSV file

The data from both sources is sorted by year, merged with a Merge Join, and exported to a single CSV file. A job orchestrates the run and sends an email notification: one on success and one on failure.
