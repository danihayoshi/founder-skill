# Nota da CFO (rascunho, 05/11/2026)

> **Leia assim:** a ferramenta escreve "$", mas tudo está em **reais (R$)**. Como uma turma não vende todo dia, a conta usa **"por dia" = por mês** (days_per_month = 1). Quase todos os custos são **estimativas** da CFO, marcadas no numbers.json, e precisam ser confirmados com orçamentos reais. Isto não é parecer contábil: um contador deve checar a estrutura (CNPJ, Simples Nacional), o pró-labore e os impostos. A receita está **antes dos impostos**.

- **A margem:** cada vaga de R$ 14.997 deixa **R$ 9.647 (64%)** depois dos custos diretos. A residência (R$ 3.500 por aluno) é o maior deles.
- **Ponto de equilíbrio:** com R$ 16.300/mês de custo fixo, são **cerca de 2 vagas por mês** (por volta de 20 por ano).
- **Ano 1 (rascunho):** Fellowship L00 nos meses 1 a 5, sem receita; turmas pagas de 6, 8 e 10 alunos nos meses 6, 9 e 12. São 24 vagas, **R$ 359.928 de receita** e **R$ 35.928 de lucro operacional** (R$ 11.428 depois do investimento inicial de R$ 24.500).
- **Caixa necessário: R$ 106.000** antes de o negócio se pagar (o ponto mais baixo vem no mês 5). **Isso é o que mais pesa.**
- **A linha a observar é o preço.** Com 10% a menos, o ano 1 fica no zero (−R$ 65). A R$ 9.997, o ano 1 dá **−R$ 84.072**. A R$ 19.997, **+R$ 155.928**. Com 20% menos alunos, −R$ 10.378.

## Para chegar a R$ 1 milhão por ano
- Só com turmas a R$ 14.997, são **cerca de 67 vagas por ano**, ou seja, umas 6 turmas de 11 a 12 alunos. Cada vaga paga sozinha os custos dela e deixa sobra, então a conta é sobre volume, não sobre margem. (O canvas previa 334 clientes porque misturava preços baixos.)
- **Patronos e empresas não mudam a margem, mudam quem paga.** 10 bolsas patrocinadas = R$ 149.970 por ano, e cada bolsa vira um caso documentado.
- **A assinatura de ex-alunos pode ser a maior alavanca** (cálculo à parte, estimativa): 200 ex-alunos × R$ 297/mês = **R$ 712.800 por ano** de receita que se repete.

## Três formas de melhorar (todas rodadas na ferramenta ou calculadas acima)
1. **Preço R$ 19.997** (escola premium com certificado forte): ano 1 vai de R$ 35.928 para **R$ 155.928**.
2. **Patronos financiando a Fellowship e a primeira turma:** reduz o caixa necessário de R$ 106 mil.
3. **Assinatura desde a turma L01:** receita entre uma turma e outra, cobrindo os meses vazios (hoje são 9 meses no vermelho).

## Condições de dinheiro do conselho (board.md)
- Unit economics: **em rascunho**, com estimativas. Falta o custo real de entrega e de capacidade.
- CAC: **ainda desconhecido.** Nada de anúncios antes de medir.
- 3 casos antes de vender acima de R$ 997: **o plano respeita isso**, porque a Fellowship L00 vem antes das turmas pagas.

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

| month | vagas a day | revenue | profit | cumulative (after $24,500 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 0 | $0 | -$16,300 | -$40,800 |
| 2 | 0 | $0 | -$16,300 | -$57,100 |
| 3 | 0 | $0 | -$16,300 | -$73,400 |
| 4 | 0 | $0 | -$16,300 | -$89,700 |
| 5 | 0 | $0 | -$16,300 | -$106,000 |
| 6 | 6 | $89,982 | $41,582 | -$64,418 |
| 7 | 0 | $0 | -$16,300 | -$80,718 |
| 8 | 0 | $0 | -$16,300 | -$97,018 |
| 9 | 8 | $119,976 | $60,876 | -$36,142 |
| 10 | 0 | $0 | -$16,300 | -$52,442 |
| 11 | 0 | $0 | -$16,300 | -$68,742 |
| 12 | 10 | $149,970 | $80,170 | $11,428 |

- **Year 1 operating profit: $35,928** on $359,928 of revenue.
- After the $24,500 startup spend: $11,428.
- Startup money earned back: month 12.
- Cash you need before it pays for itself: **$106,000**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 50% | 2 | $35,928 |
| Price -10% | 44% | 3 | -$65 |
| Volume -20% | 46% | 2 | -$10,378 |
| Unit costs +15% | 44% | 2 | $16,668 |

No red flags in these numbers. They are only as good as the inputs: check every cost against a real quote.
