# Projeto exploratório de dados em parceria com EBAC
<div align="center">
  
 ![analiseimg](https://github.com/user-attachments/assets/a9ab3ab6-2953-4db6-a52d-539d2ede7564)

</div>


# >Descrição:
 Projeto de análise de dados, criado em parceria da EBA e da Loggi, com o objetivo de melhor a eficiência das entregas de acordo com a região e a demanda dos clientes e centros de distribuições.

# >Funcionaldade

 O projeto opera começando por tratar dos dados fornecidos pela Loggi. Tratando um arquivo json para dataframe, enriquecendo seus dados, verificando arquivos NaN, fazendo combinações de colunas e renomeando colunas para otimização dos dados.
 Apresentando schema de exploração dos dados, atributos categóricos, numéricos, realizando a manipulação para que possa ser feio uma geocodificação reversa para geração de gráficos e realizações de insights.

# >Pacotes usados:
 Os pacotes usados para realizar tal projeto são:  
 
  - Pacotes nativos do python:  
    json

  - Pacotes de terceiros:  
    pandas as pd
    seaborn as sns
    geopandas as gpd
    numpy as np
    matplotlib.pyplot as plt

# >Dicionário de variáveis:
   ***solucao*** - variável criada para transformar o arquivo json  
   ***deliveries_df*** - criação do data frame para entregas  
   ***hub_origin_df*** - criado para realiar o tratamento de colunas  
   ***hub_df*** - dataframe criado para manipular dados  
   ***hub_geodata_df*** - dataframe criado para utilizar coordenadas geográficas  
   ***mapa*** - variável criada para gerar visualizações usando coordenas geográficas e o mapa do Distrito Federal

# >Razão do projeto:

  Otimização das entregas para torna-las mais eficientes.  
  Há uma necessidade de uma maior eficiência nas entrega onde será preciso uma melhor distribuição de frotas pra melhor atender as regiões de acordo com a demanda. Aplicando as informações obtidas será possível mapear as entregas de acordo com as regiões para realizar insights e atender a necessidade solicitada.

# >vizualizações:  
  ***Mapeamento das entregas***  
    
  ![vizualização 1](https://github.com/user-attachments/assets/6cffbe80-4f57-4b7b-a5a4-6b4e04d3590f)  
    
  ***Localização dos HUBs de sitribuição***  
    
  ![vizualização 2](https://github.com/user-attachments/assets/da42b4c0-baa4-4b6c-bda9-69e0e4bf64aa)  

  
# >Possíveis insights:  
  **Do Mapeamento das entregas**:  
  Ao analisar o gráfico de entregas, pode-se notar uma grande concentração de entregas próximas aos respectivos hubs. Uma pequena porção das entregas que se afastam mais dos hubs. Sendo assim, para poder otimizar as entregas, será necessário manter a concentração maior próximos aos hubs e nos locais afastados, reorganizar as entregas para maior eficiência como por exemplo carros com capacidade menor por conta do menor volume de entrega. Carros menores poderão se deslocar mais rapidamente e consumirão menos combustível para as entregas. Proporcionando uma economia e otimizando as entregas nas regiões periféricas.  

  **Da Localização dos HUBs de distribuição**:  
  O gráfico acima nos mostra claramente onde estão localizados os hubs de distribuição. Pode-se notar que os hubs estão distribuídos efetivamente nos pontos centrais das regiões, facilitando a distribuição da frota e das entregas pela região e zonas periféricas.  
    
# >Parceiros:  
   
  ![ebac logo](https://github.com/user-attachments/assets/39b14fa7-c91c-4b39-8e02-7dc996b203e0)  
  ![loggi](https://github.com/user-attachments/assets/6cb12b43-4004-490f-b216-7debefcc940c)  
 



