# Simulador-de-Investimentos-em-Fundos-Imobilirios-com-excel
planilha criada, para simular investimentos com fórmulas financeiras (juros compostos, somatórios) - Funções do Excel como `SE`, `SOMARPRODUTO`, `TAXA`, `VF`, `PGTO` , `PROCV`- Validação de dados - Formatação condicional - Uso de gráficos para visualização dos resultados

# 📊 Simulador de Investimentos em Fundos Imobiliários (FIIs)

Este projeto foi desenvolvido como parte de um laboratório prático de Excel com o objetivo de criar uma **ferramenta de simulação de investimentos em FIIs (Fundos Imobiliários)**.

A planilha permite que o usuário simule diferentes cenários de aportes mensais e taxas de rendimento para entender como seu patrimônio pode evoluir ao longo dos anos. Ideal para quem deseja investir com mais estratégia e clareza.

---

## 🎯 Objetivo

Desenvolver uma planilha em Excel que auxilie investidores iniciantes ou intermediários a responder perguntas como:

- Quanto investir mensalmente?
- Qual será meu patrimônio após X anos?
- Quanto receberei em dividendos?
- Como o tempo e os aportes impactam meu retorno?

---

## 📌 Funcionalidades

A planilha é interativa e permite simulações customizadas com base em:

- 💰 **Salário**: usado para sugerir um percentual de investimento ideal
- 💵 **Aporte mensal**: valor que será investido todo mês
- 📅 **Tempo de investimento (em anos)**
- 📈 **Taxa de rendimento mensal esperada**
- 🧮 **Resultado automático** do:
  - Patrimônio acumulado
  - Dividendos mensais estimados

Ela também mostra simulações para diferentes prazos (2, 5, 10, 20 e 30 anos).

---

## 📊 Exemplo de Simulação

Com os seguintes parâmetros:

| Campo                        | Valor           |
|-----------------------------|-----------------|
| Salário                     | R$ 5.000,00     |
| Sugestão de investimento    | R$ 1.500,00     |
| Aporte mensal               | R$ 500,00       |
| Duração do investimento     | 5 anos          |
| Rendimento mensal           | 0,89%           |

### Resultado:
- **Patrimônio estimado**: R$ 39.422,30
- **Dividendos mensais esperados**: R$ 350,86

---

## 🖼️ Visual da Planilha

![Exemplo de simulação preenchida](./exemplo_simulacao_planilha.png)

---

## 📈 Projeção de Crescimento (Simulação)

| Período (anos) | Patrimônio Acumulado | Dividendos Mensais |
|----------------|----------------------|---------------------|
| 2              | R$ 13.312,24         | R$ 118,48           |
| 5              | R$ 39.422,30         | R$ 350,86           |
| 10             | R$ 106.507,90        | R$ 947,92           |
| 20             | R$ 414.937,78        | R$ 3.692,95         |
| 30             | R$ 1.308.101,54      | R$ 11.642,10        |

> 📌 *Os valores são estimativas baseadas na taxa fixa de rendimento mensal. Dividendos são calculados com base no patrimônio acumulado.*

---

## 🧠 Conceitos Aplicados

A planilha utiliza diversos recursos e fórmulas avançadas do Excel, incluindo:

- Fórmulas financeiras:
  - `VF` (Valor Futuro)
  - `PGTO` (Pagamento Periódico)
  - `SE` (Lógica condicional)
  - `SOMARPRODUTO` (Multiplicação e soma vetorial)
  - `PROCV` (Busca de dados por categoria — usada para indicar tipo de fundo e perfil de risco)
- Validação de dados
- Formatação condicional
- Categorização de fundos por perfil e tipo
- Interface amigável com campos de entrada e saída organizados

---

## 🖥️ Como Usar

1. Faça o download da planilha:
   - [`Planilha simulador de investimentos Rafael.xlsx`](./Planilha%20simulador%20de%20investimentos%20Rafael.xlsx)
2. Abra no Excel (recomendado) ou Google Sheets.
3. Edite os campos de entrada com seus próprios dados.
4. Acompanhe os resultados calculados automaticamente.

---

## 📁 Estrutura do Repositório

📦 simulador-fundos-imobiliarios
├── Planilha simulador de investimentos Rafael.xlsx # Planilha Excel com simulações
├── exemplo_simulacao_planilha.png # Imagem da simulação preenchida
└── README.md # Documentação do projeto

---

## 🚀 Melhorias Futuras

- [ ] Incluir gráficos dinâmicos de evolução mês a mês
- [ ] Adicionar simulação com reinvestimento dos dividendos
- [ ] Criar uma versão web com interface interativa (usando JavaScript ou Python)
- [ ] Compartilhar a versão online via Google Sheets

---

## 🙌 Contribuição

Sinta-se à vontade para abrir uma issue ou enviar um pull request com sugestões de melhorias ou novas funcionalidades!

---

> Desenvolvido como parte de um treinamento prático em Excel, com foco em educação financeira e autonomia nos investimentos.


