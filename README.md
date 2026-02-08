# mug-studio

Nas minhas palavras:
Web app para auxiliar a visualização de artes na caneca para sublimação, você sobe a imagem, ajusta, e consegue visualizar na caneca 3d logo abaixo, com um visual maneiríssimo! xD 
Também é possível enviar a arte diretamente ao produtor (eu) para seguir com a sublimação da caneca.

Como bem descreveria nossa querida IA:

☕ Mug Studio 3D (Web App)

Uma aplicação web interativa e "serverless" para personalização de canecas para sublimação. O projeto permite que usuários desenhem, carreguem imagens, apliquem filtros e visualizem o resultado em um modelo 3D antes de enviar o pedido diretamente para o Google Drive da produção.

🚀 Funcionalidades

🎨 Editor 2D (Canvas)

Ferramentas de Desenho: Lápis, Borracha, Seletor de Cores e Ajuste de Espessura.

Manipulação de Imagens: Upload de imagens locais com capacidade de redimensionar (zoom) e posicionar (arrastar) antes de fixar na arte.

Filtros em Tempo Real: Ajustes de Blur, Modos de Cor (P&B, Sépia, Inverter) e controle de canais RGB.

Histórico: Sistema de Desfazer (Undo/Ctrl+Z) para as últimas 15 ações.

🧊 Visualização 3D

Renderização Realista: Utiliza Three.js para projetar a arte 2D em um modelo 3D de caneca.

Interativo: O usuário pode girar a caneca para conferir como a estampa ficará perto da alça.

Mapeamento Preciso: A área de impressão respeita as margens reais de uma prensa térmica cilíndrica.

☁️ Integração e Pedidos (Backend Serverless)

Geração de PDF: Criação automática de arquivos prontos para impressão usando jsPDF.

Envio para Google Drive: Integração via API (Google Apps Script) que salva o arquivo automaticamente em uma pasta específica do Drive do administrador.

Notificação: Compartilha o arquivo com o e-mail do cliente (gerando notificação nativa do Google) ou armazena com identificação de telefone.

ID Único: Geração de IDs de pedido baseados em timestamp para fácil rastreio (AAAAMMDDHHMM).

🛠️ Tecnologias Utilizadas

Frontend: HTML5, JavaScript (ES6+).

Estilização: Tailwind CSS (via CDN).

3D Engine: Three.js.


📞 Contato e Suporte

Para acompanhar pedidos gerados nesta plataforma:

WhatsApp: +55 (41) 99674-3862

Informe o Número do Pedido gerado ao final do envio.

Licença: MIT
Desenvolvido por: Evandro Rissatto Pereira

PDF Generation: jsPDF.

Backend/Storage: Google Apps Script + Google Drive API.
