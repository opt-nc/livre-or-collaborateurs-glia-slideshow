## Contributing

Utiliser le systèmes des [issues](https://github.com/adriens/livre-or-collaborateurs-glia-slideshow/issues).


## Règles du jeu

Le jeu consiste à alimenter ce slideshow par du code, et que ce soit agréable à regarder.

- Chaque contributeur fait une PR sur le projet
- Chaque slide horizontal correspond à un unique collaborateur
- Le collaborateur dispose d'une liberté totale sur les les slides verticaux sont il  a responsabilité. Plus c'est beau, mieux c'est
- On the touche pas aux slides des autres collaborateurs: "chacun sa colonne"
- Information minmale collaborateur: Prénom et Nom, période d'activité, photo/avatar, lien vers réseaux sociaux en lien avec le dév (linkedIn, twitter) projets réalisés et slide donnant une phrase résumant son expérience au sein du bureau
- Commenter le début et la fin de sa section afin de rendre la lecture du code plus aisée
- Déposer les images dans `img/{votre dossier dédié}`

## Exemple de code

```html
<!-- Ronny Soutart -->
<section>
    <section data-background="img/ronny/ronny.jpg">Ronny Soutart</section>
    <section>Présentation</section>
        <section>
            <h3>Contributions</h3>
            <p>
                <ul>
                    <li>Projet 1</li>
                    <li>Projet 2</li>
                    <li>Projet 3</li>
                </ul>
            </p>
        </section>
    <section data-background="img/ronny/ronny-quote.jpg">
        <blockquote>"Ma citation"</blockquote>
    </section>
</section>
<!-- Fin de Ronny Soutart -->
```