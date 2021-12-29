---
layout: post
title: Risk Management
subtitle: Talking about Risk Management, Treatments and Types of Risk Analysis
# cover-img: /assets/img/
thumbnail-img: /assets/img/risk-management-thumb.jpg
share-img: /assets/img/risk-management-thumb.jpg
tags: [informationsecurity, cybersecurity, risk management]
---

When we talk about Information Security one of the important pillar is Risk Management, a process used for prioritization of threats against assets and most importantly determining what to do about it.
Risk Management can be centric to whole of the organization or can be for single project or department as well. You might be thinking about the on what thing we perform it, so the targets of it are Servers, LEgacy Systems, Intellectual Property or Software Licensing.

## Risk Treatments

**Avoid risk**:  If the activity has a high likelihood of occurring, and it will also cause significant financial harm, it’s better to avoid it entirely. When regulations and rules apply to your industry, one significant risk is breaking the law. Avoiding this risk has an easy answer: don’t break the law. By following the guidelines regulators establish, you avoid the risk of fines, penalties, and defense costs.

**Reduce or Mitigate risk**: Reducing risk means understanding the activities with a high likelihood of occurring but with a manageable financial impact. Its like placing security controls proactively in place before undertaking the risk.

**Tranfer risk**:If a financially devastating activity could potentially occur, the best option is to share the risk. Handling it alone could result in significant setbacks, if not a shuttered business. Instead of keeping fingers crossed, a better approach is to invest in insurance.

**Accept Risk**: It’s not always that businesses can avoid, reduce, or transfer risk. Sometimes, you must buckle down and accept it. If accepting the risk is more profitable than any other option, then it’s the optimal strategy.

Now we have looked in the treatment and know what Risk MAnagement is all about, let's dive into Types of Risk Analysis:

## Quantitative Risk Analysis

Quantitative analysis is about assigning monetary values to risk components. The key variables and equations used for conducting a quantitative risk analysis are shown below.

- Exposure Factor (EF): Percentage of asset loss caused by identified threat. It ranges from 0% to 100%.
- Single Loss Expectancy (SLE): Asset Value ✕ Exposure factor.
- Annualized Rate of Occurrence (ARO): Estimated frequency a threat will occur within a year and is characterized on an annual basis. A threat occurring one time every 10 years has an ARO of 0.1. A threat occurring 10 times in a year has an ARO of 10.
- Annualized Loss Expectancy (ALE): Single Loss Expectancy ✕ Annualized Rate of Occurrence.

The concept can be summarized by analyzing the example of a stolen corporate laptop to understand better how it works. Let’s first describe the threat, vulnerability and risk:

Threat: Stolen corporate laptop
Vulnerability: Backup rarely performed
Risk: Loss of data

Data is the asset. We assess the value of the asset (AV) first: $100,000.

Next, let’s address the single loss expectancy (SLE). It contains information about the potential loss when a threat occurs. SLE = AV ✕ EF, where EF is exposure factor. Exposure factor describes the loss that will happen to the asset because of the threat. SLE is $30,000 in our example when EF is estimated to be 0.3.

Let’s continue this case. The annualized rate of occurrence (ARO) is described as an estimated frequency of the threat occurring in one year. ARO is used to calculate ALE (annualized loss expectancy). ALE is calculated as follows: ALE = SLE ✕ ARO. ALE is $15,000 ($30,000 ✕ 0.5), when ARO is estimated to be 0.5 (once in two years).

## Qualitative Risk Analysis

This is based on subjective opinions refarding: 
- Threat Likelihood
- Impact of realized threat

Threats are gives a severity rating.

We can make use of graphs, risk heat map to showcase the severity in terms of Low, High, Medium and Critical. The parameters to be defined are totally based upon an individual or the organization.
- Risk Heat Map: Taking risk severity levels and map visually by colors.
- Risk Matrix: Table of risk details, similar to a heat map but without colors.

Hope this was a helpful read.

Thanks for reading.

Cheers. :)
