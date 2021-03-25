# P.F.2_Montiel_Cruz_Joel_Gonzalo
codigo en tu portafolio realizando los widget correspondientes 

ventana from tkinter import * #llamamos las librerias from tkinter.ttk import * ![image](https://user-images.githubusercontent.com/79875834/112521050-adabe580-8d61-11eb-97bb-8154a1a8f209.png)

window = Tk() window.title("programa") #con windos tk inicializamos o arrancamos un programa lbl = Label(window, text="robot",font =("Arial Bold",50)) #tenemos un objeto etiqueta con sus atributos de palabras lbl.grid(column=0,row=0) #pocicionamiento de etiqueta
![image](https://user-images.githubusercontent.com/79875834/112521098-bbfa0180-8d61-11eb-9bc7-abf33ebc8965.png)

txt=Entry(window,width=0) #tenemos otros objetos de texto con su pocicionamiento txt.grid(column=0,row=1)
txt.focus() #objeto focus ![image](https://user-images.githubusercontent.com/79875834/112521219-e2b83800-8d61-11eb-9816-11885299f6cc.png)

def Cliked(): res = "inteligencia artificial" + txt.get() #metodo clik asignamos este evento y las secuencias que tendra al pulsar este objeto esque manda a llamar lbl.configure(text=res)
![image](https://user-images.githubusercontent.com/79875834/112521270-f06dbd80-8d61-11eb-9f35-0a585207dcd8.png)

indow.geometry("500x500") btn = Button(window, text="clik",command=Cliked) btn.grid(column=1,row=1)
window.mainloop() 
![image](https://user-images.githubusercontent.com/79875834/112521353-067b7e00-8d62-11eb-8424-cc38f3f33f4b.png)

