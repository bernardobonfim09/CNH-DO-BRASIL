# CNH Master 1500 — Simulado Completo com Revisão Espaçada

Simulado interativo e completo para a **CNH (Carteira Nacional de Habilitação) do Brasil**, com um sistema de revisão espaçada inspirado na metodologia Anki. Aplicativo web totalmente autossuficiente que roda em um arquivo HTML único.

---

## 🎯 Funcionalidades Principais

### 📝 **Simulado Adaptativo**
- **1.500 questões oficiais** do DETRAN
- **30 questões por simulado** com seleção inteligente baseada em:
  - Seu desempenho anterior (erros/acertos)
  - Nível de dificuldade (Fácil, Intermediário, Difícil)
  - Categorias de conteúdo (Sinalização, Legislação, Direção Segura, etc.)
- Sistema que **prioriza matérias fracas** enquanto consolida pontos fortes
- Feedback imediato após cada resposta

### 🔁 **Revisão Espaçada com Anki**
- Algoritmo **FSRS-inspired DSR** para espaçamento otimizado
- 4 níveis de confiança ao revisar cada card:
  - 🔴 **Difícil** (1) — Recome como novo em 1 min
  - 🟠 **Normal** (2) — Aumenta estabilidade
  - 🟢 **Bom** (3) — Avança para revisão
  - 🔵 **Fácil** (4) — Espaçamento máximo
- Estados dos cards: **Novo** → **Aprendendo** → **Revisão**
- Meta de retenção configurada em **90%**
- Filas automáticas: Aprendizagem vencida → Revisão vencida → Novos cards
- Intervalo inteligente baseado em sua performance

### 📊 **Dashboard e Análise de Desempenho**
- **Métricas em tempo real:**
  - Total de questões respondidas
  - Taxa de acerto geral
  - Desempenho por módulo
  - Desempenho por categoria
  - Desempenho por nível de dificuldade
- **Matriz de desempenho** categorizando questões como:
  - ✅ **Dominadas** — acima de 75% de acerto
  - ⚠️ **Intermediárias** — entre 50-75%
  - ❌ **Fraco** — abaixo de 50%

### 📖 **Teoria Estruturada**
- Conteúdo teórico organizado por:
  - 7 partes principais
  - Múltiplos módulos
  - Mais de 20 categorias (Sinalização, Legislação, Trânsito, Primeiros Socorros, etc.)
- Acesso rápido via índice lateral (TOC)
- Detalhes expansíveis por tópico
- Explicações detalhadas para cada conceito

### 🗓️ **Calendário de Estudos (Insights)**
- Visualiza sua **atividade diária** de revisão
- Contador de cards revisados por dia
- Identifica padrões de estudo
- Gráfico de retenção por rating
- Rastreamento de progresso ao longo do tempo

### 🗂️ **Histórico de Respostas**
- Filtros por: Todas as respostas | Apenas erros | Apenas acertos
- Ordena por frequência de erro
- Detalha módulo, categoria e dificuldade de cada questão
- Facilita revisão de conteúdo fraco

### 💾 **Backup e Importação**
- **Exportar progresso** em JSON
- **Importar backup** anterior
- Sincroniza 1.500 questões automaticamente
- Dados totalmente locais (LocalStorage) — sem sincronização online

---

## 🚀 Como Usar

### 1️⃣ **Fazer um Simulado**
- Clique em **📝 Simulado**
- Responda as 30 questões
- O sistema mostra se você acertou/errou **imediatamente**
- Veja feedback sobre cada questão
- Ao final, seus erros são registrados para reforço futuro

### 2️⃣ **Revisar com Anki**
- Clique em **🔁 Revisão Espaçada**
- Veja cards em 3 filas:
  - 🆕 **Novo** — nunca revisado
  - 📚 **Aprendendo** — em processo de memorização
  - ✔️ **Revisão** — consolidado, precisa manutenção
- Clique no card para revelar a resposta
- Classifique sua performance (1–4)
- Sistema recalcula próxima revisão automaticamente

### 3️⃣ **Estudar Teoria**
- Clique em **📖 Teoria**
- Navegue por módulo e tópico no painel lateral
- Leia explicações detalhadas
- Conceitos-chave destacados
- Correlação com questões práticas

### 4️⃣ **Monitorar Progresso**
- **📊 Dashboard**: Visão geral de performance por categoria/dificuldade
- **🗓️ Insights**: Calendário de estudos e gráficos de retenção
- **🗂️ Histórico**: Revise questões erradas com filtros

---

## 🔧 Sistema de Pontuação e Adaptação

O algoritmo considera múltiplos fatores para personalizar sua experiência:

| Fator | Peso | Descrição |
|-------|------|-----------|
| **Taxa de erro pessoal** | Alto | Questões que você erra aparecem com mais frequência |
| **Peso da questão** | Médio | Algumas categorias têm prioridade no currículo |
| **Histórico Anki** | Alto | Cards com muitos lapsos são reforçados |
| **Confiança geral** | Médio | Após 80 questões respondidas, o sistema ajusta prioridades |
| **Estágio por categoria** | Alto | Sistema detecta se você ainda está na base ou consolidação |

**Estágios de aprendizado:**
- **Base** — Consolidar fáceis (< 5 questões ou < 75% acerto)
- **Intermediário** — Trabalhar intermediárias (após dominar fáceis)
- **Avançado** — Questões difíceis (após 80% em tudo)

---

## 💡 Diferenciais

✅ **Completamente offline** — funciona sem internet (dados em LocalStorage)  
✅ **Arquivo único** — um HTML com tudo (CSS + JS + 1.500 questões embutidas)  
✅ **Algoritmo científico** — baseado em Anki e FSRS para máxima retenção  
✅ **Interface moderna** — design responsivo com tema visual profissional  
✅ **Sem propagandas** — sem paywall, sem tracking  
✅ **Compatível com mobile** — funciona em qualquer navegador  
✅ **Foco em pontos fracos** — prioriza automaticamente suas dificuldades  

---

## 🎓 Estrutura de Conteúdo

- **1.500 questões** oficiais do DETRAN
- **7 partes** de estudo
- **20+ categorias**, incluindo:
  - 🚦 Sinalização e Placas
  - ⚖️ Legislação de Trânsito
  - 🚗 Direção Segura
  - 🏥 Primeiros Socorros
  - ⚙️ Mecânica Básica
  - 🌍 Meio Ambiente e Sustentabilidade
  - E mais...
- **3 níveis** de dificuldade (Fácil, Intermediário, Difícil)
- **Teorias correlatas** integradas para cada questão

---

## 🛠️ Tecnologia

- **Frontend:** HTML5 + CSS3 + JavaScript Vanilla
- **Storage:** LocalStorage (Browser)
- **Algoritmo:** FSRS-inspired (Spaced Repetition)
- **Responsividade:** Totalmente adaptável para desktop, tablet e mobile
- **Fontes:** Inter, Lora, JetBrains Mono

---

## 📊 Dados Salvos Localmente

Todo progresso é salvo no **LocalStorage** do seu navegador:
- ✅ Histórico de respostas (corretas/incorretas)
- ✅ State dos cards Anki (novo, aprendendo, revisão)
- ✅ Intervalos de revisão customizados
- ✅ Datas de última revisão
- ✅ Estabilidade e dificuldade de cada card
- ✅ Log completo de cada revisão

**Nenhum dado é enviado para servidores.** Tudo fica no seu computador/celular.

---

## 🎯 Meta de Estudos Recomendada

Para melhor aproveitamento do sistema:
- **Simulados:** 2-3 por semana (30 questões = ~20 min)
- **Revisão Anki:** 15-20 min diários (para consolidar)
- **Teoria:** Conforme necessário (quando enfrentar dificuldades)

Com essa frequência, você pode dominar o conteúdo em **2-4 semanas**.

---

## 📝 Exemplo de Uso

1. **Dia 1:** Faça seu primeiro simulado (📝) → identifique pontos fracos
2. **Dias 2-3:** Estude a teoria (📖) dos tópicos difíceis
3. **Dia 4:** Revise com Anki (🔁) por 15 min
4. **Semana 2:** Faça outro simulado, compare com anterior
5. **Semana 3:** Intensifique revisão nos tópicos com < 75% de acerto
6. **Semana 4:** Faça simulado final, celebrate seu progresso! 🎉

---

## 📱 Compatibilidade

- ✅ Chrome, Firefox, Safari, Edge (desktop)
- ✅ Chrome Mobile, Firefox Mobile, Safari Mobile
- ✅ Tablets (iPad, Android)
- ✅ Responsivo para telas de 320px até 4K

---

## 🚀 Como Usar o Arquivo

1. **Baixe** `cnh_master_1500_anki_calendario_backup_v7_redesign.html`
2. **Abra** no navegador (funciona como arquivo local)
3. **Comece** a estudar imediatamente
4. Seu progresso é **salvo automaticamente**

Nenhuma instalação necessária!

---

## 📞 Dicas Finais

- 💾 **Faça backup regularmente** (Menu → Exportar)
- 🔄 **Não interrompa a revisão** — a retenção depende de consistência
- 📈 **Acompanhe seu progresso** no Dashboard
- 🎯 **Foco em fraco:** o sistema prioriza automaticamente suas dificuldades

**Boa sorte na prova! 🚗✨**
