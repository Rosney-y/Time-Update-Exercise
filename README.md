# Time-Update-Exercise
Adding minutes can affect the time in different ways this is what my code do.


Imagine its 23:59 andd you want to add 3 minutes 
--> its should be 00:03 right 



In this exercice i created my "heure" class who covered some methodes but the most importants are : 

public void addminute() to add one minute

and public void addbeaucoupmin(int n) to add n minutes .

My constructor cover this : 

        this.heure=heure%24;      0<hour<23 
        this.minute=minute%60;    0<minute<59 
        this.heure+=minute/60;    
        this.heure=heure%24;  

And to add a n minutes
 we have t

