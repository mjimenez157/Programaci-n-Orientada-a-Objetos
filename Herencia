class Vehiculo:
    def __init__(self, marca, modelo):
        self.marca = marca
        self.modelo = modelo
    def info(self):
        return f"Marca: {self.marca} y modelo {self.modelo}"

class Carro(Vehiculo):
    def __init__(self, marca, modelo, puertas):
#constructor de la clase padre
        super().__init__(marca, modelo)
        self.puertas = puertas
    def info(self):
        info_base = super().info()
        return f"{info_base}, Puertas: {self.puertas}"
carro1 = Carro("Porsche", "911", 2)
print(carro1.info())
