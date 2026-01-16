# projetoDioexcel
projeto do curso de excel do site DIO
# 📊 Blue Invest – Alocação de FIIs no Excel

![Excel](https://img.shields.io/badge/Microsoft%20Excel-Project-green)
![Status](https://img.shields.io/badge/status-em%20desenvolvimento-blue)
![License](https://img.shields.io/badge/license-educacional-lightgrey)

## 📌 Sobre o Projeto

O **Blue Invest** é um projeto desenvolvido em **Microsoft Excel** com foco na **alocação estratégica de Fundos Imobiliários (FIIs)** de acordo com o **perfil do investidor**.

A planilha foi estruturada para servir como **base lógica de alocação**, permitindo análises consistentes, padronizadas e facilmente escaláveis para novos perfis e estratégias de investimento.

---

## 🎯 Objetivos

* Definir alocação de FIIs por perfil de risco
* Padronizar percentuais de investimento
* Facilitar análises e simulações de carteira
* Reduzir erros manuais
* Servir como base para dashboards financeiros

---

## 🛠️ Tecnologias Utilizadas

* **Microsoft Excel**
* Fórmulas nativas
* Estrutura relacional entre abas
* Organização orientada a dados

> ℹ️ O projeto **não utiliza macros (VBA)**, garantindo compatibilidade com diferentes versões do Excel.

---

## 📂 Estrutura do Repositório

```bash
📁 blue-invest-excel
 ├── Projeto.xlsx
 ├── README.md
```

---

## 📄 Estrutura do Arquivo Excel

### Aba `projeto`

* Aba principal do projeto
* Destinada à consolidação das informações
* Pode ser utilizada para:

  * Dashboards
  * Gráficos
  * Simulações de carteira
  * Indicadores de alocação

---

### Aba `Planilha_apoio`

Planilha responsável pela **regra de negócio** do projeto.

Contém:

* Perfil do investidor (ex.: Conservador)
* Tipos de FIIs:

  * PAPEL
  * TIJOLO
  * HÍBRIDOS
  * FOFs
* Percentual de alocação por tipo
* Chave de relacionamento entre perfil e ativo

#### Exemplo de estrutura:

| PERFIL      | TIPO DE FII | %   |
| ----------- | ----------- | --- |
| Conservador | PAPEL       | 30% |
| Conservador | TIJOLO      | 50% |
| Conservador | HÍBRIDOS    | 10% |
| Conservador | FOFs        | 10% |

---

## ⚙️ Como Funciona

1. O usuário define o **perfil de investidor**
2. A planilha de apoio fornece os **percentuais ideais**
3. Esses percentuais podem ser usados para:

   * Simular carteiras
   * Criar dashboards
   * Avaliar balanceamento
4. A estrutura permite expansão para novos perfis

---

## ▶️ Como Utilizar

1. Clone ou baixe este repositório
2. Abra o arquivo `Projeto.xlsx` no Excel
3. Consulte ou edite a aba **Planilha_apoio**
4. Utilize a aba **projeto** para análises e visualizações

---

## 🚀 Possíveis Evoluções

* Inclusão de novos perfis (Moderado, Arrojado)
* Criação de dashboard visual
* Integração com Power Query
* Automatizações com VBA
* Expansão para outros ativos (ações, ETFs, renda fixa)

---

## ⚠️ Observações

* Mantenha backup do arquivo
* Evite excluir colunas da planilha de apoio
* Garanta que a soma dos percentuais seja 100%
* Projeto com finalidade educacional

---

## 👤 Autor

Desenvolvido por **Daisy**

---

## 📄 Licença

Este projeto é destinado a fins educacionais e de estudo.
Para uso comercial, entre em contato com o autor.

---

⭐ Se este projeto te ajudou, considere deixar uma **star** no repositório!
