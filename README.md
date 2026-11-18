# ⌨️ Mestre do Teclado - ABNT2 Pro Ultimate

Aplicativo web educacional e gamificado para ensino de digitação no padrão brasileiro **ABNT2**, feito para letramento digital, EJA e laboratórios de informática. Criado pelo professor **Yan Pereira de Lima**. Uso livre para fins educativos; venda comercial é proibida.

## 🎮 Modos
- **Curso completo (30 lições)**, com teste de nivelamento para quem já digita.
- **Corrida de 90 s**, **Maratona**, **Mestre dos Acentos e Símbolos**.
- **Desafios:** Treino dos Meus Erros, Desafio do Dia (mesmo texto para a turma), Morte Súbita (3 vidas), Texto Livre (professor) e **Atalhos do Windows** (Ctrl+C, Ctrl+V, Ctrl+Z...).
- Modo **Sem olhar** (teclado apagado), pausa com `Esc` e reinício rápido.

## 🏆 Recursos
- 25 troféus em sala própria (Bronze a Platina), perfil com nome e turma, exportação/importação em `.json`.
- Gráfico de evolução, certificado/relatório imprimível, mapa de calor de erros.
- PPM no padrão da digitação: **acertos ÷ 5 ÷ minutos**.
- Cada acerto toca a próxima nota de uma de 6 melodias sorteadas; música de fundo nos menus que some enquanto se digita.
- Música e efeitos separados; contraste, fonte grande e tema claro independentes.

## 🚀 Publicar no GitHub Pages
1. Envie para o repositório: `index.html`, `sw.js`, `manifest.webmanifest` e `icon.svg` (todos na mesma pasta, na raiz).
2. Em **Settings → Pages**, escolha a branch (ex.: `main`) e a pasta `/ (root)`.
3. Acesse `https://SEU-USUARIO.github.io/SEU-REPOSITORIO/`. Abra uma vez com internet: depois o service worker guarda as bibliotecas e o jogo funciona offline.
4. Ao atualizar o `index.html`, aumente a versão em `sw.js` (`mestre-teclado-v4` → `v5`) para os alunos receberem a novidade.

Também funciona abrindo `index.html` direto no navegador (sem service worker).

## ⚠️ Atalhos do Windows
O navegador reserva alguns atalhos (Ctrl+W, Ctrl+T, Alt+F4, Alt+Tab e a tecla Windows), então eles não podem ser treinados no modo Atalhos.
