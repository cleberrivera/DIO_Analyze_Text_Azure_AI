# **Analise de Sentimentos com Language Studio - Azure AI**

#### 📌 Antes de tudo [clique aqui](https://azure.microsoft.com/pt-br/free/search/?ef_id=_k_CjwKCAjw_e2wBhAEEiwAyFFFo3RE7HE2-y1etoQbR5ZCAMuisChiKRd4zrBUFLYWzX6sBgB0OCxusRoChoMQAvD_BwE_k_&OCID=AIDcmmzmnb0182_SEM__k_CjwKCAjw_e2wBhAEEiwAyFFFo3RE7HE2-y1etoQbR5ZCAMuisChiKRd4zrBUFLYWzX6sBgB0OCxusRoChoMQAvD_BwE_k_&gad_source=1&gclid=CjwKCAjw_e2wBhAEEiwAyFFFo3RE7HE2-y1etoQbR5ZCAMuisChiKRd4zrBUFLYWzX6sBgB0OCxusRoChoMQAvD_BwE) para criar a sua conta na Microsoft Azure. 

#

- Primeiramente na aba **"Create Resource"** selecionamos **"AI + Machine Learning"** e no recurso **"Language Service"** clicamos em **"create"**, assim será criado o resource group para utilizar a AI.

![Capturar](https://github.com/cleberrivera/DIO_Analyze_Text_Azure_AI/assets/132470980/a27b15a0-0627-464c-8f10-29018d6d5a69)



- Em seguida no [Language Studio](https://language.cognitive.azure.com/home) selecione o resource group já criado.

#

- Agora no menu principal selecionamos **"Classify text"** e **"Analyze sentiment and mine opinions"**.

![Capturar08](https://github.com/cleberrivera/DIO_Analyze_Text_Azure_AI/assets/132470980/5b99f998-3501-44e2-a067-a6d3efeb9a5e)


#

- Por fim selecionamos o idioma e clicamos em **"Run"** para executar a função com os seus devidos valores.

**1ª frase:**

![Capturar03](https://github.com/cleberrivera/DIO_Analyze_Text_Azure_AI/assets/132470980/b1d6738c-9e8b-4602-b0d2-bca6a66056c0)

![Capturar04](https://github.com/cleberrivera/DIO_Analyze_Text_Azure_AI/assets/132470980/29ff2882-5d5a-4b17-9ded-0f89232affac)

#

**2ª frase:**

![Capturar06](https://github.com/cleberrivera/DIO_Analyze_Text_Azure_AI/assets/132470980/e96408ea-9431-40c8-a421-f2bee43b5535)

![Capturar05](https://github.com/cleberrivera/DIO_Analyze_Text_Azure_AI/assets/132470980/ae28784f-b2ea-4d01-ad07-31a49c01dcb8)



## <a title="Objetos" href="https://pt.piliapp.com/emoji/list/#objects" class="active">💡</a> Insights e Possibilidades

- Neste exemplo utilizei um texto em inglês e outro em português, ambos são consumidores que fizeram comentários sobre o produto, porém haviam milhares de comentários e a IA com certeza ajudaria a filtrar o feedback positivo ou negativos dos consumidores em poucos segundos/minutos.

- Um ponto observado em uma das frases foi que aparentemente a IA não entende muito bem expressões, por exemplo:

![Capturar07](https://github.com/cleberrivera/DIO_Analyze_Text_Azure_AI/assets/132470980/8d5dc896-338d-4214-b947-237e63660f5f)

É notório que o comentário não é negativo, mas sim neutro, algo que precisa ter muita atenção antes de concluir a consulta.
#

## 🔎 Links de apoio:
- [AI Leitura de Texto](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html) 
#
![Microsoft Azure](https://img.shields.io/badge/MicrosoftAzure-000?style=for-the-badge&logo=MicrosoftAzure&logoColor=30A3DC)
