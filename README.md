# StackLabs-Minio-Olist
**O objetivo desse repositorio é organizar os arquivos produzidos no desenvolvimento do projeto do [StackLabs](https://github.com/HenriqueSantos0/StackLabs-Minio-Olist/blob/main/Projeto%20-%20Stack%20Labs.pdf) da squad Minio.**

## Descrição
- O nosso trabalho tem por Titulo **Previsão de vendas em regiões perifericas brasileiras**.
- O projeto proposto enquadra-se no tópico Análise de dados e Entendimento de Negócio. 
- O projeto utiliza as fontes de dados da companhia para a produção de relatório, que concentra-se na análise, exploração de dados e  desenvolvimento de modelo preditivo visando a identificação de oportunidades.

## Problema
- Tentamos com esse projeto responder a seguinte pergunta Que fatores permitem a manutenção do faturamento em acensão?
- Para isso, trouxemos algumas informações sobre a base.
1. Considerado o recorte temporal entre 2017 e 2018, as vendas anuais da empresa cresceram 18%, e o número de vendedores, 33%;
2. Os dados disponibilizados pela companhia demostram, no mesmo período, que mais de 70% dos pedidos foram entregues no eixo Sul-Sudeste, uma vez que essas regiões possuem densa rede de transporte e valor de frete menor se comparado com regiões periféricas do país;
3. A partir destes dados, verifica-se, ainda, que a distribuição de vendedores e vendas nos estados é irregular: estado de SP concentra, por exemplo, 60% dos vendedores e 40% do faturamento da companhia.

![image](https://user-images.githubusercontent.com/89212899/151978158-16452e70-82c5-43ce-b232-b89f523f527b.png)

![image](https://user-images.githubusercontent.com/89212899/151978197-07e7ab4e-f6c6-4a90-a663-2b89ba09ce3f.png)

![image](https://user-images.githubusercontent.com/89212899/151978229-6cd7ac1e-d784-420e-a7d3-cf06bd8f731d.png)

![image](https://user-images.githubusercontent.com/89212899/151978252-629c8e58-b037-412c-99a3-5fd5c1125781.png)

## Hipótese de trabalho:
Para responder a questão de que *fatores permitem a manutenção do faturamento da companhia em acensão?* formulou-se a seguinte hipótese:

- O aumento do número de vendedores nos estados das regiões Norte, Nordeste e Centro-Oeste induziria a uma redução 1) de tempo de entrega de encomendas e 2) valor do frete, aumentado o volume de vendas nessas regiões;

## Solução de Engenharia de dados:

A solução para o armazenamento, seleção de features e análises foram foram desenvolvidas a partir do servico de cloud da Google, explicitado no diagrama abaixo:

![image](https://user-images.githubusercontent.com/8771239/153863209-09f0a519-5eed-4329-917e-ec7e048ceebe.png)

## Modelos de previsão

1) Modelo de treino com resultados nacionais.

![image](https://user-images.githubusercontent.com/89212899/151978392-d521fc1c-c4cf-4cf3-8569-174aaab404c0.png)

2) O modelo de previsão paras as regiões analisadas demonstrou solidez, uma vez que as projeções de produtos vendidos são naturalemnte ascendentes. A métrica do RMSE demontrou uma variação de 28 erros padrão, o que demonstra uma baixa variação dessa previsão para um perído de 4 anos.

![image](https://user-images.githubusercontent.com/89212899/151978423-069f1bcd-2377-422a-a18f-d45bfb70f621.png)

## Insigths

Uma política de atração de vendedores nos estados da regiões Norte, Nordeste e Centro-Oeste impactaria de modo positivo nas vendas da companhia:

* O impacto mais importante está ligado a redução do preço do frete. Os dados da companhia demonstram que o custo e o tempo do transporte de mercadorias para essas localidades pode ser um fator determinante na escolha dos compradores;

* Oferecer treinamento na área de vendas, relações com o cliente, negociação com fornecedores, gamificação, administração, entre outros, podem garantir a longevidade das empresas;

* Com vendedores mais confiantes, estes novos atores podem vender de forma sustentável, garantindo o incremento nas vendas.
