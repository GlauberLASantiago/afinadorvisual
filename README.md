🎶 Afinador Visual Interativo

Um afinador eletrônico baseado na web, projetado para fornecer feedback visual e em tempo real sobre a afinação de um instrumento musical. Ideal para músicos, especialmente de sopro, que desejam analisar a estabilidade e a entonação de suas notas ao longo do tempo.


🎯 Sobre o Projeto

Este projeto foi criado como uma ferramenta de estudo e prática musical, desenvolvido em colaboração com o Prof. Glauber Santiago (UFSCar, 2025). A ideia central é ir além dos afinadores tradicionais, que apenas mostram se uma nota está afinada em um único instante. O Afinador Visual plota a afinação em um gráfico contínuo, permitindo ao músico observar tendências, variações e a estabilidade da sua emissão sonora.

O feedback visual é fornecido por uma linha que se move verticalmente e por faixas de cor no fundo que indicam o quão distante da afinação perfeita (para cima ou para baixo) a nota se encontra.

✨ Funcionalidades

Análise em Tempo Real: Captura o áudio do microfone e exibe a frequência detectada instantaneamente.

Gráfico de Afinação: Desenha uma linha contínua que representa a variação da afinação em cents ao longo do tempo.

Feedback Visual Intuitivo: O fundo da tela muda de cor em "degraus", com tons de vermelho para notas altas (sharp) e azul para notas baixas (flat).

Exibição de Enarmonia: Mostra os nomes das notas com suas enarmonias correspondentes (ex: C♯/D♭).

Suporte a Instrumentos Transpositores: Permite selecionar a clave do instrumento (C, B♭, E♭) e exibe a nota transposta corretamente.

Controles Ajustáveis:


Sensibilidade (Zoom): Ajusta o quão "próximo" o gráfico visualiza a variação em cents.

Suavização da Linha: Controla o nível de média aplicado à linha, permitindo uma visualização mais rápida ou mais estável.

Design Responsivo: Interface limpa e funcional que se adapta a diferentes tamanhos de tela.

🛠️ Tecnologias Utilizadas

HTML5: Estrutura base da aplicação.

CSS3 & Tailwind CSS: Estilização e design da interface.

JavaScript (Vanilla): Lógica principal da aplicação, manipulação do DOM e cálculos de afinação.

Web Audio API: Acesso ao microfone e análise de frequência em tempo real.

🚀 Como Usar

Clone este repositório:

git clone https://github.com/seu-usuario/afinador-visual.git

Navegue até o diretório do projeto:

cd afinador-visual

Abra o arquivo index.html em qualquer navegador moderno (Chrome, Firefox, Edge).

Não é necessário um servidor local, mas para o acesso ao microfone (getUserMedia) funcionar corretamente, o navegador pode exigir que a página seja servida via HTTPS ou a partir de localhost.

Clique em "Iniciar Afinador" e permita o acesso ao microfone quando solicitado pelo navegador.

Toque uma nota e veja a mágica acontecer!


📄 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

🙏 Agradecimentos
Agradecimentos especiais ao Prof. Glauber Santiago pela idealização e orientação no desenvolvimento desta ferramenta.
