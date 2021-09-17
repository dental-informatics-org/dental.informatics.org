# Dental Informatics: Python Education for Dental Surgeons 
![image](https://img.shields.io/github/languages/top/dental-informatics-org/dental.informatics.org)
![image](https://img.shields.io/github/repo-size/dental-informatics-org/dental.informatics.org?style=)
![image](https://img.shields.io/hexpm/l/plug?style=)

<br/>
Este repositório tem como objetivo fornecer material necessário para conhecimento e aprendizado de linguagens de programação para que cirurgiões-dentistas desenvolvam novas ferramentas e soluções inovadoras em sua área de atuação.

A programação está inserida em praticamente tudo que usamos atualmente, seja nos sistemas de atendimento de supermercados, aplicativos de bancos, análise de dados em saúde, entre outros. Assim, não precisa estar totalmente inserido na programação para entender como funciona a sua linguagem. 

Portanto, aprender as bases das linguagens de programação se tornará uma qualificação essencial para os futuros profissionais, visto que pode elevar a produtividade, as habilidades e se realçar no mercado de trabalho.

Os conhecimentos de programação incluem lógica, tomadas de decisão, resolução de problemas, o que colabora em produções criativas que ajudam no trabalho do profissional. Tudo isso traz eficiencia, criatividade e produz inovação no meio profissional.

<br/>

# Description

![image](https://img.shields.io/badge/Visual_Studio-5C2D91?style=&logo=visual%20studio&logoColor=white)
![image](https://img.shields.io/badge/Jupyter-F37626.svg?&style=&logo=Jupyter&logoColor=white)
![image](https://img.shields.io/badge/Python-FFD43B?style=&logo=python&logoColor=blue)
![image](https://img.shields.io/badge/HTML5-E34F26?style=&logo=html5&logoColor=white)
![image](https://img.shields.io/badge/CSS3-1572B6?style=&logo=css3&logoColor=white)

A era digital está em constante evolução e modificou como nos falamos e produzimos. A tecnologia faz parte do dia a dia de todos nós e inclusive de inúmeras empresas. Junto disso, quase todos os setores utilizam de softwares e hardwares para produzirem e facilitarem seus trabalhos. Por isso, é necessário que os profissionais saibam como funcionam as máquinas, os softwares e os hardwares a fim de trabalharem com maior eficácia e saberem resolver problemas que envolvam programação. Assim sendo, torna-se extremamente importante obter aprendizado de programação para criar, entender a lógica e resolver problemas em todo esse universo de forma inovadora.

A classe odontológica, apesar da adesão às tecnologias ascendentes como complementares nas técnicas, ainda é conservadora. Por isso, queremos disseminar o aprendizado de como se criam e funcionam softwares que estão por trás das grandes inovações do mercado odontológico. Sendo assim, o viés principal do Dental Informatics é capacitar os cirurgiões dentistas na linguagem de programação e torná-los profissionais com conhecimentos diferenciados no mercado, com skills que colaborem na criação de softwares, soluções inovadoras na área da Odontologia.

Aqui, separamos todos os materiais necessários para dar base aos conhecimentos de linguagens de programação, como vistos nos tópicos a seguir.

# Instalation

Não é necessário nenhuma instalação para estudar por esse repositório. Caso você queira trabalhar localmente em sua máquina recomendamentos instalar a última versão do Python 3, Conda Enviroments e Visual Studio Code.


> ## O que é o Google Colaboratory?

O Colaboratory ou "Colab" permite escrever código Python no seu navegador, com: 
- Nenhuma configuração necessária
- Acesso gratuito a GPUs
- Compartilhamento fácil

Você pode ser um <strong>estudante</strong>, um <strong>cientista de dados</strong> ou um <strong>pesquisador de IA</strong>, o Colab pode facilitar seu trabalho. Assista ao vídeo <a href="https://www.youtube.com/watch?v=inN8seMm7UI">Introdução ao Colab</a> para saber mais ou simplesmente comece a usá-lo abaixo!

## Primeiros passos

O documento que você está lendo não é uma página da Web estática, mas sim um ambiente interativo chamado notebook Colab que permite escrever e executar código.

Por exemplo, aqui está uma célula de código com um breve script Python que calcula um valor, armazena-o em uma variável e imprime o resultado:

```
seconds_in_a_day = 24 * 60 * 60
seconds_in_a_day
```
Para executar o código na célula acima, clique nela e depois pressione o botão Play à esquerda do código ou use o atalho do teclado "Command/Ctrl+Enter". Para editar o código, basta clicar na célula e começar a editar.

As variáveis definidas em uma célula podem ser usadas mais tarde em outras células:

```
seconds_in_a_week = 7 * seconds_in_a_day
seconds_in_a_week
```
Os notebooks do Colab permitem combinar código executável e rich text em um só documento, além de **imagens, HTML, LaTeX** e muito mais. Quando você cria seus próprios notebooks do Colab, eles são armazenados na sua conta do Google Drive. É possível compartilhar os notebooks do Colab facilmente com colegas de trabalho ou amigos e permitir que eles façam comentários ou até editem o documento. Para saber mais, consulte a [Visão Geral do Colab](https://colab.research.google.com/notebooks/basic_features_overview.ipynb). Para criar um novo notebook do Colab, use o menu Arquivo acima ou acesse o seguinte: [criar um novo notebook do Colab](http://colab.research.google.com/#create=true).

Os notebooks do Colab são notebooks do Jupyter hospedados no Colab. Para saber mais sobre o projeto Jupyter, acesse jupyter.org.

## Ciência de dados
Com o Colab, você pode aproveitar todo o potencial das conhecidas bibliotecas Python para analisar e ver dados. A célula de códigos abaixo usa **numpy** para gerar dados aleatórios e **matplotlib** para visualizá-los. Para editar o código, basta clicar na célula e começar a editar.

```
import numpy as np
from matplotlib import pyplot as plt

ys = 200 + np.random.randn(100)
x = [x for x in range(len(ys))]

plt.plot(x, ys, '-')
plt.fill_between(x, ys, 195, where=(ys > 195), facecolor='g', alpha=0.6)

plt.title("Sample Visualization")
plt.show()
```

É possível importar para os notebooks do Colab os dados da sua conta do Google Drive, como planilhas. Também é possível importar do GitHub e de muitas outras fontes. Para saber mais sobre como importar dados e como o Colab pode ser usado para a ciência de dados, consulte o link abaixo em [Como trabalhar com dados.](https://colab.research.google.com/notebooks/welcome.ipynb?hl=pt-BR#working-with-data)

## Machine learning

Com o Colab, é possível importar um conjunto de dados de imagem, treinar um classificador de imagens dentro dele e avaliar o modelo, tudo com apenas <a href="https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/tutorials/quickstart/beginner.ipynb">algumas linhas de código</a>. Os notebooks do Colab executam código dos servidores em nuvem do Google. Isso significa que você pode tirar proveito da potência de hardware do Google, como <a href="#using-accelerated-hardware">GPUs e TPUs</a>, independentemente da potência da sua máquina. Você só precisa de um navegador.

Com o Colab, é possível importar um conjunto de dados de imagem, treinar um classificador de imagens dentro dele e avaliar o modelo, tudo com apenas [algumas linhas de código.](https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/tutorials/quickstart/beginner.ipynb) Os notebooks do Colab executam código dos servidores em nuvem do Google. Isso significa que você pode tirar proveito da potência de hardware do Google, como [GPUs e TPUs](https://colab.research.google.com/notebooks/welcome.ipynb?hl=pt-BR#using-accelerated-hardware), independentemente da potência da sua máquina. Você só precisa de um navegador.

## Mais recursos

### Como trabalhar com Notebooks no Colab
- [Visão geral do Colaboratory](/notebooks/basic_features_overview.ipynb)
- [Guia sobre Markdown](/notebooks/markdown_guide.ipynb)
- [Importar bibliotecas e instalar dependências](/notebooks/snippets/importing_libraries.ipynb)
- [Salvar e carregar notebooks no GitHub](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb)
- [Formulários interativos](/notebooks/forms.ipynb)
- [Widgets interativos](/notebooks/widgets.ipynb)
- [TensorFlow 2 no Colab](/notebooks/tensorflow_version.ipynb)

<a name="working-with-data"></a>
### Como trabalhar com dados
- [Carregar dados: Drive, Planilhas e Google Cloud Storage](/notebooks/io.ipynb) 
- [Gráficos: visualizar dados](/notebooks/charts.ipynb)
- [Primeiros passos com o BigQuery](/notebooks/bigquery.ipynb)

### Curso intensivo de machine learning
Estes são alguns notebooks do curso on-line do Google sobre machine learning. Acesse o <a href="https://developers.google.com/machine-learning/crash-course/">site do curso completo</a> para saber mais.
- [Introdução à pandas](/notebooks/mlcc/intro_to_pandas.ipynb)
- [Conceitos do Tensorflow](/notebooks/mlcc/tensorflow_programming_concepts.ipynb)

<a name="using-accelerated-hardware"></a>
### Usar hardware acelerado
- [TensorFlow com GPUs](/notebooks/gpu.ipynb)
- [TensorFlow com TPUs](/notebooks/tpu.ipynb)

## Exemplos de machine learning

Para ver exemplos completos das análises interativas de machine learning possibilitadas pelo Colaboratory, confira estes tutoriais que usam modelos do <a href="https://tfhub.dev">TensorFlow Hub</a>.

Vejas alguns exemplos:

- <a href="https://tensorflow.org/hub/tutorials/tf2_image_retraining">Treinar novamente um classificador de imagens</a>: crie um modelo do Keras com base em um classificador de imagens pré-treinado para distinguir flores.
- <a href="https://tensorflow.org/hub/tutorials/tf2_text_classification">Classificação de texto</a>: classifique avaliações de filmes do IMDB como <em>positivas</em> ou <em>negativas</em>.
- <a href="https://tensorflow.org/hub/tutorials/tf2_arbitrary_image_stylization">Transferência de estilo</a>: use o aprendizado profundo para transferir o estilo entre imagens.
- <a href="https://tensorflow.org/hub/tutorials/retrieval_with_tf_hub_universal_encoder_qa">Perguntas e respostas sobre o codificador de frases universais multilíngue</a>: use um modelo de machine learning para responder a perguntas do conjunto de dados SQuAD.
- <a href="https://tensorflow.org/hub/tutorials/tweening_conv3d">Interpolação de vídeo</a>: preveja o que aconteceu em um vídeo entre o primeiro e o último frames.

<br/>

> ## Instalando o Python 3 no Windows
Para instalar o Python no seu sistema operacional Windows, você precisa baixar o instalador. Acesse o site oficial neste link e clique em download, como mostrado abaixo.

<br/>

![image](https://python.org.br/images/instalacao-windows/01.png)

Isso fará o download do Python 3 para sitemas de 32 bits. Para o instalador de 64 bits, acesse e selecione o instalador de 64 bits apropriado, como mostrado abaixo.

<br/>

![image](https://python.org.br/images/instalacao-windows/02.png)

Faça o download do instalador executável do Windows (32 ou 64 bits) e clique duas vezes nele para iniciar o assistente de instalação do python, como mostrado abaixo.

<br/>

![image](https://python.org.br/images/instalacao-windows/03.png)

O processo de instalação é bem simples.
1. Marque a opção "Add Python to PATH"
2. Clique em "Install Now"

A tela abaixo será mostrada. Aguarde enquanto o instalador completa o processo de instalação.

<br/>

![image](https://python.org.br/images/instalacao-windows/04.png)



Se tudo ocorrer bem, a próxima tela será mostrada. Clique em "Close".

<br/>

![image](https://python.org.br/images/instalacao-windows/05.png)


Para verificar se a instalação do Python foi bem-sucedida, pesquise no menu iniciar por "cmd" e clique duas vezes para abri-lo.

<br/>

![image](https://python.org.br/images/instalacao-windows/06.png)

Digite o seguinte comando:

```
python --version
```

<br/>

![image](https://python.org.br/images/instalacao-windows/07.png)


Agora digite:
```
pip --version
```

Esse comando retornará a versão do pip que está instalada em sua máquina. O pip é o gerenciador de pacote do Python. Com ele você poderá adicionar novas funcionalidades ao seu Python.


Este comando retornará a versão do python que está instalada em sua máquina.

<br/>

![image](https://python.org.br/images/instalacao-windows/08.png)


## IDLE

O IDLE (Ambiente de Desenvolvimento e Aprendizagem Integrado) é um ambiente de desenvolvimento integrado (IDE) para Python. O instalador do Python para Windows contém o módulo IDLE por padrão.

O IDLE pode ser usado para executar uma única instrução, como o Python Shell, e também para criar, modificar e executar scripts Python. O IDLE fornece um editor de texto completo para criar scripts Python que incluem recursos como destaque de sintaxe, preenchimento automático e recuo inteligente. Ele também possui um depurador com recursos de etapas e pontos de interrupção.

Para iniciar o shell interativo IDLE, procure o ícone IDLE no menu Iniciar e clique duas vezes nele.

<br/>

![image](https://python.org.br/images/instalacao-windows/09.png)


Isso abrirá o IDLE, onde você pode escrever o código Python e executá-lo como mostrado abaixo.

<br/>

![image](https://python.org.br/images/instalacao-windows/11.gif)


Parabéns, agora o Python, o pip e o Idle já estão instalados em seu sistema Windows.


```markdown
Syntax highlighted code block

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

# Usage
![image](https://img.shields.io/badge/Google_chrome-4285F4?style=&logo=Google-chrome&logoColor=white)
![image](https://img.shields.io/badge/Colab-F9AB00?style=&logo=googlecolab&color=525252)
![image](https://img.shields.io/badge/Windows-0078D6?style=&logo=windows&logoColor=white)
![image](https://img.shields.io/badge/mac%20os-000000?style=&logo=apple&logoColor=white)
![image](https://img.shields.io/badge/Linux-FCC624?style=&logo=linux&logoColor=black)
![image](https://img.shields.io/badge/Android-3DDC84?style=&logo=android&logoColor=white)
![image](https://img.shields.io/badge/iOS-000000?style=&logo=ios&logoColor=white)


# Roadmap
1- [Basic Sintax](https://github.com/dental-informatics-org/dental.informatics.org/blob/main/Python_Course/Basic_Syntax.ipynb)

# Support or Contact
Contate os colaboradores do projeto para obter suporte do projeto.

# Contributing
![image](https://img.shields.io/badge/Slack-4A154B?style=&logo=slack&logoColor=white)
![image](https://img.shields.io/badge/Markdown-000000?style=&logo=markdown&logoColor=white)
![image](https://img.shields.io/badge/conda-342B029.svg?&style=&logo=anaconda&logoColor=white)
![image](https://img.shields.io/badge/GitKraken-179287?style=&logo=GitKraken&logoColor=white)

Sinta-se à vontade para reportar um Issue antes de fazer um Pull Request! 


# Authors
### Igor Alves, Gustavo Raime e Vinicius Henrique

# License
Copyright [yyyy] [name of copyright owner]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

# Project status

### O projeto está em andamento.

