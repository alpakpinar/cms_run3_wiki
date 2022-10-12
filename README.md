# CMS Run-3 Wiki

This `README` aims to collect information about for the following Run-3 related topics:

* The main dataset streams
* Useful links for future analyses
* So-far known issues with the Run-3 data taking

## Useful Links

* To check out trigger rates and configurations for a given run, one can use [CMS OMS](https://cmsoms.cern.ch/).
* To check specific datasets, use [CMS DAS](https://cmsweb.cern.ch/das/). Please note that the CERN certificate **must** be installed on the browser to have access to this page.

### NanoAODv10 Datasets

Below listed are some important datasets that are collected during Run3.

| Dataset Name | Link to DAS |
| ------------ | ----------- |
| /Muon/Run2022*/NANOAOD   | [Link](https://cmsweb.cern.ch/das/request?view=list&limit=50&instance=prod%2Fglobal&input=%2FMuon%2FRun2022*PromptNanoAODv10*%2FNANOAOD) |
| /JetMET/Run2022*/NANOAOD | [Link](https://cmsweb.cern.ch/das/request?view=list&limit=50&instance=prod%2Fglobal&input=%2FJetMET%2FRun2022*PromptNanoAODv10*%2FNANOAOD) |
| /EGamma/Run2022*/NANOAOD | [Link](https://cmsweb.cern.ch/das/request?view=list&limit=50&instance=prod%2Fglobal&input=%2F*EGamma*%2FRun2022*PromptNanoAODv10*%2FNANOAOD) |

## Known Issues

This section contains information about the known issues so far with the Run3 data taking, and which runs/periods are impacted.

### L1 Jet Configuration

**Description:** A faulty L1 jet configuration was deployed, especially decreasing the L1 response for forward jets.

**Impacted eras/regions:** Part of Run C and the whole Run D are impacted. The impact comes at `run >= 356800`. Fixed in Run E (after technical stop 1).

**Related material:** Following material can be useful:
* Slide 3 [here](https://indico.cern.ch/event/1197207/contributions/5034015/attachments/2512246/4318492/2022_09_20_L1DPG_News_CMSWeek.pdf) from the L1T CMS Week presentation.
* Slide 6 [here](https://indico.cern.ch/event/1203893/contributions/5062364/attachments/2514421/4322539/2022-09-22_met_trig.pdf) from Alp's slides - on the impact of this change in `METNoMu` trigger turn-on.

### ECAL Water Leak

**Description:** Some ECAL channels are dead because of the water leak problem, `~20%` of the channels seem recoverable. 

**Impacted eras/regions:** Under investigation... Looks like ECAL endcap (EE) is effected, not sure about the `eta` range yet.

**Related material:** See slide 21 [here](https://indico.cern.ch/event/1204199/contributions/5064037/attachments/2522564/4337794/TSG_Weekly_05Oct22.pdf) on TSG News slides.
