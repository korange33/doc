Montage
=======
Kossel mini avec RAMPS 1.4 et un smart controller
 
  * [doc du site marchand] (http://builda3dprinter.eu/build-manuals/kossel_mini_build_manual/start-building/lower-frame-v2-2)
  * [think3dprint3d] (http://www.think3dprint3d.com/Kossel-Mini-3dPrinter-Kit)
  * [Doc détaillée avec plein de photos] (http://www.instructables.com/id/Detailled-Assembly-Instructions-of-the-Rostock-Min)
  * 
Calibration
===========

  * [site référence pour le calibrage d'une imprimante delta] (http://minow.blogspot.co.uk/index.html#491880551957190705)
  * [calibrage issu du site Think3DPrint3D] (https://docs.google.com/document/d/1wYwPmP2ZbZWeXFcjtXCqGfVvm05ZUVkkGT7-EKEv8fc/pub)
  * [calibrage détaillé ] (https://miscsolutions.wordpress.com/2015/01/22/upgrading-the-mini-kossel-to-duet-electronics-part-3-calibration)
  * [site en français] (http://www.blognote.info/imprimante-3d-mon-choix/)
  * [site détaillé avec photos] (http://letsmakerobots.com/content/kossel-mini-calibration)

Configuration smart controller
==============================
  * [smart controller] (http://www.reprap.org/wiki/RepRapDiscount_Smart_Controller)
  * [plan détaillé] (http://smoothieware.org/panel)


Divers
======
    * [G-code] http://reprap.org/wiki/G-code


Boutique
========

  * [imp3d-france] (http://www.imp3d-france.com/categories/4/extrudeur-et-tete-hothead)


Compilation
===========
 touch Marlin/Marlin.pde
 rm src
 make build-firmware
 ino upload -p /dev/ttyACM3 -m mega2560
 
 
 

