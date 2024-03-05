# libreoffice calc conditional formating

We want to determine all cell in coloumn A which have same value in coloumn D

Libreoffice Menu

* format
    * conditional
	    * condition

add this formula

```
VLOOKUP(A1,D:D,1,0)=A1
```

Apply range is 

```
A1:A15
```
