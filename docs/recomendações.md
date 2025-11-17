# Recomendações Técnicas

Abaixo estão recomendações práticas e diretas baseadas nos achados expostos.

---

## 1. Revisão de Subdomínios
- Remover subdomínios obsoletos  
- Encerrar ambientes de teste  
- Desindexar info.php  
- Esconder painéis administrativos por firewall/VPN  

---

## 2. Hardening de Infraestrutura
- Adicionar HSTS, CSP, X-Frame-Options  
- Garantir `Secure` e `HttpOnly` em cookies sensíveis  
- Remover banners que exponham versões  
- Usar WAF ativo em endpoints e APIs  

---

## 3. Gestão de Documentos Públicos
- Auditar todos PDFs indexados  
- Remover arquivos contendo fotos, nomes e escala interna  
- Implementar robots.txt e headers noindex para áreas sensíveis  

---

## 4. Redução de Dependências
- Minimizar número de trackers externos  
- Avaliar necessidade de SDKs de terceiros  
- Reforçar políticas de privacidade e cookies  

---

## 5. Monitoramento de Perfis Falsos
- Criar política oficial de perfis autorizados  
- Canal para denúncia  
- Monitoramento periódico em redes sociais  
