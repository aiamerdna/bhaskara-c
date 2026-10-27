# bhaskara-c
Calculadora de Bhaskara em C

Calculadora desenvolvida em linguagem C para resolver equações do segundo grau utilizando a Fórmula de Bhaskara, calculando o discriminante (Delta) e determinando as raízes reais.

---

Visão Geral e Contexto
Este projeto tem como objetivo aplicar os fundamentos da programação estruturada em C para resolver problemas matemáticos do segundo grau no formato padrão:
ax²+bx+c=0

O programa solicita os coeficientes 'a', 'b' e 'c' ao usuário, valida a entrada e calcula as raízes com precisão.

---

Tecnologias Utilizadas
* Linguagem: C (padrão C17)
* Compilador: GCC (via MinGW-w64)
* Ambiente de Desenvolvimento: Visual Studio Code (VS Code)

---

Instruções de Execução

Siga os passos abaixo para clonar e rodar o projeto localmente na sua máquina:

1. Pré-requisitos
Certifique-se de ter o GCC instalado (como o MinGW-w64). Você pode testar no terminal:
bash
gcc --version

3. Clonar o repositório
Abra o seu terminal e clone o projeto:
git clone [https://github.com/aiamerdna/bhaskara-c.git](https://github.com/aiamerdna/bhaskara-c.git)
cd bhaskara-c

3. Compilar o código
Utilize o GCC para compilar o arquivo fonte (raizquad.c) gerando o executável:
gcc raizquad.c -o calculadora

5. Executar a aplicação
No Windows (PowerShell / CMD):
./calculadora.exe
No Linux / macOS:
./calculadora

Exemplo de execução no terminal:

Plaintext
=== Calculadora de Bhaskara ===

insira o primeiro coeficiente: 1
insira o segundo coeficiente: -5
insira o terceiro coeficiente: 6
R1 = 3.00000
R2 = 2.00000

📄 Licença
Este projeto está sob a licença MIT. Sinta-se livre para utilizar, modificar e estudar o código. Veja o arquivo LICENSE para mais detalhes.
