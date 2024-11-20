![image](https://github.com/user-attachments/assets/322bba84-03dc-4182-ba86-7b577a478cc1)

class Persona:
  def __init__(self, n, e):
    self.nombre=n
    self.edad=e

  def cumpleaños(self):
    self.edad += 0.5

p=Persona(input("Ingrese nombre:"),int(input("Ingrese edad: ")))
p.cumpleaños()
p.cumpleaños()
print(f"{p.nombre} cumple {p.edad} años")
