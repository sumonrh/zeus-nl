
```
```

# Frequently Asked Questions (FAQ) #



---



### Virus in ZEUS-NL installation file ###

Q: Why do some anti-virus software block ZEUS-NL files?

A:

ZEUS-NL installation files on our website are free from virus.

But some of the installation files are identified as harmful by anti-virus software such as McAfee, in reality they are not.

To work around that please add the folder where you install ZEUS-NL, it changes depending on the operating system that you use but usually under “Program Files”, to the exceptions of the anti-virus program. Once you add the exception you should not have problem installing it.



---



### Number Formatting ###

Q: I have a problem with loading example input files.

A:

This problem might be related to the number formatting (whether the point or the comma is used as either decimal mark or digit group separator).

Please change settings in the “Regional and Language Options” as follows.
  * Open the "Regional and Language Options" in Control Panel (Start > Control Panel)
  * Click “Customize” bottom in the “Regional Options” tab
  * Use “point (.)” for “Decimal Symbol”, and “comma (,)” for “Digit Grouping Symbol”.



---



### Section Curvature Command in ZEUS-NL Post-Processor ###

Q: How can the section curvature calculated?

A:

The curvature is calculated by the formula (ε<sub>t</sub> – ε<sub>b</sub>)/h where ε<sub>t</sub> and ε<sub>b</sub> are the top and bottom layer strains respectively and h is the height of the section. Various strain layers can be selected for each
material that constitutes the section, but then attention must be paid to the definition of the layer width (h).

In order to utilize the element curvature command in ZEUS-NL post-processor, you have to specify stress/strain output setting options for your input file.

When selecting "General Settings” under the pull-down menu of “Settings”, the pop-up menu “Program Settings” will appear. Then, check the “Stress/Strain output” option under the “Output” Tab. (More detailed information about the output setting can be found in section 3.10.6 of ZEUS-NL User Manual.)

Once the stress/strain output option is specified, stresses/strains of two monitoring points (top and bottom fibers), of the two Gauss points, of each element, will be printed to your output file.

In ZEUS-NL post-processor, element curvature is calculated from strains of top and bottom fibers and the distance between two fibers.



---



```
```


<a href='Hidden comment: 
updated as of Jun 01, 2011
'></a>