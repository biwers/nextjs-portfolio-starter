---
title: Sonos Roam
date: 2021/3/30
description: Sonos Roam – petit et portable
tag: Critiques
author: Pascal Forget
---

# Sonos Roam

Le haut-parleur portable Roam est le petit dernier de Sonos. S’il est plus cher qu’un haut-parleur Bluetooth conventionnel, il diffuse la musique par wifi et s’intègre à son système Sonos existant.

### Il est vraiment tout petit

<iframe
    width="640"
    height="480"
    src="https://youtu.be/F3PKdtBOYK8"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
>
</iframe>

Malgré sa petite taille, il se synchronise avec les autres haut-parleurs Sonos et diffuse de la musique par wifi. L’ajout à son système existant est simplifié par une puce NFC située sous l’appareil. Mais étrangement, l’association par Bluetooth à un téléphone par NFC ne semble pas fonctionner.

La puissance n’est pas la même que les autres modèles Sonos. C’est assez frappant! Le volume de mon système Sonos dépasse très rarement 10%; j’écoute le Roam autour de 25%, même quand il est près de moi. Si les autres haut-parleurs de la marque remplissent bien une pièce, celui-ci est plutôt pour son espace personnel, ou pour un petit groupe.

Des micros analysent l’environnement pour optimiser le son, qui me semble très correct.

Le Roam est mono. On pourra en combiner deux pour former une paire stéréo, mais seulement en wifi.

<Image
  src="https://www.pascalforget.com/wp-content/uploads/2021/03/haut-parleur-sonos-roam-ordinateur.jpg"
  alt="Photo"
  className="next-image"
/>
<Image src="https://www.pascalforget.com/wp-content/uploads/2021/03/haut-parleur-sonos-roam-ordinateur.jpg" alt="Nextra" width={1536/2} height={768/2} layout="intrinsic"/>


## Summary

We've discussed two forms of pre-rendering for Next.js.

- **Static Generation (Recommended):** The HTML is generated at **build time** and will be reused on each request. To make a page use Static Generation, either export the page component, or export `getStaticProps` (and `getStaticPaths` if necessary). It's great for pages that can be pre-rendered ahead of a user's request. You can also use it with Client-side Rendering to bring in additional data.
- **Server-side Rendering:** The HTML is generated on **each request**. To make a page use Server-side Rendering, export `getServerSideProps`. Because Server-side Rendering results in slower performance than Static Generation, use this only if absolutely necessary.
