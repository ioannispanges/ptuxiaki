# Πτυχιακή
#Σημαντικό κομμάτι όταν ξεκινάμε το project ειναι το mvn clean και το mvn install (οδηγίες στο word).

Το έργο χωρίζεται σε πέντε υποέργα ή ενότητες: core, rest-wrapper, cfp-usecase, front και oidc-demo-idp.
Στο έργο αυτό περιλαμβάνονται δύο περιπτώσεις επίδειξης: 
ένα παράδειγμα ανάπτυξης ενός εικονικού IdP για μια συγκεκριμένη περίπτωση χρήσης (τόσο για την προσέγγιση PESTO όσο και για την προσέγγιση dp-ABC) 
και ένα παράδειγμα επίδειξης της εφαρμογής του OLYMPUS ως παρόχου ταυτότητας σε μια ροή OIDC. 

>**Πρωτο Βήμα**
1. Θέλουμε την δημιουργία του backend server καλο είναι να παρεις την ροή του OIDC μεσα στο κώδικά θα μπορέσεις να βρείς χωρίζετε σε 2 μέρη 
model->δημιουργούμε τις κλάσεις που θέλουμε για την εφαρμογή ένα τυπικό παράδειγμα ειναι:
Πρώτη κλάση SignIdentityProof
![Screenshot_1](https://user-images.githubusercontent.com/72886828/143573832-aef44d7f-7026-46c0-bdc1-29db75efb005.png)
![Screenshot_2](https://user-images.githubusercontent.com/72886828/143574738-df64be03-c6e8-47b3-a615-6e56ce91302a.png)

Δεύτερη κλαση  Uniattributes
![Screenshot_2](https://user-images.githubusercontent.com/72886828/143574996-506f69e1-331b-4d3e-a620-a55caa42d6ce.png)
![Screenshot_3](https://user-images.githubusercontent.com/72886828/143575049-e8576003-9efe-4a9a-b964-72b8dd7a6fdf.png)

>**Δευτερο Βήμα**

server
Το παράδειγμα του Server:
![Screenshot_4](https://user-images.githubusercontent.com/72886828/143575281-4225d849-2d26-44fd-b5dc-f1fdcb7fdb65.png)
![Screenshot_5](https://user-images.githubusercontent.com/72886828/143575405-80da6cdd-2dbc-41a1-a432-1baf97320d4d.png)

>**Τρίτο Βήμα**
Το setup0-1-2.json πρέπει να επεξεργαστούν με τα δικά μας δεδομένα
![Screenshot_6](https://user-images.githubusercontent.com/72886828/143575899-cdbd8410-262d-4e84-9134-13c2f95e8a8e.png)

>**Τέταρτο Βήμα**

Docker

η εντολή ειναι docker-compose up όπου θα τρέξει τρια services το τρέχουμε μέσα από το IntellijIDEA στο terminal.



