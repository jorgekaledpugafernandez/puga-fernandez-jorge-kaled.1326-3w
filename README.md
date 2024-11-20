![image](https://github.com/user-attachments/assets/69add51f-9984-4aaf-8b28-26c62b3c0390)

class Estudiante():
    def __init__(self , nombre , nota):
        self.nombre=nombre
        self.nota=nota

    def imprimir(self):
            print(f"Nombre:{self.nombre} \nNota: {self.nota}")

    def resultados(self):
        if self.nota >= 7:
            print("Has APROBADO?!")
        else:
            print("Has REPROBADO")

estudiante1=Estudiante("Pedro", 5)
estudiante1.imprimir()
estudiante1.resultados()

estudiante2=Estudiante ("Elizabeth", 7)
estudiante2.imprimir()
estudiante2.resultados()

estudiante2=Estudiante ("jorge puga", 8)
estudiante2.imprimir()
estudiante2.resultados()
