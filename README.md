# Prompt Engineering: O Básico

Anotações de estudos de Engenharia de Prompt e IA Generativa.

## Tipos de modelo de inteligência artifical: o que há por trás da arquitetura?

### Redes Neurais

Apesar de hoje usarmos o termo "inteligência artificial" para nos referirmos a qualquer máquina que nos responda, isso é um grande equívoco. Além disso, existem diferentes tipos de inteligência artificial em uso. As redes neurais artificiais são um método específico na área de inteligência artificial, mas existem outras técnicas e abordagens. A escolha entre diferentes abordagens de inteligência artificial depende das características da tarefa, da disponibilidade dos dados e da experiência no domínio. Em muitos casos, as abordagens são combinadas para aproveitar os pontos fortes de cada uma.

As **redes neurais artificiais** são muito utilizadas em tarefas que envolvem percepção sensorial, como: processamento de imagens, reconhecimento de voz e processamento de linguagem natural. Em situações em que a verdade pode ser parcial ou relativa, por exemplo, seria mais adequado utilizar a lógica difusa. Assim, seu melhor campo de atuação será sempre quando for necessário representar o conhecimento humano em um domínio específico, permitindo raciocínio e tomada de decisões baseados em regras.

#### Uso das redes neurais artificiais

- Percepção Sensorial
- Processamento de imagens
- Reconhecimento de voz
- Processamento de linguagem natural

As redes neurais artificiais são formadas por camadas de nós interligados, chamados neurônios, que processam e transmitem informações. Elas incluem uma base de conhecimento e um mecanismo de inferência para simular o raciocínio humano em um domínio específico. Podem aprender padrões e relações por meio de algoritmos de aprendizado supervisionado, não supervisionado ou por reforço, e aprendem representações automáticas de dados por meio de treinamento.

#### Algoritmos

- Apredizado supervisionado
- Aprendizado não supervisionado
- Aprendizado por reforços
- Aprendizados de representações automáticas

Para o aprendizado, seja qual for o algoritmo, são utilizadas funções de ativação. Elas determinam se o neurônio é ativado ou não em função de sua entrada ponderada. Entre os exemplos de funções de ativação estão a função sigmoide, a função ReLU (unidade linear retificada) e a tangente hiperbólica. As entradas avançam pelas camadas de neurônios, e as saídas de cada neurônio se tornam entradas para os neurônios da camada seguinte. Esse processo continua até a obtenção de uma saída final.

#### Funções de ativação

- Função sigmoide
- Função ReLU (Rectified Linear Unit)
- Tangente hiperbólica

O processo de treinamento da inteligência artificial implica ajustar os pesos das conexões entre os neurônios para que a rede neural faça previsões cada vez mais precisas. Como é de se imaginar, essa etapa exige muito tempo e mão de obra. A verdade é que treinar essas inteligências artificiais pode ser muito complexo, além de demandar grande capacidade de computação, principalmente em modelos profundos, como os transformadores. É normal que ocorram erros ao longo de muitas versões. Agora, você pode lidar com mais tranquilidade com a última bobagem que sua inteligência artificial favorita disse.
___

### Arvores de Decisão

As árvores de decisão são um método bem conhecido na área de inteligência artificial e aprendizado de máquina para tomar decisões com base nas condições e características dos dados. Imagine um mapa mental para decidir se deve ligar para alguém ou não. O problema é resolvido com um "sim" ou "não". Em seguida, você se pergunta se realmente precisa fazer algo: deve fazer algo ou não deve fazer nada? Se precisa fazer algo, novamente é "sim" ou "não". Então, você se pergunta o que deve fazer ou se não faz nada. Acho que você entendeu: é uma forma gráfica e estruturada de representar decisões e possíveis consequências, mas, claro, em uma escala maior.

Uma árvore de decisão é organizada em uma estrutura hierárquica, parecida com uma árvore invertida. Cada nó interno da árvore representa uma decisão baseada em uma determinada característica ou atributo, e as ramificações desse nó representam as diferentes opções ou resultados possíveis. Os nós internos são chamados de nós de decisão e estão associados a uma pergunta ou condição sobre uma característica específica dos dados. Cada ramificação representa uma possível resposta a essa pergunta e conduz a outro nó de decisão ou a um nó terminal. Os nós terminais, também chamados de folhas, representam uma decisão final ou a classe atribuída a um ponto de dados. Em problemas de classificação, uma folha pode representar uma classe específica; em problemas de regressão, pode ser um valor numérico.

- Nó interno = Nó de Decisão, estão associadosa uma pergunta ou condição.
- Ramificação do nó = Possível resposta, direciona a outro nó de decisão ou nó terminal.
- Nó terminal = decisão final, também chamdo de folhas.  

A árvore de decisão divide o espaço de características em regiões menores e mais fáceis de gerenciar. Cada vez que uma decisão é tomada em um nó, o espaço é dividido em subconjuntos baseados nas condições definidas por esse nó. A construção de uma árvore de decisão envolve escolher as características mais importantes e definir as condições para dividir os dados em cada nó. Esse processo se baseia em algoritmos que buscam maximizar a informação obtida com cada decisão. Em cada nova decisão, uma característica e um valor limite são selecionados para dividir os dados em dois ou mais grupos. O critério de divisão busca maximizar a homogeneidade ou pureza dos grupos resultantes, dependendo do objetivo: classificação ou regressão, seja para um resultado bom ou ruim.

#### Importante na construção de uma árvore de decisão

- Seleção de caraterísticas importantes
- Definição de condições para sua divisão em nós
- Algoritimos que buscam maximinizar as informações

As árvores de decisão podem sofrer com o sobreajuste aos dados de treinamento se forem criadas com profundidade excessiva, ou seja, se se ajustarem demais aos detalhes específicos dos dados de treinamento e não generalizare bem para novos dados. Para enfrentar o sobreajuste, são utilizadas técnicas como florestas aleatórias e gradientes, que combinam várias árvores de decisão para obter resultados mais robustos e precisos.

#### Técnicas para sobreajuste

- Florestas aleatórias
- Gradient Boosting

Uma importante vantagem das árvores de decisão é sua capacidade de serem facilmente interpretadas por humanos, já que as decisões são tomadas de forma sequencial e podem ser seguidas de maneira lógica. As árvores de decisão são aplicáveis a diversos problemas, como classificação, regressão e até tarefas mais complexas, como o aprendizado profundo. Trata-se de uma ferramenta versátil na área de inteligência artificial e aprendizado de máquina, graças à sua natureza interpretável e à capacidade de modelar relações não lineares nos dados.
___

### Modelos de máquina de verdade de vetores de suporte

Os modelos de máquinas de vetores de suporte, ou SVMs (em inglês, *Support Vector Machines*), são uma poderosa técnica de aprendizado de máquina utilizada tanto para tarefas de classificação quanto para regressão. São um pouco difíceis de explicar sem se aprofundar em geometria e trigonometria, mas vamos tentar de forma simplificada. Na sua forma mais básica, as SVMs tentam encontrar um hiperplano em um espaço multidimensional que divida duas classes de dados da melhor forma. Esse hiperplano é escolhido de modo a maximizar a distância entre os dados mais próximos das duas classes, a chamada margem máxima. Quando os dados são linearmente separáveis, um hiperplano pode separar perfeitamente as classes. No entanto, em muitos casos, os dados não são totalmente separáveis, por isso é introduzida uma tolerância para permitir certos erros de classificação.

É claro que um hiperplano é um conceito geométrico, utilizado em espaços com mais de duas dimensões, para descrever uma generalização de um plano em três dimensões. Em termos simples, é um subconjunto de um espaço euclidiano multidimensional que tem uma dimensão a menos. Não quero dar aulas de matemática, mas é importante entender isso: em um espaço bidimensional, um hiperplano se reduz a uma linha reta; em um espaço tridimensional, seria um plano; e, em um espaço com mais dimensões, é uma generalização dessas estruturas. Matematicamente, um hiperplano de dimensão (n-1) em um espaço de (n) dimensões é definido pela equação (w₁x₁ + w₂x₂ + ... + wₙxₙ + b = 0), onde (w₁, w₂, até, wₙ) são coeficientes que determinam a orientação do hiperplano, (x₁, x₂, até, xₙ) são as coordenadas do ponto no espaço, e (b) é um termo de ajuste.

Na prática, no contexto de SVMs, o objetivo é encontrar um hiperplano que maximize a margem entre duas classes de dados, separando-as de maneira otimizada. Os pontos de dados mais próximos do hiperplano são chamados de vetores de suporte. Eles desempenham um papel fundamental no funcionamento, pois influenciam a localização e a orientação do hiperplano. O objetivo é maximizar a distância entre o hiperplano e esses vetores de suporte.

Esclarecido isso, vamos ao que se pretende alcançar. A função de decisão da SVM pega um novo ponto de dados e determina em que lado do hiperplano ele se encontra. O sinal do valor da função de decisão indica a qual classe o ponto é atribuído. A margem é a distância entre o hiperplano e os vetores de suporte mais próximos. As SVMs buscam maximizar essa margem para obter uma melhor generalização em dados não analisados.

#### Hiperplano

- Um hiperplano é uma generalização de um plano em espaços multidimensionais, sendo um subconjunto de um espaço euclidiano com uma dimensão a menos que o espaço original (ex.: uma linha em 2D, um plano em 3D), definido matematicamente por uma equação linear.

#### Espaço euclidiano

- Um sistema matemático baseado na geometria de Euclides, caracterizado por ser um espaço vetorial com uma métrica que obedece às leis da geometria plana, como distâncias e ângulos bem definidos. Ele pode ter qualquer número de dimensões (ex.: 2D, 3D).

#### Margem

- Distância entre o hiperplano e vetores de suporte mais próximos.

As SVMs podem tratar dados que não são linearmente separáveis no espaço original usando funções de kernel. Essas funções transformam os dados em um espaço de maior dimensão, onde eles podem se tornar linearmente separáveis. Alguns exemplos de kernels são o linear, o polinomial e o gaussiano. Inicialmente, as SVMs foram criadas para classificação binária, mas podem ser estendidas a problemas de classificação multiclasse utilizando estratégias como "um contra todos" ou "um contra um".

#### Kernels

- Kernels são funções usadas em aprendizado de máquina, especialmente em SVMs, para transformar dados de um espaço original em um espaço de maior dimensão, onde classes não linearmente separáveis podem se tornar separáveis por um hiperplano. Exemplos comuns incluem kernels linear, polinomial e gaussiano, que permitem modelar relações complexas sem calcular explicitamente a transformação.

#### Exemplos de Kernel

- Linear
- Polinomial
- Gaussiano

Além da classificação, as SVMs também podem ser aplicadas a problemas de regressão. Nesse caso, em vez de encontrar um hiperplano que divida os dados, busca-se um hiperplano que passe perto da maioria deles, dentro de uma margem especificada. A vantagem é incluir regularização, o que significa penalizar soluções complexas. Isso ajuda a evitar o sobreajuste e melhora a capacidade de generalização do modelo. Por isso, as SVMs são muito úteis quando temos um conjunto de dados com muitas características e buscamos uma solução robusta que generalize bem para dados novos.

Às vezes, a própria generalização faz com que sejam menos precisas em casos específicos, mas sua capacidade de processar dados não linearmente separáveis e sua versatilidade em termos de kernels tornam essa técnica valiosa no aprendizado de máquina.
___

### Algoritmos de Agrupamento

Os algoritmos de agrupamento são técnicas utilizadas na área de inteligência artificial para dividir um conjunto de dados em grupos ou clusters baseados em semelhanças ou características em comum. Esses algoritmos são usados para descobrir padrões e estruturas ocultas nos dados sem a necessidade de rótulos predefinidos. A escolha do algoritmo depende da natureza dos dados e do objetivo da análise. Os algoritmos de agrupamento são essenciais para a descoberta de padrões, segmentação de mercado, análise de dados e muito mais.

Por exemplo, um dos algoritmos de agrupamento mais conhecidos é o k-means, muito utilizado na mineração de dados e no aprendizado de máquina. No início, são selecionados k pontos como centros iniciais, e em seguida os dados são atribuídos ao centro mais próximo. Esses centros são recalculados com base nos dados atribuídos, e o processo é repetido até que haja convergência na atribuição de clusters.

Há também o agrupamento hierárquico, que constrói uma estrutura hierárquica de clusters, dividindo ou combinando-os sucessivamente. Pode ser aglomerativo, começando com clusters individuais e combinando-os, ou divisivo, começando com todos os dados em um único cluster e dividindo-os. O DBSCAN (Density-Based Spatial Clustering of Applications with Noise) é um algoritmo que encontra clusters com base na densidade dos dados. Ele define clusters como regiões densas e pode identificar pontos de ruído. Os pontos próximos ao ponto central são agrupados em clusters, enquanto os pontos isolados são considerados ruído.

O deslocamento médio, ou mean shift, busca clusters identificando máximos na função de densidade dos dados. Começa com uma seleção aleatória de pontos e os desloca para regiões de maior densidade; os pontos que convergem no mesmo máximo são agrupados. O GMM (modelo de mistura de gaussianas) modela os dados como uma combinação de distribuições gaussianas, e os dados são atribuídos a clusters com base nas probabilidades de pertencerem a cada distribuição. É útil quando os dados são distribuídos de maneira mais complexa.

Temos ainda o agrupamento espectral, que utiliza o espectro da matriz de similaridade entre pontos para atribuí-los aos clusters. Pode capturar relações não lineares e estruturas complexas nos dados. O BIRCH (Balanced Iterative Reducing and Clustering using Hierarchies) é um algoritmo que utiliza uma estrutura hierárquica de clusters baseada em árvores, sendo muito eficiente em grandes conjuntos de dados. O OPTICS (Ordering Points to Identify the Clustering Structure) é semelhante ao DBSCAN, mas cria um resultado mais completo, proporcionando uma visão ordenada da estrutura de clusters e permitindo uma melhor compreensão da distribuição dos dados.

O agrupamento aglomerativo é uma abordagem hierárquica em que os pontos começam como clusters individuais que são combinados com base em sua similaridade. Cada ponto acaba formando um cluster individual, deixando de lado os exemplos. Um aspecto importante dos algoritmos de agrupamento que os diferencia de outras técnicas é que, ao contrário dos algoritmos de classificação, não exigem rótulos predefinidos para os dados. O objetivo é encontrar padrões e estruturas nos dados sem a necessidade de supervisão; por isso, não é preciso rotulá-los. Por outro lado, como se baseiam na medição de similaridade entre os pontos de dados, quanto mais semelhantes os pontos, maior a probabilidade de que pertençam ao mesmo cluster.

Um dos desafios enfrentados é definir o número ideal de clusters, o que pode exigir a realização de outras análises, como o método do cotovelo ou o índice de silhueta, para encontrar a quantidade adequada. Certamente, há muitos algoritmos de agrupamento, mas não existe um que seja sempre superior. O melhor algoritmo depende da natureza dos dados e dos objetivos da análise. Em todo caso, o pré-processamento dos dados é sempre fundamental, incluindo a eliminação de valores atípicos, a normalização de características e a seleção das características pertinentes.

Resumindo, os algoritmos de agrupamento são ferramentas valiosas para análise de dados e identificação de padrões em conjuntos não rotulados. A seleção do algoritmo, o pré-processamento adequado dos dados e a interpretação dos resultados são fatores decisivos para obter resultados úteis nesses algoritmos.
