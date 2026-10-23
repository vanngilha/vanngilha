<h2>Christopher Oliveira</h2>

**Desenvolvedor backend · PHP, Laravel e PostgreSQL** · Ilhabela, SP

Mantenho e modernizo sistemas de gestão pública que rodam em produção todos os dias na iiBrasil, desde 2020. Fora dela, construo produtos do domínio ao deploy. Gosto de domínio bem modelado, de transação que não perde dinheiro e de mudar código legado sem quebrar o que funciona.

[![Portfólio](https://img.shields.io/badge/chrisoliveira.dev-0d0c0b?style=for-the-badge&logo=googlechrome&logoColor=e0a458)](https://www.chrisoliveira.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d0c0b?style=for-the-badge&logo=linkedin&logoColor=e0a458)](https://www.linkedin.com/in/chriisoliveira)
[![Email](https://img.shields.io/badge/ceo@chrisoliveira.dev-0d0c0b?style=for-the-badge&logo=gmail&logoColor=e0a458)](mailto:ceo@chrisoliveira.dev)

<img src="https://skillicons.dev/icons?i=php,laravel,postgres,mysql,docker,nginx,linux,githubactions,js,ts,react,nextjs&theme=dark" alt="PHP, Laravel, PostgreSQL, MySQL, Docker, Nginx, Linux, GitHub Actions, JavaScript, TypeScript, React, Next.js"/>

<br>

### Agora · Guivya

Marketplace de passeios com reserva em tempo real e pagamento por PIX ou cartão. **Em desenvolvimento**, repositório privado.

`Laravel 12` `PostgreSQL 16` `filas` `Pusher` `Mercado Pago` `PHPUnit`

| Decisão | Por quê |
|---|---|
| Janela de aceite proporcional à antecedência | 3 minutos fixos faziam reserva para daqui a meses expirar se o guia não estivesse com o app aberto |
| Webhook valida HMAC, grava e responde; um job aplica o resultado | Retry, fila de falhas e replay pelo admin; reconciliação cobre o PIX que expira sem aviso |
| Uma Action só para confirmar pagamento | Idempotente, lock sempre na mesma ordem e eventos só depois do commit |
| Troca de gateway mantendo os eventos antigos | Histórico vira trilha de auditoria em vez de quebrar o replay |

**573 testes** · **850+ commits** · CI em PHP 8.2, 8.3 e 8.4 · Sentry

### Em produção para clientes

| | | |
|---|---|---|
| [**Rotamar Ilhabela**](https://www.rotamarilhabela.com.br/) | passeios de lancha, visualizador 3D da embarcação | `Three.js` |
| [**Importados da Ilha**](https://www.importadosdailha.com.br/) | loja com painel administrativo | `Next.js` `Supabase` |
| [**Pato Guia Ilhabela**](https://www.patopasseioilhabela.com/) | site de guia local, sem dependências | `HTML` `CSS` `JS` |

### Código aberto

[**color-detector**](https://github.com/vanngilha/color-detector) · nome, RGB e HEX de qualquer cor pela webcam, com Python e OpenCV. Projeto final do CS50x. A versão em JavaScript roda [no portfólio](https://www.chrisoliveira.dev/#projetos).

### Como eu trabalho

Uso o Claude Code num fluxo com etapas: discutir, planejar, executar, verificar, revisar e entregar. A IA acelera a execução; arquitetura, revisão e responsabilidade pelo código são minhas.

<sub>Análise e Desenvolvimento de Sistemas · MBA em Gerenciamento de Projetos · [CS50x Harvard](https://certificates.cs50.io/81532b44-9b96-4a68-bf98-cd162cff7011.pdf?size=letter) · AWS Educate</sub>
