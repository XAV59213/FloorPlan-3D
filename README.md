# Plan-3D
Créer son FloorPlan 3D
![SALON2](https://github.com/user-attachments/assets/1ee42076-7191-4875-bdd9-020f74329f52)
![DEMO](https://github.com/user-attachments/assets/694e8725-9414-497e-859f-d945d662e27f)
type: panel
path: 3d2
title: 3D2
cards:
  - type: picture-elements
    elements:
      - type: image
        style:
          left: 50%
          top: 50%
          width: 100%
        entity: switch.inter_chambre_fille_switch_1
        state_image:
          "on": /local/images/naomie2.png
          "off": /local/images/transparent2.png
        title: ECLnaomie
      - type: image
        style:
          left: 50%
          top: 50%
          width: 100%
        entity: switch.lampe_exterieur_cuisine_switch_1
        state_image:
          "on": /local/images/EXTERIEURCUISINE2.png
          "off": /local/images/transparent2.png
        title: ECLportecuisine
      - type: image
        style:
          left: 50%
          top: 50%
          width: 100%
        entity: switch.inter_chambre_fille_switch_1
        state_image:
          "on": /local/images/anais2.png
          "off": /local/images/transparent2.png
        title: ECLANAIS
      - type: image
        style:
          left: 50%
          top: 50%
          width: 100%
        entity: light.multiprise_passe_plat_mss425fc_bebe
        state_image:
          "on": /local/images/bebe3.png
          "off": /local/images/transparent2.png
        title: ECLBEBE
      - type: image
        style:
          left: 50%
          top: 50%
          width: 100%
        entity: light.imposte_cuisine_couloir
        state_image:
          "on": /local/images/IMPOSTECUISINE2.png
          "off": /local/images/transparent2.png
        title: ECLimpostecuisinecouloir
      - type: image
        style:
          left: 50%
          top: 50%
          width: 100%
        entity: switch.interrupteur_depart_arrive_switch_2
        state_image:
          "on": /local/images/DROIT50.png
          "off": /local/images/transparent2.png
        title: ECLimpostedroit
      - type: image
        style:
          left: 50%
          top: 50%
          width: 100%
        entity: light.passe_plat_cuisine_gauche
        state_image:
          "on": /local/images/gauche50.png
          "off": /local/images/transparent2.png
        title: ECLimpostegauche
      - type: image
        style:
          left: 50%
          top: 50%
          width: 100%
        entity: light.porte_entree_terrasse_switch_1
        state_image:
          "on": /local/images/PORTETERRASSEEXT2.png
          "off": /local/images/transparent2.png
        title: ECLPORTETERRASE
      - type: image
        style:
          left: 50%
          top: 50%
          width: 100%
        entity: light.inter_couloir_switch_1
        state_image:
          "on": /local/images/couloir123.png
          "off": /local/images/transparent2.png
        title: ECLCOULOIR
      - type: image
        style:
          left: 50%
          top: 50%
          width: 100%
        entity: switch.interrupteur_lustre_switch_1
        state_image:
          "on": /local/images/ECLLOULOU2.png
          "off": /local/images/transparent2.png
        title: ECLLOULOU
      - type: image
        style:
          left: 50%
          top: 50%
          width: 100%
        entity: switch.eclairage_lustre_papa_switch_1
        state_image:
          "on": /local/images/PAPA3.png
          "off": /local/images/transparent2.png
        title: ECLPAPA
      - type: image
        style:
          left: 50%
          top: 50%
          width: 100%
        entity: light.eclairage_lit_papa
        state_image:
          "on": /local/images/LITPAPA3.png
          "off": /local/images/transparent2.png
        title: ECLLITPAPA
      - type: image
        style:
          left: 50%
          top: 50%
          width: 100%
        entity: light.eclairage_lit_mama
        state_image:
          "on": /local/images/LITMAMAN3.png
          "off": /local/images/transparent2.png
        title: ECLLITMAMAN
      - type: image
        style:
          left: 50%
          top: 50%
          width: 100%
        entity: light.porte_entree_terrasse_switch_1
        state_image:
          "on": /local/images/TERRASSEGAUCHE2.png
          "off": /local/images/transparent2.png
        title: ECLEXTGAUCHE
      - type: image
        style:
          left: 50%
          top: 50%
          width: 100%
        entity: light.eclairage_terrasse_switch_1
        state_image:
          "on": /local/images/TERRASSEDROIT2.png
          "off": /local/images/transparent2.png
        title: ECLEXTDROIT
      - type: image
        style:
          left: 50%
          top: 50%
          width: 100%
        entity: switch.multi_prise_cuisine_mss425f_cafetiere
        state_image:
          "on": /local/images/cafetiere2.png
          "off": /local/images/transparent2.png
        title: ECLCAFETIERE
      - type: state-badge
        entity: camera.exterieur01
        style:
          left: 3%
          top: 38%
      - type: state-badge
        entity: camera.exterieur02
        style:
          left: 3%
          top: 60%
      - type: state-icon
        entity: camera.smart_doorbell
        style:
          left: 20%
          top: 15%
      - type: state-badge
        entity: camera.camera_salon_2
        style:
          left: 13%
          top: 67%
      - type: state-badge
        entity: camera.exterieur03
        style:
          left: 6%
          top: 70%
      - type: state-icon
        entity: climate.radiateur_fille
        style:
          left: 86%
          top: 42%
      - type: state-icon
        entity: climate.radiateur_papa
        style:
          left: 47%
          top: 78%
      - type: state-icon
        entity: climate.radiateur_salon
        style:
          left: 18%
          top: 53%
      - type: state-icon
        entity: climate.radiateur_garcon
        style:
          left: 46%
          top: 47%
      - type: state-badge
        entity: alarm_control_panel.systeme_d_alarme
        style:
          left: 3%
          top: 6%
      - type: state-badge
        entity: sensor.temperature_garcon_temperature
        style:
          left: 65%
          top: 40%
      - type: state-badge
        entity: sensor.temperature_fille_temperature
        style:
          left: 80%
          top: 20%
      - type: state-badge
        entity: sensor.temperature_salon_temperature
        style:
          left: 18%
          top: 47%
      - type: state-badge
        entity: sensor.chambre_papa_temperature
        style:
          left: 45%
          top: 62%
      - type: state-badge
        entity: sensor.bermerain_temperature_2
        style:
          left: 3%
          top: 15%
      - type: state-badge
        entity: person.papa
        style:
          left: 80%
          top: 5%
          width: 50%
      - type: state-badge
        entity: person.maman
        style:
          left: 84%
          top: 5%
          width: 50%
      - type: state-badge
        entity: person.maman
        style:
          left: 84%
          top: 5%
          width: 50%
      - type: state-badge
        entity: person.naomie
        style:
          left: 88%
          top: 5%
          width: 50%
      - type: state-badge
        entity: person.xavier
        style:
          left: 92%
          top: 5%
          width: 50%
      - type: state-badge
        entity: person.anais
        style:
          left: 96%
          top: 5%
          width: 50%
      - type: state-badge
        entity: person.elon
        style:
          left: 100%
          top: 5%
          width: 50%
      - type: state-badge
        entity: person.koleos
        style:
          left: 104%
          top: 5%
          width: 50%
      - type: state-badge
        entity: person.trophie
        style:
          left: 108%
          top: 5%
          width: 50%
      - type: state-badge
        entity: climate.thermostat_salon
        style:
          left: 30%
          top: 6%
          width: 50%
      - type: state-badge
        entity: sensor.temperature_sdb_temperature
        style:
          left: 49%
          top: 20%
      - type: state-icon
        entity: climate.radiateur_sdb
        style:
          left: 50%
          top: 24%
    image: /local/images/noir.png
