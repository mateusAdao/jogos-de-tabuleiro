# VALIDAÇÂO DO VALIDATOR.org
<img width="1919" height="935" alt="image" src="https://github.com/user-attachments/assets/29493ad7-6fc5-4f7e-a7fd-99bc27bbbd56" />


# TESTE NO LIGHTHOUSE
## ANTES
<img width="729" height="487" alt="image" src="https://github.com/user-attachments/assets/9723b60e-6695-45e6-abeb-0128b7b672c6" />


## DEPOIS
<img width="1919" height="937" alt="image" src="https://github.com/user-attachments/assets/f10596c0-6e33-4489-8f0e-b4f51c125aeb" />

## palavras-chave escolhidas
- jogos de tabuleiro
- jogos de estrategia
- rpg de mesa

## decisoes tomadas
- **meta tags e head:** adicao de title e meta description unicos em cada pagina usando as palavras-chave principais, alem de tag canonical para evitar conteudo duplicado.
- **open graph e favicon:** configuracao das tags og:title, og:description, og:url e og:image (1200x630) para melhorar a previa ao compartilhar o link, junto com o favicon.svg para eliminar erro 404.
- **dados estruturados (json-ld):** inclusao de schema.org do tipo ItemList no index.html listando os jogos em destaque e Article no sobre.html com informacoes de autoria e data.
- **arquivos de rastreamento:** criacao do robots.txt e sitemap.xml na raiz do projeto com as urls absolutas do github pages.
- **imagens e links internos:** conversao das imagens restantes para o formato webp, adicao de loading="lazy" nas imagens fora da primeira tela e criacao da pagina sobre.html conectada pelo menu de navegacao.