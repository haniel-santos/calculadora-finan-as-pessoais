📄 Projeto: #Calculadora de Finanças Pessoais
Autor: Haniel Silva Santos
Tecnologia: Java
Paradigma: Programação Orientada a Objetos (POO)

#1. Objetivo do Projeto
Este projeto tem como objetivo criar um software simples de controle financeiro pessoal, capaz de registrar receitas e despesas, calcular o saldo mensal e apresentar resumos por categoria de gastos.
Ele foi desenvolvido em Java com Programação Orientada a Objetos (POO), visando a prática de conceitos como herança, abstração, encapsulamento e polimorfismo.

#2. Funcionalidades
✅ Adicionar receitas (com descrição, valor e categoria)

✅ Adicionar despesas (com descrição, valor e categoria)

✅ Calcular o saldo atual com base nas movimentações

✅ Listar todas as movimentações realizadas

✅ Gerar um resumo agrupado por categoria

#3. Estrutura de Classes
1. Movimento (classe abstrata):

Atributos: descricao, valor, categoria

Método abstrato: getValor()

2. Receita (subclasse de Movimento):

Implementa getValor() retornando valor positivo

3. Despesa (subclasse de Movimento):

Implementa getValor() retornando valor negativo

#4. GerenciadorFinanceiro:

Lista de movimentos (ArrayList)

Métodos para adicionar, calcular saldo, listar movimentos e resumir por categoria

#5. Main:

Classe de execução com menu no terminal para interação com o usuário


#6. Lógica de Funcionamento
O usuário interage com o sistema por meio de um menu no terminal. Ele pode adicionar uma receita ou despesa informando os dados necessários.
Todos os movimentos são armazenados em uma lista, e o sistema oferece opções para calcular o saldo total, listar os lançamentos e exibir resumos por categoria.
As receitas somam valores positivos e as despesas subtraem do saldo total.

#7. Conceitos de POO Aplicados
🧬 Herança: Receita e Despesa herdam de Movimento

🧩 Abstração: Movimento é uma classe abstrata

🎭 Polimorfismo: o método getValor() se comporta de forma diferente em Receita e Despesa

🔒 Encapsulamento: os atributos são privados, acessados via métodos públicos

#8. Possíveis Expansões Futuras
Suporte a datas (LocalDate)

Exportar dados em .txt ou .csv

Persistência com arquivos ou banco de dados

Interface gráfica com JavaFX

Versão web com Spring Boot

