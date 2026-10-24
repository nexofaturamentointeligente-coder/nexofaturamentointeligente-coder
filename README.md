<div align="center">

<img src="assets/nexo-header.svg" width="100%" alt="NEXO — Faturamento Inteligente. Transformando relatórios complexos do PDV em inteligência financeira e decisões de lucro." />

<br />

<a href="https://nexo-faturamento-inteligente-render.onrender.com"><img src="https://img.shields.io/badge/Status-MVP_em_produ%C3%A7%C3%A3o-8B3CDE?style=for-the-badge&logo=rocket&logoColor=white" alt="Status: MVP em produção" /></a>
<img src="https://img.shields.io/badge/Modelo-SaaS_B2B-13111C?style=for-the-badge&labelColor=6D28D9" alt="Modelo: SaaS B2B" />
<img src="https://img.shields.io/badge/Varejo-Tintas_%26_Constru%C3%A7%C3%A3o-13111C?style=for-the-badge&labelColor=6D28D9" alt="Varejo: tintas e construção" />

</div>

<br />

## 💡 Sobre o NEXO

O **NEXO** é uma plataforma B2B de **inteligência de dados e consultoria analítica automatizada** para o pequeno e médio varejo, com foco em **lojas de tintas, materiais de construção e reforma**.

Ele recebe os relatórios brutos exportados pelos sistemas de frente de caixa (PDVs), processa tudo em um pipeline automatizado em Python e entrega um **portal com gráficos claros e um parecer estratégico em linguagem simples e acionável**. A ideia é tirar a decisão do *feeling* e colocá-la nos dados.

> [!NOTE]
> O NEXO não concorre com ERPs nem com sistemas contábeis. Ele é a **camada de inteligência sobre os dados que o lojista já tem**, mas raramente consegue interpretar.

## 🎯 O problema × a resposta

<table>
  <thead>
    <tr>
      <th width="50%" align="left">😵 O gargalo do pequeno varejista</th>
      <th width="50%" align="left">✅ A resposta do NEXO</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Dados opacos no PDV</b><br />Dezenas de tabelas pesadas em Excel/CSV que ninguém tem tempo de analisar.</td>
      <td><b>Importação sem esforço</b><br />Upload dos arquivos brutos, do jeito que o sistema de caixa exporta.</td>
    </tr>
    <tr>
      <td><b>Compras no <i>feeling</i></b><br />Reposição de memória: produtos encalhados e falta dos itens de alto giro.</td>
      <td><b>ETL automatizado</b><br />Limpeza e padronização imediatas com Pandas + NumPy.</td>
    </tr>
    <tr>
      <td><b>Capital de giro preso na prateleira</b><br />Dinheiro parado em mercadoria sem giro, sem nenhum alerta.</td>
      <td><b>Visualização descomplicada</b><br />Dashboards focados no que importa para a saúde financeira da loja.</td>
    </tr>
    <tr>
      <td><b>Sem visão de descasamento</b><br />O que foi comprado e o que foi faturado nunca aparecem lado a lado.</td>
      <td><b>Parecer estratégico prático</b><br />Pontos positivos, alertas e recomendações diretas para o gestor.</td>
    </tr>
  </tbody>
</table>

## ⚙️ Como funciona

<img src="assets/nexo-pipeline.svg" width="100%" alt="Fluxo do NEXO em 5 etapas: 1. Relatórios do PDV (vendas e compras em CSV ou XLSX); 2. Motor de ETL (Pandas e NumPy: leitura adaptativa, limpeza e mapeamento De-Para); 3. Indicadores (Pressão de Estoque, Curva ABC e semáforos 5W2H); 4. Parecer estratégico (IA com fallback local e revisão da equipe); 5. Portal e PDF (dashboards Plotly, alertas em tempo real e PDF executivo)." />

## 📊 Indicador de Pressão de Estoque

<img src="assets/nexo-indicador.svg" width="100%" alt="Pressão de Estoque = Total Comprado − Faturamento. Positivo: a loja comprou mais do que vendeu, acumulando estoque e prendendo capital de giro. Negativo ou equilibrado: estoque girando e geração de liquidez. Exemplo com valores ilustrativos: faturamento de R$ 142.800, compras de R$ 156.300 e pressão de +R$ 13.500." />

Métrica exclusiva do NEXO que mede o **descasamento entre o que a loja comprou e o que faturou no mesmo período**. É um sinal estratégico para orientar compras e reposição, não um número contábil.

## 🧰 O que o NEXO entrega

<table>
  <tr>
    <td width="50%" valign="top">📈 <b>Indicador de Pressão de Estoque</b><br /><sub>Compras × faturamento do período, resumidos em um único sinal.</sub></td>
    <td width="50%" valign="top">🧮 <b>Curva ABC (Pareto)</b><br /><sub>Os carros-chefe para negociar com fornecedores e os itens sem giro que prendem capital.</sub></td>
  </tr>
  <tr>
    <td valign="top">🚦 <b>Semáforos executivos 5W2H</b><br /><sub>Verde, amarelo e vermelho: o que é oportunidade, o que pede atenção e o que é crítico.</sub></td>
    <td valign="top">🧠 <b>Parecer estratégico em 5 etapas</b><br /><sub>Resumo executivo → pontos positivos → pontos de atenção → recomendações → próximos passos.</sub></td>
  </tr>
  <tr>
    <td valign="top">📄 <b>PDF executivo</b><br /><sub>A análise publicada pronta para imprimir, enviar ou levar para a reunião.</sub></td>
    <td valign="top">🤖 <b>NexoBot</b><br /><sub>Assistente de navegação em português, que roda 100% local, sem depender de IA externa.</sub></td>
  </tr>
  <tr>
    <td valign="top">🔔 <b>Notificações em tempo real</b><br /><sub>Avisos via WebSocket quando há novidade, como uma análise recém-publicada.</sub></td>
    <td valign="top">🏢 <b>Gestão multiempresa</b><br /><sub>A consultoria acompanha várias lojas, com fluxo rascunho → homologação → publicação.</sub></td>
  </tr>
</table>

## 🎬 Veja o NEXO em ação

<div align="center">
  <img src="assets/nexo-demo.gif" width="100%" alt="Prévia animada do filme de produto do NEXO mostrando o painel gerencial, o comparativo de compras e vendas, a Pressão de Estoque e a Curva ABC." />
  <br />
  <sub>Os valores e indicadores apresentados são ilustrativos.</sub>
</div>

## 💳 Planos

Todos os planos incluem indicadores e parecer estratégico. O que muda é a profundidade e a frequência da análise.

| | 🥉 **BRONZE** | 🥈 **PRATA** | 🥇 **OURO** |
| :--- | :---: | :---: | :---: |
| **Para quem** | Quer começar com clareza | Quer entender as mudanças | Quer acompanhar de perto |
| **Análises** | 1 por mês | 1 por mês | Até 2 por mês (recorte quinzenal) |
| **Indicadores** | Principais | Principais do período | Consolidados |
| **Parecer estratégico** | Objetivo | Completo: pontos positivos, alertas e recomendações | Aprofundado, com recomendações mais detalhadas |
| **Investimento** | Sob consulta | Sob consulta | Sob consulta |

## 🛠️ Stack & Engine

| Camada | Tecnologias |
| :--- | :--- |
| **Backend** | ![Python](https://img.shields.io/badge/Python_3.12-3776AB?style=flat-square&logo=python&logoColor=white) ![Flask](https://img.shields.io/badge/Flask_3-000000?style=flat-square&logo=flask&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy_2-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white) ![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white) ![Gunicorn](https://img.shields.io/badge/Gunicorn-499848?style=flat-square&logo=gunicorn&logoColor=white) |
| **Dados & ETL** | ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![ReportLab](https://img.shields.io/badge/ReportLab_%28PDF%29-5A1F8C?style=flat-square) |
| **Front-end** | ![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=flat-square&logo=bootstrap&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly.js-3F4F75?style=flat-square&logo=plotly&logoColor=white) ![Jinja](https://img.shields.io/badge/Jinja-B41717?style=flat-square&logo=jinja&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| **Banco & Infra** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white) ![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black) ![Brevo](https://img.shields.io/badge/Brevo-0B996E?style=flat-square&logo=brevo&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/CI_de_seguran%C3%A7a-2088FF?style=flat-square&logo=githubactions&logoColor=white) |
| **IA** | ![Claude](https://img.shields.io/badge/Claude_%28Anthropic%29-D97757?style=flat-square&logo=claude&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging_Face_%28opcional%29-FFD21E?style=flat-square&logo=huggingface&logoColor=black) |

## 🔐 Princípios que guiam o produto

- **Não é um sistema contábil.** O NEXO não calcula lucro, margem nem CMV: entrega sinais estratégicos para decidir melhor, não números fiscais.
- **Sucesso honesto ou recusa acionável.** Para qualquer arquivo, o motor de ETL extrai os indicadores reais ou explica exatamente o que faltou. Nunca uma análise calculada sobre dados inventados.
- **IA como apoio, não como dependência.** O parecer gerado por IA tem *fallback* determinístico local e passa pela revisão da equipe NEXO antes de chegar ao cliente.
- **LGPD desde a arquitetura.** Só indicadores agregados e o ranking da Curva ABC vão para o banco, nunca as transações linha a linha.
- **Segurança reforçada.** Proteção CSRF, *rate limiting*, sessão revalidada a cada requisição, WebSocket com origens restritas e CI de segurança a cada pull request.

## 📦 Repositórios

| Repositório | O que tem | Visibilidade |
| :--- | :--- | :---: |
| **Nexo-Faturamento-Inteligente** | Plataforma completa: portal SaaS em Flask (Admin × Cliente), motor de ETL, NexoBot, landing comercial e CI de segurança. | 🔒 Privado |
| [**nexofaturamentointeligente-coder**](https://github.com/nexofaturamentointeligente-coder/nexofaturamentointeligente-coder) | Este perfil: overview, identidade visual e assets da marca. | 🌐 Público |

## 🗺️ Roadmap

- [x] **Fase 1: Arquitetura & Engine Core**
  - Pipeline de ETL em Python/Pandas e lógica do Indicador de Pressão de Estoque.
  - Portal responsivo em tema escuro, com dashboards interativos.
  - Parecer estratégico com IA, exportação em PDF, NexoBot e notificações em tempo real.
- [ ] **Fase 2: Landing comercial & De-Para dinâmico**
  - Reestruturação comercial da landing page, orientada à conversão.
  - Interface de mapeamento dinâmico de colunas, para compatibilidade com qualquer PDV.
  - Integração com gateway de WhatsApp para alertas automáticos.
- [ ] **Fase 3: Tração regional em Brasília (DF)**
  - Programa de clientes piloto em 3 lojas de tintas locais.
  - Cases de sucesso e depoimentos em vídeo.
  - Apresentação para aceleradoras e programas de fomento (Cotidiano, FAP-DF, Centelha).

<!--
  Seções opcionais: descomente quando fizer sentido.

## 👥 Equipe

<div align="center">
  <a href="https://github.com/USUARIO_SOCIO_1"><img src="https://github.com/USUARIO_SOCIO_1.png" width="80" alt="Sócio / Lead Dev" /><br /><b>Sócio / Lead Dev</b></a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://github.com/USUARIO_SOCIO_2"><img src="https://github.com/USUARIO_SOCIO_2.png" width="80" alt="Sócio / Co-Founder" /><br /><b>Sócio / Co-Founder</b></a>
</div>

## 📈 Atividade

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=nexofaturamentointeligente-coder&theme=dark&background=0A0711&stroke=A855F7&ring=A855F7&fire=F97316&currStreakLabel=C28AFF&currStreakNum=F3F1F8&sideNums=F3F1F8&sideLabels=A9A6BA&dates=6E6A85&border=2D1B47" width="100%" alt="Sequência de contribuições" />
</div>
-->

## 📬 Vamos transformar o varejo juntos?

<div align="center">

<a href="https://nexo-faturamento-inteligente-render.onrender.com"><img src="https://img.shields.io/badge/Site-Conhe%C3%A7a_o_NEXO-8B3CDE?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Site do NEXO" /></a>
<a href="https://nexo-faturamento-inteligente-render.onrender.com/como-aderir"><img src="https://img.shields.io/badge/Como_obter_acesso-13111C?style=for-the-badge&logo=rocket&logoColor=F97316" alt="Como obter acesso ao NEXO" /></a>

<!--
  Canais oficiais: descomente quando estiverem ativos.
<a href="mailto:EMAIL_OFICIAL"><img src="https://img.shields.io/badge/E--mail-Suporte-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail de suporte" /></a>
<a href="https://wa.me/55DDDNUMERO"><img src="https://img.shields.io/badge/WhatsApp-Atendimento-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" /></a>
<a href="https://www.linkedin.com/company/PAGINA_NEXO"><img src="https://img.shields.io/badge/LinkedIn-NEXO-0A66C2?style=for-the-badge" alt="LinkedIn" /></a>
-->

<br />

<img src="assets/nexo-footer.svg" width="100%" alt="NEXO — Dados. Análise. Decisão." />

<sub>© 2026 NEXO — Faturamento Inteligente. Todos os direitos reservados.</sub>

</div>
