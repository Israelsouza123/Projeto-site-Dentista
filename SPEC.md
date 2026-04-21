# Site Profissional - Dr. Odontologia

## Concept & Vision
Um site odontológico que transmite profissionalismo, confiança e cuidado. O design minimalista com toques de cor verde transmite saúde, bem-estar e esperança. A experiência deve fazer o paciente se sentir seguro e bem cuidado desde o primeiro acesso.

## Design Language

### Aesthetic Direction
Minimalista médico com toques orgânicos. Inspirado em clínicas de alto padrão suíças — limpo, preciso, mas acolhedor.

### Color Palette
- **Primary**: #0D9488 (Teal - saúde e confiança)
- **Secondary**: #14B8A6 (Teal lighter)
- **Accent**: #F0FDFA (Teal 50 - backgrounds suaves)
- **Background**: #FFFFFF (Branco puro)
- **Background Alt**: #F8FAFC (Slate 50)
- **Text Primary**: #0F172A (Slate 900)
- **Text Secondary**: #64748B (Slate 500)
- **Gold Accent**: #D4AF37 (destaque premium)

### Typography
- **Headings**: 'Playfair Display', serif - elegância clássica
- **Body**: 'Inter', sans-serif - legibilidade moderna
- **Sizes**: Display 48px, H1 36px, H2 28px, H3 20px, Body 16px

### Spatial System
- Container max-width: 1200px
- Section padding: 80px vertical
- Card padding: 32px
- Gap between elements: 24px

### Motion Philosophy
- Transições suaves de 300ms ease
- Hover em cards com subtle lift (translateY -4px, shadow increase)
- Fade-in on scroll para seções
- Botões com scale sutil no hover

## Layout & Structure

### Seções
1. **Header** - Logo + Navegação sticky com blur backdrop
2. **Hero** - Título impactante + CTA + Imagem ilustrativa
3. **Sobre o Profissional** - Bio + Credenciais + Foto
4. **Serviços** - Grid de cards com ícones
5. **Diferenciais** - Por que escolher + números/stats
6. **Contato** - Formulário + Informações + Mapa visual
7. **Footer** - Links + Redes sociais + Copyright

### Responsive Strategy
- Desktop: Layout completo em grid
- Tablet: Stack parcial, 2 colunas
- Mobile: Stack vertical, navegação hamburger

## Features & Interactions

### Header
- Sticky com background blur ao scrollar
- Links com underline animado no hover
- Mobile: hamburger menu com slide-in

### Hero
- Título animado com fade-in
- Botão CTA com hover effect
- Imagem com sombra suave

### Cards de Serviços
- Hover: elevação + borda colorida
- Ícone com background circular
- Descrição concisa

### Formulário de Contato
- Validação em tempo real
- Estados: default, focus, error, success
- Feedback visual claro

## Component Inventory

### Navigation
- Desktop: Horizontal links
- Mobile: Hamburger + drawer
- States: default, hover (underline), active (bold)

### Button Primary
- Background: Primary color
- Text: White
- Hover: Darker shade + scale 1.02
- Active: Even darker

### Service Card
- Background: White
- Border: 1px slate-200
- Border hover: Primary
- Shadow hover: lg
- Icon: 48px circular background

### Stats Card
- Number: Display size, primary color
- Label: Secondary text

### Form Input
- Border: slate-300
- Focus: Primary ring
- Error: Red border + message
- Label: Floating or above

## Technical Approach
- React + Vite + TypeScript
- Tailwind CSS para estilos
- Component-based architecture
- Lucide React para ícones
- Google Fonts via CDN
