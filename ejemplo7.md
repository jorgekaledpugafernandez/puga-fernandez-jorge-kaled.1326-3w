![image](https://github.com/user-attachments/assets/e1003013-fd74-4cde-97b0-c9fe04a41f40)

class Universidad():
    def __init__(self, Nombre):

        self.Nombre = Nombre

class Carrera():
    def carrera(self, especialidad):

        self.especialidad = especialidad

class Estudiante(Universidad, Carrera):
    def datos(self, nombre, edad):

        self.nombre = nombre

        self.edad = edad

        print(f"El nombre del estudiante es {self.nombre}, tiene {self.edad} años, su especialidad es {self.especialidad}. Estudia en la prepatoriac {self.Nombre}")

persona = Estudiante("cbtis128")

persona.carrera("Programacion")

persona.datos("Jorge puga",  16)
