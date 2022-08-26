---
# The layout must be 'testcase'; DO NOT Change
layout: testcase

# Brief, descriptive title for the test case
title: 3:1 contrast ratio for 14 point, bold font

# The Test Case ID should follow the pattern: 
# TC[Baseline Test Procedure #]-[Test Instruction #]-
# [Expected Result (pass/fail/dna)]-[example #], e.g., TC05.1-1-fail-1
tcid: TC8.1-3-pass-2

# Description of the Test Case, the included code sample, test considerations,
# and rationale for the expected result according to the applicable ICT
# Baseline test
descr: Detect the foreground and background text and size contrast ratio. Determine whether contrast ratio is sufficient. The text in the code sample is sufficient contrast between the foreground and background.


# Reference and link to the applicable ICT Baseline test
app-baseline:|[8.1 Test Procedure for Contrast Minimum](https://section508coordinators.github.io/ICTTestingBaseline/08Contrast.html#81-test-procedure-for-contrast-minimum)

  **Baseline Test ID:** 8.1-Contrast
    
  **Test Instruction:** 2


# Expected result that the ICT Baseline would predict
# [Pass | Fail | DNA]
result: Pass

# Brief description of the rationale for the expected result
result-descr: The foreground text in the code sample provide sufficient contrast based on the text size, foreground color, and background color.

# URL for the code sample
# In the sample code file, add id="tc_code" to the 
# element that contains the relevant code snippet.
#
# Then upload the code sample to the 'testfiles' folder 
# and provide the link (and only the url) below.
sample: /testfiles/TF08/08.1-3-pass-2.html

# Table of test instructions, including the following table headers: 
# Test Instruction #; Instruction Detail; Expected Test Case Result
#
# Include the table in the content section below
---
| Test Instruction | Instruction Detail | Expected Test Case Result |
|------------------|--------------------|---------------------------|
|IC| All visible text AND images of text (except those noted in Limitations, Assumptions, or Exceptions above)|
| 8.1-1 | Determine the contrast ratio of foreground text and background. | Contrast ratio is 4:1. Pass |
| 8.1-2 | If the contrast ratio is less than 4.5:1 | Pass | 
| 8.1-3 | If the contrast ratio is less than 4.5:1, check that the ratio is at least 3:1 AND the font meets one of the following criteria 3:1 contrast ratio for 14 point, bold font. [SC 1.4.3] | Pass |
| Results |If the above checks pass, then the Baseline Test Contrast 8.1 Minimum Pass. |Pass|
