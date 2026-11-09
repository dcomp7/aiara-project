# Fichamento das citações da monografia

---

## Introdução

| # | Chave LaTeX | Tipo | Título | Status | Resumo executivo | URL / localização exata |
|---|---|---|---|---|---|---|
| 1 | `pinto2020antropoceno` | Artigo científico | O Antropoceno e a mudança climática: a percepção e a consciência dos brasileiros segundo a pesquisa IBOPE | ✅ Existe. ⚠️ Adequação do trecho: trata de percepção da mudança climática, não de rios. Sustenta pouco a afirmação sobre temas "técnicos e distantes da vivência". | Artigo (Pinto, Pires e Georges, *Desenvolvimento e Meio Ambiente*, v. 54, 2020) que reanalisa uma pesquisa do IBOPE de 2011 sobre a percepção do aquecimento global. Não vê negacionismo, mas também não vê sinais de reação ao modelo de desenvolvimento atual. | https://revistas.ufpr.br/made/article/view/67833 · DOI https://doi.org/10.5380/dma.v54i0.67833 |
| 2 | `sosma2023atlas` | Relatório técnico | Atlas dos Remanescentes Florestais da Mata Atlântica: Período 2021–2022 | 🔴 12,4% é a fração de matas maduras e bem conservadas (> 3 ha); o total de vegetação nativa remanescente aparece como ~24%. 🔴 "Mais de 150 milhões de ha" não bate com o Atlas (130.973.638 ha na Área de Aplicação da Lei). ⚠️ URL do `.bib` é uma notícia, não o relatório. | Relatório da SOS Mata Atlântica com o INPE (maio/2023). Mapeia remanescentes e desmatamento (a partir de 3 ha). Registrou 20.075 ha desmatados no período, queda de ~7%. | PDF: https://acervo.socioambiental.org/sites/default/files/documents/13d00112.pdf (cópia hospedada fora da SOS; confirmar a página do 12,4%) |
| 3 | `absaber2006ecossistemas` | Livro | Ecossistemas do Brasil | ⚠️ Sem página/capítulo: não dá para conferir o trecho sobre abrangência do bioma. | Livro de Aziz Ab'Sáber (Metalivros, 2006) sobre os domínios e ecossistemas brasileiros. É a origem da expressão "mares de morros". | Livro, ISBN 978-85-85371-66-1. Sem URL e sem página. |
| 4 | `ana_hidroweb2023` | Página web / sistema | HidroWeb: Sistema de Informações Hidrológicas – Documentação da API | ⚠️ URL não aberta por mim. ⚠️ Título diz "Documentação da API", mas o uso é descrever o sistema. | Sistema da ANA com acesso público aos dados da Rede Hidrometeorológica Nacional (chuva, nível, vazão), inclusive por API. | https://www.snirh.gov.br/hidroweb/apresentacao (bib) |
| 5 | `sosma_observandorios` | Página web / programa | Observando Rios *(título no .bib; o nome oficial é "Observando os Rios")* | 🔴 **Chave quebrada no `.bib`:** a entrada está como `@misc{f,`. O `\cite{sosma_observandorios}` fica indefinido. ⚠️ Título sem o "os". ⚠️ O texto cita "pH, turbidez, temperatura e resíduos sólidos", mas as fontes divergem (veja `reis2026observando`). | Página do programa de ciência cidadã da SOS Mata Atlântica. Voluntários treinados coletam mensalmente com kit próprio e geram um IQA por ponto. Os dados ficam públicos no site. | http://observandoosrios.sosma.org.br/ (bib, não aberta) |
| 6 | `openai2022chatgpt` | Post online (blog) | Introducing ChatGPT | ⚠️ Data de acesso em `note`, fora do padrão `urlaccessdate` dos demais. | Post de lançamento do ChatGPT (30/11/2022), assistente conversacional baseado em modelo de linguagem. | https://web.archive.org/web/20221130190543/https://openai.com/blog/chatgpt/ (bib, snapshot do dia do lançamento) |
| 7 | `unesco2023genai` | Relatório técnico (guia) | Guia para a IA generativa na educação e na pesquisa | ⚠️ Chave diz 2023, ano no `.bib` é 2024 (edição em português). ⚠️ Sem autores (Miao e Holmes). | Primeiro guia global da UNESCO sobre IA generativa na educação: regulação, privacidade, idade mínima, formação docente e abordagem centrada no humano. | https://unesdoc.unesco.org/ark:/48223/pf0000390241_por (bib, não aberta) |
| 8 | `designcouncil2019` | Relatório técnico (framework) | Framework for Innovation: Design Council's Evolved Double Diamond | ⚠️ URL do `.bib` pode redirecionar (o caminho atual que conheço é `/our-resources/framework-for-innovation/`). | Versão revisada do Double Diamond (Descobrir, Definir, Desenvolver, Entregar), com princípios, métodos e papel da cultura organizacional. | https://www.designcouncil.org.uk/resources/framework-for-innovation/ (bib) |

---

## 2_fundamentacao_teorica.tex

| # | Chave LaTeX | Tipo | Título | Status | Resumo executivo | URL / localização exata |
|---|---|---|---|---|---|---|
| 1 | `tucci2009hidrologia` | Livro | Hidrologia: Ciência e Aplicação (4ª ed.) | ⚠️ Citada 4x sem página (bacia, componentes, variáveis, história). | Manual brasileiro de hidrologia: ciclo hidrológico, bacias, precipitação, vazão e modelagem. | Livro (UFRGS/ABRH, 2009). Sem URL. |
| 2 | `villela1975hidrologia` | Livro | Hidrologia Aplicada | ⚠️ Edição de 1975 e sem página. | Texto clássico brasileiro de hidrologia aplicada. Usado junto com Tucci para definir bacia hidrográfica. | Livro (McGraw-Hill do Brasil, 1975). Sem URL. |
| 3 | `brasil1997lei9433` | Legislação | Lei nº 9.433/1997 (Política Nacional de Recursos Hídricos) | ⚠️ O texto também afirma que a Lei 9.984/2000 criou a ANA, sem citar essa lei (não está no `.bib`). | Institui a PNRH, define a bacia como unidade de gestão e cria o SINGREH. | https://www.planalto.gov.br/ccivil_03/leis/l9433.htm (bib) |
| 4 | `chow1988applied` | Livro | Applied Hydrology | ⚠️ Sem página. | Livro-texto de hidrologia (McGraw-Hill, 1988), citado para a estrutura da bacia. | Livro. Sem URL. |
| 5 | `kennish2002estuaries` | Livro | Ecology of Estuaries: Anthropogenic Effects | 🔴 Chave diz 2002, ano no `.bib` é 1992. ⚠️ Conferir se a obra trata da intrusão da cunha salina por estiagem. | Livro (CRC Press) sobre ecologia de estuários e efeitos de atividades humanas. | Livro. Sem URL. |
| 6 | `ward2000principles` | Livro | Principles of Hydrology (4ª ed.) | ⚠️ Sem página. | Livro-texto sobre como bacias transformam chuva em vazão e os fatores que controlam isso. | Livro (McGraw-Hill, 2000). Sem URL. |
| 7 | `herschy1995streamflow` | Livro (editado) | Streamflow Measurement (2ª ed.) | ⚠️ Citada 2x (nilômetros e curvas-chave), sem página. | Referência sobre medição de vazão: métodos, curvas-chave e história da hidrometria. | Livro (E & FN Spon, 1995). Sem URL. |
| 8 | `wmo2008guide` | Relatório técnico | Guide to Hydrological Practices | ⚠️ URL é a home da biblioteca da OMM. ⚠️ Citada 3x sem página. | Guia da OMM (WMO-No. 168, 6ª ed.) com procedimentos de estações, medição de vazão e controle de qualidade. | https://library.wmo.int (bib, genérica) |
| 9 | `horsburgh2011observations` | Artigo científico | An Integrated System for Publishing Environmental Observations Data | 🔴 Metadados provavelmente errados: pelo que conheço, o artigo é de 2009, *Environmental Modelling & Software* 24(8), 879–888, e não 2011, v. 26(2). Confirmar pelo DOI. | Descreve um sistema integrado para publicar dados de observações ambientais (série CUAHSI). | DOI provável: 10.1016/j.envsoft.2009.01.002 (confirmar) |
| 10 | `ana_hidroweb2023` | Página web / sistema | HidroWeb | ⚠️ Aqui é chamado de "principal fonte de dados hidrológicos do portal", mas na seção de Resultados o fluxo automatizado cobre só o Observando os Rios. | → ver Seção 1 #4 | → ver Seção 1 #4 |
| 11 | `conama2005` | Legislação | Resolução CONAMA nº 357/2005 | ⚠️ Autor no `.bib` é "Brasil"; o órgão é o CONAMA. ⚠️ A Marta menciona "atualizações" (ex.: Res. 430/2011), que não estão citadas. | Classifica corpos de água e define padrões por classe de uso. | https://www.mma.gov.br/estruturas/sqa/_arquivos/res35705.pdf (bib) |
| 12 | `brown1970wqi` | Artigo (periódico técnico) | A Water Quality Index — Do We Dare? | ✅ Confirmado como referência do NSF-WQI pelo próprio artigo Reis et al. 2026. | Propõe o Water Quality Index da National Sanitation Foundation, base do IQA. | *Water & Sewage Works* 117(10), 339–343. Sem URL. |
| 13 | `cetesb2023qualidade` | Relatório técnico | Qualidade das Águas Interiores no Estado de São Paulo | ⚠️ Citada 3x (IQA, agências estaduais, UGRHIs). Confirmar qual edição anual e a página de cada afirmação. | Relatório anual da CETESB com IQA e outros índices por UGRHI. | https://cetesb.sp.gov.br/aguas-interiores/publicacoes-e-relatorios/relatorios/ (bib) |
| 14 | `ana2021conjuntura` | Relatório técnico | Conjuntura dos Recursos Hídricos no Brasil 2021: Informe Anual | ⚠️ Confirmar título exato e a edição (a ANA publica "Informe Anual" e "Relatório Pleno"). ⚠️ Citada 2x sem página. | Panorama anual da ANA sobre disponibilidade, demanda e rede de monitoramento. | https://www.ana.gov.br/noticias/conjuntura-dos-recursos-hidricos-no-brasil-2021 (bib) |
| 15 | `sosma_observandorios` | Página web / programa | Observando Rios | 🔴 Chave quebrada no `.bib` (`f`). | → ver Seção 1 #5 | → ver Seção 1 #5 |
| 16 | `aceves2017citizen` | Artigo científico | The Accuracy of Citizen Science Data: A Quantitative Review | ⚠️ Conferir se "qualidade comparável à de coletas profissionais para diversos parâmetros" reflete a conclusão da revisão (a acurácia costuma variar por projeto e protocolo). | Revisão quantitativa que compara dados de ciência cidadã com dados profissionais. | *Bull. Ecol. Soc. Am.* 98(4), 278–290. DOI: 10.1002/bes2.1336 (confirmar) |
| 17 | `gfw2014` | Plataforma web | Global Forest Watch | ⚠️ URL é a home; indicar a data de acesso no texto ajuda. | Plataforma do WRI com alertas de desmatamento quase em tempo real. | https://www.globalforestwatch.org (bib) |
| 18 | `openaq2016` | Plataforma web | OpenAQ | ⚠️ "Mais de cem países" é dado variável; conferir hoje. | Plataforma aberta que agrega medições de qualidade do ar. | https://openaq.org (bib) |
| 19 | `iqair2023` | Plataforma web | IQAir AirVisual | ⚠️ Fonte comercial. Vale apontar a página que sustenta o "forte apelo visual". | Plataforma de índice de qualidade do ar voltada ao usuário final. | https://www.iqair.com (bib) |
| 20 | `earthecho2022` | Plataforma web | EarthEcho Water Challenge | ⚠️ Confirmar se a URL do programa ainda está ativa. | Programa global de monitoramento participativo da água. | https://www.earthecho.org/programs/water-challenge (bib) |
| 21 | `mapbiomas2023relatorio` | Relatório técnico | Relatório Anual do Desmatamento no Brasil 2022 | 🔴 O relatório trata de desmatamento e não sustenta a frase sobre barreiras de usabilidade das plataformas. ⚠️ URL é a home. | Relatório anual (RAD) do MapBiomas sobre alertas de desmatamento. | https://mapbiomas.org (bib). Para usabilidade, cite um estudo próprio. |
| 22 | `preece2015interaction` | Livro | Interaction Design: Beyond Human–Computer Interaction (4ª ed.) | ⚠️ Citada também em Resultados (prototipação). Sem página. | Livro-texto de IHC e design de interação. | Livro (Wiley, 2015). Sem URL. |
| 23 | `norman2013design` | Livro | The Design of Everyday Things (ed. revista) | ⚠️ Sem página. | Introduz *affordances*, modelos conceituais e mapeamentos naturais. | Livro (Basic Books, 2013). Sem URL. |
| 24 | `tufte2001visual` | Livro | The Visual Display of Quantitative Information (2ª ed.) | ⚠️ Citada 2x. A "razão dados-tinta" está no cap. 4. | Clássico sobre excelência gráfica e razão dados-tinta. | Livro (Graphics Press, 2001). Sem URL. |
| 25 | `ware2012information` | Livro | Information Visualization: Perception for Design (3ª ed.) | ⚠️ Sem página. | Base perceptual da visualização (posição, cor, tamanho). | Livro (Morgan Kaufmann, 2012). Sem URL. |
| 26 | `munzner2014visualization` | Livro | Visualization Analysis and Design | ✅ O modelo what/why/how é dela. | Propõe analisar visualizações por dados, tarefas e técnicas. | Livro (CRC Press, 2014). Sem URL. |
| 27 | `maceachren1995maps` | Livro | How Maps Work | ⚠️ Sem página. | Teoria da comunicação e da representação cartográfica. | Livro (Guilford, 1995). Sem URL. |
| 28 | `roth2015interacting` | Artigo científico | Interacting with Maps: The Science and Practice of Cartographic Interaction | 🔴 Não localizei com certeza um artigo com esse título na *The Pennsylvania Geographer*; ele coincide com o título da tese de doutorado de Roth (Penn State, 2011). Conferir. Citada também em Resultados. | Revisa a interação cartográfica e as dificuldades de usuários não especializados com mapas digitais. | *The Pennsylvania Geographer* 53(1), 1–43 (conforme bib, a conferir) |
| 29 | `brown2008design` | Artigo (periódico) | Design Thinking | ⚠️ Sem página no uso. | Artigo da HBR que apresenta o design thinking como abordagem centrada nas pessoas. | *HBR* 86(6), 84–92. https://hbr.org/2008/06/design-thinking (confirmar) |
| 30 | `simon1996sciences` | Livro | The Sciences of the Artificial (3ª ed.) | ✅ A ideia de design como "transformar situações existentes em preferíveis" é dele. | Define design como atividade de criar artefatos para atingir metas. | Livro (MIT Press, 1996). Sem URL. |
| 31 | `plattner2011design` | Livro (editado) | Design Thinking: Understand – Improve – Apply | ⚠️ O "modelo de cinco etapas da d.school" costuma ser creditado ao material da d.school/Stanford; conferir se este livro o descreve. | Coletânea do HPI sobre design thinking. | Livro (Springer, 2011). Sem URL. |
| 32 | `designcouncil2005` | Relatório técnico | Eleven Lessons | ⚠️ URL é a home do Design Council. | Estudo de 2005 que apresentou o Double Diamond original. | https://www.designcouncil.org.uk (bib, genérica) |
| 33 | `designcouncil2019` | Relatório técnico | Framework for Innovation | → ver Seção 1 #8 | → ver Seção 1 #8 | → ver Seção 1 #8 |
| 34 | `banathy1996designing` | Livro | Designing Social Systems in a Changing World | ⚠️ Sem página. O Design Council credita a ideia divergente/convergente a Banathy. | Teoria de design de sistemas sociais, com ciclos de divergência e convergência. | Livro (Plenum, 1996). Sem URL. |
| 35 | `lazar2017research` | Livro | Research Methods in Human–Computer Interaction (2ª ed.) | ⚠️ Sem página. | Manual de métodos de pesquisa em IHC, incluindo entrevistas. | Livro (Morgan Kaufmann, 2017). Sem URL. |
| 36 | `braun2006thematic` | Artigo científico | Using Thematic Analysis in Psychology | ✅ As seis fases descritas no texto correspondem ao artigo. ⚠️ Em Materiais e Métodos a análise temática não é citada, embora o Resumo a mencione. | Artigo que sistematiza a análise temática em seis fases. | *Qual. Res. Psychol.* 3(2), 77–101. DOI: 10.1191/1478088706qp063oa |
| 37 | `bonney2014citizen` | Artigo (Science) | Next Steps for Citizen Science | 🔴 No `.bib` está como `@incollection` com `booktitle = Science`; o certo é `@article` com `journal`. ⚠️ Conferir a citação literal "coleta, categorização, transcrição ou análise de dados científicos" (p. 1436). | Policy Forum que propõe prioridades para a ciência cidadã. | *Science* 343(6178), 1436–1437. DOI: 10.1126/science.1251554 |
| 38 | `reis2026observando` | Artigo científico | Observando os Rios: Citizen Science Monitoring Water Quality in Brazil | ✅ Existe: *Citizen Science: Theory and Practice* v. 11, n. 1 (publicado em 29/01/2026), DOI confere. 🔴 `pages = {1--16}` e `note = {Artigo 2}`: o periódico indica "Page/Article: 2", então o campo deve ser `number`/`pages = {2}`. ⚠️ A tese diz que a concordância "superou 95%"; isso vale para ±1 categoria. A concordância exata foi 90%, 10% e 65% e, no Tietê, o Kappa médio foi 0,43. ⚠️ O artigo descreve 14 parâmetros (9 na introdução), a entrevista com o Gustavo cita 16 e o texto da tese cita outro conjunto: harmonizar. | Compara o IQA do programa com o da CETESB em três mesobacias (2002–2023). Concordância de ±1 categoria acima de 95% em todas. Em trechos urbanos (Guarulhos, São Paulo), o programa tende a classificar como "Regular" onde a CETESB dá "Ruim/Péssimo". | https://doi.org/10.5334/cstp.836 · PDF: https://theoryandpractice.citizenscienceassociation.org/articles/836/files/697b609165736.pdf |
| 39 | `fung2007full` | Livro | Full Disclosure: The Perils and Promise of Transparency | ⚠️ Livro de 2007: serve como base da transparência, não das plataformas GFW/OpenAQ/MapBiomas. Citada 3x sem página. | "Transparência direcionada": políticas de divulgação só funcionam se a informação for compreensível e entrar nas decisões de quem a usa. | Livro (Cambridge UP, 2007). Sem URL no `.bib`. DOI provável: 10.1017/CBO9780511511509 (confirmar) |
| 40 | `lorenzoni2007barriers` | Artigo científico | Barriers Perceived to Engaging with Climate Change among the UK Public and Their Policy Implications | ⚠️ Estudo sobre mudança climática no Reino Unido, extrapolado para rios. Confira se "informação local" é conclusão do artigo. | Investiga barreiras ao engajamento com a mudança climática, incluindo falta de conhecimento e percepção de distância. | *Global Environmental Change* 17(3–4), 445–459. DOI: 10.1016/j.gloenvcha.2007.01.004 |

**Observação:** a seção de aspectos geográficos do Tietê tem figuras pendentes (`[[inserir imagem]]`) e nenhuma citação para a hierarquia UGRHI/bacia além da CETESB.

---

## 2_objetivos.tex

Sem citações (`\cite`) nesta seção.

---

## 3_materiais_metodos.tex

| # | Chave LaTeX | Tipo | Título | Status | Resumo executivo | URL / localização exata |
|---|---|---|---|---|---|---|
| 1 | `designcouncil2019` | Relatório técnico | Framework for Innovation | → ver Seção 1 #8 | → ver Seção 1 #8 | → ver Seção 1 #8 |

**Observação:** a análise temática (`braun2006thematic`) é usada no Resumo e em Resultados, mas Materiais e Métodos não a descreve nem cita.

---

## 4_resultados_discussao.tex

| # | Chave LaTeX | Tipo | Título | Status | Resumo executivo | URL / localização exata |
|---|---|---|---|---|---|---|
| 1 | `aceves2017citizen` | Artigo científico | The Accuracy of Citizen Science Data | ⚠️ Aqui é usada para o estudo do CENA/USP citado pelo Gustavo, que é `reis2026observando`: considere citá-lo nesse ponto. | → ver Seção 2 #16 | → ver Seção 2 #16 |
| 2 | `norman2013design` | Livro | The Design of Everyday Things | → ver Seção 2 #23 | → ver Seção 2 #23 | → ver Seção 2 #23 |
| 3 | `roth2015interacting` | Artigo científico | Interacting with Maps | 🔴 Metadados a conferir | → ver Seção 2 #28 | → ver Seção 2 #28 |
| 4 | `fung2007full` | Livro | Full Disclosure | ⚠️ Sem página. | → ver Seção 2 #39 | → ver Seção 2 #39 |
| 5 | `pruitt2003personas` | Artigo (congresso) | Personas: Practice and Theory | ⚠️ Sem página. As personas são hipóteses sem validação, o que o texto já informa. | Artigo (DUX'03) que discute a prática e a teoria de personas. | ACM, 2003. DOI: 10.1145/997078.997089 (confirmar) |
| 6 | `openai2022chatgpt` | Post online | Introducing ChatGPT | → ver Seção 1 #6 | → ver Seção 1 #6 | → ver Seção 1 #6 |
| 7 | `unesco2023genai` | Relatório técnico | Guia para a IA generativa | ⚠️ Chave 2023 × ano 2024 | → ver Seção 1 #7 | → ver Seção 1 #7 |
| 8 | `mapbiomas2023relatorio` | Relatório técnico | RAD 2022 | 🔴 O relatório de desmatamento não sustenta "navegação por camadas e séries temporais"; cite a plataforma. | → ver Seção 2 #21 | → ver Seção 2 #21 |
| 9 | `gfw2014` | Plataforma web | Global Forest Watch | → ver Seção 2 #17 | → ver Seção 2 #17 | → ver Seção 2 #17 |
| 10 | `iqair2023` | Plataforma web | IQAir AirVisual | → ver Seção 2 #19 | → ver Seção 2 #19 | → ver Seção 2 #19 |
| 11 | `openaq2016` | Plataforma web | OpenAQ | → ver Seção 2 #18 | → ver Seção 2 #18 | → ver Seção 2 #18 |
| 12 | `brasil2018lgpd` | Legislação | Lei nº 13.709/2018 (LGPD) | ✅ Lei real. ⚠️ Citada 3x sem artigo específico (ex.: art. 14 para dados de crianças). | Lei Geral de Proteção de Dados Pessoais. | https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm (bib) |
| 13 | `brasil2025ecadigital` | Legislação | Lei nº 15.211/2025 (ECA Digital) | ⚠️ Confirmar a data de vigência. Citada 3x sem artigo. | Dispõe sobre a proteção de crianças e adolescentes em ambientes digitais. | https://www.planalto.gov.br/ccivil_03/_ato2023-2026/2025/lei/L15211.htm (bib) |
| 14 | `anthropic2025projects` | Página web (ajuda) | What are projects? | ⚠️ URL é a home da central de ajuda; usar o artigo específico. Fonte do fornecedor do assistente que ajudou a redigir (Seção 3.2). | Explica projetos do Claude: instruções persistentes e documentos de referência. | https://support.claude.com (bib, genérica) |
| 15 | `openai2025projects` | Página web (ajuda) | Projects in ChatGPT | ⚠️ URL é a home da central de ajuda; usar o artigo específico. | Descreve projetos no ChatGPT com instruções e arquivos. | https://help.openai.com (bib, genérica) |
| 16 | `dillenbourg2013orchestration` | Artigo científico | Design for Classroom Orchestration | ⚠️ Sem página. | Propõe a orquestração em sala de aula como coordenação do fluxo de atividades pelo docente. | *Computers & Education* 69, 485–492. DOI: 10.1016/j.compedu.2013.04.013 (confirmar) |
| 17 | `holstein2019codesigning` | Artigo científico | Co-Designing a Real-Time Classroom Orchestration Tool to Support Teacher–AI Complementarity | ⚠️ Citada 2x. O estudo é de codesign de ferramenta com professores, não de governança. | Codesign de ferramenta de orquestração com professores. | *J. Learning Analytics* 6(2), 27–52 |
| 18 | `preece2015interaction` | Livro | Interaction Design | → ver Seção 2 #22 | → ver Seção 2 #22 | → ver Seção 2 #22 |
| 19 | `hohpe2003eip` | Livro | Enterprise Integration Patterns | ⚠️ Padrões de integração por mensageria; verificar se sustenta "evitar dependência da estrutura interna dos dados". | Catálogo de padrões de integração. | Livro (Addison-Wesley, 2003). Sem URL. |
| 20 | `fielding2000architectural` | Tese de doutorado | Architectural Styles and the Design of Network-based Software Architectures | ⚠️ Sustenta o REST, não o uso de JSON. | Tese que define o estilo arquitetural REST. | https://ics.uci.edu/~fielding/pubs/dissertation/top.htm (confirmar) |
| 21 | `laravel_docs` | Documentação técnica | Laravel Documentation | ⚠️ Indicar versão. | Documentação oficial do framework Laravel. | https://laravel.com/docs (bib) |
| 22 | `postgresql_docs` | Documentação técnica | PostgreSQL Documentation | ⚠️ Indicar versão. | Documentação oficial do PostgreSQL (incluindo JSONB). | https://www.postgresql.org/docs/ (bib) |
| 23 | `react_docs` | Documentação técnica | React Documentation | ⚠️ Citada 2x. | Documentação oficial do React. | https://react.dev (bib) |
| 24 | `fowler2015monolithfirst` | Post online | MonolithFirst | ✅ Apoia a recomendação de começar monolítico. | Artigo de Martin Fowler sobre começar por um monólito. | https://martinfowler.com/bliki/MonolithFirst.html (bib) |
| 25 | `newman2021building` | Livro | Building Microservices (2ª ed.) | ⚠️ Sem página. | Livro sobre decomposição e evolução de arquiteturas de microsserviços. | Livro (O'Reilly, 2021). Sem URL. |
| 26 | `owasp2025llm` | Página web | OWASP Top 10 for LLM Applications | ⚠️ Indicar o item (LLM01 – *Prompt Injection*). | Lista dos principais riscos de segurança em aplicações com LLMs. | https://owasp.org/www-project-top-10-for-large-language-model-applications/ (bib) |
| 27 | `leaflet_docs` | Documentação técnica | Leaflet | ⚠️ Autor no `.bib` mistura pessoa e coletivo. | Biblioteca JavaScript de mapas interativos. | https://leafletjs.com (bib) |
| 28 | `w3c2018wcag` | Norma técnica | WCAG 2.1 | ⚠️ Existe a WCAG 2.2 (W3C, 2023); considere atualizar ou justificar o uso da 2.1. | Diretrizes de acessibilidade para conteúdo web. | https://www.w3.org/TR/WCAG21/ (bib) |
| 29 | `nielsen2020ux` | Livro | Mobile Usability | 🔴 Pelo que conheço, é de 2012 (New Riders), e não 2020 / Nielsen Norman Group. ⚠️ É sobre usabilidade móvel; a abordagem *mobile first* costuma ser creditada a Luke Wroblewski (2011). | Livro de Nielsen e Budiu sobre usabilidade em dispositivos móveis. | Livro. Sem URL. |

**Observações da seção:**
- Sem citação: "polígonos municipais do IBGE" (o `.bib` tem `ibge2022malhas`, mas não é citada), Recharts, KoboCollect e Plataforma Povos.
- As funcionalidades das entrevistas (Gustavo, Marta e Paola) são citadas pelos Anexos.

---

## 5_conclusao.tex

Sem citações (`\cite`) nesta seção.