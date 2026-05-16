# Alvaro Bandim
### Desenvolvedor Python | Automação (RPA) | Engenharia de Dados Básica

Sou um desenvolvedor focado em construir soluções de backend que resolvem gargalos operacionais e reduzem custos corporativos. Minha especialidade é transformar processos manuais, repetitivos e suscetíveis a falhas humanas em esteiras de dados (Pipelines ETL) e integrações automatizadas.

## Stack Tecnológica e Competências

* **Linguagens:** Python 3, SQL
* **Engenharia de Dados (ETL):** Manipulação tabular com Pandas, higienização de dados, exportação (Openpyxl) e persistência relacional (SQLite).
* **Automação & Web Scraping:** Extração de dados não-estruturados, navegação em DOM HTML (BeautifulSoup, Requests), controle de throttling.
* **Integrações de Rede & APIs:** Arquitetura Baseada em Eventos (Event-Driven), consumo de APIs REST, disparo de webhooks e mensageria (Telegram Bot API, SMTP).
* **Ferramentas e Arquitetura:** Git, GitHub, VS Code, Controle de Ambientes Virtuais e Variáveis de Ambiente (.env).

---

## Projetos em Destaque (Portfólio Aplicado)

### 1. Market Intelligence Pipeline (Web Scraper & Mensageria)
Sistema autônomo de inteligência de mercado. Realiza varredura paginada em catálogos web, higieniza strings monetárias e aplica filtros de negócios. Os dados aprovados são persistidos em um banco de dados **SQLite** (com constraint de unicidade) que atua como gatilho para disparar **Push Notifications** em tempo real via Telegram.
* **Tech:** Python, BeautifulSoup, SQLite, Event-Driven Architecture.

### 2. Helpdesk NOC Bot (Assistente de Suporte)
Solução de backend para automação de atendimento (URA) e triagem de incidentes de TI corporativos. O bot gerencia estados de conversa (FSM), estrutura os payloads descritivos dos usuários e roteia alertas emergenciais diretamente para os canais da equipe de infraestrutura (NOC).
* **Tech:** Python, Telegram Bot API, Polling Assíncrono.

### 3. Automação de Back-office (Consolidação ETL e Reports)
Agente de integração construído para substituir rotinas manuais de controladoria. O script realiza a ingestão de múltiplas planilhas de filiais, utiliza engine de dados para limpeza e sumarização de métricas, formatando os resultados em relatórios executivos que são despachados automaticamente via protocolo seguro SMTP.
* **Tech:** Python, Pandas, smtplib (Network/Email).

---

## Contato e Networking
- **LinkedIn:** https://www.linkedin.com/in/alvarobandim/
- **E-mail:** alvarobandim@hotmail.com
