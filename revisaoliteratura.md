# Revisão de Literatura — Machine Learning para Deficiência Visual

## Proposta do Trabalho
Vocês devem escolher um tema de interesse (por exemplo: saúde, educação, e-commerce, imóveis, redes sociais, segurança, entre outros).

A partir do tema escolhido, devem utilizar a ferramenta SciSpace para realizar uma revisão rápida da literatura.

---

## Prompt para uso no SciSpace
Realize uma revisão da literatura sobre o problema de machine learning para pessoas com deficiência visual que possa ser resolvido utilizando tarefas de aprendizado de máquina (classificação, regressão ou agrupamento).

A revisão deve incluir:
- Descrição clara do problema  
- Área de aplicação  
- Tipo de tarefa (classificação, regressão ou agrupamento)  
- Principais desafios encontrados na literatura  

---

## Resultados Esperados

### Questão de pesquisa
Quais são as tarefas, aplicações e desafios de machine learning em tecnologia assistiva para pessoas com deficiência visual?

---

### Strings de busca utilizadas
- ("aprendizagem de máquina" OU "aprendizagem profunda") E ("deficiente visual" OU cego) E ("tecnologia assistiva" OU "dispositivo assistivo") E (classificação OU regressão OU agrupamento)  
- ("aprendizagem de máquina"[Título/Abstract] OU "inteligência artificial"[Termos MeSH]) E ("pessoas com deficiência visual"[Termos MeSH] OU "cegueira"[Título/Abstract]) E ("dispositivos de autoajuda"[Termos MeSH] OU "tecnologia assistiva"[Título/Abstract])  
- tarefas de machine learning (classificação, regressão, clustering) para pessoas com deficiência visual: problemas de tecnologia assistiva, aplicações e desafios  

---

### Artigos selecionados
- Broadening Our View: Assistive Technology for Cerebral Visual Impairment  
- ChainerRL: A Deep Reinforcement Learning Library  
- Accessible Interactive Maps for Visually Impaired Users  
- Vision-Based Assistive Technologies for People with Cerebral Visual Impairment: A Review and Focus Study  
- Deep Learning-Powered Visual SLAM Aimed at Assisting Visually Impaired Navigation  
- Real-Time Pill Identification for the Visually Impaired Using Deep Learning  
- Group Averaging for Physics Applications: Accuracy Improvements at Zero Training Cost  
- Hexagonal Image Processing in the Context of Machine Learning: Conception of a Biologically Inspired Hexagonal Deep Learning Framework  

---

# Revisão da Literatura

## TL;DR
Soluções com machine learning para deficiência visual focam em:
- reconhecimento de objetos  
- leitura de texto  
- assistência de navegação  

Geralmente usam modelos de visão (CNN/YOLO) em dispositivos móveis ou wearables.  
Apesar dos bons resultados, ainda existem desafios como latência, hardware e dados limitados.

---

## Problemas resolvidos
- Reconhecimento de faces e emoções: identificação de pessoas e apoio social  
- Identificação de objetos e obstáculos: navegação segura em tempo real  
- Leitura de texto (OCR): leitura de rótulos, receitas e documentos  
- Sinalização viária: detecção de semáforos e faixas  
- Reconhecimento de moeda: identificação de cédulas e moedas  

---

## Áreas de aplicação

| Área | Exemplos | Observações |
|------|---------|------------|
| Navegação | Wearables + sensores | Feedback sonoro em tempo real |
| Objetos e cenas | YOLO / CNN | Uso em mobile e Raspberry Pi |
| OCR | Leitura por celular | Apoio em medicamentos |
| Reconhecimento facial | Identificação de pessoas | Apoio social |
| Trânsito | Detecção de semáforos | Alta acurácia (~90%) |
| Moedas | CNN | Até 99,2% em testes |

---

## Tipos de tarefas de ML
- Classificação e detecção: objetos, rostos, moedas  
- Reconhecimento de texto: OCR  
- Regressão: estimativa de distância  
- Multimodal: descrição de cenas  

Observação: clustering aparece pouco na literatura analisada.

---

## Principais desafios
- Latência em tempo real  
- Limitações de hardware  
- Poucos dados disponíveis  
- Diferença entre teste e mundo real  
- Integração de sensores e usabilidade  

---

# Etapa 2 — Coleta dos artigos
- Baixar pelo menos 8 artigos em PDF  
- Garantir relevância  
- Priorizar fontes confiáveis e recentes  

---

# Etapa 3 — Análise com NotebookLM

## Prompt sugerido
Com base nos artigos fornecidos, responda:

- Quais técnicas de ML são mais usadas?  
- Quais atributos aparecem com mais frequência?  
- Quais são os principais desafios?  
- Quais técnicas de pré-processamento são usadas?  
- Quais métricas são mais comuns?  

---

## Formatos de entrega

### 1. Resumo estruturado
Síntese dos principais pontos da literatura.

### 2. Tabela comparativa
Para cada artigo:
- Nome do artigo  
- Técnicas utilizadas  
- Atributos  
- Tipo de tarefa  
- Pré-processamento  
- Métricas  
- Contribuições  

---

# Entregáveis finais
- Resumo estruturado  
- Tabela comparativa dos artigos
