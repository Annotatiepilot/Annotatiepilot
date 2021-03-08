Tijdens dit proefproject zullen we videomateriaal gaan annoteren voor het trainen van AI-modellen. Voor het ontwikkelen van AI bij mediaorganisaties zijn grote hoeveelheden goed gelabelde content nodig. We werken hierbij in een ‘annotatiestraat’: een soort productielijn voor het labelen van content. Het eindproduct zijn door de mens gemaakte datasets die de mediaorganisaties kunnen gebruiken om algoritmes te trainen.

Op deze pagina houden we bij welke taken er beschikbaar zijn en waar je die kan vinden. Je kunt zelf kiezen aan welke actieve taken je wilt werken. We verwachten dat een beetje diversiteit wel prettig is.

* * *

### Nieuws

| Datum | Bericht |
|:------|:--------|
| 8-3-2021 | Week 2! Er staan hieronder wat eerste cijfers over hoe ver jullie al gekomen zijn. Wat een berg werk al in de eerste dagen. De annotaties zien er prima uit. Let bij de gezichten nog even extra op de instructies. Er staan nu ook wat voorbeelden bij. |
| 2-3-2021 | De eerste taken zijn beschikbaar! |

* * *

### Taken

<table>
  <thead>
    <tr>
      <th>Titel</th>
      <th>Datum</th>
    </tr>
  </thead>
  <tbody>
  {% for post in site.posts %}
    <tr>
      <td><a href="{{ post.url }}">{{ post.title }}</a></td>
      <td>{{ post.date | date_to_string }}</td>
    </tr>
  {% endfor %}
  </tbody>
</table>

### Status

![Status](/status/status.svg)
