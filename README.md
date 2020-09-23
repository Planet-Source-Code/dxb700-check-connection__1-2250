<div align="center">

## Check Connection


</div>

### Description

This code will check if a connection is opened to the internet , if not , it will show a messagebox ! easy ... i like this way because am a new programmer!!!
 
### More Info
 


1- Add mswinsck.ocx to the form

2- Add a command button to the form (Caption = Detect)

3- Add a text box to the form (Visible = false)

4- Copy Code !!


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[DXB700](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/dxb700.md)
**Level**          |Unknown
**User Rating**    |1.9 (17 globes from 9 users)
**Compatibility**  |VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Complete Applications](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/complete-applications__1-27.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/dxb700-check-connection__1-2250/archive/master.zip)





### Source Code

```
Private Sub Command1_Click()
If Text1.Text = "" Then
MsgBox "No Connnection!"
Else
MsgBox "Connection Detected"
End If
End Sub
Private Sub Form_Load()
Text1.Text = Winsock1.LocalIP
End Sub
'Easy ha ? .. This is the way i like it !!
```

