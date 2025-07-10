Public Class Form1
    ' Load Object Demonstrations form when button is clicked
    Private Sub btnLoadDemo_Click(sender As Object, e As EventArgs) Handles btnLoadDemo.Click
        Dim objDemo As New Form2()
        objDemo.Show() ' Show Form2
    End Sub
    ' Exit the application when the exit button is clicked
    Private Sub btnExit_Click(sender As Object, e As EventArgs) Handles btnExit.Click
        Application.Exit()
    End Sub
    ' Maximize form and change background color to red when clicked
    Private Sub Form1_Click(sender As Object, e As EventArgs) Handles Me.Click
        Me.WindowState = FormWindowState.Maximized
        Me.BackColor = Color.Red
    End Sub

    Private Sub Form1_Load(sender As Object, e As EventArgs) Handles MyBase.Load

    End Sub
End Class
