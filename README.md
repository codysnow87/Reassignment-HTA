# Reassignment-HTA
Windows HTA file with buttons that sends simple code to another application (Kratronic Macro Recorder)
<!doctype html>
<html>
    <!--Brought to you by Cody Snow aka guiltySpark, with a bunch of code borrowed from all over the internet-->

    <head>
        <meta http-equiv="content-type" content="text/html; charset=UTF-8">
        <title>guiltySpark</title>

<head> 
 
<script language="VBScript"> 
    Sub RunProgram_OnClick() 
	Set objShell = CreateObject("Wscript.Shell")
	objShell.Run """C:\Program Files\KraTronic\Recorder\Recorder.exe"""
    End Sub

</script>

</head>


<body> 

<button id="RunProgram" style="height: 50px; width: 100px; color: Black;">Run Kratronic</button>
<hr>

</body> 

	<script type="text/vbscript">

            Sub BtnRun1_OnClick()
                Dim WShell : Set WShell = CreateObject("WScript.Shell")
                With WShell
                    .SendKeys "^%r"
                End With
            End Sub


        </script>
   </head>
    <body>
      

 <button id="BtnRun1" style="height: 75px; width: 100px; color: CornflowerBlue;">Reassign Claim</button>



<hr>

</body> 

	<script type="text/vbscript">


            Sub BtnRun2_OnClick()
                Dim WShell : Set WShell = CreateObject("WScript.Shell")
                With WShell
                    .SendKeys "^%1"
                End With
            End Sub


        </script>
   </head>
    <body>
      

 <button id="BtnRun2" style="height: 50px; width: 100px; color: Green;">User</button>



<script type="text/javascript">

    window.resizeTo(150,280);

</script>

    </body>


</html>
