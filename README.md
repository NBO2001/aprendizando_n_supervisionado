# Aprendizado não supervisionado.

## Introdução

O aprendizado não supervisionado é uma abordagem fundamental na análise de dados, permitindo que algoritmos identifiquem padrões e estruturas em conjuntos de dados sem a necessidade de rótulos ou supervisão externa. Neste experimento, exploramos duas técnicas populares de aprendizado não supervisionado: o algoritmo K-means e a rede neural auto-organizável MiniSOM (Mini Self-Organizing Map). Configuramos o K-means com 18 clusters e o MiniSOM com 18 neurônios, buscando compreender e comparar suas capacidades de agrupamento e organização dos dados. Este estudo visa não apenas explorar as características intrínsecas dos algoritmos, mas também analisar a eficácia de suas configurações em um contexto específico de análise de dados.

## Agrupamentos

### Plot 3D

Para compreender a distribuição dos dados, realizamos uma análise em três dimensões. Na Figura 1, onde aplicamos o algoritmo K-means, observamos que os clusters próximos exibem uma heterogeneidade significativa, indicando uma diversidade de padrões próximos uns aos outros. Em contraste, na Figura 2, utilizando o algoritmo MiniSOM, notamos que os dados próximos tendem a pertencer ao mesmo cluster, sugerindo uma maior coesão e uniformidade nessas regiões. Essa distinção nos padrões de agrupamento entre os dois algoritmos oferece insights valiosos sobre suas características e eficácia na análise dos dados tridimensionais.

!["K-means plot 3D"](./imgs/kmeas_plot3d.png)

​											**Figura 1.** K-means plot 3D. 
!["K-means plot 3D"](./imgs/minisom_plot3d.png)

​											**Figura 2.** MiniSom plot 3D. 
### Plot 2D
Quando reduzimos a dimensionalidade para duas, observamos o mesmo comportamento nas Figuras 1 e 2, que utilizam o K-means e o MiniSOM, respectivamente.

!["K-means plot 3D"](./imgs/kmeas_plot2D.png)

​											**Figura 3.** K-means plot 2D. 

!["K-means plot 3D"](./imgs/minisom_plot2D.png)

​											**Figura 4.** Minisom plot 2D. 

### Plot usando SNE

Ao aplicar o t-SNE (t-distributed Stochastic Neighbor Embedding), obtivemos gráficos visualmente semelhantes, porém com divisões de clusters diferentes. Na Figura 5, observamos que o K-means centraliza os clusters, enquanto na Figura 6, o MiniSom divide o centro em múltiplos clusters. Essas discrepâncias evidenciam a sensibilidade dos algoritmos aos métodos de redução de dimensionalidade, fornecendo insights adicionais sobre a estrutura dos dados.


!["K-means plot 3D"](./imgs/kmeas_plot_using_SNE.png)

​									**Figura 5.** K-means plot usando redução de dimensionalidade. 



​	!["K-means plot 3D"](./imgs/minisom_plot_using_SNE.png)

​									**Figura 6.** Minisom plot usando redução de dimensionalidade. 

# Plots dos clusters por países

# Conclusão

pass