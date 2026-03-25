class Empaque:
    def __init__(self, material, capacidad, peso):
        self.material = material
        self.capacidad = capacidad
        self.__peso = peso   # atributo privado

    def mostrar_info(self):
        print("Material:", self.material)
        print("Capacidad:", self.capacidad)

    def get_peso(self):
        return self.__peso


# Objeto CAJA
caja = Empaque("Cartón", "10kg", 2)
caja.mostrar_info()
print("Peso:", caja.get_peso())
