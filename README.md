# hello-world
this is my brand new hellow world repository
Is this awesome or what?



n=int(input("Digite un número entre 1 y 10: \n"))
if n>0 and n<=10:
    nombre_Documento="tabla-"+str(n)+".txt"
    a=open(nombre_Documento,"w")
    for i in range(1,11,1):
        #res=n*i
        a.write(str(n)+" X "+str(i)+" = "+ str(n*i)+"\n")
else:
    print("Error, no es posible realizar la actividad.")
a.close()
