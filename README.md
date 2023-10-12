# 迩原構字術
  楊端憲（皇皇者華）作。攷溯文宗，窮究字理，庶幾迩原。

# 目標
通過人機接口設備，即通用串行總綫或藍牙鍵盤，以漢字部件直接輸入漢字。每擊一鍵，代表寫一个基本部件或結構符。无重碼，故不依賴輸入法．輸入法僅用于選宂碼，多數場景中用不到。

# 數據
1. 字碼表：記每字之結構，由結構符（⿰⿲⿱⿳⿴⿵⿶⿷⿸⿹⿺⿻⿼⿽⿾⿿等）與部件遞歸組成。字源同而後世歧者（如弔吊），如後起之形理據重構則允許異解，以避重碼。所用部件應分盡分，不與鍵位一一對應〬。
2. 部件歸并與排布：包括部件與鍵之關係，及鍵在盤面上之排布。
3. 鍵盤矩陣：鍵盤電路。
4. [人機接口設備](https://www.usb.org/hid)之報碼表：各鍵之報碼。用`0x0100`至`0x400`區段。
5. 系統層之映射：驅動程序。

# 字型
需造隸書（八分）、楷書、黑體、小篆四種字型，以印鈕面、說明書等。
