# Testes de API com Postman – JSONPlaceholder

## 📌 API utilizada
JSONPlaceholder (https://jsonplaceholder.typicode.com)

## 📂 Estrutura
- `tests/collection.json` → coleção Postman com 6 cenários de teste

## ▶️ Como executar
1. Importar a coleção no Postman
2. Rodar manualmente ou usar o Collection Runner
3. Para regressão, instalar [Newman](https://www.npmjs.com/package/newman):
   ```bash
   newman run tests/collection.json
---

## 📋 Respostas do Exercício 2

1. **Quantas suítes de testes você desenvolveu?**  
   - 1 suíte (coleção Postman com 6 casos).

2. **Os testes desenvolvidos são manuais ou automatizados?**  
   - Automatizados (usando scripts no Postman).

3. **Onde os testes se localizam na pirâmide apresentada?**  
   - Na camada de **serviço/API**.

4. **Os testes desenvolvidos são funcionais ou não-funcionais?**  
   - São **funcionais**.

5. **Alguns dos testes desenvolvidos são testes Fim-a-Fim (End-To-End)?**  
   - Não, são testes isolados de endpoints.

6. **O que se deve fazer para que os testes desenvolvidos funcionem em modo regressão?**  
   - Automatizar com Newman, versionar no GitHub e rodar após alterações.
