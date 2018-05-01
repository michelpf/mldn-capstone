# Machine Learning Engineer Nanodegree
# Projeto Final (Capstone)
## Classificação de demência baseado em atributos biológicos, sócio-econômicos, educacionais e testes de cognição


![Image of Dementia](https://github.com/michelpf/mldn-capstone-dementia-prediction/blob/master/documents/proposta_latex/imagem/dementia_iStock_000029744938_Large.jpg)

### Introdução

Este estudo visa avaliar a utilização dos algoritmos de classificação Random Forest e Support Vector Machines para separar as classes de grupos de controle e demência.

Ao utilizar atributos biológicos com atributos objetivos como condição social-econômica, educação e testes de cognição, foi possível tornar o modelo mais abrangente e com excelentes pontuações, alcançando níveis de sensibilidade superiores a 90% e área sob a curva (AUC) de 95%.

Este repositório inclui o Python Notebook, arquivos finais em PDF da proposta e do trabalho final além dos arquivos em Latex para servir de modelo para outros alunos do programa Nanodegree.

### Instalação

Este projeto requer **Python 3.5 ou superior** e as seguintes bibliotecas devem estar instaladas:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [seaborn](http://seaborn.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

É necessário ter alguma o aplicativo [Jupyter Notebook](http://ipython.org/notebook.html) para execução dos ensarios.

Se você não tem o Python instalado ainda é recomendável que você instale o [Anaconda](http://continuum.io/downloads) distribuição do Python que já possui a maioria dos pacotes instalados. 

### Código

O código provido no arquivo de notebook `dementia_prediction.ipynb` compreende todas as etapas de coleta, normalização, processamento e avaliação dos diferentes algoritmos de classificação utilizados.
Todos os arquivos necessários para sua execução estão presentes no diretório do projeto `dementia_prediction/`.

### Execução

No terminal ou na janela de comando, na raiz do projeto (que contém este README), acesse o diretório `dementia_prediction/`   e execute os seguintes comandos:

```bash
ipython notebook dementia_prediction.ipynb
```  
or
```bash
jupyter notebook dementia_prediction.ipynb
```

Este comando irá abrir a aplicação Jupyter Notebook e o arquivo do projeto no seu navegador.

### Dados

Obtendo os dados disponibilizados pelo projeto OASIS Brains (http://www.oasis-brains.org/). Dos dados apresentados possuem 373 amostras e 13 atributos, dos quais serão utilizados neste estudo 8 parâmetros.

Também há o mesmo conjunto de dados disponível no [Kaggle](http://kaggle.com) em [MRI and Alzheimers](https://www.kaggle.com/jboysen/mri-and-alzheimers)

**Atributos**

1.  `Subject ID`: identificação do paciente 
2. `MRI ID `: identificação do exame de RM 
3. `Visit`: Número da visita de acompanhamento
4. `MR Delay`: delay do exame de RM (contraste)
5. `M/F`: sexo
6. `Hand`: mão dominante (destro ou canhoto)
7. `EDUC`: nível de educação
8. `SES`: nível sócio-econômico
9. `MMSE`: teste de cognição MMSE 
10. `CDR`: teste de cognição CDR 
11. `eTIV`: volume intracraniano estimado 
12. `nWBV`: volume cerebral normalizado
13. `ASF`: fator de escala Atlas

**Variável Alvo**

14. `Group`: Classe, demência ou não demência

### Documentos

Os arquivos fontes dos documentos finais e da proposta estão no diretório `documents/` . Tais arquivos estão no formato Latex, aos quais podem ser utilizados em outros projetos de outros alunos deste programa de nanodegree.

Documentos finais para proposta de avaliação `capstone_proposta.pdf` e o relatório final `capstone_final.pdf`.
