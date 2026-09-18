# 🔍 buscaVagas

O **buscaVagas** é um sistema agregador e *web scraper* de oportunidades de emprego desenvolvido em **Go (Golang)**. O objetivo principal da aplicação é consultar múltiplos portais de recrutamento e páginas de vagas de forma concorrente e ultrarrápida, consolidando os resultados em um único local.

---

## 🚀 Motivação e Objetivos

* **Alta Performance & Concorrência:** Aproveitar as **Goroutines** e **Channels** nativos do Go para realizar requisições e *scraping* em paralelo, reduzindo drasticamente o tempo total de busca.
* **Baixo Consumo de Recursos:** Manter uma pegada de memória RAM extremamente reduzida (~15MB-30MB), viabilizando o *deploy* em ambientes de hospedagem com custo mínimo ou nulo.
* **Consolidação de Vagas:** Automatizar a coleta de dados de diferentes plataformas em uma interface/API única.

---

## 🛠️ Tecnologias Utilizadas

* **[Go (Golang)](https://go.dev/):** Linguagem principal do projeto.
* **Goroutines & Channels:** Para processamento concorrente de requisições.
* **Colly / GoQuery / `net/http`:** Para navegação, extração e parse dos dados HTML das páginas de vagas.

---

## 📌 Próximos Passos (Roadmap)

- [ ] Estruturação inicial do projeto em Go.
- [ ] Implementação das Goroutines para *scraping* concorrente em portais alvo.
- [ ] Tratamento e parse das informações das vagas (título, empresa, link, localização).
- [ ] Criação dos endpoints para consulta das vagas agregadas.
- [ ] Configuração do ambiente de *deploy* leve.

