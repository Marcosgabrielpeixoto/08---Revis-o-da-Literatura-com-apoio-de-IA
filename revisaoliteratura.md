# ATIVIDADE: Revisão de Literatura e Proposição de Problemas em Aprendizado de Máquina com Apoio de IA

**Alunos:** Luanna Vitoria Benezar Viana, Marcos Gabriel Peixoto Almeida

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

- **Reconhecimento de faces e emoções** sistemas que identificam pessoas conhecidas e sinais emocionais para reduzir isolamento social e apoiar interação, incluindo leitura de rótulos de medicamentos e feedback por voz.  
- **Identificação de objetos e obstáculos** detecção em tempo real para permitir navegação autônoma e evitar colisões.  
- **Leitura de texto e OCR** extração de informação de rótulos, receitas e documentos.  
- **Sinalização viária e atravessamento** detecção de semáforos e faixas de pedestre.  
- **Reconhecimento de moeda e notas** identificação de cédulas e moedas.  

---

## Áreas de aplicação

| Área | Exemplos de implementação | Observações |
|---|---|---|
| Navegação e prevenção de colisão | Wearables com câmera + sensor de distância | Feedback sonoro em tempo real |
| Reconhecimento de objetos e cenas | Modelos YOLO / CNN | Uso em mobile e Raspberry Pi |
| Leitura de texto e OCR | OCR em smartphone | Leitura assistida |
| Reconhecimento facial e emoções | Identificação de pessoas | Apoio social |
| Trânsito e semáforos | Detecção com CNN/YOLO | Alta acurácia |
| Identificação de moedas | CNN | Alta precisão em testes |

---

## Tipos de tarefa de ML

- Classificação e detecção  
- Reconhecimento de texto  
- Regressão (estimativa de distância)  
- Geração multimodal  

---

## Principais desafios encontrados

- Latência e processamento em tempo real  
- Limitações de hardware  
- Conjuntos de dados restritos  
- Precisão em cenários reais  
- Integração de sensores e usabilidade  

---

## Etapa 2 – Coleta dos artigos

Após isso, vocês devem:
- Baixar pelo menos 8 artigos científicos em formato PDF  
- Garantir que os artigos sejam relevantes para o problema escolhido  
- Priorizar artigos recentes e de fontes confiáveis  

---

## Etapa 3 – Análise dos artigos com NotebookLM

### Prompt para uso no NotebookLM

Com base nos artigos fornecidos, responda às seguintes questões:

- Quais técnicas de aprendizado de máquina são mais utilizadas para esse problema?  
- Quais atributos (features) aparecem com mais frequência?  
- Quais são os principais desafios mencionados nos estudos?  
- Quais técnicas de pré-processamento de dados são utilizadas?  
- Quais métricas de avaliação são mais comuns?  

---

Apresente os resultados em dois formatos:

1. Um resumo estruturado em texto, sintetizando os principais pontos encontrados na literatura.  

2. Uma tabela comparativa contendo, para cada artigo:
- Nome ou referência do artigo  
- Técnica(s) utilizada(s)  
- Atributos utilizados  
- Tipo de tarefa (classificação, regressão ou agrupamento)  
- Técnicas de pré-processamento  
- Métricas de avaliação  
- Principais contribuições do artigo  

---

## Entregáveis da Etapa 3

o Resumo estruturado da literatura  

o Tabela comparativa dos artigos analisados
