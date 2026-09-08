# Plano de Melhoria do Site Kuria Saúde 🌸

## Visão Geral
Transformar o site da Kuria Saúde em uma experiência imersiva e intuitiva, inspirada em parallax premiados, com animações únicas tipo "viva" que desprendem ramos conforme o scroll.

---

## 1. DESIGN & ANIMAÇÕES 🎨

### Conceito Principal: "Viva Desprendendo Ramos"
- À medida que o usuário rola a página, ramos com bolas (ícones de seções) se desprendem da "planta"
- Cada ramo = nova seção (Escalas, Sobre, Telemedicina, etc.)
- Transição suave entre parallax e animações

### Referências Analisadas
- **CSS Design Awards Parallax Gallery** → Padrões de movimento fluido
- **Sites Premiados Notáveis:**
  - Viru – Clean transitions
  - Forge Automotive – Kinetic layered motion
  - ESQRD – Web3 interactive depth
  - Celso Marrero – Cinematic motion

### Padrões a Implementar
1. ✅ Parallax de fundo (velocidade diferente do conteúdo)
2. ✅ Animações CSS smooth (sem janks)
3. ✅ Scroll triggers para desprendimento de ramos
4. ✅ Ícones dinâmicos para cada seção
5. ✅ Transições suaves entre parallax layers

---

## 2. FUNCIONALIDADES 💡

### Interface Intuitiva
- [ ] Menu claro e acessível
- [ ] Escalas com descrição prática
- [ ] CTAs (Chamadas para Ação) bem posicionadas
- [ ] Navegação por "ramos" (seções)

### Escalas Auto-Aplicáveis
- [ ] Design card melhorado
- [ ] Instruções claras em linguagem simples
- [ ] Resultados apresentados de forma compreensível
- [ ] Sem armazenamento de dados (anonimato garantido)

### Telemedicina
- [ ] Informações sobre consultas
- [ ] Agendamento intuitivo
- [ ] Sobre a Dra. Vanessa de forma humanizada

---

## 3. TECNOLOGIA ⚙️

### Stack Sugerida
- **Frontend:** HTML5 + CSS3 + JavaScript vanilla (ou React/Vue se necessário)
- **Animações:** GSAP ou Intersection Observer API
- **Performance:** Webpack/Vite para otimização
- **Deploy:** Vercel (já alinhado com seus side-apps)

### Componentes Python/Vercel (Futuros)
- [ ] API para rastreamento anônimo de escalas
- [ ] Análise de dados (relatórios agregados)
- [ ] Integração com agenda de telemedicina

---

## 4. PERFORMANCE ⚡

### Otimizações de Velocidade
- [ ] Lazy loading de imagens
- [ ] CSS minificado e otimizado
- [ ] JavaScript tree-shaking
- [ ] Compressão de assets
- [ ] Cache estratégico
- [ ] Crítico: Evitar lag em animações parallax (usar `transform` e `opacity`)

### Métricas a Melhorar
- Core Web Vitals (LCP, FID, CLS)
- Time to First Byte (TTFB)
- Lighthouse score

---

## 5. ESTRUTURA DE ARQUIVOS

```
kuria-website/
├── index.html              # Home com "viva" principal
├── css/
│   ├── main.css           # Estilos gerais
│   ├── parallax.css       # Animações parallax
│   ├── animations.css     # Animações de ramos
│   └── performance.css    # Otimizações
├── js/
│   ├── main.js            # Lógica principal
│   ├── parallax.js        # Sistema de parallax
│   ├── scroll-triggers.js # Desprendimento de ramos
│   └── escalas.js         # Lógica das escalas
├── assets/
│   ├── images/            # Otimizadas
│   ├── icons/             # SVGs dos ramos
│   └── fonts/             # Web fonts otimizadas
└── api/                   # Futuros endpoints Python
```

---

## 6. PRÓXIMOS PASSOS

1. ✅ Analisar sites premiados de CSS Design Awards
2. ⏳ Criar templates HTML/CSS base
3. ⏳ Implementar animação "viva" com scroll triggers
4. ⏳ Adaptar escalas com novo design
5. ⏳ Testar performance e otimizar
6. ⏳ Integração com telemedicina
7. ⏳ Deploy em Vercel

---

## Notas Importantes

- **Acessibilidade:** Garantir que animações não prejudiquem a experiência para usuários com deficiências
- **Mobile First:** Considerar performance em dispositivos móveis
- **SEO:** Manter boas práticas para melhorar ranking
- **Testes:** Testar em diferentes navegadores e dispositivos

---

**Última atualização:** 2026-09-08
