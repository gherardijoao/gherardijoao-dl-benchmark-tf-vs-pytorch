# Benchmark: TensorFlow vs PyTorch

## Sobre o Projeto
Comparação de desempenho entre TensorFlow e PyTorch em uma tarefa básica de classificação usando o dataset MNIST. O projeto avalia:

- Tempo de treinamento
- Acurácia
- Eficiência por batch
- Tempo de inferência

## Tecnologias
- Python 3.10
- TensorFlow 2.12
- PyTorch 2.0
- Google Colab (GPU T4)

## Principais Resultados
| Métrica         | TensorFlow | PyTorch  |
|----------------|-----------|----------|
| Tempo total    | 54s       | 47.57s   |
| Acurácia       | 97.85%    | 97.71%   |
| Tempo/batch    | 6.8ms     | 2.86ms   |

## Como Executar
1. Clone o repositório:
```bash
git clone https://github.com/gherardijoao/dl-benchmark-tf-vs-pytorch.git
```

2. Abra os notebooks no Google Colab:
- `TensorFlow_MNIST.ipynb`
- `PyTorch_MNIST.ipynb`

3. Execute célula por célula (⌘/Ctrl+Enter)
