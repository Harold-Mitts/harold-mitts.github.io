# Word Cloud Generator

Interactive word cloud generator with two modes: automatic text analysis and manual JSON weighting.

## Features

### Text Analysis Mode
- Paste any text (articles, transcripts, documents)
- Automatic word frequency analysis
- Smart stop-word filtering
- No manual configuration needed

### JSON Weights Mode
- Manually specify word weights
- Full control over word importance
- Perfect for curated visualizations
- Format: `{"word": weight, "another": weight}`

### Customization
- 5 color schemes (Blues, Purples, Greens, Reds, Rainbow)
- Custom background and text colors
- Adjustable word count (10-300)
- High-resolution PNG export

## Usage

1. **Choose Mode**: Text Analysis or JSON Weights
2. **Input Data**: Paste text or enter JSON
3. **Customize**: Select colors and max words
4. **Generate**: Click "Generate Word Cloud"
5. **Download**: Save as PNG

## Technology

- Pure HTML/CSS/JavaScript (no build step)
- [wordcloud2.js](https://github.com/timdream/wordcloud2.js) library
- HTML5 Canvas rendering
- Client-side processing (no server needed)

## Live Demo

https://harold-mitts.github.io/word-cloud/