# SiteDoisBlazor 🌐

A aplicação traz 3 funcionalidades integradas:

1. **Conversor de Temperatura**
   - **Conceito:** Uso do @bind em inputs e cálculos matemáticos no botão.
   - **Descrição:** O usuário digita uma temperatura em Celsius e converte para Fahrenheit.

2. **Calculadora de Média do Aluno (/media)**
   - **Conceito:** Validações condicionais simples (@if) e uso de variáveis que iniciam vazias (double?).
   - **Descrição:** Calcula a média de duas notas. Mostra a mensagem verde "Aprovado!" se for maior ou igual a 7.0, ou vermelho "Reprovado!" caso contrário.

3. **Sorteador de Números (/sorteio)**
   - **Conceito:** Uso da biblioteca padrão do C# (System.Random) dentro do Blazor.
   - **Descrição:** Um botão que sorteia e exibe um número aleatório de 1 a 100.

**Navegação Integrada:** Todas as páginas foram incluídas no componente NavMenu.razor utilizando <NavLink>, permitindo acessar as atividades diretamente pelo menu lateral do site.

## 🛠️ Tecnologias
- **C#** / **.NET**
- **Blazor Web App**
