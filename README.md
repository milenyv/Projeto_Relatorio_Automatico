
## 🧠 Projeto: Relatório Automático com UiPath

### 📋 Descrição

Este projeto foi desenvolvido em **UiPath Studio** com o objetivo de automatizar a geração de relatórios no **Excel**.
A automação lê dados de uma planilha principal, realiza cálculos (como total, média e maior valor) e gera um **relatório consolidado** em uma segunda planilha.

Além disso, o robô salva e copia o arquivo atualizado automaticamente, simulando um processo real de automação de tarefas repetitivas em escritórios.

---

### ⚙️ Funcionalidades

* 📂 Leitura automática de dados em uma planilha do Excel
* 🧮 Cálculo de totais, médias e maior valor das colunas
* ✏️ Escrita automática dos resultados em uma segunda planilha
* 💾 Salvamento e cópia do arquivo final
* 🪄 Exibição de mensagem de sucesso ao final do processo

---

### 🧩 Tecnologias utilizadas

* **UiPath Studio** (automação RPA)
* **Excel** (para leitura e gravação de dados)
* **PowerShell / Windows** (para configuração e movimentação de arquivos)

---

### 🗂️ Estrutura do projeto

```
📦 Projeto_Relatorio_Automatico
 ┣ 📁 projeto
 ┃ ┣ 📜 Main.xaml               # Arquivo principal da automação
 ┃ ┣ 📜 project.json            # Configurações do projeto UiPath
 ┃ ┗ 📄 Planilha.xlsx           # Base de dados e relatório
 ┗ 📜 README.md
```

---

### 🚀 Como executar o projeto

1. Abra o **UiPath Studio**.
2. Clique em **Abrir Projeto** e selecione o arquivo `project.json`.
3. Certifique-se de que o caminho do Excel dentro das atividades está correto.
4. Clique em **Run** ▶️ para executar o robô.
5. Aguarde o processamento até aparecer a mensagem:

   > “Relatório gerado com sucesso!”

---

### 📊 Exemplo de resultado

**Planilha 1 (dados originais)**

| Produto | Quantidade | Preço | Total |
| ------- | ---------- | ----- | ----- |
| Caneta  | 10         | 2.50  | 25    |
| Lápis   | 5          | 1.20  | 6     |
| Caderno | 3          | 10.00 | 30    |

**Planilha 2 (relatório gerado)**

| Indicador      | Valor |
| -------------- | ----- |
| Total Geral    | 61,00 |
| Média de Preço | 4,56  |
| Maior Venda    | 30,00 |

---

### 🎯 Objetivo do projeto
Demonstrar habilidades em **automação de processos (RPA)**, uso de **Excel Application Scope**, **loops**, **operações matemáticas** e **gerenciamento de arquivos** no UiPath.


<img width="721" height="830" alt="image" src="https://github.com/user-attachments/assets/9b5f090f-af0e-4679-a426-b8f4cb5997c4" />


<img width="527" height="262" alt="image" src="https://github.com/user-attachments/assets/e65f74b8-ab01-4720-ab99-9f5588bca4a9" />

