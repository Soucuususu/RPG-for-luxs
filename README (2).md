# ASCEND — Life System

Primeira versão funcional do ASCEND, um app de evolução pessoal com visual premium minimalista, feito para celular e pronto para publicar no GitHub Pages.

## Funcionalidades
- Missões diárias com categorias e recompensas de XP.
- Níveis e ranks calculados pelo XP acumulado.
- Estatísticas de progresso e dias ativos.
- Hábitos com marcação diária nos últimos 7 dias.
- Temporizador de foco de 25 minutos; sessão concluída concede 15 XP.
- Backup de dados em JSON e importação.
- Salvamento local no navegador.
- Layout responsivo para celular e desktop.
- Manifesto e ícone para facilitar futura instalação como PWA.

## Publicar no GitHub Pages pelo celular
1. Crie um repositório público chamado `ascend` no GitHub.
2. Extraia este ZIP no celular.
3. No repositório, toque em **Add file → Upload files**.
4. Envie `index.html`, `manifest.json`, `icon.svg` e `README.md` para a raiz do repositório.
5. Abra **Settings → Pages**.
6. Em **Build and deployment**, selecione **Deploy from a branch**.
7. Escolha a branch `main`, pasta `/(root)`, e salve.
8. Aguarde o GitHub publicar. O endereço será parecido com `https://SEU-USUARIO.github.io/ascend/`.

## Observações importantes
- O progresso fica neste navegador/dispositivo. Ainda não existe login nem sincronização entre dispositivos.
- O temporizador funciona enquanto a página permanece ativa; navegadores móveis podem pausar abas em segundo plano.
- O manifesto é um primeiro passo para instalação, mas o suporte a PWA varia por navegador e o SVG como ícone pode ter limitações em alguns instaladores.
- Esta versão não inclui servidor, conta de usuário ou IA online. Esses recursos exigem backend e serão etapas separadas.
