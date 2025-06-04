# Anforderungen
+ Nutzer anlegen
+ Nutzer ändern
+ Nutzer löschen
+ Passwort anlegen
+ Passwort ändern
+ Passwort löschen
+ MFA anlegen
+ MFA ändern
+ MFA löschen

# UserEntity
+ keycloakId [1]
+ role[1...*]
+ handle [1]
+ firstName (Keycloak?) [0...1]
+ lastName (Keycloak?) [0...1]
+ mail (Keycloak?) [1]
+ homePlanet [0...1]
+ krtRank [0...1]
+ squadronData [0...2]
+ hangar [1]

# SquadronDataEntity

+ squadronData [1]
+ squadronRank[1]


# Needs
+ [[Keycloak]]
+ [[Frontend]]
+ [[HangarService]]
+ [[VersionService]]