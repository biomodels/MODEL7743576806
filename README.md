

Radulescu2008 - NF-κB hierarchy ℳ(16,34,46)

This is a model of NF-κB pathway functioning from hierarchy of models of
decreasing complexity, created to demonstrate application of model reduction
methods proposed in the associated publication.

The name of the model M(x,y,z) should be deciphered as following:

  * x: number of species
  * y: number of reactions
  * z: number of parameters

Simulation protocol: the model can be simulated in CellDesigner directly, or
in any simulator supporting events. The simulation period should be set up in
40 hours (t=144000 sec). The 'signal' event applies signal to the pathway at
the moment t=20 hours=72000 sec.

This model is described in the article:

[Robust simplifications of multiscale biochemical
networks.](http://identifiers.org/pubmed/18854041)

Radulescu O, Gorban AN, Zinovyev A, Lilienbaum A.

BMC Syst Biol 2008 Oct; 2(1):86

Abstract:

BACKGROUND: Cellular processes such as metabolism, decision making in
development and differentiation, signalling, etc., can be modeled as large
networks of biochemical reactions. In order to understand the functioning of
these systems, there is a strong need for general model reduction techniques
allowing to simplify models without loosing their main properties. In systems
biology we also need to compare models or to couple them as parts of larger
models. In these situations reduction to a common level of complexity is
needed.

RESULTS: We propose a systematic treatment of model reduction of multiscale
biochemical networks. First, we consider linear kinetic models, which appear
as "pseudo-monomolecular" subsystems of multiscale nonlinear reaction
networks. For such linear models, we propose a reduction algorithm which is
based on a generalized theory of the limiting step that we have developed in
1. Second, for non-linear systems we develop an algorithm based on dominant
solutions of quasi-stationarity equations. For oscillating systems, quasi-
stationarity and averaging are combined to eliminate time scales much faster
and much slower than the period of the oscillations. In all cases, we obtain
robust simplifications and also identify the critical parameters of the model.
The methods are demonstrated for simple examples and for a more complex model
of NF-kappaB pathway.

CONCLUSION: Our approach allows critical parameter identification and produces
hierarchies of models. Hierarchical modeling is important in "middle-out"
approaches when there is need to zoom in and out several levels of complexity.
Critical parameter identification is an important issue in systems biology
with potential applications to biological control and therapeutics. Our
approach also deals naturally with the presence of multiple time scales, which
is a general property of systems biology models.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[MODEL7743576806](http://identifiers.org/biomodels.db/MODEL7743576806) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

