# Vermilion Theme Development Context

## Obsidian CSS Variables Reference

공식 문서: https://docs.obsidian.md/Reference/CSS+variables/CSS+variables

### Heading Variables

문서: https://docs.obsidian.md/Reference/CSS+variables/Editor/Headings

**Size (기본값)**
- `--h1-size: 1.802em`
- `--h2-size: 1.602em`
- `--h3-size: 1.424em`
- `--h4-size: 1.266em`
- `--h5-size: 1.125em`
- `--h6-size: 1em`

**Color**
- `--h1-color` ~ `--h6-color`

**Font**
- `--h1-font` ~ `--h6-font`

**Weight**
- `--h1-weight` ~ `--h6-weight`

**Line Height**
- `--h1-line-height` ~ `--h6-line-height`

**Style**
- `--h1-style` ~ `--h6-style`

**Variant**
- `--h1-variant` ~ `--h6-variant`

**기타**
- `--heading-formatting`: Markdown 헤딩 문법(#) 텍스트 색상
- `--heading-spacing`: 헤딩 위 여백

### Typography Variables

문서: https://docs.obsidian.md/Reference/CSS+variables/Foundations/Typography

- `--font-text-size`: 기본 텍스트 크기
- `--font-text-theme`: 텍스트 폰트
- `--font-monospace-theme`: 코드 폰트
- `--line-height-normal`: 기본 줄 높이
- `--line-height-tight`: 타이트한 줄 높이

### Colors

문서: https://docs.obsidian.md/Reference/CSS+variables/Foundations/Colors

### Spacing

문서: https://docs.obsidian.md/Reference/CSS+variables/Foundations/Spacing

## 기본값 확인 방법

Obsidian 앱의 기본 CSS는 다음 경로에서 추출 가능:
```bash
npx asar extract /Applications/Obsidian.app/Contents/Resources/obsidian.asar /tmp/obsidian-extract
```

추출 후 `/tmp/obsidian-extract/app.css`에서 기본값 확인.
