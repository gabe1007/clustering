# Clustering usando a biblioteca **Rapids**


<p align="center">
  <img src="figura_clustering.jpg" width="350" title="hover text">
</p>

Clustering consiste em agrupar um conjunto de dados com base em suas semelhanças. Ao contrário de métodos de classificação e regressão, estamos lidando com aprendizagem não supervisionada, onde algoritmos compreendem as relações entre um conjunto de dados.

Aplicação
Podemos aplicar clustering em diversos setores da indústria. Alguns exemplos incluem:

* Segmentação de mercado.
* Análise de rede social.
* Agrupamento de resultados da pesquisa.
* Imagem médica.
* Segmentação de imagens.
* Detecção de anomalias.

# Dataset

O conjunto de dados utilizado foi coletado do [Condado de Montgomery](https://data.montgomerycountymd.gov/Public-Safety/Crime/icn6-v9z3) que fica no estado americano de Maryland. O dataset possui as seguintes colunas:

* **Incident ID**: Número de incidente policial.
* **Offence Code**: Offense_Code é o código para uma ofensa cometida, conforme definido pelo National Incident-Based Reporting System (NIBRS) do Programa de Relatórios Uniformes de Crimes (UCR) da Divisão de Serviços de Informações da Justiça Criminal (CJIS).
* **CR Number**: Número do relatório policial. 
* **Dispatch Date / Time**: Data de despacho de oficial de policia até a ocorrência.
* **NIBRS Code**: Códigos NIBRS (National Incident-Based Reporting System) do FBI.
* **Victims**: Vitimas. 
* **Crime Name1**: Denominação do crime. 
* **Crime Name2**: Denominação do crime.
* **Crime Name3**: Denominação do crime.
* **Police District Name**: Distrito de policia. 
* **Block Address**: Endereço do bloco.
* **City**: Cidade.
* **State**: Estado.
* **Zip Code**: Cep.
* **Agency**: Nome da agência de policia.
* **Place**: Descrição do local.
* **Sector**: Nome do setor policial.
* **Beat**: Área de patrulha da policia.
* **PRA**: Police response area (área de resposta policial).
* **Adress Number**: Número da residência.
* **Street Prefix**: Prefixo.
* **Street Sufix**: Sufixo.
* **Street Type**: Tipo de rua. 
* **Start_Date_Time**: Data do início da ocorrência. 
* **End_Date_Time**: Data do final da ocorrência
* **Latitude**: Latitude.
* **Longitude**: Longitude.
* **Police District Number**: Número do distrito policial.
* **Location**: Localização. 

## Authors

- [@gabe1007](https://github.com/gabe1007)



