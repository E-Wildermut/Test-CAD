# Test-CAD

# Hier die Ordnerstruktur 

# Arbeitsanweisung 

# Git befehle 

Wo finde ich bei github commit-hash-id

Die Commit-Hash-ID finden Sie in der GitHub-Oberfläche. Hier sind die Schritte, um die Commit-Hash-ID zu finden:

Gehen Sie zu Ihrem Repository auf GitHub.

Klicken Sie auf den Tab "Commits". Dieser Tab befindet sich normalerweise oberhalb der Dateiliste und neben dem Tab "Code".

Sie sehen eine Liste aller Commits, die in diesem Repository gemacht wurden. Jeder Eintrag enthält den Commit-Nachricht, den Autor, das Datum und eine lange Zeichenkette, die die Commit-Hash-ID ist.

Klicken Sie auf den gewünschten Commit. Sie werden zur Detailansicht des Commits weitergeleitet.

Die Commit-Hash-ID befindet sich normalerweise in der oberen rechten Ecke, direkt unter den Schaltflächen "Raw", "Blame" und "History". Es sieht etwa so aus: abc1234.

Sie können diese ID kopieren und in Ihren Git-Befehlen verwenden. Beachten Sie, dass Sie nur den ersten Teil der Hash-ID (die ersten 7 Zeichen) benötigen, um einen bestimmten Commit zu identifizieren.

Wenn Sie Ihren main Branch auf eine ältere Version zurücksetzen möchten, müssen Sie dies lokal auf Ihrem Computer tun und dann die Änderungen zu GitHub pushen.

Führen Sie folgende Schritte aus:

Öffnen Sie die Git-Befehlszeile (wie Git Bash oder das Terminal auf einem Mac) und navigieren Sie zu Ihrem lokalen Repository.

Verwenden Sie den Befehl git checkout main, um sicherzustellen, dass Sie sich auf dem main Branch befinden.

Führen Sie den Befehl git reset --hard abc1234 aus und ersetzen Sie "abc1234" durch die Commit-Hash-ID, auf die Sie zurücksetzen möchten. Dadurch wird Ihr main Branch auf den Zustand dieses Commits zurückgesetzt.

Führen Sie den Befehl git push origin +main aus, um Ihre Änderungen zu GitHub zu pushen.

Beachten Sie, dass Sie den Befehl git push origin +main vorsichtig verwenden sollten, da er den Remote-main Branch ohne Rücksicht auf Änderungen, die andere gemacht haben könnten, überschreibt.

Bitte beachten Sie auch, dass das Zurücksetzen auf einen älteren Commit und das Forcieren eines Pushs irreversible Operationen sind. Wenn Sie sich nicht sicher sind, konsultieren Sie immer einen erfahrenen Kollegen oder Mentor.
