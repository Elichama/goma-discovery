# Goma Discovery - Galerie Cloudinary
**Nom:** Goma Discovery - Galerie photo personnelle
**Auteur:** Elichama - UAC / Goma
**Cloud Name:** zhq213wx
**Cours:** Cloud Computing - Devoir Cloudinary

### Description
Petit site web statique et responsive qui présente 3 photos personnelles hébergées sur Cloudinary. Aucune image en local.

### Technologies
- HTML5 / CSS3 Responsive (Grid)
- Cloudinary pour hébergement + optimisation + CDN
- GitHub Pages pour déploiement

### Comment Cloudinary est utilisé
1. Compte gratuit sur cloudinary.com
2. Upload de 3 images dans Media Library
3. Liens Secure récupérés :
   - https://res.cloudinary.com/zhq213wx/image/upload/f_auto,q_auto/WhatsApp_Image_2026-11-03_at_16.10.37
   - https://res.cloudinary.com/zhq213wx/image/upload/v1794075169/9aaa9f973fbf19ecf28ba403f8d6d633.webp
   - https://res.cloudinary.com/zhq213wx/image/upload/v1794075198/IMG-20241020-WA0129.jpg
4. Transformations dans l'URL : c_fill,w_600,h_400 pour recadrer à 600x400 + f_auto,q_auto pour format et qualité automatiques (WebP/AVIF) + livraison via CDN mondial
5. Sécurité : Aucune API Key / Secret dans le code, seulement URLs publiques.

### Lancer en local
git clone https://github.com/Elichama/goma-discovery.git
cd goma-discovery
Ouvrir index.html dans navigateur

### Déploiement
Settings > Pages > Deploy from a branch > main / root > Save
Site publié: https://elichama.github.io/goma-discovery/

### Livrables TP
- Dépôt: https://github.com/Elichama/goma-discovery
- Site: https://elichama.github.io/goma-discovery/
