# Avaliação a Distância 2 – Tópicos Especiais I

## Universidade do Estado de Santa Catarina (UDESC)

**Curso:** Tecnologia em Análise e Desenvolvimento de Software (TADS)
**Aluno:** Michel Luiz Ayres Pontes Junior

## Repositório

**GitHub:** https://github.com/mchayres/SRI

---

# Projeções de Embeddings

Este projeto apresenta visualizações geradas com o **TensorFlow Embedding Projector**, permitindo analisar a distribuição dos embeddings no espaço vetorial e identificar relações de similaridade entre documentos, sentenças e tokens.

## Visualizações Disponíveis

### 📄 Documentos

* **Configuração:** `config_documento.json`
* **Visualização:**
  https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/mchayres/sri/main/projecao/config_documento.json

---

### 📄📝 Sentenças e Documentos

* **Configuração:** `config_sentenca_documento.json`
* **Visualização:**
  https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/mchayres/sri/main/projecao/config_sentenca_documento.json

---

### 🔤📄 Tokens e Documentos

* **Configuração:** `config_token_documento.json`
* **Visualização:**
  https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/mchayres/sri/main/projecao/config_token_documento.json

---

### 🔤 Tokens

* **Configuração:** `config_token.json`
* **Visualização:**
  https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/mchayres/sri/main/projecao/config_token.json

---

# Análise dos Resultados

Por meio dessas projeções é possível:

* Visualizar agrupamentos formados pelos embeddings;
* Identificar relações de similaridade semântica entre documentos, sentenças e tokens;
* Explorar a estrutura vetorial dos dados processados;
* Auxiliar na interpretação e validação dos resultados obtidos durante o desenvolvimento do projeto.

Essas representações fornecem uma visão intuitiva sobre como os elementos analisados se relacionam dentro do espaço de embeddings, contribuindo para uma melhor compreensão do comportamento dos modelos utilizados.
