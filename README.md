# Codigo de Barras

Este código Python gera e exibe um código de barras no formato EAN-13, que é um padrão amplamente utilizado para identificar produtos. Vamos detalhar cada parte do código:

1. Instalação da Biblioteca
- Instala a biblioteca python-barcode, que é usada para gerar códigos de barras em Python.
- A biblioteca não vem pré-instalada no Python, então é necessário instalá-la antes de usá-la.

2. Importação das Biblioteca
- Importa as bibliotecas necessárias para gerar e exibir o código de barras.
   * barcode: Biblioteca principal para gerar códigos de barras.
   * ImageWriter: Classe que permite salvar o código de barras como uma imagem.
   * IPython.display: Usado para exibir a imagem gerada diretamente no ambiente Jupyter Notebook ou IPython.

3. Definição do Tipo de Código de Barras
- Define o tipo de código de barras que será gerado. Neste caso, ean13 é o formato EAN-13, que é um padrão de código de barras de 13 dígitos.
- O formato EAN-13 é comumente usado em produtos comerciais, e o código gerado seguirá esse padrão.

4. Número para o Código de Barras
- Define o número que será codificado no código de barras. No caso do EAN-13, o número deve ter 12 dígitos (o 13º dígito é um dígito de verificação calculado automaticamente).
- O número é a informação que será representada pelo código de barras.

5. Criação da Imagem do Código de Barras
- Cria uma instância do código de barras usando o número fornecido e o ImageWriter, que permite salvar o código de barras como uma imagem.
- Esta linha gera o código de barras, mas ainda não o salva ou exibe.

6. Nome do Arquivo e Salvamento da Imagem
- Define o nome do arquivo onde a imagem do código de barras será salva (barcode_image.png) e salva a imagem.
- O código de barras é salvo como um arquivo de imagem que pode ser usado posteriormente.

7. Exibição da Imagem
- Exibe a imagem do código de barras diretamente no ambiente Jupyter Notebook ou IPython.
- Permite visualizar o código de barras gerado sem precisar abrir o arquivo de imagem manualmente.

