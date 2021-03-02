def marche(kilometre):
    f =open("comprime.txt", "w+")

    cpt = 0
    while cpt < kilometre:
        f.write(" kilometre a pieds\n")
        cpt = cpt +1 
  
    f.close()
marche(50)
