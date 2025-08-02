# 🏆 Análise do Campeonato Brasileiro 2023 com Python

Projeto desenvolvido durante o curso da **ADA (Academia de Dados)** em parceria com a **Caixaverso**. O objetivo foi aplicar conceitos de análise de dados utilizando **Python** e um arquivo JSON contendo todos os jogos do **Campeonato Brasileiro de 2023**.

---

## 📂 Dados utilizados

- **Arquivo:** `brasileirao-2023.json`
- **Fonte:** Fornecido no curso ADA
- **Conteúdo:** Jogos das 38 rodadas do Brasileirão, incluindo:
  - Times mandantes e visitantes
  - Gols
  - Técnicos
  - Estatísticas de jogo (chutes, posse, cartões etc.)

---

## 📌 Objetivos do projeto

- ✅ Extrair **todos os técnicos que atuaram** no campeonato
- ✅ Identificar o **técnico mais longevo de cada clube** (em número de jogos)
- ✅ Gerar a **tabela final do Brasileirão** com Pts, V, E, D, GP, GC, SG
- ✅ Gerar a **tabela de classificação parcial** até uma rodada específica (ex: rodada 25)
- ✅ Criar um **gráfico de dispersão** mostrando a relação entre:
  - Posição final no campeonato (eixo X)
  - Tempo do técnico mais longevo (eixo Y)

---

## ▶️ Executar no Google Colab

Você pode abrir o notebook clicando no botão abaixo:

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Guedes1981/projetos_ada/blob/main/Projeto_ada_brasileirao.ipynb)

> ⚠️ **Atenção:** O arquivo `brasileirao-2023.json` deve ser carregado manualmente no Colab.

---

## 📊 Resultados gerados

- 📋 Lista de técnicos presentes no campeonato
- 🏅 Lista dos técnicos mais longevos por clube, com total de partidas
- 📈 Tabela final do campeonato ordenada por desempenho
- 📅 Tabela da rodada 25 com Pts e PJ
- 📉 Gráfico de dispersão entre posição final e tempo do técnico mais longevo

---

## 🧰 Tecnologias utilizadas

- Python 3.10+
- Google Colab
- `json`, `collections`, `matplotlib`

---

## 👤 Autor

Murilo Guedes  
📍 Brasil  
🔗 [github.com/Guedes1981](https://github.com/Guedes1981)

---

## 📎 Licença

Este projeto é apenas para fins educacionais e não possui vínculo com a CBF ou a organização oficial do campeonato.

