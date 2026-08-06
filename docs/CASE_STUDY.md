# Estudo de caso — AlphaAI

## Contexto

Informações financeiras estão disponíveis em grande quantidade, mas muitas pessoas ainda têm dificuldade para transformar esse conteúdo em decisões práticas. É comum encontrar plataformas que começam por cotações, indicadores e produtos de investimento antes de ajudar o usuário a organizar o básico.

O AlphaAI foi criado a partir de uma ideia simples: **a pessoa precisa compreender e organizar a própria vida financeira antes de avançar para investimentos**.

## Problema trabalhado

A experiência precisava lidar com três dificuldades principais:

1. excesso de informação e linguagem técnica;
2. falta de clareza sobre qual deve ser o próximo passo;
3. separação entre aprendizado, planejamento e acompanhamento financeiro.

## Hipótese de produto

Uma plataforma educativa pode ser mais útil quando:

- entende o objetivo e o nível de conhecimento do usuário;
- apresenta uma ação por vez;
- conecta explicações a ferramentas práticas;
- mantém mercado e investimentos como laboratório de estudo;
- preserva dados pessoais localmente sempre que possível.

## Solução proposta

O produto foi dividido em quatro frentes que se complementam.

### 1. Aprendizado

O usuário cria um perfil, escolhe um objetivo e segue jornadas com missões, progresso, XP e conteúdos graduais. A experiência foi pensada para evitar que a pessoa receba assuntos avançados antes de dominar conceitos básicos.

### 2. Planejamento

A calculadora financeira transforma perguntas comuns — como montar uma reserva ou alcançar uma meta — em simulações simples. O resultado pode virar uma prioridade acompanhada pelo módulo **Meu plano**, que mostra o valor restante e o próximo passo.

### 3. Assistência contextual

O Alpha Assistant funciona como ponto de apoio dentro da aplicação. Ele explica conceitos, considera informações locais do produto e direciona o usuário para a área mais adequada, sem executar operações financeiras.

### 4. Mercado como estudo

Dados históricos, indicadores, gráficos, carteira e alertas permanecem disponíveis, mas são apresentados como ferramentas educativas. O objetivo é ajudar na compreensão de risco, comportamento e contexto, não prometer resultados.

## Decisões importantes

### Local-first

Perfil, progresso, plano e carteira são armazenados localmente. Essa decisão reduz a exposição de informações pessoais e mantém o produto utilizável sem depender de uma conta remota.

### Arquitetura por domínio

Aprendizado, planejamento, assistente, mercado, carteira e persistência são tratados como áreas separadas. Isso facilita testes, manutenção e evolução do produto.

### Educação antes de recomendação

O sistema evita linguagem que possa ser interpretada como promessa de rentabilidade ou indicação individual de investimento. Simulações são apresentadas como cenários educativos.

### Interface orientada ao próximo passo

Em vez de mostrar todas as possibilidades ao mesmo tempo, o produto tenta destacar o que é mais relevante naquele momento.

## Desafios técnicos e de produto

- manter consistência entre diferentes módulos;
- transformar conceitos financeiros em linguagem acessível;
- preservar o contexto do usuário sem depender de serviços externos;
- organizar dados de mercado, indicadores e gráficos sem sobrecarregar a experiência;
- criar testes para regras de negócio, persistência e navegação;
- separar claramente conteúdo educativo de aconselhamento financeiro.

## Competências aplicadas

Este projeto reúne prática em:

- Python e desenvolvimento modular;
- Streamlit e construção de interfaces;
- SQLite e persistência local;
- Plotly e visualização de dados;
- integração com fontes de dados de mercado;
- testes automatizados e GitHub Actions;
- UX writing e documentação;
- definição de produto e priorização de funcionalidades.

## Resultado atual

O AlphaAI já possui uma base funcional com jornada educativa, calculadora, plano financeiro guiado, assistente, mercado, carteira, alertas e verificações automatizadas de qualidade.

A próxima etapa pública é apresentar capturas reais, um vídeo curto de demonstração e uma navegação guiada pelas principais funcionalidades.

---

[Voltar para a apresentação](../README.md)
