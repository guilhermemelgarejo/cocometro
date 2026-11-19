# 💣 Cocômetro 💩

Cronômetro em forma de boneco-bomba: um fósforo acende o pavio na boca, a faísca desce pelo
intestino até a bunda e, quando o tempo acaba... **KABUM!** — explosão de cocô.

- Escolha o tempo com − / +, digitando ou pelos atalhos (10s, 30s, 1min)
- Abrir já com um tempo: `?t=90` (segundos)
- Atalhos de teclado: **Espaço** acende/pausa · **R** zera
- PWA: instalável no celular e funciona offline (precisa de HTTPS ou `localhost`)

## Rodar

Qualquer servidor estático serve, por exemplo com o PHP embutido:

```bash
php -S 0.0.0.0:8080
```

Ou com Apache: veja [`apache/cocometro.conf`](apache/cocometro.conf) (vhost `cocometro.localhost:8081`).

## Arquivos

| Arquivo | O que é |
|---|---|
| `index.html` | página inteira (HTML, CSS e JS) |
| `kabum.svg` | arte do "KABUM!" |
| `manifest.json`, `sw.js` | PWA (instalação e cache offline) |
| `icon*.png`, `icon.svg`, `apple-touch-icon.png` | ícones |
