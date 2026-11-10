# 🐍 Manipulação de Listas

> Exercício de Python para praticar a criação e manipulação de listas.

## 🎯 Objetivo
Compreender como armazenar, adicionar, remover e acessar elementos de uma lista.

## 📚 Conceitos estudados
- Criação de listas (`[]`)
- Inserção de elementos (`append()`)
- Remoção de elementos (`pop()`)
- Contagem de elementos (`len()`)
- Indexação negativa

## ⚙️ Funcionamento

1. Cria uma lista vazia chamada `historico`.
2. Adiciona três elementos utilizando `append()`.
3. Remove o último elemento utilizando `pop()`.
4. Verifica a quantidade de elementos com `len()`.
5. Acessa o último elemento utilizando `historico[-1]`.

## 💻 Código utilizado

```python
historico = []

historico.append('ligar')
historico.append('calibrar')
historico.append('medir')

historico.pop()

len(historico)
historico[-1]
```

## 📊 Resultado esperado

Após as operações:

```text
Lista: ['ligar', 'calibrar']
Quantidade de elementos: 2
Último elemento: calibrar
```

## 🧠 Aprendizado
Com este exercício, pratiquei operações fundamentais de listas, entendendo como adicionar e remover elementos, consultar seu tamanho e acessar posições específicas.

## 🚀 Possível melhoria
Exibir os resultados utilizando `print()` e permitir que o usuário adicione elementos à lista.
