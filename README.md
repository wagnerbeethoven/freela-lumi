# Centro Lumi - Website HTML Estático

Este é o código HTML estático completo do website do Centro Lumi, especializado em atendimento para pessoas com Transtorno do Espectro Autista (TEA) através dos métodos TEACCH e ABA.

## 📁 Estrutura dos Arquivos

### Páginas Principais
- `index.html` - Página inicial com hero, sobre, serviços, métodos e CTA
- `about.html` - Página sobre a empresa (história, missão, visão, valores, timeline)
- `services.html` - Página detalhada dos serviços oferecidos
- `teacch.html` - Página explicativa do método TEACCH
- `aba.html` - Página explicativa do método ABA
- `team.html` - Página da equipe com perfis profissionais
- `courses.html` - Página de cursos e formações
- `contact.html` - Página de contato com formulário e informações

### Páginas de Conteúdo
- `archive.html` - Arquivo de conteúdos e materiais
- `article.html` - Template para artigos individuais
- `video.html` - Template para vídeos educativos
- `search.html` - Página de busca de conteúdo

### Páginas Especiais
- `style-guide.html` - Guia completo de padrões visuais
- `figma-documentation.html` - Documentação para recriação no Figma
- `privacy-policy.html` - Política de privacidade
- `terms-of-use.html` - Termos de uso

### Arquivos de Estilo e Scripts
- `styles.css` - CSS compilado com todos os estilos do projeto
- Integração com Lucide Icons via CDN para ícones
- Fontes Google (Poppins + Open Sans)

## 🎨 Design System

### Cores
- **Azul Escuro Principal**: `#005073` - Títulos, botões primários
- **Azul Claro Secundário**: `#A2D5F2` - Fundos suaves, elementos secundários  
- **Verde Suave**: `#A7D7C5` - Elementos de destaque, CTA secundário
- **Branco**: `#FFFFFF` - Fundos principais
- **Cinza Neutro**: `#F7F7F7` - Fundos alternativos
- **Texto Escuro**: `#333333` - Texto corpo

### Tipografia
- **Títulos**: Poppins (400, 500, 600, 700)
- **Texto Corpo**: Open Sans (400, 500, 600)
- **Tamanho Base**: 16px
- **Line Height**: 1.6 para corpo, 1.2-1.4 para títulos

### Layout Responsivo
- **Mobile**: 375px+ (4 colunas)
- **Tablet**: 768px+ (8 colunas)  
- **Desktop**: 1024px+ (12 colunas)
- **Container Max**: 1280px

## ♿ Acessibilidade

### Conformidade WCAG AA
- Contraste mínimo 4.5:1 para texto normal
- Contraste mínimo 3:1 para texto grande
- Área mínima de toque: 48x48px
- Navegação por teclado completa
- Labels descritivos e alt text para imagens
- Indicadores de foco visíveis

### Recursos Implementados
- `aria-label` para botões e links
- `aria-current` para navegação ativa
- `aria-expanded` para menus dropdown
- Estrutura semântica HTML5
- Skip links para navegação rápida

## 📱 Funcionalidades

### Navegação
- Header fixo com logo e menu responsivo
- Menu mobile com hambúrguer
- Navegação dropdown para "Métodos" e "Conteúdo"
- Breadcrumbs e navegação contextual
- Footer com links organizados

### Componentes Interativos
- Formulários de contato e newsletter
- Botões CTA (Call-to-Action)
- Cards hover effects
- Carousel/slider de testimonials
- Accordion para FAQ
- Modais e overlays

### Integração Externa
- WhatsApp Web Link
- Google Maps integração
- Redes sociais (Facebook, Instagram, YouTube)
- Telefone click-to-call
- Email click-to-email

## 🛠️ Como Usar

### Configuração Básica
1. Baixe todos os arquivos HTML e CSS
2. Mantenha a estrutura de pastas
3. Abra `index.html` em um navegador
4. Todos os links internos funcionarão localmente

### Personalização
1. **Cores**: Edite as variáveis CSS em `styles.css`
2. **Conteúdo**: Modifique o HTML diretamente
3. **Imagens**: Substitua URLs do Unsplash por suas imagens
4. **Contatos**: Atualize telefones, emails e endereços

### Deploy
- Compatível com qualquer servidor web estático
- Hospedagem recomendada: Netlify, Vercel, GitHub Pages
- Requer HTTPS para funcionalidades modernas

## 📋 Dependências

### CDN Utilizados
- **Lucide Icons**: `https://unpkg.com/lucide@latest/dist/umd/lucide.js`
- **Google Fonts**: Poppins e Open Sans
- **Unsplash**: Imagens de placeholder (substituir em produção)

### JavaScript Mínimo
- Inicialização dos ícones Lucide
- Toggle do menu mobile
- Navegação básica
- Sem frameworks ou bibliotecas pesadas

## 🔧 Manutenção

### Atualização de Conteúdo
- Edite diretamente os arquivos HTML
- Mantenha consistência visual usando classes CSS existentes
- Use os mesmos padrões de estrutura para novas páginas

### SEO Otimização
- Meta tags já configuradas
- Estrutura semântica HTML5
- URLs amigáveis
- Schema markup pode ser adicionado

### Performance
- CSS minificado em um arquivo
- JavaScript mínimo
- Lazy loading pode ser implementado
- Otimização de imagens recomendada

## 📞 Informações de Contato (Exemplo)

- **Telefone**: (11) 3456-7890
- **WhatsApp**: (11) 98765-4321
- **Email**: contato@centrolumi.com.br
- **Endereço**: Rua das Flores, 123 - Centro, São Paulo/SP

## 📄 Licença

Este projeto foi desenvolvido como exemplo educativo. 
Para uso comercial, substitua conteúdos, imagens e informações de contato.

---

**Desenvolvido com foco em acessibilidade, performance e experiência do usuário.**

Para questões técnicas ou melhorias, consulte a documentação do Figma em `figma-documentation.html`.