# Processamento Massivo de Dados - CouchDB

**UFSCar Sorocaba - 2019/01**

Projeto desenvolvido para a disciplina de Processamento Massivo de Dados.

Alunos:
  - Bruno Morii Borges
  - Isabella Soares de Lima
  
### Descrição do Projeto

O objetivo é desenvolver um script de teste de performance, carga e estresse para o banco de dados CouchDB. A ferramenta utilizada para coletar as métricas é o Apache JMeter. Os dados estão em um arquivo no format JSON e foram retirados de um repositório online. Apenas parte dos dados é utilizado nos testes, um total de 28.061 documentos.

- **Avisos prévios quanto à execução** 

Todos os arquivos necessários para a execução de testes encontram-se neste projeto.
Utilize o JMeter que se encontra neste projeto e execute-o a partir da pasta na qual se encontra (as configurações de caminhos estão feitas a partir desta pasta)

- **Executando o JMeter no Windows** 

Executar o arquivo:

`apache-jmeter-5.1.1/bin/jmeter.bat`

(Recomenda-se a versão mais recente de Java presente no computador)

- **Plano de teste**

`Plano de Teste - PMD.jmx`

- **Dados**

Os dados da população inicial do BD estão nos arquivos `PMD.json` e `PMD. csv`.

Dados originais: "international-migration-april-2019-citizenship-by-visa-by-country-of-last-permanent-residence.csv"

Os dados utilizados para as operações de escrita durante os testes estão na pasta `CSV Inserções`.

- **Resultados**

Os resultados estão na pasta `Resultados`, com os Relatórios Agregados de todas as etapas do teste.
