# Anforderungen
+ Staffel anlegen
+ Staffel ändern
+ Staffel löschen
+ Kommandogruppe anlegen
+ Kommandogruppe ändern
+ Kommandogruppe löschen
+ Mitglied hinzufügen
+ Mitglied entfernen

# SquadronEntity
+ id [1]
+ name [1]
+ tag [1]
+ description [0...1]
+ commandGroup [0...*]
+ member[0...*]
+ 

# Needs
+ [[Keycloak]]
+ [[Frontend]]
+ [[UserService]]