# Projeto: Jogo de Pokémon baseado em NFT

Este projeto tem como objetivo a criação de um jogo de batalhas de Pokémon utilizando NFTs no padrão ERC-721. Utilizando a tecnologia da blockchain, os Pokémons são representados como tokens não fungíveis (NFTs) que podem ser trocados, batalhados e evoluídos durante o jogo.

## Tecnologias Utilizadas

- **Solidity**: Linguagem de programação utilizada para escrever contratos inteligentes.
- **Ganache**: Ferramenta que cria uma blockchain local para desenvolvimento e testes.
- **Remix IDE**: IDE online utilizada para desenvolver e compilar contratos Solidity.
- **Metamask**: Carteira de criptomoedas usada para interagir com o contrato inteligente na blockchain.
- **IPFS**: Sistema de arquivos descentralizado para armazenar as imagens dos Pokémons.

## Etapas do Projeto

1. **Implementação do Token ERC-721**:
   - Desenvolvimento do contrato inteligente que segue o padrão ERC-721 para criar os NFTs dos Pokémons.
   - Cada Pokémon tem características como nome, nível e uma imagem armazenada no IPFS.

2. **Publicação na Blockchain**:
   - O contrato inteligente será implantado em uma blockchain (usando Ganache para testes ou uma rede pública/testnet).
   - O Metamask será usado para realizar o deploy do contrato e interagir com a blockchain.

3. **Realização de Batalhas**:
   - Implementação de uma mecânica de batalhas entre os Pokémons.
   - Cada batalha resultará em um aumento no nível dos Pokémons, permitindo sua evolução conforme ganham batalhas.

4. **Transferência de NFT entre Contas**:
   - Os Pokémons (NFTs) podem ser transferidos entre diferentes contas.
   - Utilização do método `transferFrom` do contrato ERC-721 para permitir a negociação dos Pokémons entre jogadores.

## Como Executar o Projeto

### Passo a Passo

1. **Desenvolvimento e Deploy**:
   - Abra o Remix IDE e escreva o contrato inteligente em Solidity.
   - Compile o contrato e, em seguida, faça o deploy utilizando o Metamask conectado à rede do Ganache.

2. **Armazenamento de Imagens no IPFS**:
   - Faça o upload das imagens dos Pokémons no IPFS e armazene o hash resultante no contrato.

3. **Criação de Novos Pokémons**:
   - Utilize a função `createNewPokemon` no contrato inteligente para criar novos Pokémons e distribuí-los para diferentes endereços.

4. **Batalhas**:
   - Inicie batalhas entre os Pokémons utilizando a função `battle` do contrato inteligente.

5. **Transferência de Pokémons**:
   - Transfira Pokémons entre contas utilizando a função `transferFrom` ou `safeTransferFrom`.





