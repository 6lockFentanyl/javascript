Exercício 2 — Alterações no DevTools do Globo.com

Acessei o site Globo.com e abri o DevTools usando F12.

Na guia Console, digitei o seguinte comando para alterar o título de uma notícia:

document.querySelector('.post__title').textContent = 'Cientistas anunciam uma descoberta que vai salvar milhares de vidas'

Para mudar a imagem da notícia, selecionei a imagem na guia Elements e alterei seus atributos src e srcset pelo Console:

$0.srcset = 'https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?w=1200'
$0.src = 'https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?w=1200'

Depois das alterações, tirei um screenshot da página para mostrar o resultado.

Observação: as mudanças são temporárias e desaparecem quando a página é recarregada.