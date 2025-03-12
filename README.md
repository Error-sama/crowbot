# crowbot README

____

ce qu'on peut faire avec le crowbot :

  - le connecter a distance par wifi ou par bluetooth ou encore par télécommande
  - le connecter a un ordinateur pour le controler ou injecter du code

utilisation des library pour le programme princpal du crowbot :

  - Wire.h
  - U8g2lib.h
  - Ticker.h
  - FastLED.h
  - BLEScan.h
  - BLEDevice.h

pour la connection a distance il utilise :

  - BLEServer.h
  - BLEUtils.h
  - BLE2902.h

___

controle de la manette :

  - nous avons 4 bouton principal qui vont de vert pour D, rouge pour A, bleu pour C, jaune pour B.
      - chacune de ces touches on une fonctionalité :
          - Le Bouton A : Appuyez sur la touche a pour éviter les obstacles, puis appuyez sur fermer.
          - Le Bouton B : patrouille de ligne, puis appuyez sur fermer.
          - Le Bouton C : recherche de lumière, puis appuyez sur Fermer.
          - Le Bouton D : chanter, clignoter, puis appuyer pour fermer.
       
  - Nous avons ensuite deux bouton sur le haut de la manette L et R (pour gauche et droite).
      - Pour le Bouton L : allumez la lumière RVB de manière aléatoire, puis appuyez pour l'éteindre.
      - Pour le Bouton R : le buzzer sonne pendant 300 ms.

