# ATIVIDADE 1 - MODELAGEM

**Aluno(a):** Ana Helloyse Gomes de Freitas

## Estudo de Caso 1

### 1. Concepção

O Conecta Campus pretende resolver o problema da falta de centralização dos serviços acadêmicos, além das dificuldades de lentidão e usabilidade do sistema atual. Os alunos precisam acessar notas, horários e avisos, enquanto os professores necessitam publicar materiais e comunicados, e a coordenação precisa divulgar eventos e informações acadêmicas.

Seu principal objetivo é reunir esses serviços em um único sistema, tornando o acesso às informações mais rápido, seguro, organizado e fácil de utilizar, melhorando a comunicação entre alunos, professores e coordenação.

### 2. Elicitação

Os principais stakeholders do sistema são:

Alunos: precisam consultar notas, horários e avisos acadêmicos.

Professores: precisam publicar materiais didáticos e comunicados.

Coordenação: necessita divulgar eventos e informações acadêmicas.

Equipe: São responsáveis por estabelecer regras de acesso, segurança e funcionamento do sistema.

**Para identificar e compreender as necessidades desses stakeholders, podem ser utilizadas as seguintes técnicas de elicitação:**

Entrevistas: a equipe de desenvolvimento pode conversar diretamente com alunos, professores e coordenadores para compreender suas dificuldades, expectativas e necessidades. Por exemplo, pode perguntar quais informações os alunos mais consultam e quais problemas enfrentam no sistema atual.
Questionários: podem ser enviados a um número maior de usuários para identificar as funcionalidades mais desejadas e avaliar a satisfação com o sistema atual. As respostas ajudam a reconhecer necessidades comuns e definir prioridades.

### 3. Análise e modelagem

**Requisitos funcionais (RF)**

RF01: O sistema deve permitir que os alunos consultem suas notas acadêmicas.

RF02: O sistema deve permitir que os alunos consultem seus horários de aulas.

RF03: O sistema deve permitir que os alunos recebam avisos e comunicados acadêmicos.

RF04: O sistema deve permitir que os professores publiquem materiais didáticos.

RF05: O sistema deve permitir que os professores publiquem comunicados destinados aos alunos.

RF06: O sistema deve permitir que a coordenação divulgue eventos e informações acadêmicas.

RF07: O sistema deve permitir que os usuários realizem login utilizando credenciais válidas.

RF08: O sistema deve permitir que os usuários autorizados acessem as funcionalidades correspondentes ao seu perfil.

**Requisitos não funcionais (RNF)**

RNF01 — Desempenho: O sistema deve apresentar as consultas de notas e horários em até 2 segundos em pelo menos 95% das solicitações, sob condições normais de uso definidas para os testes.

RNF02 — Segurança: O sistema deve exigir autenticação para acessar informações acadêmicas restritas e impedir que usuários consultem dados para os quais não possuem autorização.

RNF03 — Usabilidade: O sistema deve permitir que pelo menos 90% dos participantes de um teste de usabilidade concluam tarefas básicas, como consultar notas e horários, sem ajuda de um avaliador.

### 4. Negociação

**Must have (indispensável):**

- Login e autenticação dos usuários.
- Consulta de notas e horários pelos alunos.
- Publicação de materiais e comunicados pelos professores.
- Divulgação de eventos e informações pela coordenação.
- Controle de acesso às informações acadêmicas.

Essas funcionalidades são indispensáveis porque atendem às principais necessidades apresentadas e às exigências de segurança da universidade.

**Should have (importante):**

- Melhorias na navegação e na organização das informações.
- Sistema de avisos e notificações acadêmicas.

São importantes para melhorar a experiência dos usuários e a comunicação, embora alguns avisos possam inicialmente ser consultados diretamente no sistema.

**Could have (desejável):**

- Personalização das notificações de acordo com as preferências dos alunos.
- Recursos adicionais de personalização da interface.

Essas funcionalidades podem melhorar a experiência de uso, mas não são essenciais para disponibilizar os serviços acadêmicos principais.

**Won't have (fora do escopo da versão atual):**

- Chat em tempo real entre alunos e professores

O chat poderá ser desenvolvido em uma versão futura, pois a equipe consider.a que sua implementação pode atrasar a primeira versão. Assim, será possível priorizar as funcionalidades essenciais e disponibilizar o sistema mais rapidamente.

### 5. Especificação

RNF01 — Desempenho: O sistema deve apresentar as consultas de notas e horários em até 2 segundos em pelo menos 95% das solicitações, sob condições normais de uso definidas para o teste.

Como testar: executar pelo menos 100 solicitações de consulta em um ambiente de teste controlado e medir os tempos de resposta, verificando se pelo menos 95% ficam dentro do limite estabelecido.

RNF02 — Segurança: O sistema deve exigir autenticação para acessar informações acadêmicas restritas e bloquear tentativas de acesso não autorizado.

Como testar: tentar acessar informações restritas sem login e utilizar contas com diferentes permissões para verificar se cada usuário consegue acessar somente os dados autorizados.

RNF03 — Usabilidade: Pelo menos 90% dos participantes de um teste com usuários representativos devem conseguir consultar notas e horários sem ajuda do avaliador.

Como testar: solicitar que os participantes realizem essas tarefas em um protótipo ou sistema funcional, registrando quantos conseguem concluí-las sem assistência.

### 6. Validação

Revisão de requisitos: a equipe apresenta os requisitos documentados a alunos, professores e coordenadores para que eles verifiquem se as funcionalidades descritas correspondem às suas necessidades. Durante a revisão, os participantes podem apontar erros, omissões e requisitos que precisam ser ajustados.

Prototipação: a equipe desenvolve uma representação inicial das telas do Conecta Campus, permitindo que os usuários visualizem e experimentem a organização das funcionalidades antes da implementação definitiva. Os participantes podem avaliar se conseguem localizar notas, horários, materiais e comunicados com facilidade.

Testes de aceitação com usuários: quando houver uma versão funcional, alunos, professores e coordenadores podem executar tarefas relacionadas aos seus papéis. Os resultados permitem verificar se o sistema atende aos requisitos estabelecidos e se as funcionalidades funcionam conforme esperado.

## Estudo de Caso 2

<!-- Escreva aqui as respostas do segundo estudo de caso. -->
