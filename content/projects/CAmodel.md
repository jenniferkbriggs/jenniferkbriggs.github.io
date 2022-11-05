---
title: "New Model of Cerebral Hemodynamics which Includes Temporally Informed Cerebral Vascular Feedback to Aid in Clinical Decision Support"
date: 2022-10-24T17:16:02-06:00
cover:
  image: /CAModel.png
weight: 2
---
Most current models of the cerebral hemodynamic system infer the bulk effect of vascular autoregulation but do not infer cerebral autoregulation mechanistically. At best, when applied for clinical decision support, these models provide an estimate of blood flow and generalized state of the vasculature. In the worst case, our lab has shown that these models predict blood flow to be out of phase of the data, possibly causing hyper- or hypo- perfusion and damage to the patient if these models are used in clinical decision support. We have a large, mutli-center data set of neurological ICU patients to execute this aim.

We will develop a novel model of cerebral hemodynamics informed by the mechanisms driving cerebral autoregualtion. Previous models perform well when tracking cerebral hemodynamics however they are highly non-identifiable or physiologically interpretable.

In the new model, there are three parameters representing the state of each autoregualtion mechanism. We will build out a data assimilation technique which infers the state of each mechanism and how it changes over time. This state will eventually be used for clinical decision support.

There is no gold standard on which to test the state of autoregulatory mechanisms against. Further, there is no ethical way to directly test the state of autoregulatory mechanisms in patients, which is the motivation for this model. However, reaction to medication as well as blood test can give us an idea of the function of different cerebral autoreuglatory mechanisms.
Therefore, we will develop a novel validation pipeline Which uses electronic health record data to evaluate the accuracy of our model prediction.
