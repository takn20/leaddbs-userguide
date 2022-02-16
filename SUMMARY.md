# Table of contents

* [Introduction](README.md)
* [How to contribute to Lead-DBS](how-to-contribute-to-lead-dbs.md)

## Installation

* [Dependencies](installation/dependencies.md)
* [Installation](installation/installation/README.md)
  * [Setting the MATLAB Path to include Lead-DBS](installation/installation/setting-the-matlab-path-to-include-lead-dbs.md)
  * [Acquiring and Installing Atlases](installation/installation/acquiring-and-installing-atlases/README.md)
    * [Customizing Atlas Visualization](installation/installation/acquiring-and-installing-atlases/customizing-atlas-visualization.md)

## Lead-DBS

* [0. Main Window](lead-dbs/0.-main-window.md)
* [1. Load Patient Folder](lead-dbs/1.-load-patient-folder.md)
* [2. Import Data](lead-dbs/2.-import-data.md)
* [3. Volume Registrations](lead-dbs/3.-volume-registrations/README.md)
  * [Brain shift Correction](lead-dbs/3.-volume-registrations/brain-shift-correction.md)
  * [Checking the Coregistrations and Normalizations](lead-dbs/3.-volume-registrations/checking-the-coregistrations-and-normalizations.md)
  * [Refine Atlas Fit](lead-dbs/3.-volume-registrations/refine-atlas-fit.md)
* [4. Surface Reconstruction (optional)](lead-dbs/4.-surface-reconstruction-optional.md)
* [5. Reconstruction of electrode trajectories (optional)](lead-dbs/5.-reconstruction-of-electrode-trajectories-optional/README.md)
  * [Manual Correction of Electrode Localization](lead-dbs/5.-reconstruction-of-electrode-trajectories-optional/manual-correction-of-electrode-localization.md)
  * [How are reconstructions stored?](lead-dbs/5.-reconstruction-of-electrode-trajectories-optional/how-are-reconstructions-stored.md)
  * [Orientation of Directional Leads](lead-dbs/5.-reconstruction-of-electrode-trajectories-optional/orientation-of-directional-leads/README.md)
    * [Prerequisites](lead-dbs/5.-reconstruction-of-electrode-trajectories-optional/orientation-of-directional-leads/prerequisites.md)
    * [Automatic Algorithm](lead-dbs/5.-reconstruction-of-electrode-trajectories-optional/orientation-of-directional-leads/automatic-algorithm.md)
    * [Possible Problems with the Automatic Algorithm](lead-dbs/5.-reconstruction-of-electrode-trajectories-optional/orientation-of-directional-leads/possible-problems-with-the-automatic-algorithm.md)
    * [User-Assisted Algorithm (Manual Refine)](lead-dbs/5.-reconstruction-of-electrode-trajectories-optional/orientation-of-directional-leads/user-assisted-algorithm-manual-refine.md)
* [6. Connectivity analyses (optional)](lead-dbs/6.-connectivity-analyses-optional.md)
* [7. Visualization](lead-dbs/7.-visualization/README.md)
  * [Reconstruction Statistics](lead-dbs/7.-visualization/reconstruction-statistics.md)

## Lead-Group

* [Group analyses with Lead-DBS](lead-group/group-analyses-with-lead-dbs.md)
* [Setup Analysis?](lead-group/setup-analysis.md)
* [General Settings?](lead-group/general-settings.md)
* [Group Visualization?](lead-group/group-visualization.md)
* [Calculate VAT and Stats?](lead-group/calculate-vat-and-stats.md)
* [Sweetspot Explorer?](lead-group/sweetspot-explorer.md)

## Appendix

* [Code Backbone?](appendix/code-backbone.md)
* [Lead Mapper](appendix/lead-mapper.md)
* [Connectomics](appendix/connectomics/README.md)
  * [Diffusion MRI: Patient Specific Processing](appendix/connectomics/diffusion-mri-patient-specific-processing.md)
  * [fMRI-Analysis: Patient Specific Processing](appendix/connectomics/fmri-analysis-patient-specific-processing.md)
  * [Using Normative Connectomes?](appendix/connectomics/using-normative-connectomes/README.md)
    * [Discriminative Fibertracts analysis](appendix/connectomics/using-normative-connectomes/discriminative-fibertracts-analysis.md)
* [MER analysis](appendix/mer-analysis.md)
* [Troubleshooting / Specific Help?](appendix/troubleshooting-specific-help/README.md)
  * [Adding Fortran dependencies for VTA modeling](appendix/troubleshooting-specific-help/adding-fortran-dependencies-for-vta-modeling.md)
* [Comand line interface](appendix/comand-line-interface/README.md)
  * [Command line options](appendix/comand-line-interface/command-line-options.md)
* [Matlab scripting examples](appendix/matlab-scripting-examples/README.md)
  * [Creating VTAs programmatically](appendix/matlab-scripting-examples/creating-vtas-programmatically.md)
  * [Installing an atlas from an online repository](appendix/matlab-scripting-examples/installing-an-atlas-from-an-online-repository.md)
  * [Warping a normative connectome to native subject space](appendix/matlab-scripting-examples/warping-a-normative-connectome-to-native-subject-space.md)
