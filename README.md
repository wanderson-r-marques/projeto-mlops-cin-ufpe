# Uma abordagem inovadora utilizando aprendizagem de máquina integrada ao Azure para classificação da causa de incêndios florestais em Alberta no Canadá
> Projeto desenvolvido por: Wanderson R. Marques , David S. Monte, Priscilla A. Lima 

![](header.png)

## Resumo

A província de Alberta no Canadá possui um amplo sistema de monitoramento e controle dos incêndios que além de combater o fogo, produz registros minuciosos sobre as ocorrências de incêndios. Nem sempre as ações investigativas sobre as origens dos incêndios são capazes de estabelecer se as ocorrências foram provocadas por ação humana ou por eventos naturais. Visando mitigar tal problema, os autores deste trabalho propuseram a utilização de modelos de aprendizagem de máquina, uma vez que o volume de informações registradas é amplo e engloba um longo período. Os resultados obtidos incluem modelos com acurácia superior 90% para a inferência da causa dos incêndios, bem como a implantação do modelo melhor avaliado no ambiente de nuvem Azure e um sistema web capaz de tornar a proposta apresentada disponível para uso imediato pelos órgãos responsáveis pelo monitoramento dos incêndios florestais em Alberta. 

## Dataframe:

As informações contidas no dataset abrangem detalhes específicos de cada ocorrência de incêndio registrada, tais como: área florestal, latitude, longitude, área atingida pelo fogo, origem do fogo, prováveis causas, data e hora de detecção, de início de combate, de controle e de extinção do incêndio.
> Para mais informações sobre o dataset, visite: https://wildfire.alberta.ca/resources/historical-data/historical-wildfire-database.aspx 

## Descrição dos arquivos

* alberta_fires_1996to2005.csv
    Dados dos incêndios registrados na província de Alberta do ano de 1996 até 2005  
* alberta_fires_2006to2018.csv
    Dados dos incêndios registrados na província de Alberta do ano de 2006 até 2018  
* features_alberta_canada.pdf
    Descreve cada variável contida no Dataframe 
* incendios_alberta_pre_processamento_versao_final.ipynb
    Notebook com pré-processamento, execução dos modelos e exibição de gráficos e métricas 
* requirements.txt
    Exibe as bibliotecas contidas no ambiente de desenvolvimento e suas respectivas versões
