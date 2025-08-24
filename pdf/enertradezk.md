# Projeto: EnerTradeZK

**EnerTradeZK** é uma corretora descentralizada de ativos energéticos tokenizados, desenvolvida durante o Hackathon *O Grande Código* da NearX, e vencedora de premiação por inovação.

## Objetivo

Permitir que qualquer cidadão participe do mercado livre de energia elétrica de forma segura, acessível e com privacidade via ZK-Proofs.

## Tecnologias
- Blockchain: Ethereum (Sepolia), NEAR
- Smart Contracts: Solidity + Hardhat
- Backend: Node.js + Express + SnarkJS
- Frontend: React + Ethers.js
- ZK: Circom + SnarkJS
- Carteira: MetaMask

## Destaques

```solidity
function consumeEnergy(address user, uint256 amount, Proof memory proof) public {
    require(verifyProof(proof), "Proof inválido");
    ...
}
```