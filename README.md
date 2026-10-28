## Integrantes
| Nome       | RA       | Papel                  |
|-----------|---------|-----------------------|
| Pedro Faria | 2224201517 | LÍDER/PESQUISADOR |
| Rian Mascarenhas | 2224106376 | DESENVOLVEDOR/DESIGNER |
| Buno Gil Ferreita | 2224104380 | APRESENTADOR/REDATOR |

# 🚗 CartBot V2
> **O seu assistente automotivo inteligente.**

O **CartBot V2** é um assistente digital voltado para o setor automotivo, desenvolvido com o objetivo de oferecer uma interface interativa e moderna para auxiliar usuários em tarefas relacionadas a veículos — seja simular atendimentos, responder dúvidas, ou facilitar interações com um sistema de suporte.

Nosso vídeo no YouTube (Se inscreve láaaaaaaaaaa): https://www.youtube.com/watch?v=aIhegVi3pVA

---
## 🧠 Funcionalidades

- 💬 Interface de chat interativa  
- ⚙️ Respostas automáticas simulando um assistente virtual  
- 🎨 Design moderno com HTML, CSS e JavaScript  
- 🚀 Estrutura leve e fácil de rodar localmente  

---

## 🧩 Tecnologias Utilizadas

| Tecnologia | Função |
|-------------|--------|
| **HTML5** | Estrutura da interface |
| **CSS3** | Estilos e layout responsivo |
| **JavaScript (ES6)** | Lógica e interação do chatbot |
| **Git / GitHub** | Controle de versão e hospedagem do código |

---
---

## 🤖 Abordagem de Inteligência Artificial

A IA utilizada é o modelo **Gemini 2.0 Flash**, da **Google AI**, por ser uma tecnologia de **geração de linguagem natural** (Generative AI).  
Ela permite criar respostas coerentes e contextualizadas para perguntas sobre o setor automotivo.  
O modelo já vem **pré-treinado** em uma base extensa de textos técnicos e gerais, dispensando treinamento manual.

**Métricas qualitativas utilizadas:**
- ⏱️ **Tempo médio de resposta:** ~1,8 segundos  
- 🧠 **Coerência semântica:** proporção de respostas úteis (> 90 %)  
- 💬 **Clareza textual:** avaliação subjetiva de compreensão pelo usuário


## ⚙️ Como Executar o Projeto no PC
**Pré-Requisitos PC(WINDOWS / macOS / LINUX)**
   - Node.js ou Python3 instalado
   - Navegador (Chrome, Edge, Firefox...)
   - (IMPORTANTE) API Key do Google Ai Studio

1. **Clone este repositório:**
   ```bash
   git clone https://github.com/PHFaria05/CartBot_V2.git
2. **Abra o terminal na pasta do projeto**
   - cd /caminho/para/CartBot_V2
     
3. Abra o arquivo App.js e substitua a API key
   - const API_KEY = 'REPLACE_WITH_YOUR_KEY';
   - const API_KEY = 'SUA_CHAVE_API_AQUI';
     
4. rode o servidor em um local (porta 8000)
   - python -m http.server 8000
    ou usando Node
   - npx serve . -1 8000 

5. abra o navegador e acesse:
   - https://localhost:8000


## ⚙️ Como Executar o Projeto no ANDROID
**Pré-Requisitos ANDROID (Termux)**
1. Istalar termux (play store)

2. **Clone o repositorio**
  - git clone https://github.com/PHFaria05/CartBot_V2.git

3. **Dentro do Termux dê autorização de acesso ao Storage e instale o python** 
   - termux-setup-storage  (permitir)
   - pkg update -y && pkg upgrade -y
   - pkg install python
     
4. **Entre na pasta do bot**
   - cd caminho/para/CartBot_V2

5. **Iniciar o servidor**
   - python -m http.server 8000

6. **Abra o navegador e acesse:**
   - http://localhost:8000

## 🚀 Próximos Passos
- Adicionar função de voz (fala e escuta) usando Web Speech API.  
- Criar armazenamento de histórico em nuvem (Firebase).  
- Otimizar interface para dispositivos móveis.

---

## 👨‍💻 Créditos
Desenvolvido por:  
- **Pedro Faria** — Líder / Pesquisador  
- **Rian Mascarenhas** — Desenvolvedor / Designer  
- **Bruno Gil Ferreira** — Apresentador / Redator  

---

## ⚖️ Licença
Projeto educacional — **MIT License**

---

## 📊 Resultados e Gráficos (Etapa 5)

```
CartBot_V12/
│
├── index.html
│   └── Estrutura da interface principal do chat:
│       - Sidebar (histórico, tema)
│       - Área de conversas
│       - Input de mensagens
│
├── app.js
│   ├── Integração com API Google Gemini
│   ├── Sistema de múltiplas conversas
│   ├── Função de criar nova conversa
│   ├── Função de excluir conversa (🗑️)
│   ├── Renderização de mensagens e histórico
│   ├── Sistema de tema claro/escuro
│   └── Tipagem e animação "digitando..."
│
├── style.css
│   ├── Estilização das bolhas de chat
│   ├── Animação de fade e typing
│   ├── Estilo de dark mode
│   └── Regras para versão mobile
│
├── package.json
│   └── Lista dependências do projeto (ex: @google/genai)
│
├── package-lock.json
│   └── Registro exato das versões das dependências
│
└── README.md
    └── Documentação do projeto
```

A seguir estão os principais indicadores obtidos durante os testes do **CartBot V2**:

| Gráfico | Descrição |
|----------|------------|
| ![Tempo de Resposta](CartBot_V2/figuras/tempo_resposta.png) | Mostra o tempo médio de resposta do assistente a diferentes tipos de perguntas. |
| ![Tipos de Dúvidas](CartBot_V2/figuras/tipos_duvidas.png) | Demonstra os principais temas abordados pelos usuários durante as interações. |
| ![Coerência das Respostas](CartBot_V2/figuras/coerencia.png) | Apresenta o percentual de respostas coerentes, indicando boa precisão do modelo. |
| ![Evolução do Projeto](CartBot_V2/figuras/evolucao.png) | Compara os indicadores da versão inicial (V1) com a versão atual (V2). |
| ![Satisfação dos Usuários](CartBot_V2/figuras/satisfacao.png) | Mostra a avaliação média dos usuários após o uso do chatbot. |

> Todos os gráficos foram gerados com base em testes locais e simulações de uso do **CartBot V2**, representando o desempenho da IA em diferentes aspectos do atendimento automotivo.
