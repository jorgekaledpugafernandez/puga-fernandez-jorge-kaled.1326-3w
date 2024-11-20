![image](https://github.com/user-attachments/assets/6a43070f-36bf-4248-94f0-f1f05ea72659)

class Persona:
    def __init__(self, nom, ape):
        self.nombre = nom
        self.apellido = ape
    
    def nombre_completo(self):
        # Retorna el nombre completo
        return f"{self.nombre} {self.apellido}"

class Estudiante(Persona):
    def __init__(self, nom, ape, carr):
        super().__init__(nom, ape)  # Llamada al constructor de la clase base
        self.carrera = carr
    
    def mostrar_carrera(self):
        # Retorna la carrera del estudiante
        return self.carrera

# Ejemplo de uso
estudiante1 = Estudiante("jorge", "puga", "programacion")
print(estudiante1.nombre_completo())  # Imprime: jorge puga
print(estudiante1.mostrar_carrera())  # Imprime: programacion
