# ATAC_CLL

This repository contains resources and instructions for performing ATAC-seq analysis on Chronic Lymphocytic Leukemia (CLL) samples using the Terra platform.

## Overview

ATAC-seq analysis on Chronic Lymphocytic Leukemia (CLL) samples using the Terra platform.

## Contents

### `Data` Folder

The `data` folder contains a TSV file formatted for upload into the Terra platform. This file includes the necessary metadata and paths to the input data for the workflow.

### `JSON` Folder

Due to the limitations of the WDL (Workflow Description Language) used in this project, variables cannot be dynamically assigned as inputs. Therefore, we have created eight JSON files in `json` foler, one for each sample.

### How to Use

1. Upload the JSON files in the workflow input section of the Terra platform.
2. Save and run the workflow to obtain your results.

## Future Plans

1. **Performance Optimization:** 
   
   - Consider utilizing more CPU resources to accelerate the processing time.

2. **Parameter Adjustment:**
   
   - Fine-tune parameters, such as incorporating a blacklist to filter out problematic regions, for improved results.

# 
