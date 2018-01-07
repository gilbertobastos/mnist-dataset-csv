# Dataset MNIST (dígitos escritos à mão) no formato CSV

Dataset MNIST no formato CSV, para ser utilizado no treinamento das
implementações da rede Perceptron Multicamadas presentes nessa página
do Github.

## Formato dos arquivos

No caso, cada conjunto de treinamento é dividido em dois arquivos,
cada um com o sufixo __amostras__ e __objetivos__, onde, o arquivo de
amostras contém os padrões de treinamento, e o de objetivo, a saída
desejada para cada um dos padrões de treinamento respectivamente. Por
exemplo:

__arquivo-amostras-xor.csv__
```csv
1;0;
1;1;
1;0;
0;1;
```

__arquivo-objetivos-xor.csv__
```csv
1;
0;
1;
1;
```

O arquivo __mnist-amostras__ possui 60000 amostras para treinamento da
rede neural, onde, para normalização das amostras, o menor e maior
item são _0_ e _255_, respectivamente.

O arquivo __mnist-amostras-teste__ possui 10000 amostras para serem
realizados os testes de eficácia da classificação, após o treinamento
da rede.

## Agradecimentos

Agradecimentos ao Márcio Piva (página dele no Github:
<https://github.com/marciopiva>), que foi o responsável de fazer a
"conversão" dos arquivos originais do dataset MNIST original (que
possuem um formato um pouco peculiar) para um formato mais fácil de se
trabalhar.

Página original: <http://yann.lecun.com/exdb/mnist/>

