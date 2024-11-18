---
layout: home
title: "Bem-vindo ao Meu Site Pessoal"
---

![Banner](assets/images/banner.jpg)

## Olá, eu sou [Seu Nome](https://github.com/leitaofilho)

Sou desenvolvedor e apaixonado por criar soluções tecnológicas inovadoras. Explore meus projetos, leia meu blog e entre em contato para colaborações.

---

### Projetos Recentes
- **[Projeto 1](https://github.com/leitaofilho/projeto1):** Descrição do projeto 1.
- **[Projeto 2](https://github.com/leitaofilho/projeto2):** Descrição do projeto 2.
- **[Projeto 3](https://github.com/leitaofilho/projeto3):** Descrição do projeto 3.

---

### Blog
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%d de %B de %Y" }}
{% endfor %}
