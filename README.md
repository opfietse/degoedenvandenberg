# De Goed en van den Berg
Bootstrap site.

## Compile sass to ccss
```
#sass scss/dgvdb.scss css/dgvdb-sass.css
dart compile-sass.dart scss/dgvdb.scss css/dgvdb-sass.css
```

## Transfer to backup
```
rsync --recursive --links --times * kube05:/home/rvk/nfs/dgvdb
```


Lettertypes

/* Import Google Fonts */
@import url('https://fonts.googleapis.com/css2?family=Lato:wght@400;500&family=Montserrat:wght@600;700&family=Playfair+Display:wght@400;700&display=swap');

/* Body tekst */
body {
font-family: 'Lato', sans-serif;
font-weight: 400;
line-height: 1.5;
color: #333; /* donkere, goed leesbare tekst */
background-color: #fff; /* heldere achtergrond */
}

/* Koppen */
h1, h2, h3, h4, h5, h6 {
font-family: 'Montserrat', sans-serif;
font-weight: 600;
color: #111; /* iets sterker contrast voor titels */
margin-top: 1.5em;
margin-bottom: 0.5em;
}

/* Quotes of testimonials */
blockquote {
font-family: 'Playfair Display', serif;
font-style: italic;
font-weight: 400;
color: #555;
border-left: 4px solid #ccc;
padding-left: 1em;
margin: 1em 0;
}

/* Links */
a {
color: #1a73e8; /* fris, professioneel blauw */
text-decoration: none;
}

a:hover {
text-decoration: underline;
}


Wat dit doet:

Lato voor de hoofdtekst → leesbaar en vriendelijk

Montserrat voor koppen → strak, professioneel en modern

Playfair Display voor quotes → elegant en inspirerend

Kleuren en spacing zijn afgestemd op een rustige, professionele uitstraling
