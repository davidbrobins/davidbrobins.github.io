---
title: "Exploring the Dependence of Gas Cooling and Heating Functions on the Incident Radiation Field with Machine Learning"
collection: talks
type: "Lightning talk"
permalink: /talks/first_stars_vii
venue: "First Stars VII"
date: 2024-05-22
location: "CCA, New York, NY"
---
Abstract: Gas cooling and heating functions control gas thermodynamics and play a crucial role in galaxy formation.  These functions depend on both gas properties (temperature, density, metallicity) and the incident radiation field.  While they can be computed exactly with photoionization codes, this is computationally expensive and impractical to do on-the-fly in hydrodynamic simulations.  As an alternative to interpolation tables of pre-computed values, we explore the capacity of machine learning to approximate cooling and heating functions with a generalized radiation field. Specifically, we use the machine learning algorithm XGBoost to predict cooling and heating functions calculated with the photoionization code Cloudy at fixed metallicity, using different combinations of photoionization rates as features. Our XGBoost models outperform a traditional interpolation approach at each fixed metallicity, regardless of feature selection. At arbitrary metallicity, we are able to reduce the frequency of the largest cooling and heating function errors compared to an interpolation table. We find that the primary bottleneck to increasing accuracy lies in accurately capturing the metallicity dependence.

<a href = 'https://events.simonsfoundation.org/event/2102b8e2-a6a7-4bd2-b9b8-d41bb73c72b1/summary'>Conference website</a>
