# FixacaoPOO

Objetivo:
Criar um sistema para gerenciar diferentes tipos de animais em um zoológico,
aplicando todos os conceitos de POO.

Tarefas:
1. Classe Base Animal:
o Propriedades: Nome (string), Idade (int)
o Método abstrato: EmitirSom()
o Método virtual: Apresentar() (exibe nome e idade)
2. Classes Derivadas:
o Cachorro: Sobrescreve EmitirSom() para latir
o Gato: Sobrescreve EmitirSom() para miar
o Pássaro: Adiciona método Voar()
3. Encapsulamento:
o Validar Idade para não aceitar valores negativos
4. Polimorfismo:
o Criar lista de animais e chamar EmitirSom() de forma polimórfica
5. Composição:
o Classe Zoo que contém uma lista de animais

1. O que devemos fazer?

• Corrigir a declaração da classe Animal para ser abstrata
• Implementar encapsulamento na propriedade Idade
• Sobrescrever EmitirSom() nas classes derivadas
• Criar método Apresentar() na classe base
• Adicionar validação para idade negativa
• Demonstrar polimorfismo em uma lista de animais
• Criar um menu interativo para adicionar animais ao zoológico
