# IDP — Transformação Digital no Governo (TDG)

Exercícios da matéria, um por pasta. Cada pasta é avaliada pelo [autograde-idp](https://github.com/alexlopespereira/autograde-idp).

| Exercício | Tema | Pasta |
|---|---|---|
| 1.2 | Primeiros passos com Git e GitHub | [exercicio-1.2](exercicio-1.2/) |
| 2.1 | Mapa de Atores da Jornada: Seguro-Desemprego pela URA da CAIXA | [exercicio-2.1](exercicio-2.1/) |

## Como validar um exercício

O autograde lê os arquivos da pasta em que é executado:

```bash
cd exercicio-2.1
autograde validar 2.1
```

## Como adicionar um exercício novo

```bash
mkdir exercicio-X.Y && cd exercicio-X.Y
# criar os arquivos pedidos no enunciado
git add . && git commit -m "Exercício X.Y: ..." && git push
```

> O exercício 1.2 foi importado do repositório original `exercicio-12`, que continua existindo porque foi o repositório avaliado naquele exercício.
