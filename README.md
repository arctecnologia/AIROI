# 🚀 Enterprise AI ROI Calculator & Decision Engine

Um *dashboard* interativo e executivo desenvolvido em Python (Google Colab/Jupyter), concebido para avaliar a viabilidade financeira e o retorno sobre o investimento (ROI) na implementação de soluções de Inteligência Artificial e Hiperautomação.

Diferente de calculadoras de ROI tradicionais, este motor de decisão incorpora o **Custo Total de Propriedade (TCO)** sob a ótica da Engenharia de Software Moderna. Ele precifica o impacto de um **Squad Integrado** (DevSecOps), garantindo que a governação de TI, a arquitetura e a segurança da informação façam parte do cálculo financeiro desde o *Day One*.

---

## 🎯 Proposta de Valor

O objetivo é fornecer uma visão clara e baseada em dados para a Administração e Direções (*C-Levels*), quantificando:
1. O custo da ineficiência atual (Cenário *AS IS* manual).
2. O investimento necessário para o desenvolvimento seguro e estruturado (Custos Totais do Squad Integrado).
3. O ponto de equilíbrio financeiro (*Break-even* / *Payback*).
4. O valor estratégico gerado pela IA (Aumento de receita, retenção e eficiência).

---

## 🛠️ Arquitetura e Governação (O Squad Integrado)

Para garantir que a automação seja construída como um produto de software resiliente, escalável e seguro, o investimento inicial (CAPEX) desta calculadora é unificado na rubrica **"Custos Totais do Squad Integrado"**.

Este valor absorve a atuação multidisciplinar de uma equipa de alta performance:
* **Product Owner (PO) & Scrum Master:** Alinhamento estratégico, gestão de *backlog* e cadência ágil.
* **Arquitetura & Engenharia (Dev):** Desenvolvimento de integrações via APIs e arquitetura escalável.
* **Governação de TI & AppSec (Sec):** Conformidade de dados, versionamento, revisão de código e implementação de esteiras de CI/CD contínuas.
* **Quality Assurance (QA):** Testes rigorosos para evitar regressões e falhas na automação de processos críticos.

---

## 🧮 Documentação Técnica e Lógica Matemática

O motor de cálculo opera com base no conceito de **Fluxo de Caixa Descontado Simplificado** focado no primeiro ano (12 meses) de implementação. Abaixo estão as equações que regem o sistema:

### 1. Cenário Atual (AS IS)
Mapeia o custo operacional atual baseado puramente em esforço humano (*Full-Time Equivalent* - FTE).
* **Custo Mensal AS IS:** `Horas Manuais Executadas por Mês × Custo Hora do Colaborador`
* **Custo Anual AS IS:** `Custo Mensal AS IS × 12`

### 2. Investimento Inicial (CAPEX)
Representa o *burn rate* total de desenvolvimento e governação durante a fase de *setup*.
* **Investimento Total:** `Custos Totais do Squad Integrado` (Variável única que consolida toda a operação ágil).

### 3. Cenário Futuro & Operação (TO BE)
Mensura o custo de sustentação e infraestrutura digital da Inteligência Artificial.
* **Custo Mensal TO BE:** `Consumo Mensal de Nuvem e Tokens + Custo Mensal de Sustentação/MLOps`
* **Custo Anual TO BE:** `Custo Mensal TO BE × 12`

### 4. Geração de Valor e KPIs de Viabilidade
* **Geração de Valor Mensal:** `(Custo Mensal AS IS - Custo Mensal TO BE) + Ganho Estratégico Mensal`
* **Benefício Líquido Anual:** `Geração de Valor Mensal × 12`
* **ROI (Projeção 1 Ano):** `((Benefício Líquido Anual - Investimento Total) / Investimento Total) × 100`
* **Payback (Ponto de Equilíbrio):** `Investimento Total / Geração de Valor Mensal`

---

## ✨ Interface de Utilizador (UI/UX) e Geração de Relatórios

O sistema é estruturado como uma aplicação *Single-Cell* que utiliza bibliotecas nativas de dados:
* **Dashboards Dinâmicos:** Construídos com `ipywidgets`, permitem a atualização imediata dos KPIs financeiros ao ajustar qualquer parâmetro.
* **Design Inclusivo e Acessibilidade:** A interface e os gráficos não possuem cores hexadecimais de texto fixas, garantindo total compatibilidade visual e legibilidade, quer o utilizador utilize **Modo Claro (Light Mode)** ou **Modo Escuro (Dark Mode)** na sua IDE.

 <img width="866" height="278" alt="image" src="https://github.com/user-attachments/assets/f8b39ebd-25b1-461b-a45d-4caba1acb185" />

<img width="524" height="136" alt="image" src="https://github.com/user-attachments/assets/ec39f6c8-3179-42c1-8928-c8d6be24fdfe" />

* **Motor Gráfico (Matplotlib):**
  * **Gráfico de Barras:** Exibe visualmente a redução do TCO anual comparando os cenários manual e IA.
  * **Gráfico de Linhas (Break-even):** Plota o fluxo de caixa acumulado ao longo de 12 meses, sombreando automaticamente as zonas de risco financeiro (vermelho) e a zona de lucro (verde).

 <img width="1489" height="490" alt="image" src="https://github.com/user-attachments/assets/ab5b1e2b-5976-4a28-8d15-1c9d9634c54b" />

    

---

## 🚀 Como Executar no Seu Ambiente

### Pré-requisitos
Certifique-se de ter um ambiente Python 3.x configurado (recomendamos Google Colab ou Jupyter Notebook).

### Instalação e Execução
1. Clone este repositório para a sua máquina local ou faça o *upload* do ficheiro `.ipynb` para o seu Google Drive:
   ```bash
   git clone [https://github.com/seu-utilizador/nome-do-repositorio.git](https://github.com/seu-utilizador/nome-do-repositorio.git)
