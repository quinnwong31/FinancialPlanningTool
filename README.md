# FinancialPlanningTool

## Description

The Financial Planning notebook is a sample notebook that illustrates how to create two financial analysis tools with the following goals in mind:

1. A financial planner for emergencies. Members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

2. A financial planner for retirement. This tool will forecast the performance of a member's retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

## Technologies

This example uses the following technologies:

- **Jupyter** - Jupyter is a web-based interactive development environment for data science and analysis. Please see [Jupyter documentation](https://jupyter.org/) for more information.
- **pandas** - pandas is a software library written for the Python programming language for data manipulation and analysis. Please see [pandas documentation](https://pandas.pydata.org/) for more information.
- **json** - `json` is library that provides APIs for interacting with JSON (JavaScript Object Notation) objects.
- **requests** - `requests` is a library that provides APIs for HTTP, including making requests and handling responses.
- **Alcpaca**

## Installation

In order to use this application, you will need to install `Jupyter`, `pandas` and '`Alpaca` SDK.   The `json` and `requests` library come with Python already, so there are no steps required to install those libraries.  Below are the instructions for installing each required library.

### Installing Jupyter

To install Jupyter, please refer to the [Jupyter Installation Guide](https://jupyter.org/install).

### Installing pandas

To install `pandas`, please refer to the [pandas Installation Guide](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html).

### Installing Alpaca

@TODO

## Usage

### Launching the Notebook

To launch the Notebook, perform the following steps:

1. Open Terminal.

![Launch_Terminal](/images/launching_open_terminal.jpg)

2. Navigate to the location of the Notebook.
3. Enter `jupyter lab` at the Terminal prompt.

![Launch_Jupyter](/images/launching_jupyter.jpg)

4. Verify that you can access Jupyter in your browser.

![Jupyter](/images/jupyter.jpg)

### Evaluate the Cryptocurrency Wallet by Using the Requests Library

![Evaluate Cryptocurrency Wallet](/images/jupyter_requests.jpg)

### Evaluate the Stock and Bond Holdings by Using the Alpaca SDK

![Evaluage with Alpaca SDK](/images/jupyter_alpaca.jpg)

## Evaulate the Emergency Fund

![Evaluate Emergency Fund](/images/jupyter_emergency_fund.jpg)

## Create the Monte Carlo Simulation

![Monte Carlo Simulation](/images/jupyter_monte_carlo.jpg)

## Contributors

This sample application was authored by:

Quinn Wong (quinn.wong@gmail.com)
LinkedIn: https://www.linkedin.com/in/quinnwong/

## License

The MIT License (MIT)

Copyright (c) 2022 Quinn Wong

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
