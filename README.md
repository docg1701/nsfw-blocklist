# nsfw-blocklist

Blocklist pessoal de sites adultos para a extensão de bloqueio do Chrome, mais a página de bloqueio.

- `blocklist.json` — formato `{urls, domains, keywords, whitelist, regexes}`; 1000 domínios, o limite que a extensão importa sem travar.
- `index.html` — página de bloqueio, usada como URL de redirecionamento da extensão. Só a tirinha, tela única, sem rolagem e sem link.

URL de redirecionamento: `https://docg1701.github.io/nsfw-blocklist/`

## Critério

Interseção de uma blocklist NSFW de ~530 mil domínios com o ranking de tráfego Tranco top-1M, cortada nos 1000 mais acessados. Fora: redes sociais (outro filtro), CDNs e hosts de asset, ad-tech e rastreadores, torrent, notícia, portal, educação e domínios mortos.

Cobre os destinos mais clicados, não a cauda longa.

## Crédito

`efficiency.png` — xkcd 1445 "Efficiency", Randall Munroe, [CC BY-NC 2.5](https://creativecommons.org/licenses/by-nc/2.5/).
