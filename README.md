# technex23
def pdf_to_audio(self):
     level=Superlevel(self)
     level.title("Convert PDF to Audio")
     level.geometry("500*300")
     level.resizable(0,0)
     level.config(bg="chocolate")
     Label(level,text="Convert PDF to Audio",font=("Comic Sans MS",15),bg="Chocolate").place(relx=0.5,y=0)
     Label(level,text="Enter the PDF file location(with extension):",bg="Chocolate",font=("Verdana",15))
