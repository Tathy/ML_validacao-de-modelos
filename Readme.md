# :bar_chart: Machine Learning: validação de modelos

[Link do Google Colab](https://colab.research.google.com/drive/15ibd-svawLuSqctiV9153p4tvtfPCv1A?usp=sharing)

* **Base de Dados:** Características físicas de alguns carros que estão ou estiveram à venda, seus preços de venda, e se foram vendidos ou não. Site de vendas fictício.

* O foco deste estudo é lidar com situações em que a aleatoriedade pode interferir muito no rendimento de modelos, situações de "azar" na formação de grupos de treino e teste ou na escolha dos seeds.

* Foram testadas validações cruzadas (cross validation) com diferentes algoritmos de aleatorização e separação dos grupos de teste e treino (splitter classes).

* O algoritmo de treino dos modelos foi mantido sempre o mesmo, Árvore de Decisão. Depois foi testado um SVC com divisão por grupos e normalização, utilizando Pipeline.

## Referências

Este projeto foi desenvolvido com referência no curso [Machine Learning: validação de modelos](https://cursos.alura.com.br/course/machine-learning-validando-modelos).
