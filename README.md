# Calculadora de Finanças Pessoais em Java

[![Java](https://img.shields.io/badge/Java-17%2B-blue.svg)](https://www.oracle.com/java/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

Um sistema completo para gerenciamento financeiro pessoal desenvolvido em Java, aplicando os principais conceitos de Programação Orientada a Objetos (POO).

## 📌 Índice

- [Funcionalidades](#-funcionalidades)
- [Tecnologias e Conceitos](#-tecnologias-e-conceitos)
- [Como Executar](#-como-executar)
- [Exemplos de Uso](#-exemplos-de-uso)
- [Roadmap](#-roadmap)
- [Contribuição](#-contribuição)
- [Licença](#-licença)

## ✨ Funcionalidades

✅ **Cadastro de transações**
- Adição de receitas e despesas com descrição, valor e categoria
- Validação de dados de entrada

📊 **Relatórios financeiros**
- Cálculo automático do saldo atual
- Listagem completa de todas as movimentações
- Resumo organizado por categorias

⚙️ **Gerenciamento**
- Armazenamento em memória (ArrayList)
- Interface via terminal intuitiva

## 🛠️ Tecnologias e Conceitos

**Tecnologias utilizadas:**
- Java 17+
- Maven (para gerenciamento de dependências)

**Princípios de POO aplicados:**
| Conceito | Implementação |
|----------|---------------|
| **Herança** | `Receita` e `Despesa` herdam de `Movimento` |
| **Polimorfismo** | Método `getValor()` com comportamentos diferentes |
| **Encapsulamento** | Atributos privados com métodos acessores |
| **Abstração** | Classe abstrata `Movimento` como modelo base |


## 🚀 Como Executar

**Pré-requisitos:**
- JDK 17+ instalado
- Maven instalado (opcional)

**Passos:**
1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/calculadora-financas.git
```

2. Navegue até o diretório do projeto:
```bash
cd calculadora-financas
```

3. Compile e execute:
```bash
javac src/main/java/*.java src/main/java/model/*.java src/main/java/service/*.java
java -cp src/main/java Main
```

Ou usando Maven:
```bash
mvn compile exec:java -Dexec.mainClass="Main"
```

## 💻 Exemplos de Uso

1. **Adicionando uma receita:**
```
>>> Selecione uma opção:
1 - Adicionar Receita
2 - Adicionar Despesa
3 - Ver Saldo
4 - Listar Transações
5 - Resumo por Categoria

Digite 1

Informe a descrição: Salário
Informe o valor: 5000.00
Informe a categoria: Renda Fixa
```

2. **Visualizando o saldo:**
```
Saldo atual: R$ 4,250.00
(Receitas: R$ 5,000.00 | Despesas: R$ 750.00)
```

## 🗺️ Roadmap

- [ ] Implementar persistência em arquivo
- [ ] Adicionar suporte a datas nas transações
- [ ] Criar interface gráfica com JavaFX
- [ ] Desenvolver relatórios mensais
- [ ] Adicionar exportação para CSV/PDF

## 🤝 Contribuição

Contribuições são bem-vindas! Siga estes passos:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/awesome-feature`)
3. Commit suas mudanças (`git commit -m 'Add some awesome feature'`)
4. Push para a branch (`git push origin feature/awesome-feature`)
5. Abra um Pull Request

## 📜 Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

---

Feito com ❤️ por [haniel](https://github.com/haniel-santos)
