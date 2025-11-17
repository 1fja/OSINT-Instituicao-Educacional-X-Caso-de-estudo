# Achados OSINT

Esta análise identificou pontos de exposição pública comuns em organizações de médio porte. Os achados abaixo representam exemplos reais de como superfícies corporativas podem se tornar amplamente visíveis.

---

## 1. WHOIS e RDAP
Foram identificados:

- Estrutura jurídica associada ao domínio  
- Contatos públicos administrativos e técnicos  
- Endereços institucionais  
- E-mails de suporte  
- Datas de criação, atualização e expiração  

**Relevância:**  
Essas informações podem ser usadas em ataques de engenharia social, spoofing ou phishing direcionado.

---

## 2. Infraestrutura Exposta
Foram encontrados:

- Vários IPs associados a subdomínios  
- Infraestrutura dividida entre Cloudflare, Vercel e provedores externos  
- Banners de tecnologias como Apache, Nginx e OpenResty  
- Subdomínios extensos e antigos  
- Painéis administrativos publicamente acessíveis (ex: `/cpanel`)  
- Arquivos info.php expondo versão do PHP  

**Relevância:**  
Painéis acessíveis e arquivos sensíveis ampliam superfície de ataque mesmo sem tentativa de acesso.

---

## 3. Tecnologias e Scripts Carregados
Foi observada uma quantidade muito grande de:

- Trackers  
- Pixels de anúncios  
- Analytics  
- SDKs de marketing  
- Ferramentas de sessão e replay (FullStory, Quantum Metric)  
- Serviços de antifraude e telemetria  
- Frameworks (React, Next.js, core-js, jQuery, etc.)

**Relevância:**  
Integrações demais aumentam risco de supply-chain e dependências frágeis.

---

## 4. Documentos Públicos
Encontrados PDFs contendo:

- Nomes e fotos de coordenação  
- Rotinas internas  
- Escalas e férias  
- Estratégias comerciais  
- Guias de pós-vendas  
- Procedimentos operacionais  

**Relevância:**  
Materiais assim podem ser usados para engenharia social extremamente convincente (golpe do funcionário).

---

## 5. Perfis Falsos em Redes Sociais
Foram identificados perfis que:

- Utilizam o nome da instituição  
- Têm poucos seguidores  
- Possuem comportamento suspeito  
- Divulgam links externos e dados pessoais  

**Relevância:**  
Possibilita fraudes, golpes, venda falsa de matrículas e danos à reputação.

---

## 6. APIs Expostas
Alguns endpoints públicos retornam respostas estáticas como `"success": true`.

**Relevância:**  
Pode indicar endpoints não autenticados que permitem enumeração ou mapeamento de serviços.
