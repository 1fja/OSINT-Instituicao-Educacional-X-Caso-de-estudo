# OSINT - Instituição-Educacional X - Caso deestudo
Relatório de inteligência de fontes abertas (OSINT) realizado para fins educacionais, demonstrando técnicas de coleta, organização e análise de informações públicas.
  Alvo: Instituição de Ensino (Real)
  Objetivo: Demonstrar técnicas OSINT para avaliação de exposição digital.

**NÃO FORAM REALIZADOS TESTES INVASIVOS OU AÇÕES DE EXPLORAÇÃO**
-----------------------------------------------
# Metodologia baseada em: 
Reconhecimento Passivo    
Coleta Pública  
Classificação de informações   
Avaliação de Riscos Potenciais  
Recomendações de mitigação  
------------------------------------------------
# METODOLOGIA UTILIZADA:

## FOOTPRINT INCIAL

**Identificação do domínio.**  
**WHOIS (versão pública anonimizante).**  
*Levantamento de:*  
-> ***Datas de criação/modificação.***    
->   ***Provedores envolvidos.***    
-> ***Contatos administrativos anonimizados.***    
->    ***Infraestrutura terceirizada (ex.: cloud providers).***    

# DNS e Infraestrutura
**Resolução DNS.**  
**Verificação de serviços expostos.**  
**Mapeamento de dependências tecnológicas.**  
**Identificação de provedores críticos.**  

# Tecnologias Utilizadas

Fingerprinting via:

BuiltWith  

Wappalyzer  

WhatRuns  

Serviços encontrados:

Frameworks web  

CDN  

Padrões de deploy  

Serviços externos integrados  

# Exposição de Dados

Busca por informações públicas em:

Portais governamentais  

Registros empresariais  

Notícias  

Documentos PDF indexados  

Subdomínios e infra correlata  

# Superfície Humana

Mapeamento de perfis profissionais públicos (anonimizados).

Análise de:

Formato dos e-mails corporativos  

Estrutura hierárquica pública  

Uso indevido de e-mails pessoais (se aplicável)  


# Achados Principais (Anonimizados)
WHOIS

O domínio está vinculado a uma associação educacional.  

Data de criação coerente com histórico da empresa.  

Contato administrativo revela estrutura descentralizada.  

Provedor DNS utiliza infraestrutura moderna (ex.: cloud global).  

# Tecnologias

O site depende de um provedor de hospedagem do tipo serverless cloud.  

Uso de bibliotecas JS terceiras.  

Dependências externas que geram riscos potenciais caso não monitoradas.  

Framework de desenvolvimento moderno (ex.: React / Next-like).  

# Possíveis Vulnerabilidades Potenciais

***(nenhuma exploração foi realizada, apenas avaliação teórica)***

Configurações de DNS mal monitoradas podem permitir:

subdomain takeover teórico  

hijack de apontamentos antigos  

E-mails administrativos expostos geram risco de phishing direcionado.  

Estrutura de fornecimento educativo (franquias/filiais) pode expor dados duplicados.  

Arquitetura baseada em muitos serviços externos aumenta a superfície de ataque.  

# Riscos Potenciais (Hipotético) 
**Engenharia Social:**
Padrão previsível de e-mails -> aumento de spear phishing.  
**Ataques de Reconhecimento:**
DNS e infraestrutura expostos permitem mapeamento rápido do ambiente.  
**Terceirização crítica:**  
Dependência de múltiplos provedores -> risco se algum deles falhar.  
***Exposição de funcionários:***
Perfis profissionais públicos permitem rastrear funções sensíveis.

# Recomendações Técnicas

Implementar política de higienização de WHOIS (quando aplicável).  

Reduzir informações administrativas públicas.  

Monitorar ativos DNS antigos para evitar subdomain takeover.  

Adotar política de segurança interna para e-mails públicos.  

Configurar DMARC, DKIM e SPF corretamente.  

Treinamento interno de awareness.  

# Ferramentas utilizadas 🤓
whois  

nslookup / dig  

amass (modo passivo)  

Wappalyzer / BuiltWith  

Google Dorks  

crt.sh  

hunter.io (sem se inscrição, coleta pública)  

arquivo.gov / receita / bases públicas  

# Autor
**Análise conduzida por Gabriel Salles, com foco em:**  
* OSINT aplicado
* Segurança ofensiva
* Análise de superfície digital
* Riscos Corporativos

	# Este estudo foi realizado como projeto técnico público, com propósito educacional e demonstrativo.
Nenhuma atividade invasiva foi conduzida, e os dados foram totalmente anonimizados.
