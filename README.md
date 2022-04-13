# -GuiChild-Then
If $GuiChild Then         GUICtrlCreateButton("flash child", 220, 8, 120, 25)         GUICtrlSetOnEvent(-1, "OnFlashBttn")         GUISetState(@SW_SHOW, $GuiChild)         OnFlashBttn()     EndIf
