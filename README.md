# EE 443 Homework and Labs

Starter code for EE 443 HW and Labs

This branch uses the ELF executable format with the latest TI compiler.

## Requirements

* Code Composer Studio v10 (see instructions below)
* OMAP-L138 LCDK
* XDS100v2 JTAG Emulator

## Setup CCS

Installation instructions:

1. Uninstall any older CCS versions to prevent potential confusion
2. Launch the installer, and proceed through the welcome screens. Make sure to select "Custom Installation"
3. In Select Components, select "OMAP-L1x DSP + ARM9(R) Processor"
4. In Install debug probes, ensure "Spectrum Digital Debug Probes and Boards" is selected.
5. Proceed through the remaining dialogs and complete CCS installation

**If you did NOT select OMAP-L1x support during installation:** (NOTE: instructions currently untested):

1. In CCS menubar, go to Help -> Install New Software...
2. Under the "Work with:" dropdown, select "Code Composer Studio v10 Updates"
3. In the components list below, select the following:
    * OMAPL Device Support
    * C6000 Compiler Tools (version 8.3.6 or newer)
4. Select "Finish"

## Setup Project

1. In a new terminal, go into your CCS workspace directory
2. Clone this repo
3. In CCS menubar, go to Project -> Import CCS Projects...
4. Select "Select search-directory", and click "Browse..." to the path where you cloned this repo
5. Click "Finish"
