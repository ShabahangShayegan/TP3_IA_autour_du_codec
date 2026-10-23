# TP3 — L’IA autour du codec : super-résolution et compromis perception-distorsion

Étude de l’utilisation de l’intelligence artificielle pour améliorer la qualité vidéo après compression, sans modifier le codec traditionnel.

## Objectifs

- Comparer l’encodage direct en 1080p avec une chaîne en basse résolution (540p) suivie d’une super-résolution.
- Évaluer différentes méthodes : interpolation bicubique, SwinIR, SwinIR-GAN et Real-ESRGAN.
- Analyser les métriques PSNR, LPIPS, VMAF et VMAF NEG.
- Tracer les courbes débit-distorsion et calculer le BD-rate.
- Étudier les points de croisement selon le débit et la métrique utilisée.
- Explorer le compromis entre fidélité objective et qualité perceptuelle.
- Évaluer le coût de calcul de la super-résolution.

## Technologies utilisées

- Python et PyTorch
- FFmpeg avec x265 ou x264
- SwinIR, SwinIR-GAN et Real-ESRGAN
- LPIPS et VMAF
- NumPy, Pandas, Matplotlib et SciPy
- Google Colab (GPU recommandé)

## Données

Les expériences utilisent des extraits de séquences vidéo UVG, notamment `Jockey` et `Bosphorus`, en résolution 1080p.

## Utilisation

Ouvrir le notebook dans Google Colab, activer un GPU si disponible, puis exécuter les cellules dans l’ordre. Compléter les exercices et analyser les courbes, les tableaux et les résultats visuels.

## Résultats attendus

- Comparaison des méthodes de super-résolution.
- Courbes débit-distorsion selon plusieurs métriques.
- Tableaux BD-rate et classements des méthodes.
- Analyse des points de croisement et du compromis perception-distorsion.
- Évaluation des temps de traitement et discussion des limites de la super-résolution.

**Travail pratique — Machine Learning appliqué à la compression vidéo, EPITA, séance 3.**
