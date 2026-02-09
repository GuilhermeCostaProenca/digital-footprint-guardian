# Zelador Digital

    [![CI](https://github.com/GuilhermeCostaProenca/zelador-digital/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/GuilhermeCostaProenca/zelador-digital/actions/workflows/ci.yml)

    Projeto de produto digital para resolver dor real de mercado com execu??o em padr?o profissional de portf?lio.

    ## Proposta
    **Gerenciador da pegada online do usu?rio** para Usu?rios com muitas contas online, foco em privacidade e seguran?a.

    ## Problema
    Falta visibilidade de onde dados pessoais est?o cadastrados e risco cont?nuo por contas abandonadas.

    ## P?blico-alvo
    Usu?rios com muitas contas online, foco em privacidade e seguran?a

    ## Stack sugerida
    Next.js, API Node, PostgreSQL, integra??es com provedores de e-mail e servi?os de breach monitoring

    ## MVP inicial
    - Mapeamento de contas a partir do e-mail principal
    - Painel de assinaturas e contas inativas
    - Alertas de vazamentos e recomenda??es de a??o
    - Fluxo guiado para limpeza e encerramento de contas

    ## Estrutura base
    - `README.md`: vis?o do produto e execu??o.
    - `PRD.md`: escopo funcional e regras de produto.
    - `ARCHITECTURE.md`: desenho t?cnico inicial.
    - `BACKLOG.md`: backlog priorizado por valor.
    - `PLAN.md`: plano de execu??o em fases.
    - `.github/workflows/ci.yml`: pipeline de valida??o.

    ## Como come?ar
    1. Refinar PRD com recorte de usu?rio e problema.
    2. Definir arquitetura de refer?ncia e stack final.
    3. Implementar fluxo principal ponta a ponta.
    4. Subir CI, testes essenciais e documenta??o de uso.

    ## Riscos principais
    Depend?ncia de provedores externos e confian?a do usu?rio

    ## Contexto da ideia
    Zelador  Digital –  gerenciador  da  sua  pegada  online:  Usuários  comuns  acumulam  uma
quantidade enorme de contas, cadastros e assinaturas digitais e não têm controle sobre isso.
Sabe aqueles cadastros em sites antigos, serviços que você nem usa mais, newsletters spam que
enchem sua caixa de entrada? A dor aqui é falta de organização e segurança pessoal: é difícil
lembrar de todos os lugares onde seu e-mail e dados estão registrados. Em média, pessoas
tinham duas dúzias de contas online já em 2015 – hoje devem ser muito mais – e muitas
dessas  contas  ficam  abandonadas,  mas  vulneráveis  (não  por  acaso,  mais  de  16  bilhões de
credenciais  vazadas  foram  encontradas  online  em  2025).  As  soluções  atuais  são
fragmentadas: gerenciadores de senhas ajudam um pouco (guardam senhas, não cancelam
contas), há sites para descadastrar e serviços pagos de proteção de dados, mas nada integrado e
fácil. Por que é uma oportunidade? Porque segurança e privacidade viraram preocupação de
todos, mas ninguém entregou uma “faxina digital” simples para o usuário médio. Quem tem
essa dor: praticamente qualquer internauta ativo há anos – profissionais preocupados com
privacidade, gente que assina um monte de serviços e se perde nas cobranças, ou quem foi
vítima de vazamento e não quer passar por isso de novo. Nome sugerido:Zelador Digital, um
app que mapeia suas contas (via seu e-mail principal), ajuda a cancelar o que não usa, gerencia
senhas únicas e alerta sobre vazamentos envolvendo seus dados – enfim, um “faxineiro” para
você ter paz no mundo online.
