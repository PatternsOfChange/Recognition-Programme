# Behavioral Change in Organizations: Their effectiveness and the Role of Reminders
 
## Overview
This dissertation explores how **recency** affects the effectiveness of recognition programs in a private institution. The research examines whether exposure to recent communications about a recognition program improves the adoption of desired behaviors.

### Key Objectives:
- **Measure the impact** of recency on staff behavior within teams.
- **Test the hypothesis** that recency increases the effectiveness of recognition programs.
- **Quantitative Analysis** using randomized controlled trials to measure results.

---

## Methodology

- **Sample Size**: 211 software development teams.
- **Design**: Randomized controlled trial (RCT) with **treatment** and **control groups**.
- **Intervention**: Seven internal communications referencing the recognition program were sent to the **treatment group**. The **control group** received the same communications without the recency reference.

### Tools Used:
- **Quantitative Methods**: Regression analysis, hypothesis testing (p-values).
- **Software**: Stata for data analysis and result validation.

---

## Main Findings

- **Impact on Behavior**: The treatment group exhibited an **8.3% increase** in the adoption of behaviors promoted by the recognition program compared to the control group.
  
  > **Statistical Significance**: This effect was **marginally significant** (p=0.048).

Below is a summary of the key statistical results from the analysis:

<table style="width:80%; border: 1px solid black; border-collapse: collapse;">
  <tr style="background-color: #f2f2f2; text-align: center;">
    <th style="padding: 10px; border: 1px solid black;">Group</th>
    <th style="padding: 10px; border: 1px solid black;">Obs.</th>
    <th style="padding: 10px; border: 1px solid black;">Mean</th>
    <th style="padding: 10px; border: 1px solid black;">Std. Error</th>
    <th style="padding: 10px; border: 1px solid black;">Std. Deviation</th>
    <th style="padding: 10px; border: 1px solid black;">95% Conf. Interval</th>
  </tr>
  <tr style="text-align: center;">
    <td style="padding: 10px; border: 1px solid black;">Control</td>
    <td style="padding: 10px; border: 1px solid black;">116</td>
    <td style="padding: 10px; border: 1px solid black;">54.14</td>
    <td style="padding: 10px; border: 1px solid black;">2.88</td>
    <td style="padding: 10px; border: 1px solid black;">31.03</td>
    <td style="padding: 10px; border: 1px solid black;">48.27 - 59.84</td>
  </tr>
  <tr style="text-align: center;">
    <td style="padding: 10px; border: 1px solid black;">Treatment</td>
    <td style="padding: 10px; border: 1px solid black;">95</td>
    <td style="padding: 10px; border: 1px solid black;">62.50</td>
    <td style="padding: 10px; border: 1px solid black;">3.04</td>
    <td style="padding: 10px; border: 1px solid black;">29.65</td>
    <td style="padding: 10px; border: 1px solid black;">56.45 - 68.54</td>
  </tr>
  <tr style="text-align: center;">
    <td style="padding: 10px; border: 1px solid black;">Combined</td>
    <td style="padding: 10px; border: 1px solid black;">221</td>
    <td style="padding: 10px; border: 1px solid black;">57.90</td>
    <td style="padding: 10px; border: 1px solid black;">2.11</td>
    <td style="padding: 10px; border: 1px solid black;">30.63</td>
    <td style="padding: 10px; border: 1px solid black;">53.74 - 62.06</td>
  </tr>
  <tr style="text-align: center;">
    <td style="padding: 10px; border: 1px solid black;">Difference</td>
    <td style="padding: 10px; border: 1px solid black;">-8.36</td>
    <td style="padding: 10px; border: 1px solid black;">4.21</td>
    <td colspan="3" style="padding: 10px; border: 1px solid black;">[-16.66, -0.063]</td>
  </tr>
  <tr style="text-align: center;">
    <td colspan="6" style="padding: 10px; border: 1px solid black; text-align: left;">
      <strong>Results:</strong> T = -1.98<br>Degrees of freedom = 209<br>P>|t| = 0.0483
    </td>
  </tr>
</table>

- **Covariate Adjustment**: After controlling for relevant covariates, the effect was reduced to **8.04%** with **statistical significance** (p=0.05).

---

## Stata Code and Data

### Stata Code:
The Stata `.do` file used for the analysis, including regression models and hypothesis testing, can be found [here](https://www.dropbox.com/scl/fi/8p9b2rj479q5xxm98foqk/18080-Dissertation-Do-File-FINAL.do?rlkey=15ywf6qajuuzwiwivx3tx1tyj&st=v2hr9uzq&dl=0).

### Data File:
The `.dta` file containing the dataset used for the analysis can be found [here](https://www.dropbox.com/scl/fi/zgv46wuwb4hk2k8fuulqi/18080-Dissertation-File-FINAL.dta?rlkey=jhzu39l42nwk2dc8kgltaqatv&st=iaxrhl0s&dl=0).

---

## Full Dissertation

You can read the full dissertation [here](https://www.dropbox.com/scl/fi/vybf2cqcvpkf3xk7yck1f/18080-PB413E-Dissertation-FINAL.pdf?rlkey=d3uq06kxx7zmpmwsizoeokv7z&st=zk4ctlzi&dl=0).

---

## Conclusion

This study supports the hypothesis that **recency can improve the effectiveness** of recognition programs in organizational settings, contributing to accelerated **behavioral change**.

### Key Contributions:
- **Practical Application**: These findings highlight how internal communication timing can improve staff engagement.
- **Behavioral Science Insight**: Recency enhances attention and salience in organizational contexts, leading to measurable behavioral shifts.

---

## Future Research Directions
1. **Broader Application**: Testing recency effects across various industries.
2. **Long-Term Impact**: Investigating whether short-term behavioral changes translate into long-term organizational improvements.

---

### Contact
For further details or collaboration:
- Email: [juancarlos@lucidity.work](mailto:juancarlos@lucidity.work)
- GitHub: [PatternsOfChange](https://github.com/PatternsOfChange)
