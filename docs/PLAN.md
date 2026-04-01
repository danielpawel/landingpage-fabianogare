# Plano de Desenvolvimento: Landing Page Fabiano Gari

## 1. Visão Geral
Construir uma landing page de alta conversão para o curso "Cálculos e Perícias Trabalhistas" do contador Fabiano Gari. O foco é aplicar técnicas avançadas de Vendas (Copywriting estruturado) e Design (UX/UI premium) para gerar identificação, necessidade e urgência no usuário.

## 2. Decisões de Design (UI/UX Pro Max)
- **Paleta de Cores:** Dark mode luxuoso e de alta conversão. Fundo escuro (preto/cinza escuro intenso), com elementos primários e botões em dourado (`#C9A84C`), contrastando com verde (`#2ECC71`, validação) e vermelho (`#E74C3C`, escassez).
- **Tipografia:** Serifada elegante para os títulos (`Playfair Display` ou similar, gerando autoridade) e Sans-serif limpa (`DM Sans` ou `Inter`) para corpo do texto, maximizando a legibilidade.
- **Efeitos Premium:** Minimalismo rico. Glassmorphism em áreas de destaque (bônus/depoimentos), sombras sutis em botões dourados, micro-interações ao passar o mouse em CTAs, animações fluidas baseadas em scroll.
- **Estrutura e Psicologia de Vendas:**
  1. **Ação Rápida (Ticker):** Alerta contínuo de "Vagas Limitadas / Garantia 7 Dias".
  2. **Hero Section (Acima da Dobra):** Promessa Irrecusável + Prova Rápida + Botão CTA Primário.
  3. **Validação da Dor:** Problemas reais e silenciosos que minam os honorários.
  4. **Audiência Alvo (Para quem é):** Gerenciamento de expectativas e mercado (+340% de crescimento).
  5. **Metodologia (O que o aluno aprende):** Currículo prático dissecado em Módulos atraentes.
  6. **Autoridade (Quem é Fabiano):** Construção de credibilidade e lastro de perito judicial.
  7. **Prova Social:** Depoimentos e resultados reais.
  8. **Empilhamento de Valor (Bônus):** Justificando o ROI da compra.
  9. **Oferta, Preço e Escassez Real (Timer).**
  10. **Tira-Dúvidas (FAQ) e CTA Final de Resgate.**

## 3. Arquitetura Técnica
- **Frontend Stack:** HTML5 e Tailwind CSS (para prototipagem super rápida e escalabilidade fácil do CSS) combinado a JavaScript Vanilla (para o Timer, Acordeão FAQ e Ticker animado).
- **Funcionalidades Extracampo (Pós-Frontend):** Integração dos CTAs com checkout da plataforma (Hotmart, Eduzz, etc.), instalação de Pixel/Tags de rastreamento.

## 4. Orquestração de Agentes (Fase 2)
Na etapa de implementação, após aprovação do plano, os seguintes agentes atuarão em paralelo:
1. `@frontend-specialist`: Codificará a interface HTML/Tailwind em altíssimo nível com as premissas estéticas de `ui-ux-pro-max`, aplicando UI responsiva e animações.
2. `@seo-specialist`: Otimizará a estrutura semântica HTML, Alt tags, acessibilidade (ARIA) e performance indexável.
3. `@performance-optimizer`: Garantirá velocidade de renderização da página refinando imports CSS/Fontes, e a responsividade mobile.

## 5. Próximos Passos (Checklist)
- [ ] **Etapa 1:** Aprovação deste planejamento (checkpoint).
- [ ] **Etapa 2:** Inicialização do ambiente Tailwind e Setup de Assets (fontes, ícones).
- [ ] **Etapa 3:** Codificação bloco por bloco integrando as melhores tags de UX.
- [ ] **Etapa 4:** Teste Mobile-first & auditoria final pela orquestração.
