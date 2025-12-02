# OOP Assignments

This repository contains Java assignments for my Object-Oriented Programming (OOP) unit. Each folder demonstrates core OOP concepts.

## Project Structure

- `invoice1/Invoice.java`
	- Static console invoice; no inputs. Prints hard-coded customer, product table, totals, discount, and grand total.

- `invoice2/Invoice.java`
	- Interactive invoice. Reads bill-to + 7 products via Scanner, computes line totals (qty×rate+tax), applies small discount, and prints a formatted table.

- `marksheet/Marksheet.java`
	- Collects marks for 5 students across 7 units, computes totals and averages, and prints a simple score sheet.

## How to Build and Run (terminal)

- Compile: `javac invoice1/Invoice.java`; `javac invoice2/Invoice.java`; `javac marksheet/Marksheet.java`
- Run: `java -cp invoice1 Invoice`; `java -cp invoice2 Invoice`; `java -cp marksheet Marksheet`

## Learning Objectives

- Practice console I/O, basic calculations, and formatted output.

## Notes

- Each assignment is self-contained; compile and run per folder.
- Follow prompts when running interactive programs.
