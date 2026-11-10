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

## 11. Conformidade técnica automatizada

Checklist complementar para configurar e verificar qualidade de código, segurança, testes, supply chain, automação e governança técnica dos repositórios do Rondoscópio. As ferramentas citadas são referências para avaliação e podem ser substituídas por soluções equivalentes. Nem todas se aplicam a todos os projetos.

Um item só deverá ser marcado como concluído quando houver evidência de configuração e funcionamento, como arquivo versionado, comando reproduzível, workflow, relatório ou referência de execução. Instalação isolada não demonstra conformidade. Itens não aplicáveis deverão ser justificados. Controles obrigatórios não devem ser dispensados apenas para obter aprovação de um pull request.

### 11.1. Aplicabilidade e critérios de verificação

- [ ] Classificar requisitos como obrigatórios, recomendados ou não aplicáveis para cada repositório.
- [ ] Diferenciar requisitos de documentação, dados, bibliotecas, aplicações e infraestrutura.
- [ ] Aceitar ferramentas equivalentes quando entregarem garantias comparáveis.
- [ ] Justificar ferramentas com funcionalidades sobrepostas ou redundantes.
- [ ] Exigir evidência verificável para marcar requisitos como atendidos.
- [ ] Registrar exceções, justificativas, responsáveis, prazos e medidas compensatórias.
- [ ] Distinguir controles configurados, executados e aprovados.
- [ ] Revisar periodicamente configurações, limites e aplicabilidade.

### 11.2. Identidade, metadados e apresentação no GitHub

- [ ] Definir nome e descrição pública do repositório.
- [ ] Configurar os topics e a categoria apropriada do repositório.
- [ ] Configurar o endereço do site ou da documentação quando aplicável.
- [ ] Criar imagem de apresentação e configurar a Social Preview do GitHub.
- [ ] Manter README com propósito, recursos, estágio, limitações e instruções de uso.
- [ ] Padronizar badges relevantes, capitalização, cores e links dos indicadores.
- [ ] Validar se badges de status mostram workflows e informações corretas.
- [ ] Incluir licença apropriada com texto integral e identificador SPDX quando aplicável.
- [ ] Distinguir licenças de código, documentação, dados e imagens.
- [ ] Configurar SECURITY.md, CONTRIBUTING.md e CODE_OF_CONDUCT.md no repositório ou por padrões herdados da organização.
- [ ] Criar ou herdar templates de issues e pull requests.
- [ ] Verificar links, imagens e recursos do README e demais páginas.

### 11.3. CODEOWNERS, branch protection e rulesets

- [ ] Configurar CODEOWNERS com responsáveis por áreas e arquivos críticos.
- [ ] Confirmar que os code owners possuem acesso e permissões adequados.
- [ ] Definir branch principal e política de integração de alterações.
- [ ] Configurar GitHub Rulesets ou Branch Protection para a branch principal.
- [ ] Impedir force push na branch principal com proteção de histórico.
- [ ] Impedir exclusão da branch principal por regra de proteção.
- [ ] Exigir pull request antes do merge quando aplicável.
- [ ] Definir critérios de revisão e aprovação por outros mantenedores.
- [ ] Exigir revisão de code owners para alterações sensíveis quando necessário.
- [ ] Definir e exigir verificações de qualidade efetivamente executadas.
- [ ] Confirmar que nomes de checks obrigatórios correspondem a jobs reais e estáveis.
- [ ] Impedir merge com checks obrigatórios pendentes, cancelados ou reprovados.
- [ ] Exigir validação da versão atualizada da branch de destino quando adequado.
- [ ] Definir política de conversas não resolvidas e atualizações após revisão.
- [ ] Restringir bypasses com justificativa e rastreabilidade.
- [ ] Proteger arquivos de CI, CODEOWNERS e configurações de segurança contra modificações indevidas.
- [ ] Testar branch protection e quality gate com pull requests de verificação.

### 11.4. Ambiente reproduzível, just, Docker e Compose

- [ ] Padronizar comandos para lint, testes, verificação e geração de artefatos.
- [ ] Avaliar just como interface única para comandos do projeto.
- [ ] Usar Docker quando necessário para reproduzir o ambiente de validação.
- [ ] Usar Docker Compose quando houver ferramentas ou serviços coordenados.
- [ ] Documentar instalação, desenvolvimento, testes e comandos de manutenção.
- [ ] Organizar configurações comuns sem ocultar diferenças entre repositórios.
- [ ] Fixar ou restringir adequadamente versões das ferramentas.
- [ ] Manter lockfiles para dependências nos ecossistemas compatíveis.
- [ ] Evitar dependências implícitas do ambiente local dos desenvolvedores.
- [ ] Executar contêineres com o mínimo de privilégios possível.
- [ ] Restringir rede, credenciais e diretórios graváveis a verificadores que não precisam deles.
- [ ] Permitir executar localmente as verificações relevantes antes de abrir um PR.
- [ ] Assegurar que a CI execute verificações equivalentes às disponíveis localmente.

### 11.5. Lint, formatação, estrutura e duplicação

- [ ] Configurar ESLint ou alternativa equivalente para JavaScript e TypeScript quando aplicável.
- [ ] Avaliar SonarJS para regras de manutenção, complexidade e qualidade.
- [ ] Configurar Prettier ou formatador equivalente quando aplicável.
- [ ] Avaliar Biome como alternativa ou complemento a ESLint e Prettier.
- [ ] Eliminar ou justificar conflitos e redundâncias entre ESLint, Prettier e Biome.
- [ ] Configurar Stylelint ou alternativa equivalente quando houver CSS ou tecnologias compatíveis.
- [ ] Definir convenções de código, estilos, organização e tratamento de exceções.
- [ ] Configurar ast-grep quando houver regras sintáticas ou restrições arquiteturais específicas.
- [ ] Testar regras de ast-grep com exemplos positivos e negativos.
- [ ] Configurar Knip ou ferramenta equivalente para detectar exports, dependências e arquivos não utilizados.
- [ ] Configurar jscpd ou alternativa equivalente para detectar duplicação de código.
- [ ] Definir limites e escopo de detecção de duplicação e falsos positivos.
- [ ] Tratar adequadamente código gerado, arquivos vendorizados e exceções.
- [ ] Bloquear integração quando regras obrigatórias de qualidade falharem.

### 11.6. Testes automatizados com Vitest e fast-check

- [ ] Configurar Vitest ou framework de testes adequado ao ecossistema.
- [ ] Implementar testes unitários para lógica e invariantes relevantes.
- [ ] Implementar testes de integração para componentes e serviços externos.
- [ ] Avaliar fast-check ou equivalente para testes baseados em propriedades.
- [ ] Testar casos extremos, entradas malformadas e estados inesperados.
- [ ] Testar falhas de dependências, exceções e códigos de erro.
- [ ] Definir metas de cobertura proporcionais à criticidade e não apenas ao percentual.
- [ ] Publicar resultados e relatórios de testes na CI quando apropriado.
- [ ] Bloquear merge quando testes obrigatórios falharem.
- [ ] Controlar aleatoriedade e outras fontes de não determinismo.
- [ ] Investigar e corrigir testes intermitentes.
- [ ] Exigir testes de regressão para falhas relevantes corrigidas.

### 11.7. Validação de workflows, Dockerfiles, YAML, shell e Markdown

- [ ] Configurar actionlint para os workflows do GitHub Actions.
- [ ] Configurar zizmor para revisar a segurança dos workflows.
- [ ] Configurar Hadolint quando houver Dockerfiles.
- [ ] Revisar imagens-base, camadas, usuários, permissões e práticas de build.
- [ ] Configurar yamllint para arquivos YAML pertinentes.
- [ ] Configurar ShellCheck para scripts de shell.
- [ ] Configurar shfmt para formatação de scripts de shell.
- [ ] Verificar códigos de saída e tratamento de falhas nos scripts críticos.
- [ ] Configurar Markdownlint ou alternativa equivalente para documentação Markdown.
- [ ] Verificar links e referências documentais.
- [ ] Verificar se documentos gerados estão sincronizados com suas fontes.
- [ ] Bloquear merge quando documentos consolidados estiverem desatualizados.
- [ ] Identificar arquivos gerados e documentar o procedimento de regeneração.

### 11.8. Segredos, SAST, dependências e vulnerabilidades

- [ ] Configurar Gitleaks ou equivalente para detecção de segredos.
- [ ] Executar detecção de segredos na CI e avaliar verificações locais.
- [ ] Definir procedimento de revogação e rotação para credenciais expostas.
- [ ] Revisar exclusões de detecção de segredos e evitar dispensas abrangentes.
- [ ] Configurar OSV-Scanner ou ferramenta equivalente para vulnerabilidades conhecidas.
- [ ] Configurar Trivy para sistemas de arquivos, imagens e configurações quando aplicável.
- [ ] Configurar Semgrep ou outra ferramenta de análise estática de segurança.
- [ ] Avaliar CodeQL nos repositórios e linguagens suportados.
- [ ] Escolher entre CodeQL automático e avançado sem executar modos incompatíveis.
- [ ] Definir severidades e condições que bloqueiam integração ou publicação.
- [ ] Distinguir vulnerabilidades novas das preexistentes sem ignorar risco acumulado.
- [ ] Definir responsáveis, priorização e prazos para tratamento de vulnerabilidades.
- [ ] Registrar e revisar exceções temporárias com justificativa.
- [ ] Evitar que erros das ferramentas sejam tratados como checks aprovados.

### 11.9. Supply chain, pinning, atestações e SBOM

- [ ] Inventariar dependências diretas e transitivas.
- [ ] Revisar origem, manutenção e licenças de dependências críticas.
- [ ] Fixar GitHub Actions de terceiros pelo SHA completo de commit.
- [ ] Documentar a versão correspondente aos SHAs fixados.
- [ ] Atualizar pins de ações externas periodicamente.
- [ ] Avaliar fixação de imagens Docker por digest para etapas críticas.
- [ ] Verificar origem e integridade de ferramentas e artefatos usados no build.
- [ ] Evitar execução de scripts de terceiros sem avaliação de riscos.
- [ ] Impedir exposição de credenciais privilegiadas a contribuições não confiáveis.
- [ ] Aplicar o princípio do menor privilégio ao GITHUB_TOKEN.
- [ ] Preferir credenciais de curta duração e identidade federada quando disponíveis.
- [ ] Evitar persistência desnecessária de credenciais de checkout.
- [ ] Avaliar assinatura e atestações de procedência dos artefatos publicados.
- [ ] Gerar SBOM para os artefatos relevantes.
- [ ] Avaliar CycloneDX como formato de SBOM.
- [ ] Validar completude, formato e integridade do SBOM.
- [ ] Associar cada SBOM à versão ou ao artefato correspondente.
- [ ] Atualizar SBOM quando dependências ou artefatos relevantes forem alterados.
- [ ] Publicar SBOM com releases quando apropriado.
- [ ] Configurar Dependency Review para alterações de dependências em PRs quando disponível.
- [ ] Definir regras para vulnerabilidades e licenças no Dependency Review.
- [ ] Configurar Dependency Submission para ecossistemas que necessitem envio de dependências ao GitHub.
- [ ] Conferir consistência entre SBOM, dependências resolvidas e Dependency Graph.

### 11.10. OpenSSF Scorecard e avaliação contínua

- [ ] Configurar OpenSSF Scorecard ou avaliação comparável.
- [ ] Executar a avaliação de forma periódica.
- [ ] Registrar resultados e sua evolução histórica.
- [ ] Priorizar melhorias a partir dos controles com maior risco ou fragilidade.
- [ ] Avaliar proteção de branches, revisão de código e permissões.
- [ ] Avaliar manutenção de dependências e segurança de workflows.
- [ ] Avaliar procedência e integridade de artefatos distribuídos.
- [ ] Investigar achados relevantes mesmo sem alteração da pontuação geral.
- [ ] Não apresentar Scorecard como certificação de segurança.

### 11.11. Atualização automatizada com Renovate

- [ ] Configurar Renovate ou solução equivalente.
- [ ] Definir regras para atualizações automáticas, semiautomáticas e manuais.
- [ ] Agrupar atualizações compatíveis e limitar volume de PRs.
- [ ] Priorizar atualizações relacionadas a vulnerabilidades.
- [ ] Manter atualizações para dependências, GitHub Actions e imagens de contêiner.
- [ ] Atualizar pins suportados de supply chain.
- [ ] Executar quality gate nos PRs de atualização.
- [ ] Adotar condições restritivas para automerge quando permitido.
- [ ] Monitorar dependências descontinuadas ou sem manutenção.
- [ ] Registrar e revisar exceções de atualização.

### 11.12. Integração contínua, quality gate e publicação

- [ ] Criar workflows de validação para pull requests.
- [ ] Definir eventos que disparam os workflows.
- [ ] Organizar verificações por categoria, linguagem ou matriz quando apropriado.
- [ ] Distinguir checks obrigatórios dos informativos.
- [ ] Criar quality gate que consolide o resultado de todas as verificações obrigatórias.
- [ ] Fazer o quality gate falhar quando alguma verificação obrigatória falhar.
- [ ] Não aprovar jobs cancelados, pendentes ou não executados sem regra explícita.
- [ ] Restringir segredos e permissões de escrita nos workflows.
- [ ] Revisar permissões de ações externas e ambientes de execução.
- [ ] Controlar o cache sem comprometer a integridade dos resultados.
- [ ] Definir limites de tempo e recursos dos jobs.
- [ ] Evitar verificações redundantes de alto custo.
- [ ] Publicar logs e relatórios suficientes para investigar falhas.
- [ ] Definir retenção adequada dos artefatos de CI.
- [ ] Configurar no ruleset o quality gate que efetivamente é executado.
- [ ] Testar bloqueio de merge com falha intencional em branch de teste.
- [ ] Testar o fluxo de integração após aprovação das verificações.

### 11.13. Evidências, auditoria e manutenção da conformidade

- [ ] Registrar ferramenta ou controle responsável por cada requisito.
- [ ] Registrar a localização de cada configuração.
- [ ] Registrar workflow, comando ou procedimento de validação.
- [ ] Registrar execução bem-sucedida recente e referência verificável.
- [ ] Distinguir presença de configuração de funcionamento validado.
- [ ] Identificar responsáveis por manter os controles.
- [ ] Justificar itens não aplicáveis.
- [ ] Documentar exceções, riscos aceitos, medidas compensatórias e prazos.
- [ ] Verificar periodicamente badges, relatórios e checks.
- [ ] Reavaliar os controles após mudanças significativas em código, infraestrutura ou governança.
- [ ] Documentar incidentes que revelem insuficiência dos controles.
- [ ] Revisar a checklist conforme a evolução das ferramentas e do projeto.

**Critério de aceite da seção:** evidência verificável de configuração e execução para cada requisito aplicável, com responsáveis, tratamento de exceções e revisão periódica. A presente checklist não equivale a certificação de segurança ou aprovação formal de tecnologia.

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
