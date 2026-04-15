# Doma CRM

> CRM Imobiliário com Motor de Recomendação Inteligente
> Projeto Técnico — Avaliação 01 | Ciência da Computação | 2026

---

## Problema Resolvido

Corretores de imobiliárias gerenciam dezenas de clientes e centenas de imóveis **sem nenhum sistema**. O matching entre cliente e imóvel é feito na memória, resultando em oportunidades perdidas e clientes mal atendidos.

**Doma CRM** resolve isso capturando o perfil de interesse do cliente de forma estruturada e calculando automaticamente um **score de compatibilidade** com os imóveis do portfólio.

---

## Stack Tecnológico

| Camada | Tecnologia |
|---|---|
| Frontend | React.js + Tailwind CSS |
| Backend / API | Python 3.11 + Django REST Framework |
| Motor de Matching | scikit-learn (score ponderado por atributos) |
| Banco de Dados | PostgreSQL |
| Autenticação | JWT (djangorestframework-simplejwt) |
| Servidor | Nginx + Gunicorn |
| Infra | Docker + Docker Compose |

---

## Funcionalidades

- Cadastro de clientes com perfil estruturado (bairro, preço, metragem, tipo, quartos)
- Motor de matching: retorna top-5 imóveis mais compatíveis por cliente
- Histórico de interações por cliente
- Alertas automáticos de follow-up
- Dashboard gerencial com funil de vendas e KPIs

---

## Algoritmo de Matching

score = (0.35 x preco) + (0.25 x bairro) + (0.20 x metragem) + (0.12 x tipo) + (0.08 x quartos)

---

## Links de Evidências

| Artefato | Link |
|---|---|
| Repositório GitHub | https://github.com/joaovictorcarneirog/doma-crm |
| Protótipo Canva | https://www.canva.com/d/OHvV1bGK4BCXdbP |

---

## Autor

**Doma** | Ciência da Computação
assessoriadoma.hub@gmail.com

*Avaliação 01 — Introdução à Infraestrutura de TI | 2026*
