# API de Reserva de Veículos

Esta é uma API para reserva de veículos, permitindo que os usuários reservem um veículo para um determinado período de tempo e façam pagamentos usando cartão de crédito/débito ou boleto.

## Funcionalidades

- **Consultar Veículos:** Obtenha uma lista de todos os veículos disponíveis.
- **Detalhes do Veículo:** Obtenha detalhes de um veículo específico.
- **Criar Reserva:** Faça uma reserva de veículo para um determinado período.
- **Realizar Pagamento:** Realize o pagamento para uma reserva utilizando cartão de crédito/débito ou boleto.

## Tecnologias Utilizadas

- **Node.js**
- **Express**
- **MySQL**
- **mysql2**
- **dotenv**
- **body-parser**

## Configure as variáveis de ambiente:

### Crie um arquivo .env na raiz do projeto com o seguinte conteúdo:

- **MYSQL_HOST** = localhost
- **MYSQL_PORT** = 3306
- **MYSQL_USER** = your_mysql_user
- **MYSQL_PASSWORD** = your_mysql_password
- **MYSQL_DATABASE** = your_mysql_database
- **PORT** = 3000