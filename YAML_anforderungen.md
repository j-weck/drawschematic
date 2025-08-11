Ziel ist es eine Plattformunabhängige Bibliothek für Bahnsymbole zu erstellen. Dafür werden die Symbole in einer YAML über Formen definiert. Für jede Sprache muss dann ein Script geschrieben werden, welches definiert wie die Formen umgesetzt werden, sodass darstellbare Symbole entstehen.

Folgende Formen müssen definiert werden:
> Linie  
> Kreis  
> Halbkreis  
> gefüllte Flächen  
> Zahlen und Buchstaben? (z.B. für Geschwindigkeits- oder Richtungsanzeiger)

Ziel ist es erstmal einen Markt zu erschließen, um das Tool zu etablieren und Geldgeber zu gewinnen. Deswegen sollen am Anfang erstmal die deutschen Symbole erzeugt werden. Langfristig sollen aber auch Symbole anderer Länder hinzugefügt werden. Auch generische Symbole sollen erstellt werden.

Die YAML Datei soll möglichst einfach gehalten werden. Es geht vor allem um die DArstellung der Formen.
Wie diese Formen zusammengesetzt werden können und welche Bedingungen dabei beachtet werden sollten muss in jeder Sprache definiert werden.

Die Symbole werden alle in einer Ausrichtung definiert (z.B. "stehend"). Das Drehen (und spiegeln?) der Symbole muss außerhalb der YAML erfolgen. 


Die Symbole sollten Kategorisiert werden. 
> baulich vs. logisch  
> Infrastrukturelemente vs. Sicherungstechnische Elemente  
> welche Einteilungen gibt es schon, an denen wir uns orientieren können?  
  
Jedes Symbol wird getrennt definiert. Die Zusammensetzung erfolgt außerhalb der YAML. (z.B. Ist das deutsche KS-Signal nur das Oval. Der Signalmast wir dgetrennt definiert.)

Soll in der YAML schon festgelegt werden welche Symbole sich miteinander kombinieren lassen?





