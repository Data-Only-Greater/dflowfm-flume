# Delft3D D-Flow Flexible Mesh Simple Example

This repository provides a public domain example of a quick and simple flume 
study, based on the experimental setup used in [[1]](#1).

## Usage

Assuming a compiled version of the Delft3D FM software is found on some path 
`\path\to\Delft3D`, and the flume example has been downloaded to, for 
instance, `\path\to\dflowfm-flume`, then this example can be executed as 
follows (using a Windows Powershell prompt):

```
PS > cd \path\to\dflowfm-flume\FlowFM\input
PS > & '\path\to\Delft3D\src\bin\x64\dflowfm\scripts\run_dflowfm.bat' .\FlowFM.mdu
...
** INFO   : Opened file : ..\output\FlowFM_numlimdt.xyz
** INFO   : Closed file : ..\output\FlowFM_numlimdt.xyz
** INFO   :

```

## References

<a id="1">[1]</a> 
Paul Mycek, Benoît Gaurier, Grégory Germain, Grégory Pinon, Elie Rivoalen,
Experimental study of the turbulence intensity effects on marine current turbines behaviour. Part II: Two interacting turbines,
Renewable Energy,
Volume 68,
2014,
Pages 876-892,
https://doi.org/10.1016/j.renene.2013.12.048.
