# Blockchain Fundamentals

Smart contracts são um conjunto de instruções executados de maneira descentralizadas sem a necessidade de um terceiro intermediando nada.

A principal diferença entre o bitcoin e o ethereum é a questão dos smart contracts, a bitcoin é basicamente um deposito de valor monetário enquanto a etherium é isso somado com os acordos descentralizados o que torna ele algo com maiores utilidades 

### Oracles

A blockchain não consegue interagir com bases de dados de fora dela mesma, e é essa a função dos oracles eles servem dados para as transações da blockchain, sendo assim servindo como um intermediário 

Oracles são qualquer dispositivos que interagem com o mundo off-chain para prover dados externos ou computar smart contracts .

Para manter nossa aplicação verdadeiramente descentralizada nós não podemos trabalhar com apenas um oracle e sim com um oracle descentralizado, com isso nós temos nossos Hybrid smart contracts, que são uma mistura de on-chain e off-chain agreements, ou seja logicas na blockchain e fora dela para formar nossos contratos, porém ainda mantendo tudo descentralizado.

O oracle usado de exemplo no curso é o chainlink. Ela é o mais popular dentre eles e funciona em multiplas outras chains.

Dapp = Descentralized application 

### Smart Contracts

Eles criam contratos em que não precisamos confiar que serão mantidos, basicamente eles criam uma promessa inquebrável.

Basicamente, tudo que fazemos na nossa vida é baseado em acordos e contratos, que podemos chamar de promessas. 

Defi- Descentralized Financial, com isso nós podemos ver trocas de maneira completamente transparente e confiável, pois qualquer um pode ver as transferências, porém é impossível ver quem fez a transação em si, o que nos garante transparência.

DAOs- São organizações autonomas descentralizadas, NFTs são tokens não fundiveis, ou digital assets.

### Gas concept

GAs é uma unidade de medica computacional que consiste em, quanto maior a complexidade da transação mais gas você tem que pagar. 

O gas é usado para calcular o valor da nossa transaction fee, a quantidade de gas usado vezes o valor do gas da exatamente o valor da transaction fee

![Untitled](Solidity%20adb60d277a5b4d6986f72d3db9822cda/Untitled.png)

Cada blockchain tme seu modo de calcular esse gasto, este é baseado na ethereum, o principal conceito por tras disso é de que todas as vezes que voce faz uma transação você tem que pagar uma parcela em gas.  

## Solidity

Durante o curso usamos um compilador chamado remix ethereum, dentro dele temos uma pasta chamada de contracts que recebe o arquivo do contrato.

Todo contrato com solidity começa especificando a versão do mesmo. Isso é feito usando a keyword pragma solidity

```solidity
pragma solidity 0.8.8;
```

para selecionar qualquer versão acima da que colocamos basta colocar um acento agudo na frente da versão.

Para escrever um contrato nós só precisamos usar a palavra chave contract passar o nome do contrato e abrir chaves, assim temos nosso primeiro contrato vazio.

```solidity
//SPDX-License-Identifier: MIT
pragma solidity 0.8.8;

contract simpleStorage {
    
}
```