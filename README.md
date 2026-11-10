# 📚 Simulação de Pilha com Listas

> Exercício de Python que demonstra o funcionamento de uma estrutura de dados do tipo pilha.

## 🎯 Objetivo
Compreender o funcionamento de uma pilha utilizando listas, praticando inserção, remoção e acesso aos elementos.

## 📚 Conceitos utilizados
- Listas (`[]`)
- `append()` — adicionar elementos.
- `pop()` — remover o último elemento.
- `len()` — consultar a quantidade de elementos.
- Indexação negativa (`[-1]`)
- LIFO (Last In, First Out).

## ⚙️ Código

```python
historico = []

historico.append('ligar')
historico.append('calibrar')
historico.append('medir')

historico.pop()

len(historico)
historico[-1]
```

## 📊 Funcionamento

1. Cria uma lista vazia chamada `historico`.
2. Adiciona três elementos utilizando `append()`.
3. Remove o último elemento utilizando `pop()`.
4. Consulta
