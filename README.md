### Christopher Oliveira

Desenvolvedor backend · PHP, Laravel e PostgreSQL · Ilhabela, SP

Mantenho e modernizo sistemas de gestão pública que rodam em produção todos os dias na iiBrasil, desde 2020. Fora dela, construo produtos do domínio ao deploy. Gosto de domínio bem modelado, de transação que não perde dinheiro e de mudar código legado sem quebrar o que funciona.

[chrisoliveira.dev](https://www.chrisoliveira.dev) · [linkedin](https://www.linkedin.com/in/chriisoliveira) · [ceo@chrisoliveira.dev](mailto:ceo@chrisoliveira.dev) · aberto a vagas backend e full stack, CLT ou PJ

#### Agora

**Guivya** (repositório privado) · marketplace de passeios com reserva em tempo real e pagamento por PIX ou cartão. Laravel 12, PostgreSQL 16, filas, Pusher.

- Webhook do Mercado Pago valida HMAC, grava o evento e responde; um job aplica o resultado com retry, fila de falhas e replay pelo admin. Reconciliação cobre o PIX que expira sem aviso.
- Confirmação de pagamento com uma porta de entrada só: idempotente, com ordem fixa de lock e eventos disparados depois do commit.
- Janela de aceite do guia proporcional à antecedência da reserva, depois que a janela fixa de 3 minutos travou as reservas antecipadas.
- 573 testes, CI em PHP 8.2, 8.3 e 8.4, Sentry. Mostro o código numa conversa.

#### Em produção para clientes

- [Rotamar Ilhabela](https://www.rotamarilhabela.com.br/) · passeios de lancha, visualizador 3D da embarcação em Three.js
- [Importados da Ilha](https://www.importadosdailha.com.br/) · loja com painel administrativo em Next.js e Supabase
- [Pato Guia Ilhabela](https://www.patopasseioilhabela.com/) · site de guia local, sem framework e sem dependências

#### Código aberto

- [color-detector](https://github.com/vanngilha/color-detector) · nome, RGB e HEX de qualquer cor pela webcam, com Python e OpenCV. Projeto final do CS50x. A versão em JavaScript roda [no portfólio](https://www.chrisoliveira.dev/#trabalho).

#### Stack

PHP 8 · Laravel · PostgreSQL · MySQL · filas e eventos · APIs REST · Docker · Nginx · Linux · GitHub Actions · PHPUnit · Sentry · JavaScript · TypeScript · React · Next.js

Uso o Claude Code num fluxo com etapas (discutir, planejar, executar, verificar, revisar, entregar). A IA acelera a execução; arquitetura, revisão e responsabilidade pelo código são minhas.

<sub>Análise e Desenvolvimento de Sistemas · MBA em Gerenciamento de Projetos · [CS50x](https://certificates.cs50.io/81532b44-9b96-4a68-bf98-cd162cff7011.pdf?size=letter)</sub>
