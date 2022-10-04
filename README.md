# code-python
MDF
def viscosite():
    v=float(input("entrez un nbr:"))
    d=float(input("entrez un nbr:"))
    w=float(input("entrez un nbr:"))
    try:
        v=float(v)
        d=float(d)
        w=float(w)
        u=w*v*d
        print("la viscosité dynamiqueest:",u,"pi")
    except:
         print("la val de densité et/ou viscositéque vous avez donné par caractére") 
    print(u)
    viscosite()
viscosite()
