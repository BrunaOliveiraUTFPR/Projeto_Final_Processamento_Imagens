Projeto_Final_Processamento_Imagens

# Classificação de Flores

Aluna: Bruna de Paula Oliveira - RA: 2312778

# Descrição do(s) descritor(es) implementados:
- HOG: extrai gradientes e bordas
- LBP: extrai padrões locais de textura
- SIFT: extrai pontos-chave robustos
- Histograma em Escala de Cinza - distribuição de intensidades de pixel
  
# Repositório do projeto:
[Link do repositório do projeto](https://drive.google.com/drive/folders/1wP4-1uw9bPZyeXej4ZtH78zN-j7pCbJm?usp=sharing)

# Dataset Utilizado:
Foi utilizada uma base de flores contendo imagens de diferentes classes como dente de leão, rosa, tulipa, margarida e girassol.  
As imagens estão organizadas em subpastas com o nome de cada flor.
No repositório do projeto no drive há um dataset (utilizado para testes mais rápidos durante o desenvolvimento) com 50 imagens de cada uma das classes, porém o download do repositório pode ser realizado em:
[Link do dataset](https://www.kaggle.com/datasets/alxmamaev/flowers-recognition)

# Classificadores e acurácia:
SVM, KNN, MLP e Random Forest

  SVM: 36%
  KNN: 48%
  MLP: 52%
  RF: 44%

-Matriz de confusão: `resultados/matriz_interface.png`
-Relatório de classificação: `resultados/relatorio_interface.png`

# Instruções e estrutura de pastas do projeto:
Projeto_Final_Processamento_Imagens/
- ├── datasets/
- ├── modulos/
- │ ├── classificadores/
- │ ├── descritores/
- │ └── utils/
- ├── resultados/
- └── janela_principal.ipynb

Como executar:
1. Acesse o notebook `janela_principal.ipynb` no Google Colab.
2. Verifique que o Google Drive está conectado.
3. selecione os checkboxes e clique em:
   - Extrair características
   - Treinar o modelo
   - Testar o modelo
4. Visualize os resultados na saída da interface ou nos arquivos salvos na pasta `/resultados` no repositório.
