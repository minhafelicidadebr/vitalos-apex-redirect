# Ativos de marca — VitalOS™

Versões web (otimizadas, servidas pelo app) da identidade visual oficial.
Os originais em alta resolução vivem em `docs/brand/vitalos/source/` —
nunca editados; toda geração aqui é reprodutível a partir deles.

| Arquivo | Dimensão | Peso | Gerado de | Processo |
|---|---|---|---|---|
| `vitalos-logo-horizontal-on-dark.png` | 1200×299 | ~149 KB | `logo-horizontal-original.png` (1500×500, texto branco) | recorte da margem 100% transparente (bbox 55,74–1460,424) + fit proporcional dentro de um canvas 1200×299, centralizado com padding transparente — zero distorção, zero redesenho |
| `vitalos-logo-horizontal-on-light.png` | 1200×299 | ~143 KB | `logo-horizontal-light-original.png` (2499×833, texto verde-escuro) | mesmo processo, mesmo canvas 1200×299 — enquadramento e escala calculados para bater com a versão on-dark (símbolo, baseline do texto e altura visual alinhados entre as duas) |
| `vitalos-mark-512.png` | 512×512 | ~125 KB | `simbolo-vitalos-original.png` (625×625) | resize direto do original em alta resolução, sem recorte — área de respiro, laços e centro verde preservados |
| `vitalos-mark-256.png` | 256×256 | ~44 KB | `simbolo-vitalos-original.png` (625×625) | mesmo processo do 512, resize menor |

**As duas versões da logo horizontal têm cores de texto diferentes por
desenho** (branco vs. verde-escuro) — cada uma existe para o tema onde o
texto fica legível. Nomenclatura é pela SUPERFÍCIE de uso, não pela
aparência do arquivo: `on-dark` = texto branco = usar sobre fundo escuro;
`on-light` = texto verde-escuro = usar sobre fundo claro. O símbolo
(`vitalos-mark-*.png`) é 100% dourado/verde opaco, sem texto — não precisa
de variante por tema.

Nenhum ativo foi recolorido, redesenhado, ampliado a partir de versão de
baixa resolução, ou gerado por IA generativa. `vitalos-mark-512.png` nunca
parte do símbolo de baixa resolução — sempre do original de alta resolução
em `docs/brand/vitalos/source/`.

Uso recomendado — ver `docs/brand/vitalos/BRAND-ASSET-MAP.md` para o mapa
completo de onde cada ativo aparece no app.
