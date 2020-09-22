<div align="center">

## 8 Ball Type Fortune Teller


</div>

### Description

Random call to find your Fortune. Like an 8 Ball. Contains a litte Easter Egg too, just for fun. This would look much nicer if you put an 8 Ball Graphic in

which I didn't do, sorry
 
### More Info
 
Ask a Question

I assume you know what an 8 ball is. To use this add a command button textbox and label, after that have fun :)

a Random Answer

Insanity - Just like me :)


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Chapin Walton](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/chapin-walton.md)
**Level**          |Unknown
**User Rating**    |4.2 (167 globes from 40 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Complete Applications](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/complete-applications__1-27.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/chapin-walton-8-ball-type-fortune-teller__1-2176/archive/master.zip)





### Source Code

```
Dim ans As Integer
Private Sub Command1_Click()
If Text1.Text = " " Or "Question_Goes_Here" Then
MsgBox "ah, ask a question first!", vbCritical, "ERROR!!!!"
' calls random Change the # 8 to get more varibles
' but don't forget to add them below
Else
ans = (Int(Rnd * 8) + 1)
'If you want diffrent answers put them in below
If ans = 1 Then
Label1.Caption = "Its not likely"
End If
If ans = 2 Then
Label1.Caption = "It looks possible"
End If
If ans = 3 Then
Label1.Caption = "Yes"
End If
If ans = 4 Then
Label1.Caption = "No"
End If
If ans = 5 Then
Label1.Caption = "Things are looking up"
End If
If ans = 6 Then
Label1.Caption = "Ask again later"
End If
If ans = 7 Then
Label1.Caption = "Only if you get me a brownie"
End If
If ans = 8 Then
Label1.Caption = "Certinally"
End If
End If
End Sub
Private Sub Form_DblClick()
MsgBox "MMM.... YOUR EYE TASTES LIKE CHEESE"
'EASTER EGG!!!! ALL PROGRAMS SHOULD HAVE THESE!!
End Sub
End Sub
Private Sub Form_Load()
Text1.Text = "Question_Goes_Here"
Command1.Caption = "Ask me..."
End Sub
Private Sub Text1_Click()
Text1.Text = " "
End Sub
```

