Categorization of the States/UTs into six different [regions].<br>
📦 [Node.js](https://www.npmjs.com/package/@ifct2017/regions),
📜 [Files](https://unpkg.com/@ifct2017/regions/).

> This is part of package [ifct2017].<br>
> Online database: [ifct2017.github.io].

<br>

```javascript
const regions = require('@ifct2017/regions');
// regions(query)
// → matches [{region, states}]


regions('central');
regions('Uttaranchal');
// [ { region: 'Central',
//     states: 'Chhattisgarh;Madhya Pradesh;Uttar Pradesh;Uttaranchal' } ]

regions('which region andhra pradesh belongs to?');
regions('details of south region');
// [ { region: 'South',
//     states: 'Andaman & Nicobar Islands;Andhra Pradesh;Karnataka;Kerala;Lakshadweep;Pondicherry;Telangana;Tamil Nadu' } ]
```

```javascript
// Additional methods:
regions.load() // → corpus
regions.sql([table], [options]) // → sql statements
regions.csv() // → path of csv file
```

<br>
<br>

[![](https://i.imgur.com/D5UYmbD.jpg)](http://ifct2017.com/)<br>
[![ORG](https://img.shields.io/badge/org-ifct2017-green?logo=Org)](https://ifct2017.github.io)
[![DOI](https://zenodo.org/badge/132935982.svg)](https://zenodo.org/badge/latestdoi/132935982)

> Data was obtained from the book [Indian Food Composition Tables 2017].<br>
> Food composition values were measured by [National Institute of Nutrition, Hyderabad].<br>
> Take a peek at the raw data here: [Document], [Webpage].

[ifct2017]: https://www.npmjs.com/package/ifct2017
[Indian Food Composition Tables 2017]: http://ifct2017.com/
[regions]: https://github.com/ifct2017/regions/blob/master/index.csv
[ifct2017.github.io]: https://ifct2017.github.io
[National Institute of Nutrition, Hyderabad]: https://www.nin.res.in/
[Document]: https://docs.google.com/spreadsheets/d/1a01-O3cex87z9My2hF3ByoUMVMLZtMYKuRFGTbmcIzQ/edit?usp=sharing
[Webpage]: https://docs.google.com/spreadsheets/d/e/2PACX-1vRXTC_URrQPaVbgG0tyMvJGkuaZgTjaQ9UZivesdtVBgpJXWHQldR9ps8C04HVDcZmEuKjCX2LhjUNA/pubhtml
