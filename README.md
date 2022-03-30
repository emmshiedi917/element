# element
$aArray[0] = "Hallo" $aArray[1] = 0 $aArray[2] = 1.9233 $aArray[3] = "Another String" Local $string = "" For $element In $aArray     $string = $string &amp; $element &amp; @CRLF Next MsgBox(0, "For..IN Arraytest", "Result is: " &amp; @CRLF &amp; $string)
