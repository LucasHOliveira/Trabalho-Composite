# **Pattern Name and Classification**
 **Composite**

# **Intent**

Combine objetos em uma estrutura de árvore para representar parte da hierarquia geral. O Composite permite que o cliente lide uniformemente com objetos únicos e combinações de objetos.

# **Motivation**

A necessidade de inserir comportamentos ou estado a objetos individuais, onde a herança acaba não sendo viável, pois é estática e aplica para uma classe inteira.

# **Applicability**

você está desenvolvendo um jogo na qual o jogador possui a possibilidade de alterar os componentes de uma arma (adicionando mira, cabo, cano,...), então você cria uma classe principal que é a arma e atrela duas outras classes onde uma é apenas o corpo original da arma (sem nenhum acessório) e a outra são os possiveis acessórios para adição.

# **Structure**

[Imagem com a estrutura](https://github.com/LucasHOliveira/Trabalho-TemplateMethod/blob/master/ImagemEstrutura/Estrutura.png)

# **Participants**

Nome: LucasGonçalves

RA: 1811511908

# **Sample Code**

[Link para a pasta do código](https://github.com/LucasHOliveira/Trabalho-TemplateMethod/tree/master/ProjetoTM-Codigo)