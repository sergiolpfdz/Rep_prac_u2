# Rep_prac_u2
#ejemplo 1 import wx

app = wx.App (clearSigInt = True) # clearSigInt para permitir la terminación del programa con CTRL + C frame = wx.Frame (parent = None, title = "") ## main window object panel = wx.Panel (parent = frame ) text = wx.StaticText (parent = panel, label = "Hola, desde wxPython !!", pos = (40,50)) frame.Show () app.MainLoop ()
![image](https://user-images.githubusercontent.com/79875888/112391316-53594900-8cbd-11eb-953d-d4e8cad7c27c.png)

#ejemplo 2 import wx import webbrowser

clase MyApp (wx.App): def init (self): super (). init (clearSigInt = True)
![image](https://user-images.githubusercontent.com/79875888/112392934-dc717f80-8cbf-11eb-9ac5-15b0a9b8e346.png)

class MyFrame (wx.Frame): # subclase de wx.Window; El marco es una ventana de nivel superior # Un marco es una ventana cuyo tamaño y posición pueden (normalmente) ser cambiados por el usuario. # Por lo general, representa la primera ventana principal que verá un usuario def init (self, parent, title, pos = pos): super (). init (padre = padre, título = título, pos = pos)
![image](https://user-images.githubusercontent.com/79875888/112393114-2ce8dd00-8cc0-11eb-903a-da0206c0c14f.png)
![image](https://user-images.githubusercontent.com/79875888/112393637-07a89e80-8cc1-11eb-88c1-68f6aa627e22.png)

#ejemplo 3 import wx import navegador web

clase MyApp (wx.App): def init (self): super (). init (clearSigInt = True)
![image](https://user-images.githubusercontent.com/79875888/112393790-3c1c5a80-8cc1-11eb-918c-b7447bb80bb9.png)
class MyFrame (wx.Frame): # subclase de wx.Window; El marco es una ventana de nivel superior # Un marco es una ventana cuyo tamaño y posición pueden (normalmente) ser cambiados por el usuario. # Por lo general, representa la primera ventana principal que verá un usuario def init (self, parent, title, pos): super (). init (padre = padre, título = título, pos = pos) self.OnInit ()
![image](https://user-images.githubusercontent.com/79875888/112393874-5b1aec80-8cc1-11eb-9650-86b487e0a4ee.png)
class MyPanel (wx.Panel): # Un panel es una ventana en la que se colocan los controles. (por ejemplo, botones y cuadros de texto) # La clase wx.Panel generalmente se coloca dentro de un objeto wxFrame. Esta clase también se hereda de la clase wxWindow. def init (yo, padre): super (). init (padre = padre)
![image](https://user-images.githubusercontent.com/79875888/112393973-869dd700-8cc1-11eb-8dbf-d0c9f3c81220.png)
if name == " main ": app = MyApp () app.MainLoop 
![image](https://user-images.githubusercontent.com/79875888/112394198-ef854f00-8cc1-11eb-9f1c-39c152286943.png)
![image](https://user-images.githubusercontent.com/79875888/112394279-0d52b400-8cc2-11eb-862d-dd55c44b0fbd.png)
#ejemplo 4 import wx

clase MyApp (wx.App): def init (self): super (). init ()
![image](https://user-images.githubusercontent.com/79875888/112394391-45f28d80-8cc2-11eb-8d67-e8ae776bfc93.png)
class MyFrame (wx.Frame): # subclase de wx.Window; El marco es una ventana de nivel superior # Un marco es una ventana cuyo tamaño y posición pueden (normalmente) ser cambiados por el usuario. # Por lo general, representa la primera ventana principal que verá un usuario def init (self, parent, title): super (). init (padre = padre, título = título, pos = (100, 100))
![image](https://user-images.githubusercontent.com/79875888/112394483-66bae300-8cc2-11eb-9ef2-84005c404aad.png)
class MyPanel (wx.Panel): # Un panel es una ventana en la que se colocan los controles. (por ejemplo, botones y cuadros de texto) # La clase wx.Panel generalmente se coloca dentro de un objeto wxFrame. Esta clase también se hereda de la clase wxWindow. def init (yo, padre): super (). init (parent = parent) self._dont_show = False # para el cuadro dediálogo del mensaje
![image](https://user-images.githubusercontent.com/79875888/112421035-f2009c80-8cf3-11eb-8365-de376ac3c0d4.png)
si nombre == " principal ":
![image](https://user-images.githubusercontent.com/79875888/112421184-3855fb80-8cf4-11eb-8620-97773b686e62.png)
#ejemplo 5 import wx

clase MyApp (wx.App): def init (self): super (). init (clearSigInt = True)
![image](https://user-images.githubusercontent.com/79875888/112421298-62a7b900-8cf4-11eb-9b9b-cb93eddcda47.png)
class MyFrame (wx.Frame): def init (self, title = "MyButtonApp", pos = (100,100)): super (). init (None, title = title, pos = pos) # inicializa el contenido del marco self.OnInit ()
![image](https://user-images.githubusercontent.com/79875888/112421404-94b91b00-8cf4-11eb-85ff-c83e0b95d63c.png)
clase mi_panel (wx.Panel):
![image](https://user-images.githubusercontent.com/79875888/112421488-badebb00-8cf4-11eb-88d4-5c392b87e58c.png)
![image](https://user-images.githubusercontent.com/79875888/112421608-f6798500-8cf4-11eb-8dd0-45fc8a3376da.png)
![image](https://user-images.githubusercontent.com/79875888/112421723-38a2c680-8cf5-11eb-9b17-3b97d4f70551.png)
![image](https://user-images.githubusercontent.com/79875888/112421799-638d1a80-8cf5-11eb-9007-d64869284b63.png)
EJECUCION DEL PROGRAMA
if nombre == ' principal ': aplicación = MyApp () app.MainLoop ()
![image](https://user-images.githubusercontent.com/79875888/112421875-8b7c7e00-8cf5-11eb-8298-b73007699d5d.png)
![image](https://user-images.githubusercontent.com/79875888/112421892-97684000-8cf5-11eb-8f73-961d1fa01915.png)
![image](https://user-images.githubusercontent.com/79875888/112422010-ced6ec80-8cf5-11eb-85ed-45697912aaa3.png)
![image](https://user-images.githubusercontent.com/79875888/112422045-e1e9bc80-8cf5-11eb-9b14-8957468bb75d.png)
![image](https://user-images.githubusercontent.com/79875888/112422149-0e9dd400-8cf6-11eb-8b26-790aabc66a74.png)
![image](https://user-images.githubusercontent.com/79875888/112422200-1d848680-8cf6-11eb-9da1-3a5ecc6a2f46.png)
![image](https://user-images.githubusercontent.com/79875888/112422281-3d1baf00-8cf6-11eb-914e-002c73b031e3.png)
