# Cubo Mágico 3D

Este repositório contém uma página única (`index.html`) com um cubo mágico 3D feito em Three.js. Abaixo estão passos rápidos para abrir e testar no computador ou no celular.

## Como testar

### 1) Abrir localmente no navegador (método simples)
1. Baixe ou clone o repositório.
2. Abra o arquivo `index.html` direto no navegador (Chrome, Firefox ou Edge). Basta dar duplo clique no arquivo.
3. Interaja com o cubo:
   - Arraste com um dedo ou mouse para girar.
   - Pinça (dois dedos) para aproximar/afastar no celular; scroll do mouse no desktop.
   - Arraste com dois dedos para mover a cena.
   - Clique/toque em **Resetar posição** para recentrar a câmera.

### 2) Servir via HTTP (opcional, útil para celular)
Alguns celulares bloqueiam arquivos abertos direto do sistema de arquivos. Se precisar rodar via HTTP:

1. No terminal, dentro da pasta do projeto, rode um servidor simples (Python 3):
   ```sh
   python3 -m http.server 8000
   ```
2. Acesse http://localhost:8000/index.html no computador.
3. Para testar no celular, conecte-o à mesma rede e abra `http://SEU_IP:8000/index.html`.

## Requisitos
- Navegador moderno com suporte a WebGL.
- Não é necessário instalar dependências ou compilar nada.

## Dicas
- Se a rotação estiver lenta, desligue outros apps que usem GPU.
- Toque no botão de reset sempre que quiser voltar à visão padrão do cubo.
