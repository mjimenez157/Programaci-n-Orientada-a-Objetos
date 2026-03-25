class Bolsa(Empaque):  # herencia
    def __init__(self, material, capacidad, peso, tipo):
        super().__init__(material, capacidad, peso)
        self.tipo = tipo

    def mostrar_tipo(self):
        print("Tipo de bolsa:", self.tipo)


# Objeto BOLSA
bolsa = Bolsa("Plástico", "5kg", 1, "Reusable")
bolsa.mostrar_info()
bolsa.mostrar_tipo()
print("Peso:", bolsa.get_peso())
