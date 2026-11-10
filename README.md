# Conformidade: checklist de boas práticas

Checklist de preparação, manutenção, governança e sustentabilidade dos projetos do [Rondoscópio](https://github.com/Rondoscopio), com base no [Open Source Guides](https://opensource.guide/) e adaptações às necessidades da iniciativa.

**Finalidade:** orientar avaliações e melhorias. Esta lista não é certificação de conformidade, avaliação jurídica nem declaração de que cada prática já esteja implementada. Os itens começam desmarcados porque ainda precisam de verificação. Uma caixa desmarcada não prova ausência da prática. A conclusão deve ser acompanhada, quando possível, de referência verificável (arquivo, configuração, issue, commit, política ou procedimento).

**Estado dos projetos:** em formação. As práticas aplicáveis dependem do estágio e da natureza de cada repositório. Itens relativos a software executável e serviços em operação podem ser tratados como não aplicáveis enquanto esses componentes não existirem.

## Como acompanhar

- [ ] Revisar a aplicabilidade deste checklist para cada repositório da organização.
- [ ] Associar evidências aos requisitos confirmados e registrar pendências em issues.
- [ ] Definir responsáveis e prioridades para os itens aplicáveis.
- [ ] Rever periodicamente o checklist e registrar mudanças relevantes.

## 1. Identidade e preparação do projeto

**Referência:** [Open Source Guides](https://opensource.guide/starting-a-project/).

- [ ] Definir claramente missão, visão e objetivos.
- [ ] Explicar o problema que o projeto pretende resolver.
- [ ] Delimitar o escopo e os limites de atuação.
- [ ] Identificar o público-alvo e os possíveis colaboradores.
- [ ] Explicar a escolha pelo desenvolvimento open source.
- [ ] Definir os tipos de contribuição externa aceitos.
- [ ] Verificar nomes de projetos e eventuais conflitos de marca.
- [ ] Manter um README acessível e atualizado em cada repositório.
- [ ] Informar estágio de desenvolvimento, funcionalidades disponíveis e limitações.
- [ ] Manter um roadmap público com prioridades e dependências.
- [ ] Organizar issues com títulos, descrições e labels.
- [ ] Identificar pessoas responsáveis pela manutenção.
- [ ] Planejar redundância no acesso administrativo quando houver uma equipe.
- [ ] Definir canais e estratégias responsáveis de divulgação.

## 2. Documentação e experiência de contribuição

**Referência:** [Open Source Guides](https://opensource.guide/best-practices/).

- [ ] Revisar o README para explicar finalidade, utilidade, início rápido e ajuda.
- [ ] Publicar ou revisar CONTRIBUTING.md.
- [ ] Explicar como reportar bugs e propor funcionalidades.
- [ ] Documentar configuração do ambiente de desenvolvimento.
- [ ] Descrever como executar testes e validar alterações.
- [ ] Documentar convenções de código, commits e pull requests.
- [ ] Definir critérios de avaliação e aceite de propostas.
- [ ] Disponibilizar templates de issues e pull requests.
- [ ] Separar bugs, ideias, dúvidas e discussões em canais apropriados.
- [ ] Registrar decisões técnicas relevantes e suas justificativas.
- [ ] Documentar arquiteturas, integrações e dependências quando existirem.
- [ ] Manter documentação sincronizada com código e comportamento reais.
- [ ] Informar versões, plataformas e ambientes suportados.
- [ ] Sinalizar conteúdos técnicos desatualizados.
- [ ] Publicar changelogs ou notas de versão quando houver lançamentos.

## 3. Licenciamento e aspectos jurídicos

**Referência:** [Open Source Guides](https://opensource.guide/legal/).

- [ ] Declarar uma licença apropriada em cada repositório.
- [ ] Incluir o texto integral da licença e identificadores claros, quando aplicável.
- [ ] Distinguir licenciamento de software, documentação, dados, imagens e marcas.
- [ ] Registrar atribuições e avisos de direitos autorais pertinentes.
- [ ] Verificar compatibilidade de licenças das dependências.
- [ ] Conferir direitos de uso e redistribuição de materiais de terceiros.
- [ ] Explicar sob qual licença as contribuições serão recebidas.
- [ ] Avaliar se acordos adicionais de contribuição são realmente necessários.
- [ ] Verificar restrições a nomes, logotipos e marcas de terceiros.
- [ ] Documentar critérios para eventuais mudanças de licenciamento.
- [ ] Não presumir que conteúdo público na internet seja livre para reutilização.

## 4. Segurança e cadeia de suprimentos

**Referência:** [Open Source Guides](https://opensource.guide/security-best-practices-for-your-project/).

- [ ] Exigir autenticação multifator nas contas privilegiadas.
- [ ] Aplicar o princípio do menor privilégio a pessoas e automações.
- [ ] Proteger a branch principal contra alterações indevidas.
- [ ] Configurar revisões e verificações obrigatórias antes do merge, quando aplicável.
- [ ] Incorporar análise estática de segurança (SAST) ao desenvolvimento.
- [ ] Ativar detecção de segredos e credenciais nos repositórios.
- [ ] Impedir o versionamento de tokens, senhas, chaves privadas e dados sensíveis.
- [ ] Monitorar vulnerabilidades nas dependências.
- [ ] Avaliar atualização automatizada de dependências com Dependabot ou Renovate.
- [ ] Verificar a procedência e o licenciamento das dependências.
- [ ] Gerar SBOM para artefatos distribuídos, quando aplicável.
- [ ] Publicar ou revisar SECURITY.md.
- [ ] Estabelecer canal privado para comunicação de vulnerabilidades.
- [ ] Avaliar Private Vulnerability Reporting do GitHub.
- [ ] Documentar modelo de ameaças e limites de confiança.
- [ ] Definir procedimento de resposta a incidentes.
- [ ] Definir responsáveis pela triagem, correção e comunicação de vulnerabilidades.
- [ ] Estabelecer critérios para publicação de avisos e correções de segurança.
- [ ] Revisar periodicamente acessos administrativos e permissões.

## 5. Comunidade e colaboração

**Referências:** [guia 1](https://opensource.guide/building-community/) · [guia 2](https://opensource.guide/code-of-conduct/).

- [ ] Publicar um código de conduta.
- [ ] Definir o alcance do código de conduta, inclusive nos canais comunitários.
- [ ] Disponibilizar canal de relato de violações de conduta.
- [ ] Prever alternativa de relato quando a pessoa responsável estiver envolvida.
- [ ] Definir procedimento de apuração, resposta e medidas possíveis.
- [ ] Marcar tarefas apropriadas com good first issue.
- [ ] Marcar tarefas apropriadas com help wanted.
- [ ] Reconhecer contribuições em código, documentação, pesquisa, tradução e revisão.
- [ ] Responder a dúvidas e propostas com respeito e clareza.
- [ ] Justificar recusas de contribuições de forma proporcional.
- [ ] Registrar decisões públicas sempre que não envolverem conteúdo confidencial.
- [ ] Reduzir barreiras desnecessárias à participação.
- [ ] Definir canais distintos para suporte, propostas e discussões.
- [ ] Informar expectativas realistas de tempo de resposta.
- [ ] Atribuir corretamente a autoria e o trabalho dos colaboradores.

## 6. Governança, liderança e transparência

**Referência:** [Open Source Guides](https://opensource.guide/leadership-and-governance/).

- [ ] Documentar papéis de contribuidores, mantenedores e administradores.
- [ ] Definir quem pode revisar e aprovar alterações.
- [ ] Definir critérios para admissão de novos mantenedores.
- [ ] Estabelecer regras de concessão e revogação de acesso.
- [ ] Explicar como decisões importantes são tomadas.
- [ ] Criar procedimento de resolução de divergências.
- [ ] Definir como documentos de governança podem ser alterados.
- [ ] Distribuir responsabilidades e registrar seus limites.
- [ ] Registrar decisões institucionais e suas justificativas.
- [ ] Prever continuidade caso pessoas fundadoras se afastem.
- [ ] Evitar concentração desnecessária de autoridade e credenciais.
- [ ] Manter processos de decisão transparentes, proporcionais ao tamanho da comunidade.

## 7. Financiamento e sustentabilidade

**Referências:** [guia 1](https://opensource.guide/getting-paid/) · [guia 2](https://opensource.guide/maintaining-balance-for-open-source-maintainers/).

- [ ] Estimar custos de infraestrutura, manutenção e operação.
- [ ] Identificar fontes possíveis e legítimas de financiamento.
- [ ] Confirmar habilitação e funcionamento efetivo do GitHub Sponsors.
- [ ] Definir política pública de doações, patrocínios e outros apoios.
- [ ] Explicar destinação e prestação de contas dos recursos recebidos.
- [ ] Evitar prometer contrapartidas incompatíveis com a capacidade operacional.
- [ ] Documentar e administrar potenciais conflitos de interesses.
- [ ] Definir critérios para aceitar ou recusar patrocinadores.
- [ ] Planejar continuidade operacional e manutenção de longo prazo.
- [ ] Distribuir responsabilidades e conhecimento técnico.
- [ ] Estabelecer limites saudáveis para trabalho voluntário.
- [ ] Não anunciar suporte, garantias ou prazos inviáveis.
- [ ] Preparar procedimentos para períodos de inatividade.
- [ ] Formar novos mantenedores e diminuir dependência de uma única pessoa.

## 8. Acessibilidade

**Referência:** [Open Source Guides](https://opensource.guide/accessibility-best-practices-for-your-project/).

- [ ] Publicar política ou declaração de acessibilidade (por exemplo, ACCESSIBILITY.md).
- [ ] Definir metas de conformidade (por exemplo, WCAG nível AA).
- [ ] Garantir navegação completa por teclado.
- [ ] Utilizar HTML semântico nas interfaces.
- [ ] Incluir textos alternativos adequados nas imagens.
- [ ] Disponibilizar legendas e transcrições para conteúdos audiovisuais.
- [ ] Verificar contraste entre texto, interface e fundo.
- [ ] Respeitar preferência por movimento reduzido.
- [ ] Fornecer rótulos claros para controles e formulários.
- [ ] Não depender exclusivamente da cor para transmitir informação.
- [ ] Testar com tecnologias assistivas, incluindo leitores de tela.
- [ ] Validar zoom, reflow e layouts para dispositivos móveis.
- [ ] Automatizar testes de acessibilidade como complemento aos testes manuais.
- [ ] Permitir reporte específico de problemas de acessibilidade.
- [ ] Incluir acessibilidade nos critérios de revisão de alterações.
- [ ] Convidar pessoas com deficiência a avaliar a usabilidade.
- [ ] Em ferramentas CLI, oferecer ajuda clara, códigos de saída consistentes e saídas acessíveis.

## 9. Divulgação, usuários e métricas

**Referências:** [guia 1](https://opensource.guide/finding-users/) · [guia 2](https://opensource.guide/metrics/).

- [ ] Preparar uma apresentação curta e compreensível da iniciativa.
- [ ] Explicar os diferenciais em relação a iniciativas semelhantes.
- [ ] Manter um local central com informações e documentação.
- [ ] Disponibilizar exemplos reais e verificáveis quando existirem.
- [ ] Participar de comunidades pertinentes sem divulgação invasiva.
- [ ] Cooperar com projetos e organizações de objetivos compatíveis.
- [ ] Pesquisar necessidades reais de usuários e contribuidores.
- [ ] Solicitar feedback sobre documentos, produtos e fluxos.
- [ ] Acompanhar visualizações e acesso aos repositórios de forma proporcional.
- [ ] Monitorar stars, forks e clones sem confundi-los com impacto social.
- [ ] Medir participação, contribuições e retenção de colaboradores.
- [ ] Acompanhar tempo de resposta a issues e pull requests.
- [ ] Observar a saúde e sustentabilidade da comunidade.
- [ ] Usar métricas para melhorar prioridades, não para mascarar resultados.
- [ ] Evitar rastreamento invasivo e coleta desnecessária de dados de usuários.

## 10. Requisitos adicionais do Rondoscópio

Itens próprios da iniciativa, inspirados em seus objetivos institucionais. Não devem ser apresentados como exigências textuais do Open Source Guides.

- [ ] Distinguir fato documentado, indício, hipótese, interpretação e conclusão.
- [ ] Registrar proveniência, integridade e cadeia de tratamento dos registros.
- [ ] Publicar critérios de seleção e avaliação de fontes.
- [ ] Definir procedimentos de retificação e direito de resposta.
- [ ] Documentar proteção de denunciantes, fontes e informantes.
- [ ] Definir níveis de acesso e tratamento de registros restritos.
- [ ] Garantir rastreabilidade das etapas investigativas e das alterações.
- [ ] Documentar métodos estatísticos, algoritmos, parâmetros e limitações.
- [ ] Exigir revisão humana antes de conclusões sensíveis ou acusações públicas.
- [ ] Estabelecer política de uso responsável de inteligência artificial.
- [ ] Definir processo de correção de publicações e preservação do histórico.
- [ ] Estabelecer salvaguardas de independência político-partidária.
- [ ] Definir retenção, preservação, acesso e eliminação legalmente exigida de dados.
- [ ] Diferenciar explicitamente funcionalidades previstas, em desenvolvimento e operacionais.
- [ ] Publicar metodologia, limitações, incertezas e fontes de cada indicador.
- [ ] Documentar critérios de aceitação, recusa e transparência dos financiadores.

## Prioridades sugeridas

A organização das tarefas abaixo é uma sugestão de implementação, não uma ordem obrigatória do Open Source Guides.

1. **Fundamentos e responsabilidade:** escopo, README, licenças, orientações de contribuição, segurança e responsáveis.
2. **Colaboração e desenvolvimento:** templates, proteção de branches, testes, acessibilidade e revisão de alterações.
3. **Governança e sustentabilidade:** papéis, registro de decisões, métricas, prestação de contas, financiamento e formação de mantenedores.

## Projetos de referência

- [Constituição](https://github.com/Rondoscopio/constituicao): princípios, objetivos e governança proposta.
- [OSINT Rondônia](https://github.com/Rondoscopio/osint-rondonia): catálogo de fontes e ferramentas.
- [Amnésia](https://github.com/Rondoscopio/amnesia): coleta e monitoramento multimodal planejados.
- [Córtex](https://github.com/Rondoscopio/cortex): análise de dados e inteligência investigativa planejadas.
- [Portal](https://github.com/Rondoscopio/portal): interface pública planejada.
- [Ouvidoria](https://github.com/Rondoscopio/ouvidoria): canal de manifestações planejado.
- [Preservador](https://github.com/Rondoscopio/preservador): preservação distribuída planejada.
- [Arquivos comunitários](https://github.com/Rondoscopio/.github): políticas, modelos e perfil da organização.

## Fontes e interpretação

O [Open Source Guides](https://opensource.guide/) oferece orientações para comunidades e mantenedores de software livre. Este documento **resume e adapta** recomendações dos guias temáticos, sem reproduzi-los integralmente nem transformar sugestões em obrigações universais. Os requisitos investigativos da seção 10 são próprios do Rondoscópio. As recomendações deverão ser confrontadas com a legislação aplicável, as políticas institucionais e as características de cada projeto.
