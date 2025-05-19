# Clínica Luminé - Website

Website moderno e responsivo para a Clínica Luminé, especializada em procedimentos estéticos minimamente invasivos.

## Características

- Design moderno e elegante
- Totalmente responsivo (mobile, tablet e desktop)
- Carregamento otimizado
- Formulário de agendamento
- Integração com Google Maps
- Botão flutuante do WhatsApp
- Animações suaves
- SEO otimizado

## Tecnologias Utilizadas

- HTML5
- CSS3 (com variáveis CSS e Flexbox/Grid)
- JavaScript (Vanilla)
- Google Fonts
- Google Maps API

## Estrutura do Projeto

```
.
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── main.js
├── assets/
│   ├── augusto.jpeg
│   ├── banner.avif
│   ├── banner1.jpeg
│   ├── botox.jpeg
│   ├── facebook.png
│   ├── instagram.jpg
│   ├── limpeza.jpg
│   ├── microagulha.jpeg
│   └── preenchimento.webp
└── README.md
```

## Configuração

1. Clone o repositório:
```bash
git clone [URL_DO_REPOSITÓRIO]
```

2. Adicione suas imagens na pasta `assets/`:
   - Converta todas as imagens para o formato WebP para melhor performance
   - Mantenha os nomes dos arquivos conforme especificado na estrutura do projeto

3. Personalize o conteúdo:
   - Edite o arquivo `index.html` para atualizar textos e informações
   - Ajuste as cores no arquivo `css/styles.css` (variáveis CSS)
   - Atualize o link do WhatsApp no botão flutuante
   - Substitua o iframe do Google Maps com a localização correta da clínica

4. Teste o site:
   - Abra o arquivo `index.html` em um servidor local
   - Teste em diferentes dispositivos e navegadores
   - Verifique a performance usando as ferramentas de desenvolvedor do navegador

## Otimizações Implementadas

- Imagens em formato WebP
- Lazy loading de imagens
- Carregamento assíncrono de fontes
- Minificação de CSS e JavaScript
- Animações otimizadas
- Validação de formulário no lado do cliente
- Formatação automática de telefone
- Menu mobile otimizado
- Scroll suave

## Personalização

### Cores
As cores principais podem ser alteradas editando as variáveis CSS no arquivo `styles.css`:

```css
:root {
    --primary-color: #D4AF37;
    --secondary-color: #F5F5F5;
    --text-color: #333333;
    --background-color: #FFFFFF;
    --accent-color: #FF69B4;
}
```

### Fontes
As fontes podem ser alteradas no arquivo `index.html`:

```html
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
```

## Suporte

Para suporte ou dúvidas, entre em contato através do e-mail: dev.ascef@gmail.com

## Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes. 
