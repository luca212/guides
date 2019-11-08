# Installation de Unlaunch

Unlaunch is a DSi bootcode exploit which will allow you to run HiyaCFW, a DSi Custom Firmware, and homebrew with full access to your console.

## Ce dont vous avez besoin
* La dernière version de Unlaunch
* La dernière version du HBMenu
* La dernière version de Flipnote ( ͡° ͜ʖ ͡°) (“Flipnote Lenny”)
   * Nous n'avons pas besoin de Flinote Studio sur la DS
* La dernière version de Memory Pit
  * pour firmware 1.0 - 1.3 (USA, EUR, AUS, JPN)
  * pour firmware 1.4 - 1.4.5 (USA, EUR, AUS, JPN)
  * pour firmware 1.0 - 1.4.6 (KOR, CHN)
  
## Création de la nand backup
  
1. Lancez l'application DSi Camera
2. Vérifier que vous êtes dans l'onglet `Carte SD` puis sélectionner `Album`, Vous devriez aboutir sur l'application de la 3ème image
    * Si ce n'est pas le cas revérifier vos fichiers sur la carte sd
4. Sélectionnez `Fwtool`

![](dsi/images/1_home.png)
![](dsi/images/2_camera.png)
![](dsi/images/3_hbmenu.png)

5. Un fois dans Fwtool sélectionnez `Backup DSi Nand`, puis attendez ça devrait prendre une dizaine de minutes
    * la backup est finie lorsque `saved nand.bin.sha1.` apparait
6. Sélectionnez `Exit` et éteignez la console
    
![](dsi/images/4_fwtool.png)
![](dsi/images/5_dsinand.png)

## Installation d'Unlaunch

6. Refaites les étapes 1 et 2 de la partie précédente

7. Sélectionnez `UNLAUNCH.NDS`

8. Sélectionnez `Install Now`

![](dsi/images/6_hbmenu2.png)
![](dsi/images/7_ulinstaller.png)
![](dsi/images/8_installation.png)

10. Ce menu devrait apparaître lorsque vous démarrez la console

![](dsi/images/9_ulmenu.png)
