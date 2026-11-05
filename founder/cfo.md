# Nota da CFO (rascunho v2, 05/11/2026, sem bolsas no início)

> **Leia assim:** a ferramenta escreve "$", mas tudo está em **reais (R$)**. "Por dia" na tabela quer dizer **por mês** (days_per_month = 1). Quase todos os custos são **estimativas**: ver `cfo-sources.md`. Isto não é parecer contábil: um contador deve checar o CNPJ, o regime de impostos e o pró-labore. A receita está antes dos impostos.

**A fundadora não aprovou começar com bolsas.** Por isso a Fellowship L00 saiu do modelo. A v2 começa direto com turmas pagas.
O volume ainda é um **marcador** da CFO e deve ser trocado pelo da fundadora: turmas nos meses 3, 6, 9 e 12, com 6, 8, 10 e 10 alunos (34 vagas no ano).

- **Margem por vaga:** R$ 9.647 (64%) a R$ 14.997.
- **Ponto de equilíbrio:** cerca de 2 vagas por mês.
- **Ano 1:** **R$ 509.898 de receita**, **R$ 132.398 de lucro operacional** (R$ 116.898 depois do investimento inicial de R$ 15.500).
- **Caixa necessário: R$ 48.100.** O investimento se paga no mês 6.
- **Sensibilidade:**
  - R$ 9.997 → −R$ 37.602
  - R$ 19.997 → +R$ 302.398
  - metade dos alunos → −R$ 31.601
- **O risco:** o conselho e o painel avisaram que, sem casos de alunos, é difícil vender uma vaga cara. "Sem resultados" foi a objeção nº 1 do painel. A conta só fecha se as 6 primeiras vagas venderem.

## Para chegar a R$ 1 milhão por ano
- Cerca de 67 vagas por ano a R$ 14.997 (6 turmas de 11 ou 12 alunos), ou 50 vagas a R$ 19.997.
- Empresas e patronos pagando vagas mudam quem paga, não a margem.
- Assinatura de ex-alunos (estimativa): 200 × R$ 297/mês = R$ 712.800 por ano, receita que se repete.

---

# Unit economics: Landell School of Business: turma premium (rascunho; quase tudo é ESTIMATIVA a confirmar com a fundadora)

Every number below comes from the input file. Nothing is looked up or guessed.

## One vaga

| line | per vaga |
| --- | ---: |
| Price | $14,997.00 |
| Residência de 1 semana por aluno (hospedagem + alimentação + espaço) [estimativa] | -$3,500.00 |
| Guias ex-alunos: 1 guia por 10 alunos, R$ 6.000 por turma [estimativa] | -$600.00 |
| Créditos de IA/APIs da equipe de agentes por aluno na turma [estimativa] | -$300.00 |
| Taxa de pagamento/parcelamento ~5% [estimativa; conferir no gateway] | -$750.00 |
| Kit, certificado e material [estimativa] | -$200.00 |
| **Contribution** (what each vaga leaves to pay the fixed costs) | **$9,647.00** (64%) |

## The margin that matters

Fixed costs: $16,300 a month (Pró-labore da fundadora [A DEFINIR pela fundadora; estimativa] $10,000, Plataforma, site, ferramentas e IA [estimativa] $2,500, Conteúdo e marca (Os Landells, redes) [estimativa] $3,000, Contador [estimativa] $800).

- **Break-even: 2 vagas a day.** Below that you lose money every month.
- **Profit margin at your plan** (8 a day): **50%** of every sale, after every cost.
- Capacity: 30 a day.

## Year 1, month by month

| month | vagas a day | revenue | profit | cumulative (after $15,500 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 0 | $0 | -$16,300 | -$31,800 |
| 2 | 0 | $0 | -$16,300 | -$48,100 |
| 3 | 6 | $89,982 | $41,582 | -$6,518 |
| 4 | 0 | $0 | -$16,300 | -$22,818 |
| 5 | 0 | $0 | -$16,300 | -$39,118 |
| 6 | 8 | $119,976 | $60,876 | $21,758 |
| 7 | 0 | $0 | -$16,300 | $5,458 |
| 8 | 0 | $0 | -$16,300 | -$10,842 |
| 9 | 10 | $149,970 | $80,170 | $69,328 |
| 10 | 0 | $0 | -$16,300 | $53,028 |
| 11 | 0 | $0 | -$16,300 | $36,728 |
| 12 | 10 | $149,970 | $80,170 | $116,898 |

- **Year 1 operating profit: $132,398** on $509,898 of revenue.
- After the $15,500 startup spend: $116,898.
- Startup money earned back: month 6.
- Cash you need before it pays for itself: **$48,100**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 50% | 2 | $132,398 |
| Price -10% | 44% | 3 | $81,408 |
| Volume -20% | 46% | 2 | $66,798 |
| Unit costs +15% | 44% | 2 | $105,113 |

No red flags in these numbers. They are only as good as the inputs: check every cost against a real quote.
