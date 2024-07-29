# Formal verification of Hybrid Post-Quantum TLS protocol

This project provides a formal verification of the [Hybrid Post-Quantum TLS protocol](https://datatracker.ietf.org/doc/html/draft-campagna-tls-bike-sike-hybrid) using the Maude-NPA tool. Maude-NPA is a tool written in Maude for analyzing cryptographic protocols.

## Prerequisites

- [Maude-NPA](https://maude.cs.illinois.edu/w/index.php/Maude_Tools:_Maude-NPA#Downloads)

## Installation

1. Download and install Maude-NPA from the [official website](https://maude.cs.illinois.edu/w/index.php/Maude_Tools:_Maude-NPA#Downloads).
2. Download and move hybridpqtls.maude to the `maude-npa` directory.

## Usage

1. Open a terminal and navigate to the `maude-npa` directory.
2. Start Maude by running the following command:
    ```sh
    maude
    ```
3. Load the `maude-npa.maude` file:
    ```sh
    load maude-npa.maude
    ```
4. Load the `hybridpqtls.maude` file:
    ```sh
    load hybridpqtls.maude
    ```
    If `hybridpqtls.maude` is located in a different directory, provide the full path to the file:
    ```sh
    load /path/to/hybridpqtls.maude
    ```
5. Use the Maude-NPA commands to test the protocol.
