# ⌨️ Mestre do Teclado - ABNT2 Pro Ultimate

**Edição Laboratório Inclusivo**

Um aplicativo web educacional interativo e gamificado para o ensino de digitação por toque, com foco absoluto no padrão de teclado brasileiro **ABNT2**[cite: 2]. Foi desenvolvido especialmente para turmas de letramento digital, Educação de Jovens e Adultos (EJA) e laboratórios de informática escolares[cite: 2].

## 🎯 Objetivo Educacional

Diferente de outras plataformas de digitação, o *Mestre do Teclado* foca não apenas na velocidade, mas na **técnica correta e memória muscular**[cite: 2]. O motor do jogo rastreia ativamente o uso de *Dead Keys* (teclas mortas para acentos) e penaliza o uso incorreto das teclas modificadoras, exigindo que o aluno utilize o `Shift` ou `AltGr` da mão oposta à tecla digitada[cite: 2].

## ✨ Novidades e Melhorias Recentes

*   **Responsividade Total (Mobile/Tablet):** O teclado virtual agora se ajusta dinamicamente a diferentes larguras de tela, garantindo que a interface não quebre em dispositivos móveis (`@media (max-width: 720px)`)[cite: 2].
*   **Motor de Digitação Robusto:** Suporte aprimorado para a composição de caracteres do sistema operacional (eventos `compositionstart` e `compositionend`), evitando falhas ao processar acentos complexos[cite: 2]. Os temporizadores agora utilizam `Date.now()` para não perderem a sincronia quando a aba fica em segundo plano[cite: 2].
*   **Acessibilidade Aprimorada (A11y):** As preferências de Alto Contraste agora são salvas localmente (para que o aluno não precise reativá-las a cada aula), foram adicionados atributos ARIA, e o teclado permite navegação e ativação de lições nativamente[cite: 2].
*   **Detecção Inteligente de Caps Lock:** O sistema emite um alerta visual caso o usuário tente jogar com o Caps Lock ativado, evitando frustrações[cite: 2].
*   **Sanitização de Perfil:** O módulo de importação de arquivos `.json` conta agora com a função `Profile.sanitize()`, que impede o carregamento de perfis corrompidos ou arquivos maliciosos[cite: 2].
*   **Áudio Failsafe:** O jogo funciona perfeitamente e sem travamentos mesmo em ambientes escolares mais restritos onde o carregamento da biblioteca `Tone.js` possa falhar[cite: 2].

## 🎮 Modos de Jogo

1.  🎓 **Curso Completo (30 Lições):** Uma trilha guiada do zero absoluto até a digitação profissional. Foco no repouso dos dedos e progressão gradual[cite: 2].
2.  ⚡ **Corrida de 90 Segundos (Rush):** Teste de velocidade pura. O cronômetro conta 90 segundos e a string de texto se expande infinitamente para que o usuário nunca pare de digitar[cite: 2].
3.  📚 **Maratona:** Treino focado na resistência, contendo 6 textos sequenciais baseados em vocabulário profissional[cite: 2].
4.  ⭐ **Mestre dos Acentos e Símbolos:** Treino intensivo para dominar as *Dead Keys* e o uso da tecla `AltGr` (º, ª, °, §, ¢)[cite: 2].

## ⚙️ Principais Funcionalidades

*   **Validação Híbrida Rigorosa:** Avalia o caractere digitado em conjunto com as teclas físicas pressionadas para validar a postura correta[cite: 2].
*   **Gamificação:** Sistema de pontos de experiência (XP), evolução de níveis e vitrine de conquistas (Medalhas/Badges)[cite: 2].
*   **Portabilidade de Perfil (Export/Import):** Ideal para laboratórios compartilhados. Os alunos salvam o progresso em um arquivo `.json` e podem importá-lo em outro computador no dia seguinte[cite: 2].
*   **Tutor Analítico com Mapa de Calor (Heatmap):** Analisa os erros e recomenda automaticamente exercícios focados nas dificuldades detectadas[cite: 2].
*   **Áudio Dinâmico:** Sintetizadores sem atraso (`Tone.js`) geram sons de feedback mecânico, acordes de vitória e uma trilha sonora procedural[cite: 2].

## 🛠️ Tecnologias Utilizadas

O projeto foi construído em um formato **Single File Component** (tudo em um único arquivo `html`), facilitando a execução offline sem servidores:

*   **HTML5 & CSS3** puros[cite: 2].
*   **JavaScript (ES6+) Vanilla** (Sem frameworks externas)[cite: 2].
*   **Tailwind CSS** (via CDN para design rápido e responsivo)[cite: 2].
*   **FontAwesome** (Ícones vetoriais)[cite: 2].
*   **Tone.js** (Web Audio API para geração de som em tempo real)[cite: 2].

## 🚀 Como Executar

A execução é imediata e totalmente local:

1. Faça o download do repositório.
2. Abra o arquivo HTML em qualquer navegador moderno (Chrome, Firefox, Edge, Safari).
3. Não é necessária a instalação de dependências como `Node.js` nem de um servidor local.

## 👨‍🏫 Autor

Projeto educacional de código aberto criado pelo professor **Yan Pereira de Lima**, Licenciado em Computação[cite: 2].

## 📄 Licença e Uso

Este software é de **uso livre para fins educativos**. É expressamente proibida a venda comercial ou apropriação indevida da ferramenta
