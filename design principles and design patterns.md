# Design Principles and Design patterns

## Arquitetura e dependências
### Sintomas de um design porco
- Rigidez, tendencia do software ser dificil de mexer
  - medo de corrigir problemas não criticos
- Fragilidade, tendencia de quebrar em multiplos locais quando o código é mexido
  - Cada correção é um problema que cria outras necessidades de correção
- Imobilidade, tendencia de não conseguir reutilizar projetos ou códigos já escritos
- Viscosidade
  - Design
    - Quando é dificil preservar o design
  - Ambiente
    - Quando o ambiente de desenvolvimento é muito lendo e ineficiente
      - Faz os desenvolvedores perderem tempo atoa

### Mudanças de requisitos
- Se não conseguimos acompanhar de maneira adequada as mudanças dos requisitos, é culpa do design no projeto.
- Precisamos encontrar caminhos para tornar nossos designs resilientess

### Gerenciamento de dependências
- Cada um dos sintomas de um design ruim acontece por conta de novas e não planejadas dependencias entre modulos

## Principios de design de classes orientadas a objeto
### O principio do aberto e fechado