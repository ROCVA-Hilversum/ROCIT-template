# Werken met Git en GitHub

Tijdens het ontwikkelen van software werken jullie samen aan dezelfde code. Git en GitHub helpen om dit goed te organiseren.

## 1. Wat is Git?

Git is een hulpmiddel waarmee je wijzigingen in je code bijhoudt.

Je kunt:
- Opslaan wat je hebt veranderd.
- Eerdere versies terugvinden.
- Samen aan dezelfde software werken.
- Wijzigingen van anderen binnenhalen.

Zie Git als een geschiedenis van alle veranderingen in je project.

## 2. Wat is GitHub?

GitHub is een website waarop jullie jullie code opslaan en samen aan projecten werken.

Binnen GitHub hebben jullie een eigen repository.

Een repository is eigenlijk de projectmap van jullie softwarebedrijf. Hierin staan jullie code, bestanden en documentatie.

## 3. De belangrijkste begrippen

| Begrip | Betekenis |
|---|---|
| Repository | De projectmap van jullie software |
| Commit | Een opgeslagen wijziging |
| Push | Je wijzigingen naar GitHub sturen |
| Pull | Wijzigingen van GitHub ophalen |
| Clone | Een repository naar je eigen computer kopiëren |
| Branch | Een aparte werklijn om wijzigingen te maken |
| Merge | Verschillende wijzigingen samenvoegen |
| Pull request | Een voorstel om jouw wijzigingen samen te voegen |

## 4. Hoe werk je aan een project?

In de basis werk je steeds met dezelfde stappen:

**Stap 1 – Haal de nieuwste versie op**

Zorg dat je de meest recente versie van het project hebt.

```bash
git pull
```

**Stap 2 – Maak je wijzigingen**

Open je project in je code-editor en werk aan je opdracht.

**Stap 3 – Bekijk wat je hebt veranderd**

```bash
git status
```

**Stap 4 – Selecteer je wijzigingen**

```bash
git add .
```

**Stap 5 – Sla je wijzigingen op**

```bash
git commit -m "Voeg contactpagina toe"
```

**Stap 6 – Stuur je wijzigingen naar GitHub**

```bash
git push
```

Je wijzigingen staan nu ook op GitHub.

## 5. Samenwerken met branches

In dit project is jullie main branch protected. Daarom moet je altijd eerst een aparte branch maken.

Een branch is een aparte werklijn. Hierdoor kun je werken zonder direct de hoofdversie van het project aan te passen.


Bijvoorbeeld:

```bash
git switch -c feature/contactpagina
```

Als je klaar bent, stuur je de branch naar GitHub:

```bash
git push -u origin feature/contactpagina
```

Daarna kun je op GitHub een **Pull Request** aanmaken.

Een teamgenoot kan je werk controleren. Daarna kunnen jullie de wijzigingen samenvoegen.

Met dit 4 ogen principe blijf jullie main branch schoon met alleen werkende code. 

## 6. Onze Git-afspraken

- Haal regelmatig de nieuwste versie op.
- Commit regelmatig je wijzigingen.
- Gebruik duidelijke commitberichten.
- Werk niet zomaar in elkaars bestanden. En werk altijd op je eigen branch en niet direct op de main branch.
- Controleer wijzigingen voordat je ze samenvoegt.
- Overleg bij problemen met je team.
- Zet nooit wachtwoorden of geheime sleutels in GitHub.

## 7. Onthoud dit!

- **Git** houdt wijzigingen in je code bij.
- **GitHub** is de plek waar jullie code en samenwerking samenkomen.
- **Commit** betekent dat je een wijziging opslaat.
- **Push** betekent dat je wijzigingen naar GitHub stuurt.
- **Pull** betekent dat je wijzigingen van GitHub ophaalt.

Je hoeft niet alles direct uit je hoofd te kennen. Gebruik deze uitleg als naslagwerk en leer door ermee te werken!
