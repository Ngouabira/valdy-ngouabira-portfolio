# Guide SEO et configuration – Portfolio Valdy NGOUABIRA

## ✅ Modifications déjà appliquées

- **Meta title et description** personnalisés avec mots-clés
- **Structure H1, H2, H3** optimisée pour Google
- **Mots-clés** : Développeur Full Stack Sénégal, Portfolio développeur Java, Laravel Angular API REST
- **Alt text** sur toutes les images
- **Section Projets** détaillée (technologies, résultats)
- **Section Contact** avec formulaire et liens réseaux
- **Sitemap XML** et **robots.txt** pour Google Search Console

---

## 🔧 À configurer manuellement

### 1. Formulaire de contact (Formspree)

Le formulaire utilise [Formspree](https://formspree.io/) (gratuit).

1. Crée un compte sur https://formspree.io
2. Crée un nouveau formulaire
3. Remplace `YOUR_FORM_ID` dans `index.html` par ton ID Formspree :
   ```html
   action="https://formspree.io/f/YOUR_FORM_ID"
   ```

### 2. Google Search Console

1. Va sur https://search.google.com/search-console
2. Ajoute ta propriété : `https://ngouabira.github.io/valdy-ngouabira-portfolio/`
3. Soumets le sitemap : `https://ngouabira.github.io/valdy-ngouabira-portfolio/sitemap.xml`

### 3. URL canonique et sitemap

Si ton site a une URL différente (domaine personnalisé, autre repo), mets à jour :
- `index.html` : balise `<link rel="canonical">`
- `sitemap.xml` : toutes les URLs
- `robots.txt` : URL du sitemap

### 4. Lien Twitter/X

Le lien Twitter est `https://x.com/valdy_ngouabira`. Si ton compte est différent, modifie-le dans `index.html` et la section Contact.

---

## 🔗 Backlinks (à faire de ton côté)

Pour renforcer ton référencement, ajoute des liens vers ton portfolio depuis :

- **LinkedIn** : section "Site web" de ton profil
- **GitHub** : bio et lien dans les README
- **Twitter/X** : lien dans la bio
- **Annuaires** : annuaires de développeurs, freelances
- **Sites clients** : si possible, un lien "Réalisé par" sur les sites que tu as développés

