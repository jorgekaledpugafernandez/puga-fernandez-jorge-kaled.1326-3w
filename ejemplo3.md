![image](https://github.com/user-attachments/assets/cd8cefe3-8d30-46cc-98b5-18b84c3514ab)
![image](https://github.com/user-attachments/assets/0c84db4c-9c3c-4280-a64d-2af03cab8cc2)


class Calculadora():
    def __init__(self, num1, num2):
        self._num1=num1
        self._num2=num2

    def suma(self):
        resultado=self._num1 + self._num2
        print(f"El resultado de la suma es: {self._num1} + {self._num2}={resultado}")

    def resta(self):
        resultado=self._num1 - self._num2
        print(f"El resultado de la resta es: {self._num1} – {self._num2}={resultado}")

    def division(self):
        resultado=self._num1 // self._num2
        print(f"El resultado de la divisón es: {self._num1} // {self._num2}= {resultado}")

    def multiplicacion(self):
        resultado=self._num1 * self._num2
        print(f"El resultado de la multiplicación es: {self._num1} * {self._num2} = {resultado}")

operacion=Calculadora (10, 5)
operacion.suma()

operacion=Calculadora(20, 5)
operacion.resta()

operacion=Calculadora(15, 3)
operacion.division()

operacion=Calculadora(8, 4)
operacion.multiplicacion()
