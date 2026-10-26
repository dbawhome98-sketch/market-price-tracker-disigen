# Market Price Tracker (Design)

A logical design for a system that helps people in Sierra Leone
compare food prices across local markets.

## Problem
Prices for goods like rice, cassava and palm oil vary between
markets and change often. Buyers cannot easily compare, and
traders may sell below a fair price.

## Solution
Trusted reporters submit prices. The system validates and stores
them, flags sudden price jumps, and lets the public compare prices
by item and market.

## Modules
1. Login
2. ValidatePrice
3. SavePrice
4. CheckAlert
5. SearchPrices
6. GetAverage (helper)

## Contents
- `docs/` : problem statement, algorithm, pseudocode, modules, SDG/open source/DPG
- `flowcharts/` : colored flowcharts for submit price and search price
- `pseudocode-screenshots/` : colored screenshots of the pseudocode for each module

## SDG alignment
SDG 1 (No Poverty), SDG 2 (Zero Hunger), SDG 9 (Industry, Innovation and Infrastructure)

## Note
This is a design only. No source code has been written.

## Licence
MIT. See the LICENSE file.

## Author
David, Limkokwing University of Creative Technology, Sierra Leone.
PROG101 Assignment 1.

## Flowchart preview
![Submit price flowchart](flowcharts/submit-price.png)
![Search price flowchart](flowcharts/search-price.png)

## Pseudocode preview
![Main program](pseudocode-screenshots/main-program.png)
