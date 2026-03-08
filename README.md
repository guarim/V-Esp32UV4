# V-Esp32UV4 By M.Guarim
Système Complet de Voiture Autonome ESP32U — une interface HUD style cockpit militaire.
Ce qui est inclus
Vision par ordinateur

Activation caméra smartphone (vue arrière par défaut)
Détection de lignes colorées en temps réel (blanc, noir, rouge, vert, jaune, bleu) avec analyse pixel par pixel
3 modes de vision : Normal / Contours (filtre Sobel) / Couleur saturée
Bounding boxes avec pourcentage de confiance pour piétons, cyclistes, véhicules, obstacles

Contrôle moteur

D-Pad tactile + raccourcis clavier (flèches + espace)
Slider PWM 0–255 avec envoi BLE
Distance de sécurité configurable (10–100 cm)
Bouton arrêt d'urgence
Arrêt automatique 2s avec overlay compte à rebours si STOP détecté

BLE (Bluetooth Low Energy)

Connexion via Web Bluetooth API (Chrome Android)
UUID service standard ESP32 : 4FAFC201...
Commandes : F/B/L/R/S/E/A0/A1/V{pwm}
Mode simulation automatique si BLE indisponible

Interface

Télémétrie en temps réel (moteurs L/R, direction, FPS)
Journal d'événements horodaté
Toggles individuels par module de détection
Mode autonome avec suivi de ligne automatique
