# CV-Online — memória da app

> Contexto para retomar o trabalho nesta app mais tarde. Manter curto e atual.

## O que é
Página de currículo pessoal do Fábio Barros (estática). Era o `fabiodrb.github.io`:
um único ecrã "My Resume" com foto, perfil, contactos e redes sociais.

## Stack / como corre
- Site **estático**: `index.html` + `style.css` + `assets/` (foto). Sem build, sem framework, sem backend.
- Ícones via Font Awesome 4.7 (CDN).
- Servido como estático no **home-server** (deploy pelo painel).

## Estrutura
- `index.html` — a página toda (um só ecrã, secção "Home / My Profile").
- `style.css` — estilos.
- `assets/fb-gray(1)(1).jpg` — foto de perfil.

## Estado / pendências
- Está a sair do **GitHub Pages** (a despublicar).
- Conteúdo estático: para mudar texto/foto, editar `index.html` / `assets` e publicar.
- Limpeza possível: o `index.html` tem HTML aninhado duplicado (um <!DOCTYPE>/<html>
  dentro do outro, resto de um "partial") e referencia `css/styles.css` que não existe
  (o ficheiro real é `style.css`).

## Como pôr no ar
Re-build no cartão da app no painel (home-server).
