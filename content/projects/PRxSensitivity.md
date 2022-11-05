---
title: "Minimizing Uncertainity and Error in Pressure Reactivity Index to Aid in Clicial Decision Support"
date: 2022-10-24T16:59:20-06:00
cover:
  image: /PRx.png
weight: 2
---
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-GDLL5EC1GF"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-GDLL5EC1GF');
</script>

Neurovascular injuries are a leading cause of death. A goal in neurocritical care is to optimize brain perfusion. Cerebral Autoregulation (CA) is an intrinsic property of healthy vasculature which maintains optimal perfusion over large pressure gradients. To ensure proper brain perfusion, clinical guidelines recommend targetting ABP to where CA is optimized. Pressure Reactivity Index (PRx) is a common proxy for CA. PRx is estimated by taking the correlation coefficient between a given number of averaged ICP and ABP samples. Averaging window size and number of samples taken for correlation are therefore hyperparameters in the PRx calculation. *However, little work has been done to understand the choice of hyperparameters used for PRx calculation is controversial.* Due to the data's invasive nature, clinically accessible cerebral autoregulation metrics are not validatible in the typical sense. In this project, we calculate PRx for many different combinations of averaging and correlation windows in patient and synthetic data to quantify the sensitivity of PRx to hyperparameters and explore patient specific methodology
