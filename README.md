# 
<div style="display: inline_block">
  <img align="center" alt="VS" src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" />
  <img align="center" alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img align="center" alt="C++" src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
</div><br/>

# 🎰 Métodos de Ordenação 
<div align="justify">
Este repositório apresenta uma variedade de algoritmos de ordenação, com o objetivo de fornecer uma visão geral dos métodos mais comuns utilizados para organizar elementos em uma lista. Cada algoritmo de ordenação abordado neste documento possui suas próprias características, complexidade e eficiência, o que pode influenciar a escolha da abordagem mais adequada para diferentes situações.
  
Os seguintes métodos de ordenação serão explorados em detalhes:

  - 1️⃣ Bubble Sort;
  - 2️⃣ Bucket Sort;
  - 3️⃣ Selection Sort;
  - 4️⃣ Insertion Sort;
  - 5️⃣ Merge Sort;
  - 6️⃣ Heap Sort;
  - 7️⃣ Radix Sort;
  - 8️⃣ Shell Sort;
  - 9️⃣ Counting Sort;
  - 🔟 Quick Sort;  

Espera-se que essa compilação seja útil para entender os diferentes métodos de ordenação e escolher a abordagem mais apropriada para suas necessidades.
</div>

## 1️⃣ Bubble Sort

- Algoritmo simples
- **Como funciona:**
  - Percorre repetidamente a lista, comparando pares de elementos adjacentes e trocando-os caso estejam na ordem errada
  - Esse processo é repetido até que a lista esteja completamente ordenada
- **Complexidade de tempo:** O(n<sup>2</sup>)
- **Desvantavem(s):** Ineficiente para grandes conjuntos de dados

<p align="center">
<img src="imgs/bubble2.gif" width="350"/> 
</p>
<p align="center">
<em>Imagem 1: Gif esquemático do funcionamento do método.</em>
</p>

<!--
<p align="center">
<img src="imgs/bubble.gif" width="350"/> 
</p>
<p align="center">
<em>Imagem 2: Gif gráfico do funcionamento do método.</em>
</p>
-->
## 2️⃣ Bucket Sort

- **Como funciona:**
- Divide o intervalo de valores em intervalos menores, chamados de "baldes", e distribui os elementos nos baldes correspondentes.
- Em seguida, os elementos em cada balde são ordenados individualmente, geralmente usando outro algoritmo de ordenação.
- Por fim, os elementos são concatenados na ordem correta.
- **Complexidade de tempo:** O(n+k), onde n é o número de elementos e k é o número de baldes
- **Vantagem(s):** Eficiente quando os elementos de entrada são distribuídos de maneira uniforme
- **Desvantavem(s):** Ineficiente para grandes conjuntos de dados
  
<p align="center">
<img src="imgs/bucket2.gif" width="350"/> 
</p>
<p align="center">
<em>Imagem 3: Gif esquemático do funcionamento do método.</em>
</p>

<!--
<p align="center">
<img src="imgs/bucket.gif" width="350"/> 
</p>
<p align="center">
<em>Imagem 4: Gif gráfico do funcionamento do método.</em>
</p>
-->
## 3️⃣ Selection Sort

- Algoritmo simples
- **Como funciona:**
  - Divide a lista em duas partes: uma parte ordenada e outra desordenada
  - A cada iteração, o algoritmo encontra o menor elemento na parte desordenada e o coloca no final da parte ordenada
  - Isso é repetido até que a lista inteira esteja ordenada
- **Complexidade de tempo:** O(n<sup>2</sup>)
- **Desvantavem(s):** Ineficiente para grandes conjuntos de dados

<p align="center">
<img src="imgs/selection2.gif" width="350"/> 
</p>
<p align="center">
<em>Imagem 5: Gif esquemático do funcionamento do método.</em>
</p>

<p align="center">
<img src="imgs/selection.gif" width="350"/> 
</p>
<p align="center">
<em>Imagem 6: Gif gráfico do funcionamento do método.</em>
</p>

## 4️⃣ Insertion Sort;

- **Como funciona:**
- Constrói uma lista ordenada um elemento de cada vez, inserindo cada novo elemento na posição correta.
- Percorre a lista, comparando cada elemento com os elementos anteriores e movendo-os uma posição para a direita, se necessário. 
- **Complexidade de tempo:** O(n<sup>2</sup>)
- **Vantagem(s):** Eficiente para pequenos conjuntos de dados ou quando a lista já está quase ordenada
- Seu desempenho é melhor que o **Bubble Sort** e o **Selection Sort** em muitos casos.

<p align="center">
<img src="imgs/insertion2.gif" width="350"/> 
</p>
<p align="center">
<em>Imagem 7: Gif esquemático do funcionamento do método.</em>
</p>

<!--
<p align="center">
<img src="imgs/insertion.gif" width="350"/> 
</p>
<p align="center">
<em>Imagem 8: Gif gráfico do funcionamento do método.</em>
</p>
-->
## 5️⃣ Merge Sort;


<p align="center">
<img src="imgs/merge2.gif" width="350"/> 
</p>
<p align="center">
<em>Imagem 9: Gif esquemático do funcionamento do método.</em>
</p>

<p align="center">
<img src="imgs/merge.gif" width="350"/> 
</p>
<p align="center">
<em>Imagem 10: Gif gráfico do funcionamento do método.</em>
</p>

## 6️⃣ Heap Sort;


<p align="center">
<img src="imgs/heap2.gif" width="350"/> 
</p>
<p align="center">
<em>Imagem 11: Gif esquemático do funcionamento do método.</em>
</p>

<p align="center">
<img src="imgs/heap.gif" width="350"/> 
</p>
<p align="center">
<em>Imagem 12: Gif gráfico do funcionamento do método.</em>
</p>

## 7️⃣ Radix Sort;

<p align="center">
<img src="imgs/radix2.gif" width="350"/> 
</p>
<p align="center">
<em>Imagem 13: Gif esquemático do funcionamento do método.</em>
</p>

## 8️⃣ Shell Sort; 


<p align="center">
<img src="imgs/shell2.gif" width="350"/> 
</p>
<p align="center">
<em>Imagem 15: Gif esquemático do funcionamento do método.</em>
</p>

<p align="center">
<img src="imgs/shell.gif" width="350"/> 
</p>
<p align="center">
<em>Imagem 16: Gif gráfico do funcionamento do método.</em>
</p>

## 9️⃣ Counting Sort;


<p align="center">
<img src="imgs/counting2.gif" width="350"/> 
</p>
<p align="center">
<em>Imagem 17: Gif esquemático do funcionamento do método.</em>
</p>

<p align="center">
<img src="imgs/counting.gif" width="350"/> 
</p>
<p align="center">
<em>Imagem 18: Gif gráfico do funcionamento do método.</em>
</p>

## 🔟 Quick Sort; 


<p align="center">
<img src="imgs/quick2.gif" width="350"/> 
</p>
<p align="center">
<em>Imagem 19: Gif esquemático do funcionamento do método.</em>
</p>

<p align="center">
<img src="imgs/quick.gif" width="350"/> 
</p>
<p align="center">
<em>Imagem 20: Gif gráfico do funcionamento do método.</em>
</p>
