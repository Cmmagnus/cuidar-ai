# 🌍 Cuidar.AI · Inteligência Artificial para Cidadania e Verdade

**"Em um mundo afogado em desinformação, o Cuidar.AI é o farol que guia para a verdade e a inclusão."**

[![Imersão Alura](https://img.shields.io/badge/Imersão%20Alura-2025-blue?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA0AAAAQCAYAAADNo/U5AAAAWUlEQVQoz2NgQAL/j8fExMT8f4rIyMh/gZGRkYkBNpA7a1JSUlLpDhrYJSUl+N+JiYmBhYGAfAxMTEwMOzU1NRXo7e0dTgM8LSwsHKABmZ2eHv56ecUjXQgAwBRMCAbEtGxvJAAAAAElFTkSuQmCC)](https://www.alura.com.br/)
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/) [![Google AI](https://img.shields.io/badge/Google%20AI-Gemini-orange.svg)](https://ai.google/) [![Colab](https://img.shields.io/badge/Google%20Colab-Run%20Now-green.svg)](https://colab.research.google.com/) [![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## 🚨 O Desafio que Nos Move

Vivemos na era da informação instantânea, mas também da desinformação desenfreada. Fake news se espalham como fogo, minando a confiança e polarizando comunidades. A cidadania digital — a habilidade de navegar, questionar e construir um mundo mais justo — é mais urgente do que nunca.

**Cuidar.AI** nasce dessa pergunta. Não é apenas um projeto; é uma missão. Um chatbot alimentado por inteligência artificial que educa, esclarece e inspira. Desenvolvido com propósito e rigor técnico, ele combina tecnologia de ponta com paixão por transformação social.

---

## 🌟 O que é o Cuidar.AI?

O **Cuidar.AI** é um chatbot educativo que promove **cidadania digital**, **combate à desinformação** e incentiva **a educação cidadã**. Ele utiliza a API **Google Gemini** para fornecer módulos interativos e inteligentes.

> Seja planejando conteúdos sobre temas sociais ou desmascarando fake news, o Cuidar.AI é uma ferramenta para o presente e um legado para o futuro.

### ✨ Por que Cuidar.AI?

- 🚀 **Impacto Social**: Educa com linguagem acessível e foco em temas relevantes.
- 🧠 **IA Generativa Avançada**: Usa múltiplos agentes Gemini com simulação de busca e cadeia de execução.
- 📝 **Inclusivo e Flexível**: Suporte a interfaces GUI (visual) ou textual.
- 🌍 **Aberto e Expansível**: Estrutura modular para novos módulos futuros.

---

## 🔥 Funcionalidades

| Módulo                              | Descrição                                                                                         | Impacto                                                           |
| ----------------------------------- | ------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| **Saúde Preventiva**                | Orientações gerais de saúde e bem-estar com linguagem acessível.                                  | Estimula hábitos saudáveis e autocuidado.                         |
| **Serviços Públicos**               | Ajuda o cidadão a entender documentos, serviços e canais públicos.                                | Facilita o acesso a direitos e informações governamentais.        |
| **Tradução Cidadã**                 | Traduz conteúdos sociais com foco em acessibilidade e empatia.                                    | Garante inclusão linguística em contextos críticos.               |
| **Tradução para Outras Línguas**    | Traduções automáticas para 8 idiomas, baseadas em IA generativa.                                  | Promove acessibilidade e diálogo intercultural.                   |
| **Tradução Cultural Brasileira**    | Explica expressões, costumes e gírias brasileiras para estrangeiros.                              | Fortalece compreensão e integração sociocultural.                 |
| **Emergência Cidadã**               | Suporte em emergências civis, como desastres ou situações de risco coletivo.                      | Aumenta a segurança e rapidez na resposta em crises.              |
| **Segurança Doméstica**             | Dicas e ações de primeiros socorros e segurança em casa.                                          | Reduz riscos domésticos e amplia o conhecimento popular.          |
| **Emergência Infantil**             | Respostas e orientações em situações de emergência com crianças.                                  | Protege a infância e prepara cuidadores.                          |
| **Apoio Emocional**                 | Diálogos empáticos voltados à saúde mental e à prevenção do suicídio.                             | Oferece acolhimento e escuta ativa em momentos sensíveis.         |
| **Passa Tempo**                     | Jogos, curiosidades e interações leves com IA.                                                    | Alivia o estresse e estimula o aprendizado lúdico.                |
| **Planejador de Cidadania Digital** | Criação de conteúdos educativos com cadeia de agentes (busca → planejamento → redação → revisão). | Empodera cidadãos a educar suas comunidades com responsabilidade. |
| **Combate à Desinformação**         | Verifica fatos, avalia impactos e gera alertas educativos sobre fake news.                        | Constrói pensamento crítico e fortalece o senso coletivo.         |
| **Feedback**                        | Permite que o usuário avalie a experiência e contribua com melhorias.                             | Garante evolução contínua com base na participação popular.       |

---

## 🛠️ Arquitetura e Tecnologias

### 🧬 Multiagentes

Cadeias de agentes colaborativos:

- ✉️ **Busca** → simula motores de busca.
- 💡 **Planejamento** → estrutura o conteúdo.
- ✍️ **Redação/Revisão** → gera linguagem cidadã.

### 💻 Stack Tecnológica

- Python 3.8+
- Google Gemini API (`google.generativeai`)
- Google Colab
- ipywidgets
- Markdown

---

## 🚀 Como Executar o Projeto

> Execute diretamente no Google Colab:

### 1. Clone o repositório

```bash
!git clone https://github.com/seu-usuario/cuidar-ai.git
```

### 2. Instale as dependências

```python
!pip install google-generativeai ipywidgets
```

### 3. Configure sua API KEY

```python
from google.colab import userdata
userdata.set("GOOGLE_API_KEY", "sua-chave-aqui")
```

### 4. Execute o notebook

- Rode o notebook `Cuidar_AI.ipynb`.
- Escolha [1] Botões ou [2] Menu textual.

![Exemplo da Interface do Menu](/assets/menu.png)
![Execução do Planejador](/assets/planejador.png)

---

## 🌍 Visão de Futuro

> O Cuidar.AI é um primeiro passo. Nosso sonho é que ele evolua para um ecossistema de assistência cidadã e educação crítica.

- Módulos de Educação Ambiental
- Versão mobile/app
- Integração com bases de dados reais
- Acessibilidade por voz

---

## 🤝 Contribua

1. Fork o repositório
2. Crie sua branch: `git checkout -b feature-x`
3. Commit e PR

Ideias:

- Melhorar interface
- Integrar busca real (ex: SerpAPI)
- Adicionar módulos regionais (leis, serviços públicos, etc.)

---

## 🙏 Agradecimentos

- Aos professores e mentores da Imersão Alura + Google:  
  [![Fabrício Carraro](https://img.shields.io/badge/LinkedIn-Fabrício%20Carraro-blue?logo=linkedin)](https://www.linkedin.com/in/fabriciocarraro/)  
   [![Luciano Martins](https://img.shields.io/badge/LinkedIn-Luciano%20Martins-blue?logo=linkedin)](https://www.linkedin.com/in/lucianommartins/)  
   [![Valquíria Alencar](https://img.shields.io/badge/LinkedIn-Valquíria%20Alencar-blue?logo=linkedin)](https://www.linkedin.com/in/valquiria-alencar/)

- À comunidade open-source, por inspirar inovação acessível
- À equipe da **Alura**, pela proposta educacional transformadora
- À equipe do **Google AI**, pela criação e disponibilização do Gemini
- Aos colegas que votaram, apoiaram e acreditaram no Cuidar.AI ✨

> 💡 Siga esses mentores incríveis no LinkedIn para mais conteúdo sobre IA, tecnologia e cidadania digital.

---

## 🌟 Apoie o Cuidar.AI com seu voto!

Se este projeto tocou você de alguma forma — seja pela proposta social, pela tecnologia ou pelo cuidado com os detalhes — considere deixar seu voto na plataforma da Imersão. 💙

📢 **Vote no Cuidar.AI e ajude a espalhar cidadania digital com inteligência e propósito!**

[![Vote no Cuidar.AI](https://github.com/Cmmagnus/cuidar-ai/blob/main/assets/VO.gif?raw=true)](https://discord.com/invite/49n2pVED7r)

🟣 Acesse o [Discord oficial da Imersão IA 2025](https://discord.com/invite/49n2pVED7r) e participe da votação.

> Cada voto é um gesto de apoio à educação, à verdade e à construção de um futuro melhor.  
> Obrigado por caminhar comigo nessa jornada! 🙌✨

---

## 📜 Licença

Este projeto está licenciado sob a **MIT License** – uma licença permissiva que permite uso, modificação e distribuição, inclusive para fins comerciais, desde que os devidos créditos sejam mantidos.

Veja o arquivo [LICENSE](LICENSE) para o texto completo.

---

## 👤 Autor

**Carlos Magno Marcelino**  
Técnico em Química | Analista de Segurança da Informação  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Carlos%20Magno-blue?logo=linkedin)](https://www.linkedin.com/in/carlos-magno-marcelino-619ab9186/)  
[![GitHub](https://img.shields.io/badge/GitHub-Cmmagnus-black?logo=github)](https://github.com/Cmmagnus)

> “Cuidar.AI: Porque o futuro não espera. É hora de cuidar, educar e transformar.”

---

**⭐ Deixe uma estrela se este projeto te inspirou!**

---

<sub>🔧 Este projeto está em ajustes finos contínuos. Novos módulos e melhorias estão em desenvolvimento.</sub>
