# Exemplo 00

Projeto simples em Node.js que demonstra o treinamento e uso de uma rede neural com TensorFlow.js.

O script treina um modelo de classificação a partir de dados fictícios de pessoas. As entradas combinam idade normalizada, cor e localização usando codificação one-hot. A saída prevê uma categoria entre:

- `premium`
- `medium`
- `basic`

Após o treinamento, o projeto faz uma predição para uma nova pessoa e exibe as probabilidades ordenadas no terminal.

## Bibliotecas usadas

- `@tensorflow/tfjs-node`: versão do TensorFlow.js para Node.js, usada para criar, treinar e executar o modelo de rede neural.

## Pré-requisitos

- Node.js instalado
- npm instalado

## Como instalar

```bash
npm install
```

## Como rodar

```bash
npm start
```

O comando executa:

```bash
node --no-warnings --watch index.js
```

Ou seja, o arquivo `index.js` fica em observação e o programa reinicia automaticamente quando houver alterações.

## Estrutura

```text
.
├── index.js
├── package.json
├── package-lock.json
└── README.md
```

## Observação

Não há testes automatizados configurados neste projeto. O script `npm test` ainda contém o comando padrão gerado pelo npm.
