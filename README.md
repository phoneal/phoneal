 Private Sub Button1_Click(ByVal sender As System.Object,ByVal e As System.EventArgs)
  Handles Button1.Click
  Dim testmsg As Integer 
  testmsg = MsgBox("Click to test", 1,"Test message") 
  If testmsg = 1 Then
  Messagebox.show("you have clicked the OK button") 
  Else
  MessageBox.Show("you have clicked the Cancel button")  
  End If 
  End Sub
  
