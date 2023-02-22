# Pipeline de Extração, Carregamento, Tratamento e Envio de Dados de Marketing 📈

Este projeto tem como objetivo realizar a extração, carregamento, tratamento e envio de dados de marketing. Os dados são extraídos de um conjunto de dados disponível no Kaggle e são armazenados em um banco de dados MongoDB e em um bucket no Google Cloud Platform (GCP).


## Índice

- [Workflow](#workflow)
- [Tratamento](#tratamento)
- [Load](#load)
- [Considerações](#considerações)
- [Contribuição](#contribuição)
- [Links](#links)


## Workflow
![workflow.jpg](https://github.com/nayyarabernardo/marketing_analytics/blob/main/workflow.jpg)


## Tratamento

O processo de tratamento dos dados é realizado com o uso de bibliotecas como Pandas e PySpark, onde as colunas são tratadas com base em critérios como ano de nascimento, escolaridade, estado civil, renda, quantidade de crianças e adolescentes na família, data de filiação, dias desde a última compra, gastos em diferentes categorias (vinho, frutas, carne, peixe, doce e ouro), compras por meio de diferentes canais (promoção, website, catálogo, loja), visitas ao website e campanhas anteriores.

## Load

Os dados foram armazenados nos bancos de dados MongoDB e MySQL e em um bucket na GCP.

O MongoDB é um banco de dados NoSQL amplamente utilizado para armazenar dados não estruturados e semiestruturados. Ele é especialmente útil para projetos que envolvem grandes quantidades de dados, pois permite uma escalabilidade horizontal fácil e oferece uma alta disponibilidade de dados. No projeto ELTL, o MongoDB foi utilizado para armazenar os dados brutos extraídos do Kaggle, bem como os dados tratados após a limpeza e transformação.

Já o Google Cloud Storage (GCP) é um serviço de armazenamento em nuvem altamente escalável e durável, projetado para armazenar grandes volumes de dados. Ele é ideal para projetos que exigem armazenamento de objetos não estruturados, como arquivos de imagem, áudio e vídeo. No projeto ELTL, o GCP foi utilizado para armazenar os dados brutos extraídos do Kaggle e os dados tratados após a limpeza e transformação.


## Considerações

Este projeto tem como objetivo fornecer um exemplo de como realizar o processo de ELT (Extração, Carregamento e Tratamento) de dados de marketing utilizando diferentes tecnologias e bibliotecas. É importante destacar que o projeto pode ser adaptado para outras fontes de dados e tecnologias, de acordo com as necessidades do usuário.

## Contribuição

Este projeto é aberto a contribuições. Se você deseja melhorar ou adicionar recursos, sinta-se à vontade para criar uma solicitação pull ou entrar em [contato](https://www.linkedin.com/in/nayyarabernardo).

## Links

- [Documentação do MongoDB](https://docs.mongodb.com/)
- [Documentação do Google Cloud Platform](https://cloud.google.com/docs)
- [Documentação do Pandas](https://pandas.pydata.org/docs/)
- [Documentação do PySpark](https://spark.apache.org/docs/latest/api/python/)
