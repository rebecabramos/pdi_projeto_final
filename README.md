## Projeto Final da disciplina de Processamento Digital de Imagens 🖼

### 📚 Organização do repositório

### 📄 Descrição da tarefas
Neste trabalho, a DCT-2D (direta e inversa) deve ser desenvolvida utilizando as equações estudadas em sala de aula, sem o uso de bibliotecas prontas para esse fim. 
1. Dada uma imagem I em níveis de cinza, de dimensões RxC, era preciso desenvolver um programa para
- Exibir o módulo normalizado da DCT de I, sem o nível DC, e o valor (numérico) do nível DC
- Encontrar e exibir uma aproximação de I obtida preservando o coeficiente DC e os n coeficientes AC mais importantes de I, e zerando os demais. O parâmetro n é um inteiro no intervalo [0, RxC-1]. 
2. Foi desenvolvido um programa para reforçar os graves, no domínio DCT, de um sinal s, em formato .wav, com N amostras. O reforço será obtido pela multiplicação do coeficiente de frequência (adimensional) k por um valor y dado por:

<p align="center">
  <img src="resources/imgs/formula.PNG" alt="formula"/>
</p>

Em que g controla o ganho (g = 0.5 é 50% de ganho máximo), fc é a frequência de corte (adimensional) e n é a ordem do filtro.

### ⚙ Como rodar
1. Faça um clone do repositório
2. Use o Jupyter ou Colab para abrir o projeto
3. No Colab clique em Ambiente de execução -> Executar Tudo, ou use o comando ctrl+F9.
4. No Jupyter basta clicar em *run*
