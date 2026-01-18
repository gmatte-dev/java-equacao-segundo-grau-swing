# 📐 Calculadora de Equação do 2º Grau

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/Swing-GUI-blue?style=for-the-badge" alt="Swing">
  <img src="https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen?style=for-the-badge" alt="Status">
</p>

## 📝 Sobre o Projeto

Aplicação desktop desenvolvida em **Java** com interface gráfica **Swing JFrame** para calcular equações do segundo grau (ax² + bx + c = 0). O programa recebe os coeficientes A, B e C informados pelo usuário e retorna:

- O valor do **Delta (Δ)**
- O **tipo de raízes** (reais distintas, reais iguais ou inexistentes nos reais)
- Os **valores das raízes** (quando existem)

---

## 🎓 Origem do Projeto

> Este projeto foi desenvolvido durante o **Curso de Java - 40 Horas** ministrado pelo professor **Gustavo Guanabara** no [Curso em Vídeo](https://www.cursoemvideo.com/).

O curso oferece uma base sólida em programação Java, abordando desde conceitos fundamentais até a criação de interfaces gráficas com Swing.

---

## 🧮 Conceitos Matemáticos

### Fórmula de Bhaskara

```
x = (-b ± √Δ) / 2a
```

### Cálculo do Delta (Discriminante)

```
Δ = b² - 4ac
```

### Tipos de Raízes

| Delta (Δ) | Tipo de Raízes |
|-----------|----------------|
| Δ > 0 | Duas raízes reais e distintas |
| Δ = 0 | Duas raízes reais e iguais |
| Δ < 0 | Não possui raízes reais |

---

## 🚀 Funcionalidades

- [x] Entrada dos coeficientes A, B e C
- [x] Cálculo automático do Delta
- [x] Identificação do tipo de raízes
- [x] Exibição dos valores das raízes (quando existem)
- [x] Interface gráfica amigável com Swing JFrame
- [x] Validação de entrada de dados
- [x] Botão para limpar campos e realizar novo cálculo

---

## 🖥️ Pré-requisitos

Antes de executar o projeto, certifique-se de ter instalado:

- **Java JDK 8** ou superior
- Uma IDE de sua preferência (NetBeans, Eclipse, IntelliJ IDEA, VS Code)

---

## ⚙️ Como Executar

1. **Clone o repositório**
   ```bash
   git clone https://github.com/seu-usuario/calculadora-equacao-2grau.git
   ```

2. **Acesse a pasta do projeto**
   ```bash
   cd calculadora-equacao-2grau
   ```

3. **Compile o projeto**
   ```bash
   javac Main.java
   ```

4. **Execute a aplicação**
   ```bash
   java Main
   ```

> 💡 **Dica:** Se estiver usando uma IDE como NetBeans ou Eclipse, basta abrir o projeto e clicar em "Run".

---

## 📸 Screenshot

```
┌─────────────────────────────────────────┐
│     CALCULADORA EQUAÇÃO 2º GRAU         │
├─────────────────────────────────────────┤
│                                         │
│   Coeficiente A: [___________]          │
│   Coeficiente B: [___________]          │
│   Coeficiente C: [___________]          │
│                                         │
│        [ CALCULAR ]  [ LIMPAR ]         │
│                                         │
├─────────────────────────────────────────┤
│   Delta (Δ): 49                         │
│   Tipo: Duas raízes reais distintas     │
│   X' = 2.0                              │
│   X'' = -3.0                            │
└─────────────────────────────────────────┘
```

---

## 📁 Estrutura do Projeto

```
calculadora-equacao-2grau/
│
├── src/
│   ├── Main.java           # Classe principal
│   ├── Calculadora.java    # Lógica de cálculo
│   └── TelaCalculadora.java # Interface Swing
│
└── README.md
```

---

## 🛠️ Tecnologias Utilizadas

- **Java SE** - Linguagem de programação
- **Swing** - Biblioteca para interface gráfica
- **JFrame** - Container principal da aplicação
- **JTextField** - Campos de entrada de dados
- **JButton** - Botões de ação
- **JLabel** - Exibição de resultados

---

## 📚 Aprendizados

Durante o desenvolvimento deste projeto, foram aplicados os seguintes conceitos:

- Programação Orientada a Objetos (POO)
- Criação de interfaces gráficas com Swing
- Manipulação de eventos (ActionListener)
- Tratamento de exceções
- Operações matemáticas em Java
- Estruturas condicionais

---

## 🤝 Contribuições

Contribuições são sempre bem-vindas! Se você tem alguma sugestão para melhorar este projeto:

1. Faça um Fork do projeto
2. Crie uma Branch para sua feature (`git checkout -b feature/NovaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona NovaFeature'`)
4. Push para a Branch (`git push origin feature/NovaFeature`)
5. Abra um Pull Request



## 👨‍💻 Autor

Desenvolvido com 💜 durante o **Curso de Java 40 Horas** do [Curso em Vídeo](https://www.cursoemvideo.com/)

**Professor:** Gustavo Guanabara

---

## 🔗 Links Úteis

- [Curso em Vídeo - Java](https://www.cursoemvideo.com/curso/java-basico/)
- [Documentação Java](https://docs.oracle.com/en/java/)
- [Tutorial Swing](https://docs.oracle.com/javase/tutorial/uiswing/)

---

<p align="center">
  ⭐ Se este projeto te ajudou, considere dar uma estrela!
</p>
