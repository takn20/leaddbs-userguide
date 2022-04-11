# Table of contents

* [Introduction](README.md)
* [How to contribute to Lead-DBS](ways-to-contribute-to-lead-dbs.md)

## Installation <a href="#installation-1" id="installation-1"></a>

* [Dependencies](installation-1/dependencies.md)
* [Installation](installation-1/installation.md)

## Lead-DBS

* [Overview](lead-dbs/0.-overview.md)
* [1. Load Patient Folder](lead-dbs/1.-load-patient-folder.md)
* [2. Image Import](lead-dbs/2.-image-import.md)
* [3. Volume Registrations](lead-dbs/3.-volume-registrations/README.md)
  * [Normalizing the Images](lead-dbs/3.-volume-registrations/normalization-of-images.md)
  * [Brainshift Correction](lead-dbs/3.-volume-registrations/subcortical-refine-post-to-pre-transforms.md)
  * [Checking the Coregistrations and Normalizations](lead-dbs/3.-volume-registrations/checking\_the\_coregistration.md)
  * [Refine Atlas Fit with WarpDrive](lead-dbs/3.-volume-registrations/refine-atlas-fit-with-warpdrive.md)
* [4. (optional) Surface Reconstruction](lead-dbs/4.-optional-surface-reconstruction.md)
* [5. (optional) Reconstruction of Electrode Trajectories](lead-dbs/5.-optional-reconstruction-of-electrode-trajectories/README.md)
  * [Orientation of Directional Leads](lead-dbs/5.-optional-reconstruction-of-electrode-trajectories/determining-the-orientation-of-directional-leads/README.md)
    * [Prerequisites](lead-dbs/5.-optional-reconstruction-of-electrode-trajectories/determining-the-orientation-of-directional-leads/prerequisites.md)
    * [Automatic Algorithm](lead-dbs/5.-optional-reconstruction-of-electrode-trajectories/determining-the-orientation-of-directional-leads/automatic-algorithm.md)
    * [Possible Problems with the Automatic Algorithm](lead-dbs/5.-optional-reconstruction-of-electrode-trajectories/determining-the-orientation-of-directional-leads/possible-problems-with-the-automatic-algorithm.md)
    * [User-Assisted Algorithm (Manual Refine)](lead-dbs/5.-optional-reconstruction-of-electrode-trajectories/determining-the-orientation-of-directional-leads/user-assisted-algorithm-manual-refine.md)
  * [TRAC/CORE Details](lead-dbs/5.-optional-reconstruction-of-electrode-trajectories/trac-core-details.md)
  * [Reconstruction File](lead-dbs/5.-optional-reconstruction-of-electrode-trajectories/reconstruction-file.md)
* [6. (optional) Perform Connectivity Analysis](lead-dbs/6.-optional-perform-connectivity-analysis.md)
* [7. Visualization](lead-dbs/7.-visualization/README.md)
  * [MER Analysis](lead-dbs/7.-visualization/mer-analysis.md)
* [Reconstruction Statistics](lead-dbs/reconstruction\_statistics.md)
* [Untitled](lead-dbs/untitled.md)

## Lead-Group

* [Group analyses with Lead-DBS](lead-group/group\_analyses\_with\_lead-dbs.md)
* [Setup Analysis](lead-group/setup-analysis.md)
* [General Settings](lead-group/general-settings.md)
* [Group Visualization](lead-group/group-visualization.md)
* [Calculate VTA and Stats](lead-group/calculate-vta-and-stats.md)
* [Sweetspot Explorer](lead-group/sweetspot-explorer.md)

## Connectomics

* [Connectomics](connectomics/connectomic\_analyses/README.md)
  * [Diffusion MRI: Patient Specific Processing](connectomics/connectomic\_analyses/dmri.md)
  * [fMRI-Analysis: Patient Specific Processing](connectomics/connectomic\_analyses/fmri\_analysis.md)
  * [Using Normative Connectomes](connectomics/connectomic\_analyses/using-normative-connectomes/README.md)
    * [Discriminative Fibertracts analysis](connectomics/connectomic\_analyses/using-normative-connectomes/discriminative-fibertracts-analysis.md)
* [Lead Connectome Mapper](connectomics/lead-mapper.md)

## Appendix

* [Code Backbone](appendix/code-backbone.md)
* [Acquiring and Installing Atlases](appendix/acquiring\_and\_setting\_atlases/README.md)
  * [Customizing Atlas Visualization](appendix/acquiring\_and\_setting\_atlases/customizing\_atlas\_visualization.md)
* [Troubleshooting / Specific Help](appendix/troubleshooting-specific-help/README.md)
  * [Adding Fortran dependencies for VTA modeling](appendix/troubleshooting-specific-help/adding-fortran-dependencies-for-vta-modeling.md)
* [Command line interface](appendix/command-line-interface/README.md)
  * [Command line options](appendix/command-line-interface/command-line-options.md)
* [Matlab scripting examples](appendix/useful-command-line-tools/README.md)
  * [Installing an atlas from an online repository](appendix/useful-command-line-tools/installing-an-atlas-from-a-repository.md)
  * [Warping a normative connectome to native subject space](appendix/useful-command-line-tools/warping-a-normative-connectome-to-native-subject-space.md)
