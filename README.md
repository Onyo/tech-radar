# Pede Pronto Tech Radar
Radar de tecnologias utilizadas na pede pronto.

## Formato
Para adicionar uma tecnologia mantenha o formato especifico.
```js
{
    // Nome da tecnologia
    "name": "Enzyme",
    // aneis no radar, sao constantes e cada anel novo criará uma nova subdivisao
    "ring": "Desuso",
    //  quadrante, como o nome sugere 1 de 4 opções.
    "quadrant": "Testes Unitários",
    "isNew": "FALSE",
    // descrição que suporta formato HTML
    "description": "<a href='https://enzymejs.github.io/enzyme/'>Enzyme</a> is a JavaScript Testing utility for React that makes it easier to test your React Components' output. You can also manipulate, traverse, and in some ways simulate runtime given the output."
}
```

### Quadrantes e Aneis Frontend

- Anéis:
     - Adotada: tecnologia adotada
     - em Adesão: será / pode ser adotada
     - desuso: já foi adotada mas não utilizamos mais.

- Quadrantes
     - Langs and Frameworks: linguagens and frameworks centrais (React apesar de ser considerado uma lib foi enquadrado neste contexto por ser o centro do ecossistema para construção de views.)
     - Libraries: Pacotes e módulos terceiros utilizados no projeto como dependências, de importância para serem classificadas.
     - Developer Tools: Qualquer módulo usado pelo desenvolvedor para o desenvolvimento do produto.
     - Unit Tests: Módulos focados em produção de testes unitários.