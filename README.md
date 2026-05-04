# 032 Atelier — Interior Design Studio

**Live site:** [032atelier.com](https://032atelier.com)

## Files

```
032atelier/
├── index.html          # Main page (hero, about, services, publications, contact)
├── portfolio.html      # Projects page with gallery overlay
├── images/
│   ├── about-photo.png                 # Team photo (About section)
│   └── [add your project photos here]
└── README.md
```

## How to add project photos

1. Copy your photos into the `images/` folder
2. Open `portfolio.html` and find the `projects` object in the `<script>` section
3. Add image paths for each project:

```js
project1: {
  images: [
    'images/banacha-1.jpg',
    'images/banacha-2.jpg',
    // ...
  ]
},
project2: {
  images: [
    'images/obriy-1.jpg',
    // ...
  ]
},
```

## Deploy to Netlify

1. Push this folder to a GitHub repository
2. Go to netlify.com → Add new site → Import from Git → select your repo
3. No build settings needed — click Deploy
4. Go to Domain settings → Add custom domain → `032atelier.com`
5. Copy the 2 nameservers Netlify gives you into your domain registrar

## Languages
EN | PL — visitor's choice is saved automatically.
