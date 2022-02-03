## Fama French Model

Fama French model is a 3-factor model which is an extension of the Capital Asset Pricing Model (CAPM). The factors are related to the **market return**, firm’s size (**market capitalization**) and firm’s **book-to-market equity** (BE/ME) ratio.

## Carhart 4-factor Model

FIn addition to the above factor coefficients, Carhart model adds a 4th factor - **Momentum factor** (MOM). The MOM takes into account the tendency for assets to continue on a given path, rising or falling.
<br/>

### Methodology

The analysis is done for Chinese stock market. The python code extracts the monthly coefficients (2013 - 2018) from the _.csv_ file. Then, we use Excel for regression analysis and comparison between different factor models - CAPM, Fama-French and Carhart.

&emsp;&emsp;&emsp; Formulae:

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; **β<sub>2</sub>** (Small minus Big (SMB)) = R<sub>small-cap companies</sub> - R<sub>large-cap companies</sub>

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; **β<sub>3</sub>** (High minus Low (HML)) = R<sub>high-ROE companies</sub> - R<sub>low-ROE companies</sub>

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; **β<sub>4</sub>** (Momentum (last 1 year)) = R<sub>high-return comapanies</sub> - R<sub>low-return comapanies</sub>
<br><br>
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;here,
<br>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;R<sub>i</sub> represents the excess returns of i
