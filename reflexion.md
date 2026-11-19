\# Reflexion zur Git-Übung

Florin Decker



\## 15.1 Repository und Staging Area



1\. Die Staging Area dient dazu, gezielt die Änderungen auszuwählen, die im nächsten Commit gespeichert werden sollen.



2\. git diff zeigt Unterschiede zwischen dem Arbeitsverzeichnis und der Staging Area. git diff --cached zeigt Unterschiede zwischen der Staging Area und dem letzten Commit.



3\. git add . nimmt alle Änderungen im aktuellen Verzeichnis und seinen Unterverzeichnissen auf. Dadurch können unerwünschte Änderungen mit vorgemerkt werden. Mit git add DATEI wählt man einzelne Dateien gezielt aus.



\## 15.2 Branches und Merge



1\. CSS und JavaScript wurden in getrennten Branches entwickelt, damit beide Funktionen unabhängig voneinander bearbeitet werden konnten.



2\. Der erste Merge war ein Fast-Forward, weil auf main seit der Verzweigung keine neuen Commits entstanden waren. Git musste nur den Branch-Zeiger nach vorne verschieben.



3\. Beim zweiten Merge entstand ein Konflikt, weil beide Branches denselben Bereich in index.html unterschiedlich verändert hatten.



4\. HEAD kennzeichnet in der Konfliktmarkierung die aktuelle Version. Die Zeichen ======= trennen die beiden Varianten. Der Branch-Name kennzeichnet die eingehende Version.



5\. git add index.html übernimmt die korrigierte Datei in die Staging Area und markiert ihren Konflikt als gelöst. Der Merge wird danach mit git commit abgeschlossen.

