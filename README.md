# Manipulação de Listas em Python

Em Python, uma **lista** é uma estrutura de dados que armazena uma coleção ordenada de elementos, que podem ser de diferentes tipos (como números, strings ou até outras listas). As listas são mutáveis, ou seja, seus elementos podem ser alterados depois que a lista é criada. Cada item na lista é indexado, começando do índice 0 para o primeiro elemento.

## Características principais
- São criadas usando colchetes (`[]`), com os itens separados por vírgulas.
- Permitem adicionar, remover e modificar elementos.
- Suportam operações de fatiamento (slicing) e métodos específicos para manipulação, como `append()`, `remove()`, `sort()`, entre outros.

### Função `pop()`

Remove o último elemento da lista 
```python
lista = ['maria', 'jose', 'ricardo']
# remove 'ricardo'
lista.pop()
#resultad: ['maria', 'jose']
```

### Comando `del`

Utilizado para exclusão de objetos, como por exemplo *listas* ou *elementos* de uma lista

```python
lista = ['maria', 'jose', 'ricardo']

# exclui o elemento no índice 0
del lista[0]
print(lista)

# exclui a lista
del lista
```