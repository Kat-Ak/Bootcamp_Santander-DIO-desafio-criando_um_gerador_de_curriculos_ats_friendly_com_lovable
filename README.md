<div align="center">

# 🧩 CV Inteligente | versão customizada do seu currículo destacando sua experiência real de forma combinada com a vaga sem inventar dados fictícios
<div></div>
<br>
   <img src="http://img.shields.io/static/v1?label=STATUS&message=VERSAO%20BETA%20|%20v2%20|%2005/11/2026&color=purple&style=for-the-badge"/><br>
<p align="center">
 
  ---

> ### `Desafio Final 3 | Criando um Gerador de Currículos ATS Friendly com Lovable` 
> ###  [ Bootcamp | Construa seu primeiro App com IA ]
> ###  *Santander em parceria com a plataforma da DIO*

---

## 📟 Resumo do Enunciado

A proposta desse desafio é **construir do zero um [MVP](#mvp) (Mínimo Produto Viável) real utilizando IA como [Co-Founder](#cofounder) (ChatGPT) e uma [plataforma No-Code](#nocode) ([Lovable](#lovable)) que compara um currículo com a descrição de uma vaga, calcula a compatibilidade, mapeia as palavras-chave ausentes, gera uma versão [otimizada](#otimizado) para sistemas de triagem sem inventar dados fictícios e oferece um painel de controle de [leads](#lead) administrativos**.

Este repositório reúne os bastidores de planejamento, lógica de processos e inteligência operacional desse desafio, utilizando linguagem acessível, prática e sem jargões complicados de programação para o pequeno empresário ou profissional de negócios.

---
<div align="left">
  
## 🧬 Estrutura do Desafio | Índice Prático

🛰️ 1. [A Dificuldade Real & a Visão do Negócio](a-dificuldade-real--a-visão-do-negócio) <br>
🧪 2. [O Fluxo de Funcionamento da Análise do Sistema](o-fluxo-de-funcionamento-da-análise-do-sistema)<br>
🤖 3. [Mega Prompt Único Otimizado & Versões](mega-prompt-único-otimizado--versões)<br>
🧰 4. [Ajustes Pós-Testes no Sistema & Motivos dos Ajustes](ajustes-pós-testes-no-sistema--motivos-dos-ajustes)<br>

---

## 🛰️ 1. A Dificuldade Real & a Visão do Negócio

Atualmente muitas empresas utilizam o sistema [ATS](#ats) de rastreamento de candidatos (baseado em palavras-chave). Esse filtro ranqueia currículos automaticamente antes de qualquer ser humano ter acesso, fazendo com que muitos bons profissionais nem sequer sejam cogitados a participar dos processos seletivos.

Como os robôs de recrutamento funcionam rastreando a presença de termos técnicos específicos contidos nas descrições de vagas, se o candidato descreve suas competências de uma forma diferente (usando sinônimos não mapeados ou esquecendo de citar palavras-chave críticas da vaga), sua nota despenca e ele é desclassificado automaticamente sem que nenhum recrutador humano chegue a analisar sua experiência.

**O Problema Prático:** Essa barreira digital cria um abismo invisível entre ótimas empresas e excelentes profissionais devido a uma simples desorganização textual.

**A Solução:** O **CV Inteligente** [aplicação](#aplicacao) web (que roda direto no navegador) distribuída e comercializada como um [SaaS tipo Freemium](#freemium), que atua como um [Agente](#agente) de IA, criando uma versão [customizada](#customizado) do currículo destacando a experiência real do candidato de forma combinada com a vaga. Ao cruzar esses dados de forma inteligente, o sistema ensina o candidato a preencher e reorganizar sua apresentação de forma enxuta, inserindo contextualmente os termos exigidos na descrição da vaga, sem inventar nenhuma informação ou cargo fictício.

---

## 🧪 2. O Fluxo de Funcionamento da Análise do Sistema

O processamento estratégico de dados do **CV Inteligente** foi desenhado em uma esteira de fluxo limpa dividida em 4 fases sequenciais:

1.  **Alimentação de Entrada de Dados no Sistema [Input](#input):** Através da [interface](#interface) inicial, o candidato insere a descrição textual completa da vaga e o texto do seu currículo bruto atual. O sistema realiza a leitura estrutural em busca de cruzamentos de dados.
2.  **Análise de Compatibilidade & Processamento Comparativo (Triagem):** Simulando as regras internas de um robô [ATS](#ats), o motor do aplicativo cruza os textos e calcula a pontuação encontrada ([Match](#match) [Score](#score)) em percentual. Ele escaneia o documento e separa os termos detectados em duas listas ordenadas por ordem alfabética: as palavras-chave encontradas e os termos críticos ausentes.
3.  **Remodelagem Ética de Narrativa ([Otimização](#otimizado)):** Respeitando a [premissa](#premissa) obrigatória de nunca inventar dados falsos, a IA analisa o histórico real do candidato e reestrutura os resumos profissionais de forma a incorporar harmonicamente as palavras-chave que faltavam apenas nas lacunas onde o usuário comprovadamente possui a vivência prática.
4.  **Entrega e [Gatilho de Conversão](#gancho) Comercial [Output](#output):** O software exibe a versão [otimizada](#otimizado) pronta na tela dentro de uma caixa de texto. Para fazer o download estruturado do arquivo final em PDF [amigável](#amigavel) ou DOCX, o candidato aciona o botão inteligente de exportação, aplicando a trava de [Paywall](#paywall) do Plano Pro 💠 e direcionando o [lead](#lead) para o fechamento comercial.

---

## 🤖 3. [Mega Prompt](#mega) Único Otimizado & Versões

Para garantir que o software inteiro ficasse pronto, funcional logo na primeira tentativa, minimizando o uso de créditos na conta gratuita do [Lovable](#lovable), foi desenvolvido este [Mega Prompt](#mega) em [Markdown](#markdown) extremamente detalhado, em uma estrutura fluida de página única, aplicando a [tipografia](#tipografia) corporativa **Segoe UI** e orientando a IA a desenhar a [interface](#interface) utilizando os componentes visuais limpos do [Design system shadcn/ui](#shadcn) e o catálogo de estilos [Tailwind CSS](#css).

<details>
<summary><b> [ 🖇️ Clique para visualizar | o Mega Prompt utilizado no Lovable ]</b></summary>

[Markdown](#markdown)
# MEGA PROMPT: 🧩 CV Inteligente ([versão BETA](#beta) v2 05/11/2026)

## 1. Visão Geral, Identidade Visual e Design ([UI](#ui)/[UX](#ux))

Crie uma aplicação de página única [SPA](#spa) responsiva, clean e minimalista usando o [design system shadcn/ui](#shadcn) e [Tailwind CSS](#css).
- **Nome Oficial e Logo (Topo Esquerdo):** Exibir o emoji 🧩 seguido imediatamente pelo texto em negrito "CV Inteligente" e uma etiqueta cinza claro escrita "([versão BETA](#beta)) v2 05/11/2026)".
- **[Tipografia](#tipografia):** Use estritamente a fonte "Segoe UI" ou fontes nativas do sistema equivalentes, garantindo excelente legibilidade.
- **Cores Institucionais:** 
  - Fundo da página: Cinza ultra-claro/gelo (bg-slate-50).
  - Estruturas e Títulos: Azul Marinho Escuro (text-slate-900 ou text-blue-950).
  - Cards internos: Fundo totalmente branco (bg-white) com bordas finas e sombras suaves (shadow-sm).

## 2. [Interface](#interface) do Usuário (Telas dispostas na mesma página)

### Seção 1: [Landing Page](#landing) & Entrada de Dados (Mecanismo de Escaneamento) | Topo da Página
- **Título Principal (Grande e Centralizado):** "CV Inteligente | versão [customizada](#customizado) do seu currículo destacando sua experiência real de forma combinada com a vaga sem inventar dados fictícios"
- **Subtítulo (Tamanho Médio, Cor Cinza Escuro):** "Seu currículo traduzido para a linguagem das empresas (sistemas automáticos [ATS](#ats) que buscam palavras-chave e termos específicos do anúncio da vaga no seu cv)"
- **Texto Explicativo:** "Aumente suas chances de entrevista, através da análise do CV inteligente, descubra o quanto seu cv combina com a vaga pretendida em % ([match](#match)
[score](#score)), quais as palavras-chave encontradas tanto no seu cv quanto na descrição da vaga e quais estão ausentes, experimente por um período de degustação grátis de 30 dias (nosso Plano Padrão🔹). 
E caso perceba que sua pontuação está muito abaixo do recomendado, temos 2 recursos premium 🔼 exclusivos para assinantes do Plano Pro 💠 que podem ajudar ainda mais a aumentar sua visibilidade e suas chances de conseguir uma entrevista: 
- Diagnóstico de Legibilidade - verifica se o arquivo do seu cv possui elementos visuais que os robôs de leitura dos RHs não conseguem interpretar.
- Alinhamento de Perfil Corporativo - sugere substituições e/ou adições por termos sinônimos e cargos corporativos equivalentes sutis e estratégicos de palavras para "dar [match](#match)" com a vaga almejada, sem criar dados."
- **Ação:** Dois campos de texto grandes dispostos lado a lado:
  - Campo Esquerdo: "ℹ️ Cole aqui a Descrição da Vaga"
  - Campo Direito: "🪪 Cole aqui o seu Currículo Atual"
- Botão central de destaque em azul marinho: [ 📡 Analisar meu currículo agora ]

### Seção 2: O Painel de Triagem (Exibido de forma elegante após o clique)

Ao clicar no botão, o software revela de forma animada a estrutura de 5 caixinhas organizadoras dispostas em grade (grid) ou coluna (em telas mobile), simulando o padrão [Google Keep](#keep) / [Google Tarefas](#tarefas). Todos os dados exibidos nos blocos são simulados e estáticos para validação do [MVP](#mvp):

1. **Caixinha 1: 🫆 [Match](#match) [Score](#score)**
   * **Visual:** Borda superior fina na cor laranja. Exibe um indicador gráfico simulado de 45%.
   * **Texto:** "Abaixo do recomendado (mínimo 75%). O currículo corre risco de desclassificação automática pelo robô."

2. **Caixinha 2: 🧲 Palavras-Chave Encontradas**
   * **Visual:** Borda superior fina na cor verde. 
   * **Texto:** Exibir em formato de [bullet points](##bullet) numerados em verde por ordem alfabética as palavras: "Comunicação Corporativa", "Excel Avançado" e "Gestão de Processos".

3. **Caixinha 3: ⛔ Termos Críticos Ausentes**
   * **Visual:** Borda superior fina na cor vermelha.
   * **Texto:** Exibir em formato de [bullet points](##bullet) numerados em vermelho por ordem alfabética as palavras que faltaram: "Fluxo Enxuto", "Indicadores de Desempenho" e "[KPIs](#kpi) Operacionais".

4. **Caixinha 4: 🔒 Diagnóstico de Legibilidade (Recurso Premium 🔼 do Plano Pro 💠)**
   * **Visual:** Bloco inteiro com opacidade reduzida e um pequeno selo roxo escrito "PRO 💠" no topo superior direito.
   * **Texto:** É uma análise avançada que verifica se o arquivo do currículo possui elementos visuais (como tabelas, caixas de texto, colunas ou fontes raras) que travam e confundem os robôs de leitura dos RHs, que podem ser interpretados como um bloco de caracteres invisível, códigos corrompidos ou até mesmo o currículo inteiro em branco. Identificar e eliminar esses "pontos cegos" garante que o conteúdo do documento seja totalmente visível e legível para qualquer [sistema de triagem algorítmica](#algoritmica).
	Atenção ⚠️: Foram encontrados 2 problemas de leitura em seu currículo. Para ter acesso ao resultado da análise completa de escaneamento do robô e saber exatamente quais elementos corrigir, assine o Plano Pro 💠.

5. **Caixinha 5: 🔒 Alinhamento de Perfil Corporativo (Recurso Premium 🔼 do Plano Pro💠)**
   * **Visual:** Bloco inteiro com opacidade reduzida e selo roxo "PRO 💠".
   * **Texto:** Com o cruzamento do currículo com a vaga, verifica-se a possibilidade de melhoria com a sugestão de substituições e/ou adições por termos sinônimos e cargos corporativos equivalentes sutis e estratégicos de palavras para "dar [match](#match)" com a vaga almejada, sem criar dados. 
	Melhorias💡: Foram encontradas sugestões de 3 termos sinônimos corporativos e 2 cargos equivalentes para substituir ou adicionar. Recurso Premium 🔼 exclusivo para assinantes do Plano Pro💠.

### Seção 3: Geração do Currículo Ajustado & Conversão | Rodapé

- Área do Currículo [Otimizado](#otimizado): Exibir uma nova caixa de texto grande contendo uma versão simulada e estruturada do currículo do candidato, mantendo sua experiência real intacta, mas inserindo de forma harmoniosa os termos "[KPIs](#kpi) Operacionais" e "Fluxo Enxuto" escolhidos para serem inseridos nos resumos profissionais.
- **Botão Inteligente de Exportação:** Exiba o botão com uma pequena etiqueta roxa contendo o texto "PRO 💠": [ 📤 Exportar versão [customizada](#customizado) do meu cv em PDF [amigável](#amigavel) / DOCX (plano PRO 💠) ]

- Ação ao clicar: Abre uma janela [pop-up](#pop-up) elegante mostrando um modelo de currículo limpo e o aviso: "Esta é uma demonstração do recurso de exportação direta em PDF [amigável](#amigavel) para sistemas de RH. Solicite acesso a esse recurso de automação no seu perfil acessando o plano PRO 💠."
	- Botão de ação destacado no [pop-up](#popup): [ Solicitar acesso ao recurso premium 🔼 do plano Pro 💠 no WhatsApp ] (Simula redirecionamento).

- Rodapé Geral (Seção de Conversão): Botão definitivo de conversão do software com sombra elegante: [ β Quero acesso antecipado ao 🧩 CV Inteligente (versão [BETA](#beta) v2 05/11/2026)] (redireciona para o link simulado de fechamento de [lead](#lead)).

3. Painel de Administração (Acesso via [Rota](#rota)/admin ou link discreto no rodapé)

- Uma tela com uma tabela simples contendo as colunas: Nome do Candidato ([lead](#lead)), Vaga Alvo, [Score](#score) Encontrado, Recurso Clicado, Status (Interessado na [versão BETA](#beta)), Entregas de Currículos, Lembretes de Retorno do RH.
- Salve as interações locais usando o banco interno gratuito do [Lovable Cloud](#cloud).

</details>

---

## 🧰 4. Ajustes Pós-Testes no Sistema & Motivos dos Ajustes

Após a primeira geração no [Lovable](#lovable), foram aplicadas versões incrementais para adequar as telas às correções rápidas de [engenharia de prompts](#prompt), blindando o layout e continuando a garantir o uso mínimo de créditos da plataforma:
- v1. **Alteração e melhoria do nome:** Alteração do nome do software de "[MATCH](#match) [ATS](#ats)" para um nome mais popular, humano e amigável: **"CV Inteligente"**.
- v2.1. **Melhoria e alteração do título:** Ajuste do cabeçalho inicial de "Seu currículo está pronto para passar pelo filtro dos robôs de RH?" para a inclusão direta da marca corporativa e da proposta de valor em uma frase direta: *"CV Inteligente | versão [customizada](#customizado) do seu currículo destacando sua experiência real de forma combinada com a vaga sem inventar dados fictícios"*.
- v2.2. **Melhoria e alteração do subtítulo:** Ajuste do subtítulo "O CV Inteligente compara seu currículo com a descrição da vaga, mapeia as palavras-chave ocultas e reorganiza sua apresentação para garantir que você chegue ao RH.", que ficaria redundante após a mudança do título. Para complementar a linha de raciocínio de forma mais compreensível para o usuário final: *"Seu currículo traduzido para a linguagem das empresas (sistemas automáticos [ATS](#ats) que buscam palavras-chave e termos específicos do anúncio da vaga no seu cv)"*.

---

### 🔄 Sincronização & Proteção do [Código-Fonte](#fonte)

O repositório técnico restrito à programação bruta do aplicativo foi exportado de forma nativa pela Inteligência Artificial do [Lovable](#lovable) e está hospedado publicamente. Para proteger a integridade do [MVP](#mvp) avaliado e resguardar os direitos autorais, o arquivo `README.md` daquela pasta foi [customizado](#customizado) sob as seguintes diretrizes:

*   **Identidade Visual:** Vinculação e direcionamento explícito ao [🌌 Hub Panorâmico Visual](https://github.com/Kat-Ak/HUB-visual), resguardando a narrativa gráfica autoral das telas e componentes.
*   **Colaboração Segura:** Convite à comunidade de negócios para debater novas ferramentas e evoluções utilizando estritamente a aba **[Issues](#issue)**, mantendo o [código-fonte](#fonte) original trancado contra alterações diretas.
*   **Nota de Segurança:** Desativação de *[Pull Requests](#pull)* diretos para blindar a [aplicação](#aplicacao) contra panes técnicas e garantir a estabilidade do software durante o período de avaliação do bootcamp.

---

## 📈 Estratégias Comerciais

A [interface](#interface) do software foi construída estrategicamente para demonstrar o potencial comercial da conversão de [leads](#lead) através do [modelo de **comercialização SaaS (Software como Serviço)** baseado na estratégia de aquisição de clientes (precificação) Freemium](#freemium):
*   **Degustação de 30 Dias (Plano Padrão🔹):** O usuário experimenta gratuitamente a triagem de [Score](#score), vê as palavras encontradas e descobre quais termos vitais causaram a sua desclassificação automática através das 3 primeiras caixinhas de controle.
*   **Barreiras Visuais Premium 🔼 e [Paywall](#paywall) (selo roxo Plano Pro 💠):** A quarta e a quinta caixinha de relatórios complexos aparecem bloqueadas com opacidade reduzida. O botão inteligente de download em PDF [amigável](#amigavel)/DOCX também carrega o selo roxo Plano Pro 💠. O clique abre uma simulação informativa e direciona o candidato a assinar a versão completa no WhatsApp, validando a intenção de compra imediata.

### 🖼️ Planejamento da [Imagem Social](#imagem-social) (Gatilho de Autoridade)
A [imagem social](#imagem-social) (capa de compartilhamento para o LinkedIn) foi arquitetada via [engenharia de prompts](#prompt) analítico. Em vez de utilizar mídias genéricas, foi desenhado um encarte minimalista sob a identidade visual do software, utilizando a paleta de cinza-gelo e azul-marinho institucional com a fonte **Segoe UI**. Essa estratégia foi implementada para garantir credibilidade imediata de marca na linha do tempo das redes sociais e impulsionar a captação de [leads](#lead) orgânicos para a lista de espera da [versão Beta](#beta).

---

## ☑️ Checklist de Requisitos do Enunciado

| Status | Requisito do Enunciado | Link de Evidência / Entregável |
| :---: | :--- | :--- |
| ✔️ | **A Dificuldade Real & a Visão do Negócio** | [Ir para Seção 1](#-1-a-dificuldade-real--a-visão-do-negócio) |
| ✔️ | **O Fluxo de Funcionamento da Análise do Sistema** | [Ir para Seção 2](#-2-o-fluxo-de-funcionamento-da-análise-do-sistema) |
| ✔️ | **Mega Prompt Único Otimizado & Versões** | [Ir para Seção 3](#-3-mega-prompt-único-otimizado--versões) |
| ✔️ | **Ajustes Pós-Testes no Sistema & Motivos dos Ajustes** | [Ir para Seção 4](#-4-ajustes-pós-testes-no-sistema--motivos-dos-ajustes) |
| ✔️ | **Design System shadcn/ui & as Cores da Paleta** | `Design_System_shadcn_ui-&-Cores_da_Paleta.pdf` |
| ✔️ | **Captura de tela 1: landing page** | `print_tela/landing_page.png` |
| ✔️ | **Captura de tela 2: análise do cv** | `print_tela/analise_cv.png` |
| ✔️ | **Captura de tela 3: botão inteligente de exportação** | `print_tela/botao_exportacao.png` |
| ✔️ | **Captura de tela 4: painel admin (leads, candidatos, vagas, scores, recursos, status, entregas e lembretes)** | `print_tela/painel_admin.png` |
| ✔️ | **Captura de tela 5: revisão de segurança do Lovable** [Nenhum problema de Segurança encontrado] | `print_tela/seguranca_lovable.png` |
| ✔️ | **Captura de tela 6: Aplicação publicada (nome, descrição e imagem social)** | `print_tela/aplicacao_publicada.png` |
| ✔️ | **Endereço da aplicação publicada** | [Link da Aplicação no Lovable](https://cv-inteligente-mvp-beta.lovable.app) |
| ✔️ | **Repositório técnico (código bruto) do software exportado e gerado por IA (Lovable)** | [Acessar Código-Fonte do Software](https://github.com/Kat-Ak/cv-inteligente-mvp-beta)

---

## 🏆 Conclusão | Melhorias & Próximos Passos

A desenvolvimento do software *CV Inteligente* demonstrou que a inteligência de processos e o desenho lógico de fluxos de dados superam qualquer barreira de programação complexa. Com um planejamento inteligente de processos através do uso combinado de [engenharia de prompts](#prompt) com [mega prompt](#mega) no [Lovable](#lovable), guiamos a inteligência artificial para entregar uma ferramenta [SaaS](#freemium) de alto valor funcional com uso mínimo de créditos.

Próximos Passos (Evolução):

• Automação Real com [n8n](#n8n) (plataforma de automações): Conectar a [API](#api) oficial do Gmail/Outlook via [n8n](#n8n) para que o [Agente](#agente) leia descrições diretamente de e-mails recebidos.
• Integração do [Stripe](#stripe) [checkout](#checkout) financeiro automático: configurar o período de teste gratuito (trial) de 30 dias no 🔹 Plano Padrão, realizando a primeira cobrança recorrente automática apenas após o vencimento deste prazo. E implementar o [Paywall](#paywall) nos botões com cadeados do Plano Pro 💠 direcionando para a página do [Stripe](#stripe), para liberar o recurso instantaneamente após a confirmação da transação. 
• Disparo Automático de [Leads](#lead): Configurar a integração da [chave de API](#chave) do [Resend](#resend) para alertar o e-mail do administrador a cada novo [lead](#lead) coletado no formulário ou cliques nos [ganchos](#gancho) de conversão do WhatsApp.

---

## 🆘 Central SOS (Glossário Retrátil)

Se tiver dúvidas sobre os termos utilizados neste projeto, clique nas setinhas abaixo para abrir a nossa biblioteca de conceitos:

<details>
  <summary>Clique para expandir o glossário 📇 CONCEITOS DE MERCADO & NEGÓCIOS</summary>

<a id="ats"></a>
### ATS

**ATS (Applicant Tracking System / Sistema de Rastreamento de Candidatos):** Software robótico utilizado por departamentos de RH para escanear, filtrar e ranquear currículos automaticamente com base em palavras-chave antes que qualquer ser humano leia o documento.

<a id="customizado"></a>
### Customizado

**Customizada/o / Customização:** O ato de personalizar e adaptar algo sob medida para atender exatamente às necessidades específicas de um determinado cenário ou cliente.

<a id="freemium"></a>
### modelo de comercialização SaaS (Software como Serviço) baseado na estratégia de 
aquisição de clientes (precificação) Freemium

**Modelo de **comercialização SaaS (Software como Serviço)** baseado na estratégia de aquisição de clientes (precificação) Freemium / Modelo de Distribuição e Comercialização SaaS Tipo Freemium | (Modelo de Negócio):** 

**Saas:** Modelo de comercialização e distribuição de tecnologia onde o cliente não precisa instalar nenhum programa no computador nem comprar uma licença cara para sempre. O software fica hospedado na nuvem (na internet) e o usuário o acessa direto pelo navegador (como um site), pagando um valor recorrente (um serviço de assinatura mensal ou anual) para utilizá-lo. Exemplos: Netflix, Spotify, Gmail, Canva, Notion e CV Inteligente (você não "compra" o software deles, você assina o direito de usá-los pela internet).

**SaaS Tipo Freemium:** Estratégia comercial onde o cliente tem acesso gratuito ou degustação (Free) por um período das funções básicas, mas que restringe os recurso mais valiosos, automatizados e avançados (Premium) através de uma barreira de pagamento ([Paywall](#paywall)) de um valor de assinatura.

<a id="gancho"></a>
### Gancho

**Gancho ou gatilho (de conversão de leads):** Link ou botão estratégico espalhado colocado em um texto, site ou anúncio, como uma isca estratégica criado especificamente para "fisgar" a atenção do visitante e incentivar essa pessoa a tomar uma ação. O termo vem do comportamento de "pescar" o interesse do usuário no meio de tantas distrações digitais, servindo como o ponto de partida para transformar um visitante comum em um [lead](#lead) ou cliente pagante.

<a id="kpi"></a>
### KPIs

**KPIs (Key Performance Indicators / Indicadores de Desempenho):** Sigla para os indicadores-chave de performance. São as métricas e números fundamentais que as empresas utilizam para medir o desempenho de um processo ou funcionário (se está alcançando as metas planejadas).

<a id="lead"></a>
### Lead

**Lead:** Contato (e-mail ou Whatsapp) de uma pessoa ou empresa (cliente em potencial) que demonstrou interesse real no seu produto ou software.

<a id="match"></a>
### Match

**Match:** Termo em inglês para "combinação" ou "encaixe". No sistema, significa o nível de afinidade e correspondência direta entre as competências do seu currículo e as exigências da vaga.

<a id="mvp"></a>
### MVP

**MVP (Mínimo Produto Viável):** Versão inicial e simplificada de um produto ou software (um protótipo), lançada no mercado com o menor custo e tempo possíveis, contendo apenas as funções principais para começar a rodar. Permite testar a ideia na prática e validar o interesse do mercado antes de investir em um desenvolvimento pesado. Ver se os clientes gostam da solução e faturar os primeiros reais. Usar os comentários dos usuários reais para melhorar o sistema aos poucos.

<a id="otimizado"></a>
### Otimizado

**Otimizada/o / Otimização:** Processo de melhorar, aperfeiçoar e deixar algo mais eficiente, enxuto e performático para alcançar o melhor resultado possível com o menor esforço ou desperdício.

<a id="amigavel"></a>
### PDF Amigável

**PDF Amigável / ATS Friendly:** Formato de arquivo digital gerado de uma forma muito específica, sendo leve, limpo e estruturado por trás das telas apenas com texto puro e fontes padrão do sistema para que as IAS e os robôs de triagem de currículos ([ATS](#ats)) de recrutamento dos RHs consigam ler, escanear, extrair e interpretar 100% das informações sem travar ou corromper o texto, gerar erros de leitura, bloquear leitores de dados ou "pontos cegos" que causam a desclassificação automática do candidato, como arquivos em formato de imagem ou design cheios de elementos gráficos complexos (caixas de texto flutuantes e tabelas).

<a id="premissa"></a>
### Premissa

**Premissa / Regra Obrigatória:** Condição inicial, ponto de partida ou regra de ouro que não pode ser descumprida de forma alguma durante a execução de um projeto ou processo.

<a id="score"></a>
### Score

**Score:** Pontuação ou nota numérica gerada pelo sistema para medir a qualidade de um resultado (ex: o seu nível de compatibilidade com a vaga).

</details>

<details>
  <summary>Clique para expandir o glossário 🧰 CONCEITOS TÉCNICOS & INTERFACE & ENGENHARIA DE IA</summary>

<a id="agente"></a>
### Agente de IA

Agente de IA (AI Agent) | (A Tecnologia): Sistema inteligente de computador (o cérebro que roda dentro dessa aplicação). É o que diferencia o seu sistema de um site comum. Não apenas responde a comandos de texto simples (como um chat tradicional), mas tem a capacidade de agir de forma autônoma, analisar dados, calcular fusos horários, organizar caixas de entrada, tomar decisões lógicas e executar tarefas completas sozinho para atingir um objetivo específico. Ele funciona como um "funcionário virtual" focado em uma função.

<a id="algoritmica"></a>
### Sistema de Triagem Algorítmica

**Sistema de Triagem Algorítmica:** Mecanismo automatizado comandado por regras matemáticas e robôs de software (algoritmos) que toma decisões de triagem, filtragem e classificação de dados em massa de forma automática, sem intervenção humana.

<a id="api"></a>
### API

**API (Application Programming Interface / Interface de Programação de Aplicações):** Espécie de ponte ou canal de comunicação seguro que permite que dois sistemas totalmente diferentes "conversem" entre si e troquem informações automaticamente.

<a id="aplicacao"></a>
### Aplicação

**Aplicação / Aplicações / Aplicativo (App) | (O Formato):** A base de tudo. Termo técnico para se referir a qualquer programa, software ou sistema de computador que executa tarefas específicas, práticas e úteis para o usuário (como organizar e-mails, calcular rotas ou processar pagamentos). 
No contexto de internet, quando dizemos "aplicação publicada", significa que o sistema saiu do computador do programador e já está "no ar" em um endereço de site acessível para qualquer pessoa usar. 

**Aplicação Web:** significa que o programa interativo funciona direto na internet através de um navegador (Chrome, Safari, etc.), sem que o usuário precise baixar e instalar um arquivo .exe ou .apk no computador ou celular.

<a id="beta"></a>
### Beta / Versão Beta

**Beta / Versão Beta:** Versão de testes de um software que já está funcional, mas é liberada antecipadamente para um grupo restrito de clientes reais com o objetivo de coletar opiniões e validar o uso prático antes do lançamento oficial no mercado.

<a id="bullet"></a>
### Bullet Points

**Bullet Points (Pontos de Tópicos / Marcadores):** Lista de itens organizada verticalmente por pequenas bolinhas, símbolos ou números, utilizada para deixar a leitura de um texto rápida, limpa e visualmente organizada.

<a id="chatgpt"></a>
### ChatGPT

**ChatGPT:** Sistema de IA em formato de chat (conversa) que consegue entender perguntas em texto e gerar respostas humanas, profissionais e completas de forma instantânea.

<a id="chave"></a>
### Chave de API

**Chave de API (Tokens / Senhas de Integração):** Códigos secretos que funcionam como uma "chave digital" para permitir que um aplicativo acesse os recursos de outro de forma segura. Por segurança, elas nunca devem ficar visíveis ou expostas no código público do GitHub.

<a id="checkout"></a>
### Checkout

**Checkout:** Tela ou página final onde o cliente insere os dados de pagamento (como cartão de crédito ou Pix) para concluir uma compra ou um plano de assinatura.

<a id="cofounder"></a>
### Co-Founder

**Co-Founder (Co-Fundador):** Parceiro de negócios que ajuda a fundar a empresa. Neste projeto, o [ChatGPT](#chatgpt) foi utilizado como um co-founder analítico para validar o mercado e desenhar a lógica das regras operacionais.

<a id="fonte"></a>
### Código-Fonte

**Código-Fonte / Código Bruto:** Conjunto original de linhas de texto e instruções lógicas escritas em linguagem de programação que os desenvolvedores ou as IAs criam para fazer o aplicativo funcionar por trás das telas.

<a id="shadcn"></a>
### Design system shadcn/ui

**Design system shadcn/ui:** Coleção de componentes visuais e blocos de construção de altíssimo nível mais populares e modernas do desenvolvimento web atual, utilizada para desenhar interfaces de sites modernos. Diferente de bibliotecas tradicionais, onde você instala um pacote de ferramentas fechadas e se restringe aos designs deles, o shadcn/ui permite total liberdade de customização (cores, bordas, fontes e espaçamentos) com extrema facilidade e garante um visual limpo, minimalista, elegante e altamente profissional por padrão, porque copia o código dos componentes diretamente dentro do seu projeto.

<a id="prompt"></a>
### Engenharia de Prompt

**Engenharia de Prompt:** Técnica especializada de planejar, estruturar e redigir comandos textuais ultra-detalhados e lógicos para que uma inteligência artificial construa um layout ou código sem erros e sem desperdiçar processamento.

<a id="keep"></a>
### Google Keep

**Google Keep:** Ferramenta de produtividade que usa o modelo de cartões colados lado a lado (estilo o método Kanban) como um mural de post-its, facilitando a visualização da gestão de tarefas e ideias de forma organizada.

<a id="tarefas"></a>
### Google Tarefas

**Google Tarefas:** Ferramenta de produtividade que usa o modelo de tópicos de listas verticais que você vai riscando, embora em algumas visualizações integradas (como no Google Agenda ou no painel lateral do Gmail), também se comporte como uma caixinha de controle de status, facilitando o controle de tarefas.

<a id="imagem-social"></a>
### Imagem Social

**Imagem Social (OG Image / Open Graph Image / Capa de Compartilhamento):** Foto de capa ou miniatura que aparece de forma automática na tela quando o link do aplicativo é compartilhado em redes sociais como o LinkedIn ou WhatsApp. Quando é publicado um link no LinkedIn, o sistema "puxa" um bloco visual contendo o título do site, uma breve descrição e uma imagem retangular de destaque. Funciona como o "cartão de visitas" visual profissional do site, garantindo uma apresentação bonita, profissional e atraente na linha do tempo dos usuários gerando credibilidade imediata. Caso a imagem social não seja configurada, quando alguém compartilhar o link, aparecerá um quadrado cinza vazio ou o logotipo padrão do [Lovable](#lovable), o que passa uma impressão amadora.

<a id="input"></a>
### Input

**Input (Entrada de Dados):** Qualquer tipo de informação, texto ou arquivo que você insere ou "alimenta" dentro de um sistema para que ele possa processar.

<a id="interface"></a>
### Interface

**Interface:** Toda a parte visual do sistema com a qual o usuário interage diretamente (as telas, as caixas de texto, as cores e os botões). É a "ponte" entre o ser humano e as linhas de código do computador.

<a id="issue"></a>
### Issues

**Issues (Aba de Discussões):** Painel público em formato de fórum dentro do GitHub utilizado para que usuários e a comunidade abram chamados, tirem dúvidas, relatem problemas ou debatam sugestões de melhorias sobre um projeto.

<a id="landing"></a>
### Landing Page

**Landing Page (Página de Destino):** Página de internet criada com um único objetivo comercial muito específico: prender a atenção do visitante imediatamente, explicar a proposta de valor de forma clara e direta e levá-lo a tomar uma única ação importante, como preencher um formulário de cadastro ou clicar em um botão de compra. Ao contrário de um site tradicional, ela elimina distrações para transformar um visitante comum em um [lead](#lead) ou cliente pagante no menor tempo possível.

<a id="lovable"></a>
### Lovable

**Lovable:** Plataforma moderna de Inteligência Artificial que funciona como um "programador virtual", permitindo criar softwares e aplicativos inteiros instantaneamente através de conversas sem precisar digitar códigos complexos. Na prática, o criador apenas escreve comandos simples em português — explicando o que o sistema deve fazer e como deve ser o visual — e a tecnologia gera instantaneamente as telas e funções automáticas de bastidores, reduzindo drasticamente o tempo e o custo de desenvolvimento de soluções.

<a id="cloud"></a>
### Lovable Cloud

**Lovable Cloud:** Serviço de hospedagem e infraestrutura integrado do [Lovable](#lovable). 
Cria o banco de dados para salvar informações de forma segura, gerencia o cadastro e login dos usuários e garante que o sistema funcione 24 horas por dia, eliminando totalmente a necessidade inicial (possui limites no plano grátis) de contratar servidores externos ou especialistas em infraestrutura de TI.

<a id="markdown"></a>
### Markdown

**Markdown:** Método de formatação de texto extremamente simples e universal que utiliza símbolos básicos (como hashtags para títulos e asteriscos para negrito) para organizar e estruturar documentos e instruções textuais de forma limpa, garantindo que tanto humanos quanto inteligências artificiais consigam ler e entender a hierarquia das informações perfeitamente (organização visual e leitura eficiente).

<a id="mega"></a>
### Mega Prompt

**Mega Prompt (Supercomando):** Comando textual ultra-detalhado, estruturado e extenso que reúne em um único bloco de texto o contexto do negócio, as regras lógicas de programação, o papel esperado da inteligência artificial e os limites do sistema. Ao contrário de um comando simples, o Mega Prompt funciona como um manual de instruções completo fornecido à IA (como o [ChatGPT](#chatgpt) ou o [Lovable](#lovable) para que ela execute tarefas complexas de ponta a ponta — como programar uma funcionalidade inteira do CV Inteligente — com máxima precisão e sem margem para erros. 

<a id="n8n"></a>
### n8n

**n8n:** Ferramenta moderna de automação e integração de processos que funciona como um "maestro de sistemas", conectando aplicativos e criando fluxos de trabalho automáticos sem complicação.

<a id="nocode"></a>
### No-Code

**Plataforma No-Code (Sem Código):** Ferramenta ou software de desenvolvimento que permite criar sistemas modernos (como o [Lovable](#lovable)), aplicativos inteiros e automações apenas por comandos de texto ou blocos visuais, sem precisar saber programar ou escrever linhas de código de computador.

<a id="output"></a>
### Output

**Output (Saída de Dados):** Resultado final, relatório ou arquivo entregue e gerado pelo sistema após processar as informações que você inseriu.

<a id="paywall"></a>
### Paywall

**Paywall:** "Parede" / barreira de pagamento / trava digital / bloqueio visual ou funcional inserido intencionalmente na tela avisando ao usuário que o acesso a esse recurso é exclusivo para assinantes, convidando-o a realizar o pagamento ou upgrade do plano.

<a id="popup"></a>
### Pop-up

**Pop-up:** Elemento de interface visual que surge subitamente centralizado na frente da tela principal do site após um clique para prender a atenção do usuário, borrando e escurecendo de leve o fundo da página. Costuma ser uma caixinha utilizada para exibir avisos de plano urgentes, travas de segurança de dados, formulários elegantes ou conteúdos complementares importantes sem tirar o usuário da página atual.


<a id="pull"></a>
### Pull Requests

**Pull Requests (Pedidos de Alteração de Código):** Solicitação formal feita por outro programador para enviar e misturar uma alteração de código dele dentro do arquivo original. Bloquear esse recurso protege o software contra alterações acidentais de terceiros.

<a id="resend"></a>
### Resend

**Resend:** Serviço moderno de internet especializado no disparo de e-mails automáticos direto de forma limpa para administradores do sistema, garantindo que mensagens de alerta sobre novas movimentações (como avisos de que um novo cliente se cadastrou) cheguem de forma instantânea e sem cair na caixa de spam.

<a id="rota"></a>
### Rota

**Rota / Acesso via Rota:** Caminho do endereço de texto digitado na barra do navegador após o link principal para abrir uma página ou tela específica dentro do sistema (por exemplo: digitar /admin no final do link para abrir a tela secreta de gerenciamento).

<a id="spa"></a>
### SPA

**SPA (Single Page Application / Aplicação de Página Única):** Formato de site moderno onde tudo funciona em uma única tela dinâmica. Conforme o usuário clica nos botões, os elementos aparecem e desaparecem, mudando de forma limpa e fluida, sem que a página precise ficar recarregando, eliminando a lentidão.

<a id="stripe"></a>
### Stripe

**Stripe:** Uma das plataformas de pagamentos e cobranças digitais mais seguras do mundo. Funciona como a "maquininha de cartão invisível" do seu site, permitindo que a empresa receba pagamentos por cartão de crédito ou assinaturas recorrentes de forma automatizada e protegida.

<a id="css"></a>
### Tailwind CSS

**Tailwind CSS:** Manual de componente de estilos modernos que a inteligência artificial usa para desenhar (caixas, botões e cores), pintar e estruturar as telas de forma rápida e padronizada. Funciona como um catálogo pronto de formatações visuais (bordas, sombras e espaçamentos), deixando o site bonito e profissional sem peso de carregamento.

<a id="tipografia"></a>
### Tipografia

**Tipografia:** A escolha e o desenho das fontes (letras) utilizadas nas telas. Uma boa tipografia corporativa garante que dados numéricos e horários internacionais fiquem perfeitamente nítidos e fáceis de ler por qualquer pessoa.

<a id="ui"></a>
### UI

**UI (User Interface / Interface do Usuário):** Cuida de toda a parte visual do software, definindo elementos como as cores, as fontes, os botões e o layout das caixinhas com os quais o cliente interage na tela.

<a id="ux"></a>
### UX

**UX (User Experience / Experiência do Usuário):** Planeja como o usuário se sente ao navegar pelo sistema, mapeando a jornada do cliente para garantir que o software seja fácil, lógico, intuitivo e totalmente sem complicações.
</details>

---
