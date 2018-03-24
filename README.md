
SEBELUM DI RUN

jawab = 'y'
while(jawab == 'y' ):
    no = input("no: ")
    nama = input("nama : ")
    nim = input("nim : ")
    nt = float(input("tugas : "))
    nuts = float(input("uts : "))
    nuas = float(input("uas : "))
    nakhir  = (nt*30/100+nuts*35/100+nuas*35/100)
    print (nakhir)
    jawab = input("Tambah data (ya/tidak) :")
if (jawab == 'tidak') :
    print ("-----------------------------------------------------")
    print ("| NO |   NAMA   |  NIM  | N.TUGAS | N.UTS | N.AKHIR |")
    print ("-----------------------------------------------------------")
    print ("|",no," |",nama," |",nim,"|",nt,"|",nuts," |",nuas," |",nakhir,"|")
    
    
  
  SESUDAH DI RUN
   no: 1
nama : dede
nim : 311710347
tugas : 75
uts : 85
uas : 80
80.25
Tambah data (ya/tidak) :y
no: 2
nama : setiawan
nim : 322710347
tugas : 80
uts : 75
uas : 70
74.75
Tambah data (ya/tidak) :tidak
-----------------------------------------------------
| NO |   NAMA   |  NIM  | N.TUGAS | N.UTS | N.AKHIR |
-----------------------------------------------------------
| 2  | setiawan  | 322710347 | 80.0 | 75.0  | 70.0  | 74.75 |
>>> 

