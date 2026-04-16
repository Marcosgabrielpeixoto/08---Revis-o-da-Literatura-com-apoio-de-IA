# ATIVIDADE: Revisão de Literatura e Proposição de Problemas em Aprendizado de Máquina com Apoio de IA

**Alunos:** Luanna Vitoria Benezar Viana, Marcos gabriel Peixoto Almeida

## Etapa 1 – Revisão da literatura com SciSpace

Vocês devem escolher um tema de interesse (por exemplo: saúde, educação, e-commerce, imóveis, redes sociais, segurança, entre outros).

A partir do tema escolhido, devem utilizar a ferramenta SciSpace para realizar uma revisão rápida da literatura.

### Prompt para uso no SciSpace

Realize uma revisão da literatura sobre o problema de machine learning para pessoas com deficiência visual que possa ser resolvido utilizando tarefas de aprendizado de máquina (classificação, regressão ou agrupamento).

A revisão deve incluir:
- descrição clara do problema  
- área de aplicação  
- tipo de tarefa (classificação, regressão ou agrupamento)  
- quais são os principais desafios encontrados na literatura  

---

Após a execução do prompt, vocês devem apresentar:

### o Questões de pesquisa geradas
- Quais são as tarefas, aplicações e desafios de machine learning em tecnologia assistiva para pessoas com deficiência visual?  
- Em quais áreas de aplicação essas soluções de machine learning são mais utilizadas no contexto de tecnologia assistiva para pessoas com deficiência visual?  

---

### o Strings de busca utilizadas pela ferramenta
- ("aprendizagem de máquina" OU "aprendizagem profunda") E ("deficiente visual" OU cego) E ("tecnologia assistiva" OU "dispositivo assistivo") E (classificação OU regressão OU agrupamento)  
- ("aprendizagem de máquina"[Título/Abstract] OU "inteligência artificial"[Termos MeSH]) E ("pessoas com deficiência visual"[Termos MeSH] OU "cegueira"[Título/Abstract]) E ("dispositivos de autoajuda"[Termos MeSH] OU "tecnologia assistiva"[Título/Abstract])  
- tarefas de machine learning (classificação, regressão, clustering) para pessoas com deficiência visual: problemas de tecnologia assistiva, aplicações e desafios  

---

### o Lista dos 8 artigos escolhidos
1. Broadening Our View: Assistive Technology for Cerebral Visual Impairment  
2. ChainerRL: A Deep Reinforcement Learning Library  
3. Accessible Interactive Maps for Visually Impaired Users  
4. Vision-Based Assistive Technologies for People with Cerebral Visual Impairment: A Review and Focus Study  
5. Deep Learning-Powered Visual SLAM Aimed at Assisting Visually Impaired Navigation  
6. Real-Time Pill Identification for the Visually Impaired Using Deep Learning  
7. Group Averaging for Physics Applications: Accuracy Improvements at Zero Training Cost  
8. Hexagonal Image Processing in the Context of Machine Learning: Conception of a Biologically Inspired Hexagonal Deep Learning Framework  

---

### o Texto de revisão da literatura gerado pela ferramenta

## TL;DR

Soluções com machine learning para deficiência visual focam em reconhecimento de objetos, leitura de texto e assistência de navegação, geralmente usando modelos de visão (CNN/YOLO) em dispositivos móveis ou wearables. Há bons resultados em testes controlados, mas desafios de latência, hardware e conjuntos de dados persistem.

---

## Problemas resolvidos

- Reconhecimento de faces e emoções  
- Identificação de objetos e obstáculos  
- Leitura de texto (OCR)  
- Sinalização viária  
- Reconhecimento de moeda  

---

## Áreas de aplicação

| Área | Exemplos de implementação | Observações |
|---|---|---|
| Navegação | Wearables + sensores | Feedback sonoro |
| Objetos | YOLO / CNN | Uso mobile |
| OCR | Smartphone | Leitura assistida |
| Facial | Identificação | Apoio social |
| Trânsito | CNN/YOLO | Alta acurácia |
| Moedas | CNN | Alta precisão |

---

## Tipos de tarefa de ML
- Classificação e detecção  
- Reconhecimento de texto  
- Regressão  
- Multimodal  

---

## Principais desafios encontrados
- Latência  
- Hardware limitado  
- Poucos dados  
- Diferença entre teste e real  
- Integração de sensores  

---

## Etapa 2 – Coleta dos artigos

- Baixar pelo menos 8 artigos científicos em PDF  
- Garantir relevância  
- Priorizar fontes confiáveis  

---

## Etapa 3 – Análise dos artigos com NotebookLM

### Prompt para uso no NotebookLM

Com base nos artigos fornecidos, responda:

- Quais técnicas de aprendizado de máquina são mais utilizadas para esse problema?  
- Quais atributos (features) aparecem com mais frequência?  
- Quais são os principais desafios mencionados nos estudos?  
- Quais técnicas de pré-processamento de dados são utilizadas?  
- Quais métricas de avaliação são mais comuns?  

---

## Resultados

### o Resumo estruturado da literatura

A literatura revisada destaca uma transição significativa de métodos tradicionais para técnicas de Deep Learning para resolver problemas de navegação e identificação para deficientes visuais.

- Técnicas de aprendizado de máquina: uso de YOLO (especialmente YOLOv8), Visual SLAM, redes neurais profundas e aprendizado por reforço (DQN, PPO, SAC).  
- Atributos: keypoints, descritores visuais, cor, formato e marcações.  
- Desafios: ambientes complexos, iluminação, sobrecarga sensorial e limitações de hardware.  
- Pré-processamento: redimensionamento de imagens, data augmentation, escala de cinza.  
- Métricas: mAP, precisão, recall, RMSE e ATE.  

---


## Entregáveis da Etapa 3

o Resumo estruturado da literatura


o Tabela comparativa dos artigos analisados


| Artigo | Técnica(s) | Atributos | Tipo de Tarefa | Pré-processamento | Métricas | Contribuições |
|---|---|---|---|---|---|---|
| Artigo 1 e 4 | Revisão (CNN, YOLO) | Sinais fisiológicos e imagens | Classificação | N/A | N/A | Identificação de desafios |
| Artigo 2 | DRL (DQN, PPO) | Estados do ambiente | Regressão | Normalização | Score | Biblioteca RL |
| Artigo 5 | SLAM + DL | Keypoints | Regressão | Grayscale | RMSE | Navegação robusta |
| Artigo 6 | YOLOv8 | Cor, formato | Classificação | Augmentation | mAP | App de pílulas |
| Artigo 7 | Group Averaging | Variáveis físicas | Regressão | Transformações | RMSE | Melhoria de precisão |
| Artigo 8 | H-CNN | Pixels hexagonais | Classificação | Interpolação | Acurácia | Novo framework |

---
