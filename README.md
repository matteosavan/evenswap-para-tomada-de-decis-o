# Even Swap para Tomada de Decisão Multicritério

Aplicação web interativa para apoiar decisões multicritério utilizando o método **Even Swap**.

A ferramenta permite comparar alternativas com base em múltiplos critérios numéricos ou categóricos, eliminar opções dominadas e realizar trocas equivalentes (*even swaps*) para chegar à melhor decisão.

## Funcionalidades

- Cadastro de alternativas;
- Cadastro de critérios:
  - Maximização ou minimização;
  - Critérios numéricos;
  - Critérios categóricos ordinais;
- Construção automática da matriz de decisão;
- Eliminação de:
  - alternativas dominadas;
  - critérios irrelevantes (empates práticos);
- Aplicação interativa do método **Even Swap**;
- Histórico e botão de voltar;
- Interface web simples e intuitiva.

## Como utilizar

1. Adicione as alternativas.
2. Defina os critérios da decisão.
3. Preencha a matriz de avaliação.
4. Execute a análise lógica.
5. Realize as trocas equivalentes (*Even Swaps*).
6. Obtenha a alternativa vencedora.

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript puro (Vanilla JS)

## Método utilizado

O projeto implementa o método **Even Swap**, proposto por:

> Hammond, Keeney e Raiffa (1998)

O método busca simplificar problemas multicritério através de trocas equivalentes entre atributos, reduzindo gradualmente o número de critérios até restar a melhor alternativa.

## Executando localmente

Clone o repositório:

```bash
git clone https://github.com/matteosavan/evenswap-para-tomada-de-decis-o.git
```

Abra o arquivo:

```text
index.html
```

em qualquer navegador moderno.

## GitHub Pages

A aplicação está disponível em:

https://matteosavan.github.io/evenswap-para-tomada-de-decis-o/

## Exemplo de aplicação

O sistema pode ser utilizado para:

- escolha de fornecedores;
- seleção de veículos;
- contratação de serviços;
- decisões de investimento;
- priorização de projetos.

## Licença

Este projeto foi desenvolvido para fins acadêmicos e educacionais.
