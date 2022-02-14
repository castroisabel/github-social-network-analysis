# github-social-network-analysis

Análise da Rede Social do GitHub

Nesse trabalho, será explorado um conjunto de dados de rede social coletado no GitHub chamada musae-github que foi coletada de API pública em junho de 2019.
Existe uma grande rede social de desenvolvedores GitHub, onde os vértices representam os usuários da plataforma que possuem no mínimo 10 repositórios com estrela, enquantos as arestas são relacionamentos de seguidor mútuo entre eles. Os atributos dos vértices são extraídos com base na localização, repositórios marcados com estrela, empregador e endereço de e-mail. A tarefa a ser trabalhada é a classificação de nós binários - deve-se prever se o usuário do GitHub é um desenvolvedor web ou de machine learning, onde este rótulo foi derivado do cargo de cada usuário. Desse modo, será tratado um problema de aprendizagem supervisionada de classificação de nós, isto é, dado um grafo de uma rede social, onde os usuários representam seus vértices e os relacionamentos entre eles são suas arestas, deve-se prever cada grupo de usuários. Portanto, será realizado inicialmente uma introdução a conteitos importantes em grafos, um pré processamento dos dados, plotagem de alguns gráficos para visualização e compreensão do problema, construção e vizualição da rede e por fim, como principal objetivo desse projeto, construir e treinar um modelo de Graph Neural Network (GNN), que é uma classe de redes neurais para processar dados representados por grafos, simples para a tarefa de classificação de nós.

*Palavras-chave*: Social Network Analysis, Data Science, Graph Neural Network

*Referências*: \
https://snap.stanford.edu/data/github-social.html \
https://github.com/franciscoicmc/tutorial-networks \
https://github.com/benedekrozemberczki/MUSAE \
https://awadrahman.medium.com/hands-on-graph-neural-networks-for-social-network-using-pytorch-30231c130b38

