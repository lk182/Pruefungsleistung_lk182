# Datensatz Codebuch für die Prüfungsleistung #
Codebuch erstellt von Leonie Kühn (lk182@hdm-stuttgart)

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

## Ursprung und Datenerhebung

Das Netzwerk ist ein *ungerichtets two-mode Netzwerk*. Es wurden zwei getrennte Fragen erhoben:

# EDGE-Attribute

**from (id)**  
(eindeutige Codierung des Knoten)   
codiert von 1 bis 38, jede ID entspricht einem Studenten

**to (id)**  
Beziehungsstärke aufgrund der Nennung in den Fragen)  
3 = sehr starke Beziehung (erste Nennung),   
1 = starke Beziehung vorhanden (zweite Nennung)

**relationship**
1 = Ministerium (auch angegliedert als Staatsekretär:in), 2 = politische Funktionen, 3 = Ehrenamt, 4 = Unternehmen und Aufsichtsräte, 5 = Stipendien, 6 = Berufstätigkeiten, 7 = Studienort in In- und Ausland 


# NODE-Attribute  
  
**id**  
Identische ID wie aus der edgelist zur Identifikation der Knoten.

**name_short**

**name**
ausgeschriebener Name

**type**
0 = Person, 1 = Organisationen/Verbände/etc.

**sex**    
1 = female, 2 = male, 3 = divers
  
**birth***    
(entsprechendes Geburtsjahr)

**position**  
1 = Parlamentarische Staatssekretär/in, 2 = Staatsminister/in, 3 = Bundesminister/in  

**education**  
1 = Promotion, 2 = Lizenziat, 3 = juristisches Staatsexamen, 4 = Diplom, 5 = Magister

**subject**   
1 = Politikwissenschaften, 2 = Rechtswissenschaften, 3 = Wirtschaftswissenschaften, 4 = Sozialpädagogik, 5 = Volkswirtschaftslehre 

**party**   
1 = Grüne, 2 = FDP, 3 = SPD 

**religion**    
1 = römisch-katholisch, 2 = evangelisch, 3 = muslimisch  
  
**kids**    
(entsprechende Anzahl der Kinder)  

**twitter**  
1 = unter 5.000, 2 = 5.000 - 10.000, 3 = 10.001 - 15.000, 4 = über 15.000  
  
**instagram**    
1 = bis 2.500, 2 = 2.501 bis 5.000, 3 = ab 5.000  

**facebook**  
1 = bis 3.000, 2 = 3.001 bis 5.000, 3 = 5.001 bis 50.000, 4 = über 50.000    

**youtube** 
1 = bis 50, 2 = 51 bis 100, 3 = über 100

##
