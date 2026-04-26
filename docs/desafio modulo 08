'''
crie um sistema de biblioteca com classes  Livros e Biblioteca para gerenciar empréstimos.

criar duas classes:
(PRODUTOS)Livro:
(PROCESSO / FAZER ALGO)Biblioteca, emprestar, adicionar;


atributos;
metodos;
        metodo especial - > self
'''


class Livro:
   
    def __init__(self, titulo, autor):
        self.titulo = titulo
        self.autor = autor
        self.disponivel = True

    
    def __str__(self):
        status = "Disponivel" if self.disponivel else "Emprestado"
        return f"'{self.titulo}' - {self.autor} [{status}]"

class Biblioteca:

    def __init__(self):
        self.livros = []

    def adicionar_livro(self, livro):        
        self.livros.append(livro)
        

    def emprestar_livro(self, titulo_procurado):

    for livro in self.livros:

        if livro.titulo == titulo_procurado:

            if livro.disponivel:
                livro.disponivel = False
                print(f"Empréstimo de '{livro.titulo}' realizado")
            else:
                print(f"O livro '{livro.titulo}' já está emprestado")

            return

    print("Livro não está no acervo.")

    bilioteca_municipal = Biblioteca()
    livro1 = Livro("Authentic Games", "Authentic Games")    
    livro2 = Livro("Minecraft", "Notch")
    livro3 = Livro("The Witcher", "Andrzej Sapkowski")    
    livro4 = Livro("death note", "Tsugumi Ohba")


    bilioteca_municipal.adicionar_livro(livro1)
    bilioteca_municipal.adicionar_livro(livro2)  
    biblioteca_municipal.adicionar_livro(livro3)   
    biblioteca_municipal.adicionar_livro(livro4)        

    print (livro1)
    biblioteca_municipal.emprestar_livro("Minecraft")   
    print (livro1)      
