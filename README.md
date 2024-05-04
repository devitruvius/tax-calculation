# Customer Control System

## Description

This program calculates the income tax for individuals and legal entities in Brazil. It takes into account the type of taxpayer (individual or legal entity), their personal information (name, address, CPF or CNPJ, and IE), and the value of their purchase. The program then calculates the tax due and displays the total amount to be paid.

## Features

* Calculates income tax for individuals and legal entities
* Takes into account the type of taxpayer, personal information, and value of purchase
* Displays the tax due and total amount to be paid

## Requirements

* .NET Framework
* Visual Studio

## Installation

1. Clone the repository or download the project files.
2. Open the project in Visual Studio.
3. Set the project as the startup project.
4. Press F5 to run the program.

## Usage

1. Run the program.
2. Enter the requested information:
   * **Nome**: Taxpayer's name
   * **Endereço**: Taxpayer's name
   * **Pessoa Física (f) ou Jurídica (j)?**: Type of taxpayer (individual or legal entity)
   * **CPF (Se Pessoa Física)**: Taxpayer's CPF (if individual)
   * **CNPJ (Se Pessoa Jurídica)**: Taxpayer's CNPJ (if legal entity)
   * **IE (Se Pessoa Jurídica)**: Taxpayer's IE (if legal entity)
   * **Valor de Compra**: Value of purchase
  
3. The program will display the tax due and total amount to be paid.

## Example Output

  ```python
  Informar Nome
  João da Silva
  Informar Endereço
  Rua dos Santos, 123
  Pessoa Física (f) ou Jurídica (j) ?
  f
  Informar CPF:
  123.456.789-00
  Informar RG:
  10.200.300
  Informar Valor de Compra:
  1000.00
  -------- Pessoa Física --------
  Nome ..........: João da Silva
  Endereço ......: Rua dos Santos, 123
  CPF ...........: 123.456.789-00
  RG ............: 10.200.300
  Valor de Compra: R$1.000,00
  Imposto .......: R$150,00
  Total a Pagar : R$1.150,00
  ```

## Contributing

Please feel free to fork the repository and submit pull requests.
