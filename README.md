# Gerar o conteúdo do README em um arquivo de texto
conteudo_readme = """
# Automação de Cadastro de Produtos e Análise de Cancelamento de Clientes

## Descrição
Este projeto contém dois módulos principais: 
1. **Automação de Cadastro de Produtos**: Automatiza o cadastro de produtos em um sistema online usando a biblioteca **PyAutoGUI** para simular interações no navegador e **Pandas** para manipular dados de produtos.
2. **Análise de Cancelamentos de Clientes**: Realiza uma análise de cancelamento de clientes, identificando padrões e causas para o cancelamento usando **Plotly** para visualizações gráficas e **Pandas** para tratamento de dados.

## Funcionalidades
### Automação de Cadastro de Produtos
- Acessa o sistema da empresa automaticamente.
- Realiza login com credenciais pré-definidas.
- Lê uma base de dados CSV contendo informações dos produtos.
- Cadastra cada produto automaticamente.
- Código adicional para identificar a posição do mouse em diferentes resoluções.

### Análise de Cancelamento de Clientes
- Carrega uma base de dados de clientes.
- Realiza análise exploratória dos dados para identificar clientes que cancelaram e os fatores relacionados.
- Gera gráficos interativos para explorar a relação entre variáveis e cancelamentos.
- Identifica causas específicas e sugere ações para reduzir o cancelamento.

## Tecnologias Utilizadas
- **PyAutoGUI**: Automação de interface gráfica.
- **Pandas**: Manipulação e análise de dados.
- **Plotly**: Visualização gráfica interativa.
- **Jupyter Notebook**: Para execução dos scripts de análise.

## Requisitos
- Python 3.x
- Bibliotecas:
  - `pyautogui`: Para instalar, execute `pip install pyautogui`
  - `pandas`: Para instalar, execute `pip install pandas`
  - `plotly`: Para instalar, execute `pip install plotly`

## Como Rodar o Projeto

### Automação de Cadastro de Produtos

1. **Instalar Dependências**:
   ```bash
   pip install pyautogui pandas
