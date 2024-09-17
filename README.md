### Kundensegmentierung mit Spark

**1. Spark-Sitzung und Datenimport:**
Spark wird initialisiert und die CSV-Daten werden eingelesen.

**2. Datenaufbereitung:**
Fehlende Werte werden behandelt und neue Spalten wie `NEW_order_num_total` und `NEW_customer_value_total` werden erstellt.

**3. Analyse:**
Daten werden nach Kanälen und Plattformtypen aggregiert.

**4. K-Means Clustering:**
Recency, Frequency und Monetary Features werden erstellt, skaliert und für das K-Means-Clustering verwendet. Fünf Cluster werden als optimal identifiziert und Kunden entsprechend zugewiesen.

**Ergebnisse:**
Die Kunden werden in fünf Cluster gruppiert, basierend auf ihren Kaufverhalten und -werten.
