# actix-gcd

Este é um projeto simples em Rust que utiliza o framework Actix-web para criar um servidor web que calcula o Máximo Divisor Comum (GCD) de dois números.

## Requisitos

- Rust
- Cargo

## Dependências

- actix-web = "4.9.0"
- serde = { version = "1.0", features = ["derive"] }
- tokio = { version = "1.0.0", features = ["rt", "rt-multi-thread", "macros"] }

## Como executar

1. Clone o repositório:
    ```sh
    git clone https://github.com/HaroldoFV/actix-gcd.git
    cd actix-gcd
    ```

2. Compile e execute o projeto:
    ```sh
    cargo run
    ```

3. O servidor estará disponível em `http://localhost:3000`.

## Endpoints

- `GET /` - Página inicial com um formulário para calcular o GCD.
- `POST /gcd` - Calcula o GCD dos números fornecidos.

## Exemplo de uso

1. Acesse `http://localhost:3000` no seu navegador.
2. Insira dois números no formulário e clique em "Compute GCD".
3. O resultado será exibido na página.

## Licença

Este projeto está licenciado sob a licença MIT.

---

# actix-gcd

This is a simple Rust project that uses the Actix-web framework to create a web server that calculates the Greatest Common Divisor (GCD) of two numbers.

## Requirements

- Rust
- Cargo

## Dependencies

- actix-web = "4.9.0"
- serde = { version = "1.0", features = ["derive"] }
- tokio = { version = "1.0.0", features = ["rt", "rt-multi-thread", "macros"] }

## How to run

1. Clone the repository:
    ```sh
    git clone https://github.com/HaroldoFV/actix-gcd.git
    cd actix-gcd
    ```

2. Compile and run the project:
    ```sh
    cargo run
    ```

3. The server will be available at `http://localhost:3000`.

## Endpoints

- `GET /` - Home page with a form to calculate the GCD.
- `POST /gcd` - Calculates the GCD of the provided numbers.

## Usage example

1. Access `http://localhost:3000` in your browser.
2. Enter two numbers in the form and click "Compute GCD".
3. The result will be displayed on the page.

## License

This project is licensed under the MIT license.


![Screenshot 2024-09-10 at 11 00 44 PM](https://github.com/user-attachments/assets/1b059033-07fe-4b64-9adf-93407225a897)
![Screenshot 2024-09-10 at 11 01 01 PM](https://github.com/user-attachments/assets/71033e5b-23d7-412e-bcce-4e41969826ac)


