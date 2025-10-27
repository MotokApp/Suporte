# DBL / Motok — Procedimentos Avançados

Este documento descreve os principais procedimentos técnicos e rotinas de manutenção utilizadas pelo suporte da **DBL / Motok**.  
Essas instruções devem ser seguidas apenas por atendentes de **Nível 2 ou superior**.

---

## 1. Limpeza de Cache e Dados Locais

A limpeza do cache pode resolver falhas de carregamento, lentidão e erros de login.

**Passos:**
1. Pressione `Ctrl + Shift + R` no navegador para forçar a atualização.  
2. Se o problema persistir, acesse as configurações do navegador → **Privacidade / Limpar Dados**.  
3. Marque as opções:
   - Cookies e outros dados do site  
   - Imagens e arquivos armazenados em cache  
4. Reabra o sistema e faça login novamente.  

> *Dica:* para testar em ambiente limpo, use o **modo anônimo** do navegador.

---

## 2. Reconfiguração de Ambiente `.env`

Para restaurar ou corrigir variáveis de ambiente incorretas no backend:

1. Acesse o servidor via SSH.  
2. Localize o arquivo `.env` no diretório raiz do backend.  
3. Edite com:
