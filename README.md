# Desafio DIO: Trabalhando com Machine Learning na Prática no Azure ML

Este repositório contém o passo a passo para realizar um experimento de Machine Learning utilizando o Azure Machine Learning, com foco na funcionalidade **Automated ML**.

## 🔧 Pré-requisitos

- Conta ativa no [Azure](https://portal.azure.com/)
- Permissões para criação de recursos (Grupo de Recursos, Workspace, Máquina Virtual, etc.)

## 🚀 Passo a Passo

### 1. Acesse o Portal do Azure

Entre no [portal do Azure](https://portal.azure.com/) com sua conta Microsoft.

### 2. Crie um Grupo de Recursos

Crie um **Resource Group** para manter os recursos organizados e facilitar a gestão do projeto.

### 3. Crie um Workspace no Azure Machine Learning

No menu lateral, procure por **Machine Learning** e crie um novo **Workspace**. Preencha os campos obrigatórios (nome, grupo de recurso, região etc.).

### 4. Configure um novo experimento com Automated ML

Após o Workspace ser criado:

- Acesse o menu **Automated ML** no canto esquerdo da interface.
- Inicie um novo experimento.
- Defina a **fonte de dados** (dataset) que será utilizada.

### 5. Defina as configurações da tarefa

Configure os seguintes parâmetros:

- Tipo de tarefa (Classificação, Regressão, etc.)
- Coluna alvo
- Limites de execução (tempo máximo, número de iterações, etc.)
- Tipo de validação e divisão de dados

### 6. Configure o ambiente de computação (Compute)

Crie ou selecione uma **máquina virtual (Compute Instance)** que será usada para treinar o modelo.

### 7. Execute, publique e teste o modelo

- Execute o experimento e aguarde a finalização do processo de treinamento.
- Publique o melhor modelo encontrado.
- Crie um **endpoint** de inferência para testar o modelo com novos dados.
- Colete as **métricas de desempenho** (como acurácia, precisão, recall, etc.)

---
