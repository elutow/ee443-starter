# EE 443 Homework and Labs

Starter code for EE 443 HW and Labs

This branch uses the legacy COFF executable format with TI compiler v7. *It is recommended to use the `starter` branch instead.*

## Requirements

* Code Composer Studio v10
* OMAP-L138 LCDK
* XDS100v2 JTAG Emulator

## Setup

First, install C6000 Compiler Tools v7 (for legacy COFF format support):

1. In CCS menubar, go to Help -> Install Code Generation Compiler Tools...
2. In the "type filter text" textbox, type in `C6000 Compiler Tools`
3. In the listing below, check the box for "C6000 Compiler Tools" corresponding to "7.4.24" (or the latest 7.4.x version)
4. Click "Finish", and let the compiler install.

Second, add this project to your CCS workspace:

1. In a new terminal, go into your CCS workspace directory
2. Clone this repo
3. In CCS menubar, go to Project -> Import CCS Projects...
4. Select "Select search-directory", and click "Browse..." to the path where you cloned this repo
5. Click "Finish"
