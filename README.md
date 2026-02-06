# 🛒 Instacart Orders Analysis (Tripleten)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

## 📝 Descrição
Este projeto realiza uma **Análise Exploratória de Dados (AED)** detalhada nos registros de pedidos da plataforma Instacart. O foco principal foi limpar uma base de dados propositalmente modificada com valores ausentes e duplicatas, para então extrair insights sobre o comportamento de consumo dos usuários.

O projeto faz parte do currículo de Data Science da **Tripleten**.

---

## 📂 Estrutura do Repositório
```text
├── datasets/             # Pasta com ficheiros CSV (apenas cabeçalhos)
│   ├── aisles.csv
│   ├── departments.csv
│   ├── instacart_orders.csv
│   ├── order_products.csv
│   └── products.csv
├── notebooks/            # Pasta com o desenvolvimento do projeto
│   └── Instacart-orders.ipynb 
├── .gitignore            # Ficheiros ignorados (dados pesados e sistema)
├── requirements.txt      # Dependências para reprodução do ambiente
└── README.md             # Documentação principal do projeto

---

## 🛠️ Etapas do Projeto
1. **Pré-processamento de Dados**: 
   - Identificação e tratamento de valores nulos.
   - Remoção de dados duplicados.
   - Conversão de tipos de dados para otimização de memória.
2. **Análise Exploratória (EDA)**:
   - Distribuição de pedidos por hora do dia e dia da semana.
   - Análise de tempo de espera entre pedidos.
   - Identificação dos produtos mais populares e departamentos mais visitados.
3. **Conclusões**: Síntese dos padrões de compra identificados.

---

## 🚀 Tecnologias e Bibliotecas
- **Python 3.x**
- **Pandas**: Manipulação e limpeza de tabelas.
- **NumPy**: Operações matemáticas.
- **Matplotlib & Seaborn**: Criação de gráficos e visualizações.

---

## ⚙️ Como Executar
1. Clone o repositório:
   ```bash
   git clone [https://github.com/seu-usuario/instacart-orders.git](https://github.com/seu-usuario/instacart-orders.git)
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

3. **Dados**: Os arquivos CSV na pasta `datasets/` contêm apenas os cabeçalhos. Você precisa adicionar os dados reais aos arquivos CSV conforme descrito no notebook. Os dados originais são modificados da base Instacart e podem ser obtidos separadamente.

4. Abra o Jupyter Notebook:
   ```bash
   jupyter notebook Instacart-orders.ipynb
   ```

5. Execute as células sequencialmente para reproduzir a análise.

---

## 📊 Dados
O conjunto de dados inclui 5 tabelas CSV:
- `instacart_orders.csv`: Informações sobre os pedidos.
- `products.csv`: Detalhes dos produtos.
- `order_products.csv`: Itens em cada pedido.
- `aisles.csv`: Corredores dos produtos.
- `departments.csv`: Departamentos dos produtos.

**Nota**: Os arquivos criados contêm apenas os cabeçalhos das colunas. Insira os dados correspondentes para executar a análise.

---

## 📈 Resultados Principais
- Padrões de pedidos por hora e dia da semana.
- Produtos mais populares.
- Distribuição de itens por pedido.
- Análise de comportamento de recompra.

---

## 🤝 Contribuição
Contribuições são bem-vindas! Abra uma issue ou pull request.

## 📄 Licença
Este projeto é para fins educacionais.

---

## 🤝 Contato
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/phaa/)
