# -varFields-
If Not IsObj($objConnection) Then Return -1     If Not IsString($varTableName) Then Return -2     If Not IsArray($arrFields) Then Return -3     $varFields = ""     $varFieldCount = Ubound($arrFields)-1     For $x = 0 to $varFieldCount
