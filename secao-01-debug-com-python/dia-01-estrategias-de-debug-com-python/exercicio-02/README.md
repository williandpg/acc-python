# Exercício 2

Considere o exemplo de código a seguir:

```sh
from math import factorial


def map_factorial(numbers):
    result = []

    for num in numbers:
        result.append(factorial(num))

    return result


def main():
    input_list = [1, 2, 3, 4, 5]
    return map_factorial(input_list)


if __name__ == "__main__":
    main()

```

### Sem alterar o código, descubra qual exceção é levantada se:

1. Um dos elementos da `input_list` for um inteiro negativo.

- Ocorreu uma exceção: ValueError: factorial() not defined for negative values.

2. Um dos elementos da `input_list` for uma string.

- Ocorreu uma exceção: TypeError: 'str' object cannot be interpreted as an integer.