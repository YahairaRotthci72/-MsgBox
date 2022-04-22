# -MsgBox
$aArray[2][1] = [["1"], ["2"]] ; Call the function with an array as first parameter ($aArray) Local $sWriteArray = _CreateCodeArray($aArray, Default, Default, 0, 3) ; in this example the GUI will appear If @error Then MsgBox(0, "", $sWriteArray)
