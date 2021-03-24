# Rep_prac_u2
#ejemplo 1 import wx

app = wx.App (clearSigInt = True) # clearSigInt para permitir la terminación del programa con CTRL + C frame = wx.Frame (parent = None, title = "") ## main window object panel = wx.Panel (parent = frame ) text = wx.StaticText (parent = panel, label = "Hola, desde wxPython !!", pos = (40,50)) frame.Show () app.MainLoop ()
![image](https://user-images.githubusercontent.com/79875888/112391316-53594900-8cbd-11eb-953d-d4e8cad7c27c.png)

#ejemplo 2 import wx import webbrowser

clase MyApp (wx.App): def init (self): super (). init (clearSigInt = True)

#init frame
    self.InitFrame()

def InitFrame(self):
    frame = MyFrame(parent=None, title="Basic Frame", pos=(100, 100))
    frame.Show(True)
    
