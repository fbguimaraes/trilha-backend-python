# trilha-backend-python

Diário público da minha trilha de estudos em back-end com Python:
exercícios por unidade, anotações e glossário técnico.

## Estrutura

| Pasta | Conteúdo |
|---|---|
| `t1_python/` | Python em profundidade |
| `t2_algoritmos/` | Lógica e algoritmos |
| `t3_sql/` | SQL com PostgreSQL |
| `notas/` | Anotações e glossário |
| `tests/` | Testes gerais do repositório |

## Como rodar

Requer [uv](https://docs.astral.sh/uv/).

```bash
uv sync
uv run pytest
uv run ruff check .
```
