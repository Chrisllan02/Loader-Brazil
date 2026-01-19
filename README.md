Loader Bandeira do Brasil 🇧🇷 (CSS 3D & Typewriter)

Um loader (tela de carregamento) moderno, realista e patriótico, desenvolvido puramente com HTML5 e CSS3. O projeto apresenta uma animação de "construção" da bandeira brasileira em 3D, transições suaves e suporte automático a temas claros e escuros.

✨ Funcionalidades

Animação Complexa: Ciclo contínuo de "Onda" → "Fusão" → "Explosão" (formação da bandeira) → "Desconstrução".

Efeito 3D Realista: Uso avançado de gradientes, box-shadow e perspective para criar volumetria e iluminação (esfera de vidro, camadas físicas).

Precisão Astronômica: As 27 estrelas da bandeira estão mapeadas de acordo com a Lei Federal, incluindo o Cruzeiro do Sul e o Escorpião.

Responsivo e Adaptável:

Fundo Transparente: Pode ser sobreposto a qualquer site.

Dark Mode Automático: O texto "CARREGANDO..." e o cursor mudam de cor (azul/branco) automaticamente baseados na preferência do sistema do usuário.

Efeito Typewriter: Texto de carregamento com animação de máquina de escrever centralizada.

📂 Estrutura do Projeto

O código foi separado para facilitar a manutenção e integração:

/
├── index.html   # Estrutura (HTML + SVG das estrelas)
├── style.css    # Estilização (Animações, Keyframes, 3D)
└── README.md    # Documentação


🚀 Como Usar

1. Download / Clone

Baixe os arquivos index.html e style.css para o seu computador.

2. Integração

Se você quiser usar apenas o loader em seu projeto existente:

Copie o arquivo style.css para sua pasta de estilos e linke-o no seu <head>.

Copie o bloco HTML <div class="loader-wrapper">...</div> do index.html e cole onde deseja que o loader apareça.

3. Visualização Online (GitHub Pages)

Para ver a animação rodando diretamente do GitHub:

Vá em Settings > Pages no seu repositório.

Em Source, selecione Deploy from a branch.

Escolha a branch main e salve.

O link será gerado automaticamente (ex: seu-usuario.github.io/seu-loader).

🎨 Personalização

Você pode ajustar facilmente as cores ou tempos no arquivo style.css:

Velocidade: Altere o tempo 5s nas propriedades animation para deixar mais rápido ou mais lento.

Tamanho: Ajuste width e height da classe .flag-container (mantendo a proporção 7:10).

Feito com 💚 e CSS.
