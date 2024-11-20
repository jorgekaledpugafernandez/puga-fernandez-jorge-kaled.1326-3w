![image](https://github.com/user-attachments/assets/da05d014-d711-4216-b642-73d55267d1ba)

class Marino:
    def hablar(self):
        print("Hola, soy un animal marino!")

class Pulpo(Marino):
    def hablar(self):
        print("Hola, soy un pulpo!")

class Foca(Marino):
    def hablar(self, mensaje):
        self.mensaje = mensaje
        print(mensaje)

marino = Marino()
marino.hablar()

pulpo = Pulpo()
pulpo.hablar()

foca = Foca()
foca.hablar("Hola, soy una foca!")
