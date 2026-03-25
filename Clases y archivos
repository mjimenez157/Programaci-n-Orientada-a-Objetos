class Libro:
    def __init__(self, titulo, autor):
        self.titulo = titulo
        self.autor = autor

    def mostrar(self):
        print(self.titulo, "-", self.autor)


class Biblioteca:
    def __init__(self, nombre):
        self.nombre = nombre
        self.libros = []

    def agregar(self, libro):
        self.libros.append(libro)

    def listar(self):
        print("\nBiblioteca:", self.nombre)
        for libro in self.libros:
            libro.mostrar()

    # Método para guardar en archivo
    def guardar(self):
        archivo = open("libros.txt", "w")
        for libro in self.libros:
            archivo.write(libro.titulo + "," + libro.autor + "\n")
        archivo.close()

    # Método para leer archivo
    def cargar(self):
        archivo = open("libros.txt", "r")
        for linea in archivo:
            datos = linea.strip().split(",")
            titulo = datos[0]
            autor = datos[1]
            libro = Libro(titulo, autor)
            self.agregar(libro)
        archivo.close()

bib = Biblioteca("Central")

bib.agregar(Libro("Cien años de soledad", "Gabriel García Márquez"))
bib.agregar(Libro("Don Quijote", "Miguel de Cervantes"))

bib.listar()

bib.guardar()

otra = Biblioteca("Copia")
otra.cargar()
otra.listar()
