<template>
  <b-container>
    <b-row>
      <b-col>
        <h1>Software für Risikobeurteilung, Gefährdungsanalyse und CE-Kennzeichnung</h1>
        <p>
          Die Planung und Dokumentation der Maschinensicherheit sind wesentliche gesetzliche Anforderung. Software-Werkzeuge helfen dabei den Prozess einzuhalten und erleichtern die Erfassung der Informationen in dem sie dem Anwender Führung und Hilfestellung bieten.
          Hier stellen wir einige ausgewählte Softwareprodukte zu Risikobeurteilung, Gefährdungsanalyse und CE-Kennzeichnung vor und geben Einblick in die Verwendung.
        </p>
      </b-col>
    </b-row>

    <b-row class="spacer">
      <b-col>
        <h2>Secutify Solo Risk Assessment</h2>
        <p>
          Secutify Solo ist eine Windows Anwendung zur Erstellung von Risikobeurteilungen für Maschinen. Die Software bildet das in der Sicherheitsnorm DIN EN ISO 12100 "Sicherheit von Maschinen - Allgemeine Gestaltungsleitsätze - Risikobeurteilung und Risikominderung (ISO 12100:2010)" Verfahren zur Erstellung von Risikobeurteilungen übersichtlich ab.
          Der Aufbau der Software führt den Anwender durch alle Schritte zur Erstellung der Risikobeurteilung.
        </p>

        <p>
          Wesentliche Produktfunktionen:
          <ul>
            <li>EN ISO 12100 konforme Risikobeurteilung</li>
            <li>Effiziente Erfassung von Gefährdungen die an mehreren Stellen oder bei mehreren Aufgaben auftreten</li>
            <li>Übersichtliche Berichtsfunktion, die bereits eine Beschreibung zum angewandten Verfahren enthält</li>
            <li>Unterstützt die Dokumentation in mehreren Sprachen</li>
            <li>Verwaltung von Normen und Richtlinien</li>
            <li>Praktische Piktogramm-Bibliothek mit wichtigen Sicherheitszeichen</li>
            <li>Geringe technische Anforderungen, ohne eigenen IT-Admin zu betreiben</li>
          </ul>

          Herstellerlink: <a href="https://secutify.com" target="_blank">secutify.com</a>
        </p>
        <p>
          Die Software eignet sich für Betreiber und Hersteller von Maschinen die der Maschinenrichtlinie 2006/42/EG oder anderen einschlägigen EU-Produktsicherheitsrichtlinien unterliegen.
          Für große Teams ist die Lösung nur bedingt geeignet, da sie die Dokumentation nicht in einer Datenbank verwaltet, sondern in Form von Dateien auf dem lokalen oder Netzlaufwerk.
          Wer nicht den Anspruch hat zeitgleich an einem Dokument zu arbeiten, hat damit eine gute Lösung, die einfach zu verwalten ist.

        </p>
      </b-col>
    </b-row>


  </b-container>
</template>

<script>
export default {
  name: "software-werkzeuge",
  head: {
    htmlAttrs: {
      lang: 'de',
    },
    title: 'Software-Werkzeuge | Maschinensicherheit',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'Software für Maschinensicherheit, Risikobeurteilung, Gefährdungsanalyse und CE-Kennzeichnung'
      }
    ],
  }
}
</script>

<style scoped>

</style>
