# Leonardo de Paiva Souza

Analista de Tecnologia da Informação (UnB) • Mestrando em Segurança Cibernética (UnB) | Especialista em Segurança da Informação
Foco em **WordPress/PHP**, **Python + IA**, **Integração via APIs**, **Docker** **Kubernetes**, **Virtualização** e **DevSecOps**

---

## Portfólio selecionado
- **GestorOpenWRTSec** · Sistema de gerenciamento seguro para dispositivos **OpenWRT** com **API REST (Flask)**, geração de chaves/certificados, **autenticação JWT**, automação de configuração e **observabilidade via OpenSearch**.  
  ➜ https://github.com/leopsdf/GestorOpenWRTSec
- **INCLUA – Demo (WordPress Plugin)** · Plugin em PHP/WordPress com página de configurações e shortcode que consome uma API de IA.  
  ➜ https://github.com/leopsdf/wordpress-plugin-demo
- **INCLUA – API de IA (FastAPI)** · Microserviço em Python (scikit-learn) com endpoint `/predict` para classificar textos.  
  ➜ https://github.com/leopsdf/python-ai-api
- **Dockerized WordPress + IA API** · Ambiente Docker com WordPress + MariaDB + API de IA; comunicação interna por hostname (`aiapi`).  
  ➜ https://github.com/leopsdf/dockerized-wordpress-ai

> Demonstração local completa:
> ```bash
> git clone https://github.com/leopsdf/dockerized-wordpress-ai
> cd dockerized-wordpress-ai
> docker compose up -d --build
> # WordPress: http://localhost:8080
> # API:       http://localhost:8000/predict?text=serviço%20público
> ```
> No WordPress, configure o plugin **INCLUA Demo** com `http://aiapi:8000/` e crie uma página com  
> `[inclua_quote text="inclusão e equidade"]`.

---

## Tecnologias
PHP (WordPress) • Python (FastAPI, scikit-learn) • Docker/Compose • HTTP/REST • Git

---

## Contato
- GitHub: **@leopsdf**  
- LinkedIn: https://www.linkedin.com/in/leopaivasouza/
