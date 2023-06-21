# M6-S9_Solucoes_PLN

---
O objetivo desta atividade é realizar um levantamento das ferramentas de PLN presentes em uma nuvem comercial. Listar os serviços e um exemplo de aplicação de cada um deles. Atenção: cada aluno deve listar os serviços de apenas uma nuvem comercial. Apresentar os resultados como um arquivo Markdown no Github.

# Google Cloud Platform (GCP)

O google cloud paltform é uma plataforma, como o próprio nome diz, de computação em nuvem que oferece serviços de computação, armazenamento, big data, machine learning e diversos outros. Aumentando a escalabilidade e tecnologia de empresas e desenvolvedores.


<sub><sup>É importante notar que cada plataforma de cloud irá impor suas restrçoes de implementação e compatibilidades com outras plataformas, então deve se calcular muito bem os custos antes de realizar qualquer migração ou implementação em qualquer serviço cloud</sup></sub>


## 1.0 IA para negócios e apps

### 1.1 Cloud Natural Language

O Cloud Natural Language permite que os desenvolvedores integrem facilmente a análise de linguagem natural (NLP) aos aplicativos. O Cloud Natural Language é uma API que analisa texto e retorna informações sobre o texto, como a categoria do conteúdo, a análise de sentimento e a extração de entidade.

#### Exemplo de aplicação

O Cloud Natural Language pode ser usado para entender o sentimento por trás das opiniões dos clientes. Por exemplo, um aplicativo de análise de mídia social pode usar o Cloud Natural Language para entender o sentimento por trás dos tweets sobre um produto ou CAMPANHA. O aplicativo pode analisar o sentimento geral sobre o produto, bem como o sentimento em relação a recursos específicos do produto.

### 1.2 Cloud Translation

O Cloud Translation API permite que os desenvolvedores traduzam facilmente entre milhares de pares de idiomas. As traduções de texto são retornadas em um formato JSON. A API reconhece mais de 100 idiomas e variações de idiomas para oferecer suporte aos usuários globais. Você pode dinamicamente traduzir texto entre milhares de pares de idiomas.

#### Exemplo de aplicação

O Cloud Translation pode ser usado para traduzir o conteúdo do site para varios idiomas. Por exemplo, um site de Marketplace pode usar o Cloud Translation para traduzir o conteúdo do site para vários idiomas, permitindo que os clientes comprem em seu idioma preferido como acontece na Aliexpress.

### 1.3 Cloud Speech-to-Text

O Cloud Speech-to-Text permite que os desenvolvedores convertam o áudio do usuario em texto. Ele usa deeplearning que se aproxima da precisão humana. Pode processar áudio armazenado em um arquivo ou áudio gravado de um fluxo de dados em tempo real (por exemplo, a entrada de áudio de um microfone).

#### Exemplo de aplicação

O Cloud Speech-to-Text pode ser usado para transcrever o áudio de um vídeo ou podcast, tornando-o mais acessível para pessoas com deficiência auditiva ou estrangeiros, assim como acontece instantaneamente pelo Google Meet.

### 1.4 Cloud Text-to-Speech

O Cloud Text-to-Speech permite que os desenvolvedores convertam texto em áudio, fazendo o caminho inverso. O Text-to-Speech usa deeplearning que se aproxima da precisão humana. Suporta vários idiomas e vozes, e permite que você crie aplicativos que falem, como por exemplo o Google Maps e a Google Assistant, permitindo que os usuários interajam com seus aplicativos por conversas de voz. Também ajuda pessoas com deficiência visual.

#### Exemplo de aplicação

O Cloud Text-to-Speech pode ser usado para criar um aplicativo que lê em voz alta o texto de um livro, permitindo que pessoas com deficiência visual possam ler livros.

## 2.0 IA para desenvolvedores

### 2.1 Cloud AutoML

O Cloud AutoML permite que os desenvolvedores treinem modelos de aprendizado de máquina de alta qualidade específicos para suas necessidades de forma rápida. Ele conta com a mesma tecnologia de aprendizado de máquina que o Google usa em seus próprios produtos, como a Pesquisa Google, o Google Fotos e o Google Tradutor.

### Exemplo de aplicação

O Cloud AutoML pode ser usado para criar um modelo de aprendizado de máquina que detecta objetos em imagens, permitindo que você crie um aplicativo que detecta produtos em vídeos e fotos, como por exemplo o Google Lens.

### 2.2 Cloud Vision

O Cloud Vision permite que os desenvolvedores compreendam o conteúdo de uma imagem, aplicando  modelos de aprendizado de máquina em uma API. Ele rapidamente classifica imagens em milhares de categorias (por exemplo, "sorvete", "cachorro", "pessoa") Ele também pode encontrar e ler palavras contidas em imagens. Você pode fornecer informações sobre a identificação de objetos (por exemplo, "carro", "flor", "cachorro") e identificar rostos individuais (por exemplo, "Joyce", "Franco", "Maria"), dando uma classificação para algum padrão que ele encontrar.

#### Exemplo de aplicação

O Cloud Vision pode ser usado para criar um aplicativo que detecta faces em fotos, permitindo que você crie uma pasta que detecta pessoas específicas em fotos, como por exemplo o Google Fotos.

## 3.0 Análise e obtenção de dados

### 3.1 BigQuery

data warehouse totalmente gerenciado e sem servidor que permite análise escalável. O BigQuery é um data warehouse amplamente utilizado, rápido e econômico que processa petabytes de dados em questão de segundos e mantém um SLA de disponibilidade de 99,9%, ou seja, seguro assim como os serviços da AWS. O BigQuery elimina a necessidade de gerenciar a infraestrutura de data warehouse denrto de sua propria empresa, permitindo que você foque na análise de dados para encontrar informações úteis usando ferramentas familiares de SQL.

#### Exemplo de aplicação

O BigQuery pode ser usado para analisar dados de vendas, permitindo que você crie um aplicativo que fornece insights sobre o desempenho de vendas, como por exemplo o Google Analytics.

## 4.0 Outros serviços

### 4.1 Google Maps Platform

O Google Maps Platform é um conjunto de APIs e SDKs que permitem que os desenvolvedores criem aplicativos com dados de localização (longitude e latitude ou ate nome de ruas). O Google Maps Platform oferece mapas, locais e coordenadas para aplicações.

#### Exemplo de aplicação

O Google Maps Platform pode ser usado para criar um aplicativo que mostra a localização de um usuário, permitindo que você crie um aplicativo como o Uber.

#### Ilustrativo

Neste primeiro exemplo podemos observar como o Google Maps Platform pode ser usado para criar um forms que mostra a localização do endereço inserido por um usuário instantaneamente, permitindo que você se localize mais facilmente.

<img src= https://github.com/VitorMoura01/M6-S9_Solucoes_PLN/tree/main/assets/maps1.png>

Além disso o endereço ja é autocompletado através de uma sugestão de endereço, permitindo que você não precise digitar o endereço completo.

<img src= https://github.com/VitorMoura01/M6-S9_Solucoes_PLN/tree/main/assets/maps2.png>

Por fim, o endereco é mostrado no mapa, permitindo que você visualize a localização do endereço.

<img src= https://github.com/VitorMoura01/M6-S9_Solucoes_PLN/tree/main/assets/maps3.png>
