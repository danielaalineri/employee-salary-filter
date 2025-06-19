📊 Employee Salary Filter

Este é um pequeno programa Java que lê dados de funcionários a partir de um arquivo .csv, filtra e processa informações com uso de Streams e Lambda expressions.
💡 Funcionalidades

    Lê uma lista de funcionários de um arquivo.

    Filtra e imprime os e-mails dos funcionários que ganham acima de um determinado salário informado pelo usuário.

    Calcula a soma dos salários dos funcionários cujo nome começa com a letra M.

📂 Formato do Arquivo de Entrada

O arquivo deve conter uma lista de funcionários com os seguintes campos, separados por vírgula:

nome,email,salário

📄 Exemplo (employees.csv)

Maria,maria@gmail.com,3200.00
Bob,bob@gmail.com,1900.00
Alex,alex@gmail.com,3100.00
Marco,marco@gmail.com,2800.00
Martha,martha@gmail.com,3000.00

▶️ Como Executar

    Compile as classes Java.

    Execute a classe Program.

    Digite o caminho completo do arquivo .csv quando solicitado.

    Informe um valor de salário para filtrar os e-mails.

💻 Exemplo de uso:

Enter full file path: C:\Users\daniela\Documents\employees.csv
Enter salary: 2500.00

🔎 Resultado esperado:

Email of people whose salary is more than 2500.00:
alex@gmail.com
maria@gmail.com
martha@gmail.com
marco@gmail.com

Sum of salary from people whose name starts with 'M': 9000.00

🛠 Tecnologias

    Java 22.0.2

    Programação funcional (Streams)

    Leitura de arquivos com BufferedReader

📁 Estrutura

src/
├── app/
│   └── Program.java
└── entities/
    └── Employee.java

