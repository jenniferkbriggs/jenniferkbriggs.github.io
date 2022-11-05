---
title: "New Model of Cerebral Hemodynamics which Includes Temporally Informed Cerebral Vascular Feedback to Aid in Clinical Decision Support"
date: 2022-10-24T17:16:02-06:00
cover:
  image: /CAModel.png
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
Most current models of the cerebral hemodynamic system infer the bulk effect of vascular autoregulation but do not infer cerebral autoregulation mechanistically. At best, when applied for clinical decision support, these models provide an estimate of blood flow and the generalized state of the vasculature. In the worst case, our lab has shown that these models predict blood flow to be out of phase of the data, possibly causing hyper- or hypo-perfusion and damage to the patient if these models are used in clinical decision support. We have an extensive, multi-center data set of neurological ICU patients to execute this aim.

We will develop a novel model of cerebral hemodynamics informed by the mechanisms driving cerebral autoregulation. Previous models perform well when tracking cerebral hemodynamics; however, they are highly non-identifiable or physiologically interpretable.

In the new model, we include three parameters representing each autoregulation mechanism's state and two parameters representing the metabolic state of the cerebrum. We will integrate this model with data via data assimilation to infer the dynamic state of each mechanism in time. In the future, we hope to use this information to aid in clinical decision support.

![Model response to functionality of metabolic reactivity](/CAModel_Met.png)
