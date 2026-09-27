# NetCalc-IPv4

<div align="left">
  <br>
  <img width="400" alt="Calculadora de Sub-redes IPv4" src="https://github.com/user-attachments/assets/f264a9ee-22d3-4201-bd2b-74d064608ee6" />
  <br><br>
</div>

Calculadora de sub-redes IPv4 focada em performance e precisão. **[Testar agora](https://kleinmoretty-coder.github.io/NetCalc-IPv4/)**

[![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](LICENSE)

---

## Sobre o projeto

Ferramenta de interface minimalista para cálculos de sub-redes de Classe A, B e C. Aceita máscaras tanto em formato decimal quanto em notação CIDR, com validação matemática de continuidade de bits. Roda 100% no navegador, sem backend.

## Funcionalidades

- Validação estrita de endereços IPv4 e limites de octetos
- Verificação matemática de continuidade de bits para máscaras de sub-rede
- Suporte nativo para máscaras CIDR (ex: `24`) e decimais (ex: `255.255.255.0`)
- Cálculo de Endereço de Rede, Broadcast, Tamanho do Bloco e Faixa de IPs Úteis
- Prevenção de erros do usuário em tempo real

## Exemplo

```
IP:      192.168.10.85
Máscara: 24  (ou 255.255.255.0)
```

## Tecnologias

- HTML5
- Tailwind CSS
- JavaScript (Vanilla)

## Estrutura

```
.
├── index.html
├── app.js
└── favicon.png
```

## Como rodar

A forma mais rápida é usar a versão hospedada:

**[kleinmoretty-coder.github.io/NetCalc-IPv4](https://kleinmoretty-coder.github.io/NetCalc-IPv4/)**

Para rodar localmente:

```bash
git clone https://github.com/kleinmoretty-coder/NetCalc-IPv4.git
cd NetCalc-IPv4
# Abra index.html no navegador
```
