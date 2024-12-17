## Vorwort der Projektleiter

Die OWASP Top 10 für LLM-Applikationen wurde 2023 als ein von der Community vorangetriebenes Projekt ins Leben gerufen, um Sicherheitsprobleme, die speziell in KI-Anwendungen auftreten, hervorzuheben und zu beheben. Seitdem hat sich die Technologie in immer mehr Branchen und Anwendungen verbreitet, und mit ihr die damit verbundenen Risiken. Da LLMs immer tiefer in alle Bereiche, von der Kundeninteraktion bis hin zu internen Prozessen, integriert werden, entdecken Entwickler und Sicherheitsexperten neue Schwachstellen - und Möglichkeiten, diese zu beheben.

Die Liste aus dem Jahr 2023 war ein großer Erfolg, um das Bewusstsein zu schärfen und eine Grundlage für die sichere Nutzung von LLMs zu schaffen, und wir haben seitdem noch mehr gelernt. Für die neue Version 2025 haben wir mit einer größeren und vielfältigeren Gruppe von Mitwirkenden weltweit zusammengearbeitet, die alle an der Gestaltung dieser Liste mitgewirkt haben. Der Prozess umfasste Brainstorming-Sitzungen, Abstimmungen und Feedback aus der Praxis von Fachleuten, die sich intensiv mit der Sicherheit von LLM-Anwendungen befassen, sei es durch Beiträge oder durch die Verfeinerung dieser Einträge durch Feedback. Jede Stimme war entscheidend, um diese neue Version so gründlich und praxisnah wie möglich zu gestalten.

### Was ist neu in den Top 10 von 2025

Die Liste von 2025 spiegelt ein besseres Verständnis der bestehenden Risiken wider und enthält wichtige Aktualisierungen darüber, wie LLMs heute in realen Anwendungen eingesetzt werden. Beispielsweise wurde das Konzept des „**Unbegrenzten Verbrauchs**“ (Unbounded Consumption) erweitert, um Risiken im Zusammenhang mit dem Ressourcenmanagement und unerwarteten Kosten zu berücksichtigen - ein dringendes Problem bei groß angelegten Einsatz von LLM-Anwendungen.

Der Eintrag „**Vektor und Einbettungen**“ (Vector and Embeddings) ist eine Reaktion auf Anfragen aus der Community nach Anleitungen zur Absicherung von Retrieval-Augmented Generation (RAG) und anderen auf Einbettungen basierenden Methoden, die heute zu den grundlegenden Praktiken für die Absicherung von Modellausgaben gehören.

Wir haben auch „**Offenlegung des Systems Prompts**“ (System Prompt Leakage) hinzugefügt, um einen Bereich realer Exploits abzudecken, der von der Community stark nachgefragt wurde. Viele Anwendungen gingen davon aus, dass Eingabeaufforderungen sicher isoliert sind, aber jüngste Vorfälle haben gezeigt, dass Entwickler nicht davon ausgehen können, dass die Informationen in diesen Eingabeaufforderungen vertraulich bleiben.

„**Exzessive Agentenaktivität**“ (Excessive Agency) wurde angesichts des zunehmenden Einsatzes von Agentenarchitekturen, die dem LLM mehr Autonomie verleihen können, erweitert. Wenn LLMs als Agenten oder in Plugin-Umgebungen agieren, können ungeprüfte Berechtigungen zu unbeabsichtigten oder gefährlichen Aktionen führen, was diesen Eintrag wichtiger denn je macht.

### Die Zukunft

Wie die Technologie selbst ist auch diese Liste ein Produkt der Erkenntnisse und Erfahrungen der Open-Source-Community. Sie wurde durch Beiträge von Entwicklern, Data Scientists und Sicherheitsexperten aus verschiedenen Sektoren gestaltet, die sich alle für die Entwicklung sichererer KI-Anwendungen einsetzen. Wir sind stolz darauf, diese Version von 2025 mit euch zu teilen, und hoffen, dass sie euch die Werkzeuge und das Wissen an die Hand gibt, um LLMs effektiv zu sichern

Vielen Dank an alle, die bei der Erstellung dieses Dokuments mitgeholfen haben, und an alle, die es weiterhin nutzen und verbessern. Wir sind dankbar, mit euch an dieser Arbeit beteiligt zu sein.


###@ Steve Wilson
Projektleiter
OWASP Top 10 for Large Language Model Applications
LinkedIn: https://www.linkedin.com/in/wilsonsd/

###@ Ads Dawson
Technischer Leiter und Leiter der Schwachstellenmeldungen
OWASP Top 10 for Large Language Model Applications
LinkedIn: https://www.linkedin.com/in/adamdawson0/

### Das deutsche Übersetzungsteam

Rico Komenda
[https://www.linkedin.com/in/ricokomenda/](https://www.linkedin.com/in/ricokomenda/)  

### Über diese Übersetzung
Bei der Erstellung dieser Übersetzung haben wir uns bewusst dafür entschieden, nur menschliche Übersetzer einzusetzen, in Anerkennung der außerordentlich technischen und kritischen Natur der OWASP Top 10 für LLM-Applikationen. Die oben aufgeführten Übersetzer verfügen nicht nur über ein tiefes Verständnis des Originalinhalts, sondern auch über die sprachliche Kompetenz, um diese Übersetzung sinnvoll zu gestalten.

###@ Talesh Seeparsan
Übersetzungsleiter, OWASP Top 10 für LLM-Applikationen
[https://www.linkedin.com/in/talesh/](https://www.linkedin.com/in/talesh/)