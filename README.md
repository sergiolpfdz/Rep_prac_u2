# Rep_prac_u2
#ejemplo 1 import wx

app = wx.App (clearSigInt = True) # clearSigInt para permitir la terminación del programa con CTRL + C frame = wx.Frame (parent = None, title = "") ## main window object panel = wx.Panel (parent = frame ) text = wx.StaticText (parent = panel, label = "Hola, desde wxPython !!", pos = (40,50)) frame.Show () app.MainLoop ()
![image](https://user-images.githubusercontent.com/79875888/112391316-53594900-8cbd-11eb-953d-d4e8cad7c27c.png)

#ejemplo 2 import wx import webbrowser

clase MyApp (wx.App): def init (self): super (). init (clearSigInt = True)
![image](https://user-images.githubusercontent.com/79875888/112392934-dc717f80-8cbf-11eb-9ac5-15b0a9b8e346.png)

class MyFrame (wx.Frame): # subclase de wx.Window; El marco es una ventana de nivel superior # Un marco es una ventana cuyo tamaño y posición pueden (normalmente) ser cambiados por el usuario. # Por lo general, representa la primera ventana principal que verá un usuario def init (self, parent, title, pos = pos): super (). init (padre = padre, título = título, pos = pos)
![image](https://user-images.githubusercontent.com/79875888/112393114-2ce8dd00-8cc0-11eb-903a-da0206c0c14f.png)

! [imagen] (https://user-images.githubusercontent.com/79875888/112392564-39b90100-8cbf-11eb-83a4-eacd2b63f290.png)

#ejemplo 3 import wx import navegador web

clase MyApp (wx.App): def init (self): super (). init (clearSigInt = True)
