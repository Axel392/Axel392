#este programa crea correos:
#Lista de nombres y apellidos.
nombres = [ "adriano" , "francisco" , "sarahi" , "segio" , "aurelio" ]
apellidos = [ "hernandez" , "perez" , "patricio" , "lezama" , "hernandez" ]
correo = []
#checar que sean de igual tamaño
ln = len ( nombres )
la = len ( apellidos )
si  ln  == la :
    #abrirarchivo
    lista = abrir ( "lista.txt" , "w" )
    para  i  en el  rango ( ln ):
     correo = nombres [ i ] +  "." + apellidos [ i ] + "@correo.com"
     Correos . adjuntar ( correo )
     imprimir ( correo )
para  x  en el  rango ( ln ):
    lista _ escribir ( correos [ x ])
    lista _ escribir ( " \n " )
lista _ cerrar ()
