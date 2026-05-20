# 🚢 YAKAMI NET: Protocolo DePIN de Governança Ciberfísica

[![HackWeb](https://img.shields.io/badge/HackWeb-Residência_TIC_29-blue)](#)
[![Desafio](https://img.shields.io/badge/Desafio-TrustCode-success)](#)
[![Rede](https://img.shields.io/badge/Testnet-Sepolia-purple)](#)

**Startup:** YAKAMI TECH  
**Equipe:** Erick Mattos (CEO) & Helen Araújo (CLO)  

---

## 🎯 1. O Problema: A Fricção Regulatória na Amazônia
A logística na Bacia Amazônica movimenta bilhões para o Polo Industrial de Manaus, mas sofre com um gargalo analógico: a fiscalização ambiental e portuária. Hoje, a liberação de uma embarcação depende de validações manuais de documentos da ANTAQ, NORMAM 204 (Marinha), licenças do IBAMA e protocolos da SUFRAMA. Essa burocracia gera atrasos, corrupção e inviabiliza o mercado de auditoria de Créditos de Carbono (ESG).

## 🚀 2. A Solução: Yakami NET
O **YAKAMI NET** é o primeiro Sistema de Operações Multimodais Ciberfísico da Amazônia. Desenvolvemos uma arquitetura Web3 (DePIN) que atua como um ERP Logístico e um Cartório Digital. Cruzamos telemetria inviolável de hardware (IoT) com normativas jurídicas programadas em Smart Contracts para automatizar liberações, pagamentos e incentivos sociais.

### 🧩 2.1 A Arquitetura de 4 Smart Contracts
O nosso protocolo elimina intermediários através de execução descentralizada:

1. **YakamiNodeOracle.sol (O Hardware):** Oráculo que registra on-chain a telemetria (nível do rio, clima, status do motor) captada diretamente pelos nossos nós físicos IoT na floresta.
2. **YakamiCompliance.sol (O Cartório Digital):** Motor jurídico que emite Selos Notariais Criptográficos. Cruza a telemetria com as regras da ANTAQ/Marinha e a validade de licenças ambientais, aprovando ou bloqueando rotas automaticamente.
3. **YakamiClearance.sol (A Operação):** Despachante digital que libera o Conhecimento de Transporte Eletrônico (CT-e) e executa o *split* automático de taxas portuárias (60% Porto, 30% Yakami, 10% Fundo Social).
4. **YakamiECOFlow.sol (O Incentivo):** Tokenomics deflacionária (YKM Coin). Distribui recompensas programadas aos guardiões da rede.

## 🌍 3. Impacto Real e Tração
Esta infraestrutura não é apenas teórica:
* **Hardware Validado:** Integrado ao hardware da **ECO Station EDU**, desenvolvido e validado com sucesso junto ao IREDE/IFCE, atuando como o nó físico desta rede DePIN.
* **Impacto Social (Trilha do Aprendiz):** O contrato `YakamiECOFlow` remunera diretamente os jovens que atuam como mantenedores das estações. Esta arquitetura alavanca a infraestrutura da nossa startup Trilha do Aprendiz, que já inseriu e impactou diretamente mais de 1.500 jovens na Indústria 4.0 do Polo Industrial de Manaus.

## 🛠️ 4. Como Executar (Sepolia Testnet)
A aplicação está interligada a um painel Low-Code (Mendix) que simula o painel de fiscalização governamental.

### Endereços Deployados (Sepolia):
* `YakamiNodeOracle`: `0x...` *(insira o hash aqui)*
* `YakamiCompliance`: `0x...` *(insira o hash aqui)*
* `YakamiClearance`: `0x...` *(insira o hash aqui)*
* `YakamiECOFlow`: `0x...` *(insira o hash aqui)*

**Passos para testar localmente:**
```bash
git clone [https://github.com/yakamitech/YakamiNET-Protocol.git](https://github.com/yakamitech/YakamiNET-Protocol.git)
cd YakamiNET-Protocol
npm install
npx hardhat test# YakamiNET-Protocol
Desafio: 2 (TrustCode) | Foco: Smart Contracts, Compliance Jurídico e DePIN - YAKAMÍ-NET
