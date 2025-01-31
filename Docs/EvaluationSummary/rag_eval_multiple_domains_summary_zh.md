<!--
 * @Description: 
 * @Author: shenlei
 * @Date: 2024-01-29 16:17:57
 * @LastEditTime: 2024-02-04 11:33:00
 * @LastEditors: shenlei
-->
# RAG Evaluations in LlamaIndex  

## Multiple Domains Scenarios in ["zh"] 
| Embedding Models | WithoutReranker <br> [*hit_rate/mrr*] | CohereRerank <br> [*hit_rate/mrr*] | bge-reranker-large <br> [*hit_rate/mrr*] | ***bce-reranker-base_v1*** <br> [*hit_rate/mrr*] | 
|:-------------------------------|:--------:|:--------:|:--------:|:--------:| 
| OpenAI-ada-2 | 77.35/56.19 | 85.36/68.13 | 86.19/69.59 | **88.67/75.26** |  
| OpenAI-embed-3-small | 84.53/62.51 | 90.06/70.70 | 89.78/71.83 | **92.54/78.36** |  
| OpenAI-embed-3-large | 84.25/60.10 | 88.12/69.97 | 89.23/71.21 | **92.27/77.28** |  
| bge-large-zh-v1.5 | 84.81/61.90 | 89.50/69.81 | 89.50/71.07 | **92.82/77.64** |  
| bge-m3-large | **87.57/65.01** | 91.16/71.39 | 91.44/72.03 | **94.75/79.46** |  
| CohereV3-multilingual | 82.87/63.22 | 86.19/68.14 | 85.64/68.26 | **88.40/74.42** |  
| JinaAI-v2-Base-zh | 78.45/56.80 | 84.81/67.33 | 84.81/68.14 | **88.12/75.09** |  
| gte-large-zh | 77.35/55.33 | 85.36/67.06 | 85.08/68.83 | **87.85/74.79** |  
| e5-large-multilingual | 87.02/65.26 | 89.78/70.73 | 90.33/71.51 | **92.82/78.69** |  
| ***bce-embedding-base_v1*** | 83.70/62.90 | **92.27/71.94** | **92.27/72.79** | ***95.03/79.57*** |  
