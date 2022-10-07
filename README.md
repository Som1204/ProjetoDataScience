# ProjetoDataScience
# Objetivo:
A partir de uma base de dados retirada do site Kaggle (https://www.kaggle.com/allanbruno/airbnb-rio-de-janeiro), de informações acerca dos imóveis disponibilizados por usuários do Airbnb na cidade do Rio de Janeiro, construir um modelo de previsão de preço que permita uma pessoa comum que possui um imóvel, consiga estimar o preço a se cobrar pela diária do seu imóvel, e usuários do serviço possam saber se o preço cobrado está dentro do previsto para os imóveis semelhantes em características e localização. Além de verificar quais informações deste imóveis são mais relevantes para se chegar em um resultado mais acertivo. O projeto atual foi inspirado na solução apresentada pelo usuário Allan Bruno do kaggle no Notebook: https://www.kaggle.com/allanbruno/helping-regular-people-price-listings-on-airbnb e a pasta com os arquivos utilizados na resolução atual ('dataset') está disponível no seguinte endereço: https://drive.google.com/drive/folders/1Shk_Jj5h_RllGc345ICPUpAEhc6fOngO?usp=sharing .
# Tecnologias Utilizadas:
O projeto foi desenvolvido em Python e utiliza Machine Learning para previsão dos resultados.
# Estrutura:
O projeto segue um ciclo contínuo de visualização e tratamento dos dados, análise, interpretação, alterações e assim sucessivamente até chegar em um resultado satisfatório. Para tal se fez uso de vários artifícios gráficos e planilhas para identitificação de informações relevantes, assim como outliers a serem desconsideradas e possibilidades de melhoria do modelo.
# Resultados e Comentários:
Ao fim, chegamos em um resultado bastante satisfatório, atingindo 97% de precisão do modelo. A versão final pode ser utilizada por meio do prompt de comando do Python utilizando o Streamlit.
Antes será necessário baixar a pasta 'dataset' citada acima, colocá-la no mesmo diretório do arquivo "Solução Airbnb Rio de Janeiro.ipynb" e executar esse mesmo arquivo para que seja gerado o 'modelo.joblib'. Após isso basta acessar o arquivo 'DeployProjetoAirbnb.py' e executar com o Streamlit por meio do prompt de comando. O Streamlit irá gerar um link local para que seja possível inserir as informações do imóvel a ser analisado e fazer a previsão.

Os arquivos baixados externamente ao GitHub não foram colocados juntos na plataforma devido ao tamanho considerável dos mesmos.
