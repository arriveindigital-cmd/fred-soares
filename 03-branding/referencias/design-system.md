# Design System — Dr. Frederico Soares

> Base visual da marca. Todas as skills que geram conteúdo visual (carrossel, proposta, criativo, landing page) leem este arquivo antes de criar qualquer coisa.

---

## Cores

| Papel | Nome | Hex | Figma 0–1 | Onde usar |
|-------|------|-----|-----------|-----------|
| Vermelho marca | Carmim | `#980C28` | r:.596 g:.047 b:.157 | Logo, badges, acentos, CTA |
| Vermelho escuro | Borgonha | `#6B0A1C` | r:.420 g:.039 b:.110 | Hover, sombra do carmim |
| Gradiente início | Rosa | `#C0426A` | r:.752 g:.259 b:.416 | Gradient start (foto overlay) |
| Gradiente fim | Azul Marinho | `#1C3F80` | r:.110 g:.247 b:.502 | Gradient end (foto overlay) |
| Fundo principal | Branco | `#FFFFFF` | r:1 g:1 b:1 | Fundo de posts tipográficos |
| Fundo alternativo | Off-white | `#F5F7FA` | r:.961 g:.969 b:.980 | Cards secundários |
| Texto principal | Escuro | `#0F1725` | r:.059 g:.090 b:.145 | Títulos e corpo em fundo claro |
| Texto secundário | Cinza médio | `#4A5568` | r:.290 g:.333 b:.408 | Subtítulos, legendas |
| Assinatura | Cinza dim | `#718096` | r:.443 g:.502 b:.588 | Assinatura, labels |

**Cores proibidas:** verde, amarelo, cores "natureza" — a marca é clínica e profissional.

---

## Tipografia

**Família única: Montserrat** (sem serifa — visual direto e clínico)

| Papel | Família | Peso | Tamanho base | Onde usar |
|-------|---------|------|-------------|-----------|
| Headline principal | Montserrat | ExtraBold | 56–72px | Título do post, frase de impacto |
| Headline secundário | Montserrat | Bold | 40–56px | Subtítulo, pergunta de gancho |
| Corpo | Montserrat | Regular | 16–20px | Parágrafos, explicações |
| Label / UI | Montserrat | SemiBold | 10–13px | Badges, assinaturas, datas, CTA |
| Assinatura | Montserrat | Regular | 11px | "DR. FREDERICO SOARES · FISIOTERAPEUTA" |

**Destaque inline:** palavras-âncora do headline recebem cor carmim `#980C28` — sem mudar o peso ou família.

**Fonte no Google Fonts:** Montserrat

---

## Elementos visuais

- **Border-radius dos cards:** 0px (visual limpo, sem arredondamento)
- **Acento separador:** retângulo 52×3px, cor sólida carmim `#980C28` — usado entre headline e corpo do texto
- **Barra de gradiente:** 6px de altura, largura total, na base do frame — gradiente Rosa→Azul Marinho
- **Destaque inline:** palavras-âncora do headline em carmim (mesmo peso, só cor muda)
- **CTA box:** box com borda 1px carmim, texto Montserrat SemiBold 15px carmim, padding 24px
- **Margem padrão:** 100px em todos os lados (content width = 880px em 1080)
- **Slide counter:** Montserrat SemiBold 18px carmim, alinhado topo-direito nos slides do carrossel
- **Sombras:** sem sombra nos elementos — visual clínico e limpo

---

## Estilo geral

Clínico e confiante. Usa foto editorial com sobreposição de gradiente Rosa→Azul (overlay) para posts de foto, e fundo off-white `#F5F7FA` para posts tipográficos. A tipografia é inteiramente Montserrat — ExtraBold nos headlines para peso e autoridade, Regular no corpo para fluidez. O destaque de palavras-âncora em carmim inline é o principal recurso visual dos textos. O vermelho carmim é usado como acento preciso — nunca como fundo principal.

---

## O que nunca fazer

- Usar verde ou cores de "natureza/bem-estar" — contradiz o posicionamento clínico
- Colocar texto sobre foto sem overlay de gradiente — ilegível e fora do padrão
- Usar outro font além de Montserrat — a família é única e não muda
- Usar tipografia cursiva/script — fora do tom direto e confiante
- Cores saturadas ou vibrantes além do carmim — a paleta é contida

---

## Logo

- **Arquivo principal:** assets/logo.svg
- **Ícone isolado (símbolo):** assets/stamp-iso.svg
- **Avatar:** assets/Avatar.jpg (símbolo carmim em fundo branco)
- **Texto logotipo:** "FRED SOARES" em sans-serif bold
- **Cores:** carmim `#980C28` degradê para borgonha `#6B0A1C`
- **Área de respiro mínima:** 24px em todos os lados
- **Tamanho sugerido em posts:** símbolo ~40px + texto ao lado

---

## Gradiente padrão (Figma)

```
Stops: [{color:{r:.752,g:.259,b:.416,a:1},position:0}, {color:{r:.110,g:.247,b:.502,a:1},position:1}]
Transform: [[1,0,0],[0,0,0.5]]  ← esquerda para direita
```

---

## Assinatura padrão

`DR. FREDERICO SOARES  ·  FISIOTERAPEUTA`
- Família: Montserrat Regular
- Tamanho: 11px
- Letter spacing: 12%
- Cor: Cinza dim `#718096`
- Posição: y = H - 100 - 16 (base, margem inferior)
