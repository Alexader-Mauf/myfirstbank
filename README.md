# Erstellen einer Datenbank für das "Bank-Beispiel"
eine transaktion soll ausgeführt werden ; also eine überweisung von xxx€ die von konto1 abgehen und auf Konto2 eingehen

erstellen der DB
erstellen der Abfrage: um eine Transaktion in einem Schritt durchzuführen
erstellen von log's ??

das ganze in django bauen....



Datenbankmodell:

	accounts:
	id	besitzer(userid)	balance
	
	
	users:
	id 	name		Vorname
  
  logs:
  id  description(logs_code)
  
  transfers:
  id  acc_from  acc_to  sum
  
	
	
	
