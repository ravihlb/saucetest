# Sauce Demo - A aplicação

Sauce Demo é um site de demonstração de um sistema de e-commerce comum.
Desenvolvido pela Sauce Labs, empresa de software especializada em ferramentas para testes.

O site, então, é um ótimo candidato para projetos de testes automatizados e manuais e para praticar QA e testes de software.

## Funcionalidades Principais

- **Login e logout**
- **Página de produtos com filtros de ordenação**
- **Visualização individual de cada produto**
- **Sistema de carrinho, com adição e remoção de produtos**
- **Fluxo de checkout**

Dadas as funcionalidades listadas, os principais fluxos são: **login** e **compra**, que cobrem todas as funcionalidades.

# Escopo dos testes

Devem ser realizados testes manuais e automatizados. Estes testes devem cobrir os principais cenários, concebidos a partir de uma análise de risco baseada no funcionamento das principais funcionalidades e fluxos.

Os testes devem ser realizados através da interface visual do site www.saucedemo.com. 
Já em sua página de login, lista diversos nomes de usuários, cada um com um nome que reflete o seu status na aplicação. Usuários podem ter status bloqueado, com erro, etc. O status de cada usuário causará um efeito específico na aplicação.

# Objetivo dos testes

Garantir que o sistema de ecommerce tenha todos os principais casos de uso cobertos com testes manuais e automatizados, a fim de impedir ao máximo que bugs ou erros cheguem a ser publicados em produção e impactem negativamente a experiência dos usuários.

# Estratégia

## 1. Testes Não-Funcionais

Serão realizados testes exploratórios não-funcionais a fim de cobrir os principais casos de uso em aspectos de **usabilidade**, **interface visual** e **responsividade**.

A partir da rodada de testes exploratórios, serão documentados quaisquer bugs ou oportunidades de melhoria do sistema sob teste.

Os testes exploratórios serão realizados primeiro pois permitem encontrar uma grande parte das falhas enquanto se familiariza com a aplicação.

## 2. Testes Funcionais

Serão realizados testes funcionais manuais e automatizados, a partir dos casos de teste mais relevantes, formulados a partir dos **fluxos principais** **(login e compra)** e as funcionalidades envolvidas nestes.
