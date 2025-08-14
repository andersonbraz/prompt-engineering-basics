# prompt-engineering-basics

Anotações de estudos de Engenharia de Prompt e IA Generativa.

## Redes Neurais

Apesar de hoje usarmos o termo "inteligência artificial" para nos referirmos a qualquer máquina que nos responda, isso é um grande equívoco. Além disso, existem diferentes tipos de inteligência artificial em uso. As redes neurais artificiais são um método específico na área de inteligência artificial, mas existem outras técnicas e abordagens. A escolha entre diferentes abordagens de inteligência artificial depende das características da tarefa, da disponibilidade dos dados e da experiência no domínio. Em muitos casos, as abordagens são combinadas para aproveitar os pontos fortes de cada uma.

As **redes neurais artificiais** são muito utilizadas em tarefas que envolvem percepção sensorial, como: processamento de imagens, reconhecimento de voz e processamento de linguagem natural. Em situações em que a verdade pode ser parcial ou relativa, por exemplo, seria mais adequado utilizar a lógica difusa. Assim, seu melhor campo de atuação será sempre quando for necessário representar o conhecimento humano em um domínio específico, permitindo raciocínio e tomada de decisões baseados em regras.

### Uso das redes neurais artificiais

- Percepção Sensorial
- Processamento de imagens
- Reconhecimento de voz
- Processamento de linguagem natural

As redes neurais artificiais são formadas por camadas de nós interligados, chamados neurônios, que processam e transmitem informações. Elas incluem uma base de conhecimento e um mecanismo de inferência para simular o raciocínio humano em um domínio específico. Podem aprender padrões e relações por meio de algoritmos de aprendizado supervisionado, não supervisionado ou por reforço, e aprendem representações automáticas de dados por meio de treinamento.

### Algoritmos

- Apredizado supervisionado
- Aprendizado não supervisionado
- Aprendizado por reforços
- Aprendizados de representações automáticas

Para o aprendizado, seja qual for o algoritmo, são utilizadas funções de ativação. Elas determinam se o neurônio é ativado ou não em função de sua entrada ponderada. Entre os exemplos de funções de ativação estão a função sigmoide, a função ReLU (unidade linear retificada) e a tangente hiperbólica. As entradas avançam pelas camadas de neurônios, e as saídas de cada neurônio se tornam entradas para os neurônios da camada seguinte. Esse processo continua até a obtenção de uma saída final.

### Funções de ativação

- Função sigmoide
- Função ReLU (Rectified Linear Unit)
- Tangente hiperbólica

O processo de treinamento da inteligência artificial implica ajustar os pesos das conexões entre os neurônios para que a rede neural faça previsões cada vez mais precisas. Como é de se imaginar, essa etapa exige muito tempo e mão de obra. A verdade é que treinar essas inteligências artificiais pode ser muito complexo, além de demandar grande capacidade de computação, principalmente em modelos profundos, como os transformadores. É normal que ocorram erros ao longo de muitas versões. Agora, você pode lidar com mais tranquilidade com a última bobagem que sua inteligência artificial favorita disse.

## Arvores de Decisão

As árvores de decisão são um método bem conhecido na área de inteligência artificial e aprendizado de máquina para tomar decisões com base nas condições e características dos dados. Imagine um mapa mental para decidir se deve ligar para alguém ou não. O problema é resolvido com um "sim" ou "não". Em seguida, você se pergunta se realmente precisa fazer algo: deve fazer algo ou não deve fazer nada? Se precisa fazer algo, novamente é "sim" ou "não". Então, você se pergunta o que deve fazer ou se não faz nada. Acho que você entendeu: é uma forma gráfica e estruturada de representar decisões e possíveis consequências, mas, claro, em uma escala maior.

Uma árvore de decisão é organizada em uma estrutura hierárquica, parecida com uma árvore invertida. Cada nó interno da árvore representa uma decisão baseada em uma determinada característica ou atributo, e as ramificações desse nó representam as diferentes opções ou resultados possíveis. Os nós internos são chamados de nós de decisão e estão associados a uma pergunta ou condição sobre uma característica específica dos dados. Cada ramificação representa uma possível resposta a essa pergunta e conduz a outro nó de decisão ou a um nó terminal. Os nós terminais, também chamados de folhas, representam uma decisão final ou a classe atribuída a um ponto de dados. Em problemas de classificação, uma folha pode representar uma classe específica; em problemas de regressão, pode ser um valor numérico.

- Nó interno = Nó de Decisão, estão associadosa uma pergunta ou condição.
- Ramificação do nó = Possível resposta, direciona a outro nó de decisão ou nó terminal.
- Nó terminal = decisão final, também chamdo de folhas.  

A árvore de decisão divide o espaço de características em regiões menores e mais fáceis de gerenciar. Cada vez que uma decisão é tomada em um nó, o espaço é dividido em subconjuntos baseados nas condições definidas por esse nó. A construção de uma árvore de decisão envolve escolher as características mais importantes e definir as condições para dividir os dados em cada nó. Esse processo se baseia em algoritmos que buscam maximizar a informação obtida com cada decisão. Em cada nova decisão, uma característica e um valor limite são selecionados para dividir os dados em dois ou mais grupos. O critério de divisão busca maximizar a homogeneidade ou pureza dos grupos resultantes, dependendo do objetivo: classificação ou regressão, seja para um resultado bom ou ruim.

### Importante na construção de uma árvore de decisão

- Seleção de caraterísticas importantes
- Definição de condições para sua divisão em nós
- Algoritimos que buscam maximinizar as informações

As árvores de decisão podem sofrer com o sobreajuste aos dados de treinamento se forem criadas com profundidade excessiva, ou seja, se se ajustarem demais aos detalhes específicos dos dados de treinamento e não generalizare bem para novos dados. Para enfrentar o sobreajuste, são utilizadas técnicas como florestas aleatórias e gradientes, que combinam várias árvores de decisão para obter resultados mais robustos e precisos.

### Técnicas para sobreajuste

- Florestas aleatórias
- Gradient Boosting

Uma importante vantagem das árvores de decisão é sua capacidade de serem facilmente interpretadas por humanos, já que as decisões são tomadas de forma sequencial e podem ser seguidas de maneira lógica. As árvores de decisão são aplicáveis a diversos problemas, como classificação, regressão e até tarefas mais complexas, como o aprendizado profundo. Trata-se de uma ferramenta versátil na área de inteligência artificial e aprendizado de máquina, graças à sua natureza interpretável e à capacidade de modelar relações não lineares nos dados.
