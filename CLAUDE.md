# CLAUDE.md: briefing do projeto

Leia antes de editar. Projeto de estudo do MBA (disciplina Digital Growth & AI-Driven Marketing). Entregas individuais, prazo final em 22/11 às 23h59.

## Contexto

- Produto-base hipotético: bolos caseiros ("gosto de casa"), venda só online, entrega num raio de poucos quilômetros.
- A confeitaria real serve apenas de guia e fonte de dados. Não alterar nada do negócio real nem do site real.
- Pedido mínimo e taxas vêm de dados reais do app de delivery, quando citados.

## Regra de ouro

Nunca inventar números. Todo valor citado precisa ter origem: dado do aluno, página pública com link ou execução de código reexecutável.

## Rótulos de origem (obrigatórios na persona)

- **EU INFORMEI**: dado que o aluno trouxe (cardápio, preços, taxas, observações de clientes).
- **A IA DEDUZIU**: inferência direta a partir do que o aluno informou.
- **A IA SUPÔS**: hipótese da IA sem base nos dados. Precisa de validação.

## Regras da persona

- Descrever por situação (dia, lugar, onde trava), nunca por idade, gênero, geração ou renda.
- Frases concretas. Proibido: "busca praticidade", "valoriza qualidade".
- Antipersona por incompatibilidade com o que o produto entrega, nunca por renda ou idade.
- A leitura crítica final é escrita pelo aluno, não pela IA.

## Segurança e privacidade

- Nada de chaves, senhas, tokens ou `.env` no repositório.
- Nada de CPF, RG, endereço residencial ou CNPJ em arquivos versionados.
- Imagens e depoimentos reais só entram com autorização de quem aparece.

## Estrutura

```
.
├── CLAUDE.md
├── README.md
├── .gitignore
├── .env.example
├── persona/   # aula 1: ficha de 8 linhas, prompt, retrato e PDF
├── anuncio/   # aula 2: anúncio e testes de mensagem
└── site/      # aula 3: landing page (Astro + Vercel)
```

## Stack prevista

Claude Code, GitHub, Astro (ou HTML puro) e Vercel, todos no plano gratuito.
