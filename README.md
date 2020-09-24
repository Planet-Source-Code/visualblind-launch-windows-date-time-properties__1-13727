<div align="center">

## Launch Windows Date/Time Properties


</div>

### Description

Launch Windows Date/Time Properties
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[VisualBlind](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/visualblind.md)
**Level**          |Beginner
**User Rating**    |5.0 (15 globes from 3 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Windows System Services](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/windows-system-services__1-35.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/visualblind-launch-windows-date-time-properties__1-13727/archive/master.zip)





### Source Code

```
Code:
'Launch Windows Date/Time Properties Dialog
Dim dblReturn As Double
dblReturn = Shell("rundll32.exe shell32.dll,Control_RunDLL timedate.cpl", 5)
```

