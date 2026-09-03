---
aliases:
  - Anlael of Aelin
tags: []
name:
  full: Anlael of Aelin
  title: ""
  given: Anlael
  clan: Aelin
  aliases: []
id: UddzsCAUsmWroNwb
folder: wqZxeSsm1ABX2AGx
shortcode: anlaelofaelin
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
social:
  occupation: Feudal Yeoman, Shortbow
  class: serf
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: human
  gender: female
  age: 38
  birthday: 682/6/16
  height:
    m: 1.68
  weight:
    kg: 52.62
  build:
    frame: scant
  appearance:
    eye_color: blue
    hair_color: auburn
    skin_color: medium
    complexion: average
    extra_features:
      - Ambidexterous
hm3:
  species: human
  sunsign: nadai
  attributes:
    str: 13
    sta: 10
    dex: 18
    agl: 16
    int: 12
    aur: 14
    wil: 13
    eye: 15
    hrg: 8
    sml: 9
    voi: 5
    cml: 9
    mor: 9
  move: 12
  items:
    - { shortcode: skull, type: armorlocation }
    - { shortcode: face, type: armorlocation }
    - { shortcode: neck, type: armorlocation }
    - { shortcode: lshoulder, type: armorlocation }
    - { shortcode: rshoulder, type: armorlocation }
    - { shortcode: luparm, type: armorlocation }
    - { shortcode: ruparm, type: armorlocation }
    - { shortcode: lelb, type: armorlocation }
    - { shortcode: relb, type: armorlocation }
    - { shortcode: lhand, type: armorlocation }
    - { shortcode: rhand, type: armorlocation }
    - { shortcode: thorax, type: armorlocation }
    - { shortcode: abdm, type: armorlocation }
    - { shortcode: groin, type: armorlocation }
    - { shortcode: lhip, type: armorlocation }
    - { shortcode: rhip, type: armorlocation }
    - { shortcode: lthigh, type: armorlocation }
    - { shortcode: rthigh, type: armorlocation }
    - { shortcode: lknee, type: armorlocation }
    - { shortcode: rknee, type: armorlocation }
    - { shortcode: lcalf, type: armorlocation }
    - { shortcode: rcalf, type: armorlocation }
    - { shortcode: lfoot, type: armorlocation }
    - { shortcode: rfoot, type: armorlocation }
    - { shortcode: climbing, type: skill, system: { masteryLevel: 75 } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 108 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 68 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 80 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 39 } }
    - { shortcode: language, type: skill, name: "Language, Serf", system: { masteryLevel: 80 } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 24 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 24 } }
    - { shortcode: bow, type: skill, name: Shortbow (Bow), system: { masteryLevel: 112 } }
    - { shortcode: dagger, type: skill, system: { masteryLevel: 114 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 112 } }
    - { shortcode: shield, type: skill, system: { masteryLevel: 112 } }
    - { shortcode: sword, type: skill, name: Falchion (Sword), system: { masteryLevel: 102 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 75 } }
    - { shortcode: foraging, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: heraldry, type: skill, system: { masteryLevel: 45 } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 45 } }
    - { shortcode: survival, type: skill, system: { masteryLevel: 70 } }
    - { shortcode: weaponcraft, type: skill, system: { masteryLevel: 42 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 1270 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: RByr, type: armorgear }
    - { shortcode: CvCloak, type: armorgear }
    - { shortcode: KHlfHelm, type: armorgear }
    - { shortcode: LtLeg, type: armorgear }
    - { shortcode: LLeg, type: armorgear }
    - { shortcode: CShoe, type: armorgear }
    - { shortcode: LTunic, type: armorgear }
    - { shortcode: Dgr, type: weapongear }
    - { shortcode: SBw, type: weapongear }
    - { shortcode: Kni, type: weapongear }
    - { shortcode: backbagsmcanvas, type: containergear }
    - { shortcode: tndrbx, type: miscgear }
    - { shortcode: pipesmokin, type: miscgear }
    - { shortcode: quiverlgsh, type: miscgear }
    - { shortcode: tankardwooden, type: miscgear }
sohl:
  kbcat: archetype
  archetype: 1
  body:
    structure:
      zones:
        - name: Head
          shortcode: headzone
          probWeight: 1
        - name: Arms
          shortcode: armszone
          probWeight: 4
        - name: Torso
          shortcode: torsozone
          probWeight: 4
        - name: Legs
          shortcode: legszone
          probWeight: 6
      parts:
        - name: Head
          shortcode: headpart
          bodyZoneCode: headzone
          roles:
            - vital
          canHoldItem: false
          probWeight: 1
        - name: Right Arm
          shortcode: rarmpart
          bodyZoneCode: armszone
          roles:
            - manipulator
          canHoldItem: true
          probWeight: 2
        - name: Left Arm
          shortcode: larmpart
          bodyZoneCode: armszone
          roles:
            - manipulator
          canHoldItem: true
          probWeight: 2
        - name: Torso
          shortcode: torsopart
          bodyZoneCode: torsozone
          roles:
            - core
          canHoldItem: false
          probWeight: 4
        - name: Right Leg
          shortcode: rlegpart
          bodyZoneCode: legszone
          roles:
            - locomotor
          canHoldItem: false
          probWeight: 3
        - name: Left Leg
          shortcode: llegpart
          bodyZoneCode: legszone
          roles:
            - locomotor
          canHoldItem: false
          probWeight: 3
      locations:
        - name: Skull
          shortcode: skullloc
          bodyPartCode: headpart
          bleedingSusceptibility: low
          amputability: none
          shockValue: 5
          probWeight: 500
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Left Eye
          shortcode: leyeloc
          bodyPartCode: headpart
          bleedingSusceptibility: medium
          amputability: none
          shockValue: 5
          probWeight: 15
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Right Eye
          shortcode: reyeloc
          bodyPartCode: headpart
          bleedingSusceptibility: medium
          amputability: none
          shockValue: 5
          probWeight: 15
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Nose
          shortcode: noseloc
          bodyPartCode: headpart
          bleedingSusceptibility: medium
          amputability: none
          shockValue: 5
          probWeight: 30
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Left Cheek
          shortcode: lcheekloc
          bodyPartCode: headpart
          bleedingSusceptibility: medium
          amputability: none
          shockValue: 4
          probWeight: 60
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Right Cheek
          shortcode: rcheekloc
          bodyPartCode: headpart
          bleedingSusceptibility: medium
          amputability: none
          shockValue: 4
          probWeight: 60
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Left Ear
          shortcode: learloc
          bodyPartCode: headpart
          bleedingSusceptibility: medium
          amputability: none
          shockValue: 4
          probWeight: 15
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Right Ear
          shortcode: rearloc
          bodyPartCode: headpart
          bleedingSusceptibility: medium
          amputability: none
          shockValue: 4
          probWeight: 15
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Mouth
          shortcode: mouthloc
          bodyPartCode: headpart
          bleedingSusceptibility: medium
          amputability: none
          shockValue: 4
          probWeight: 30
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Jaw
          shortcode: jawloc
          bodyPartCode: headpart
          bleedingSusceptibility: medium
          amputability: none
          shockValue: 4
          probWeight: 60
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Neck
          shortcode: neckloc
          bodyPartCode: headpart
          bleedingSusceptibility: high
          amputability: low
          shockValue: 5
          probWeight: 200
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Right Shoulder
          shortcode: rshldloc
          bodyPartCode: rarmpart
          bleedingSusceptibility: medium
          amputability: none
          shockValue: 3
          probWeight: 30
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Right Upper Arm
          shortcode: rupaloc
          bodyPartCode: rarmpart
          bleedingSusceptibility: low
          amputability: medium
          shockValue: 1
          probWeight: 30
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Right Elbow
          shortcode: relbloc
          bodyPartCode: rarmpart
          bleedingSusceptibility: low
          amputability: medium
          shockValue: 2
          probWeight: 10
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Right Forearm
          shortcode: rfraloc
          bodyPartCode: rarmpart
          bleedingSusceptibility: low
          amputability: medium
          shockValue: 1
          probWeight: 20
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Right Hand
          shortcode: rhandloc
          bodyPartCode: rarmpart
          bleedingSusceptibility: none
          amputability: high
          shockValue: 2
          probWeight: 10
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Left Shoulder
          shortcode: lshldloc
          bodyPartCode: larmpart
          bleedingSusceptibility: medium
          amputability: none
          shockValue: 3
          probWeight: 30
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Left Upper Arm
          shortcode: lupaloc
          bodyPartCode: larmpart
          bleedingSusceptibility: low
          amputability: medium
          shockValue: 1
          probWeight: 30
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Left Elbow
          shortcode: lelbloc
          bodyPartCode: larmpart
          bleedingSusceptibility: low
          amputability: medium
          shockValue: 2
          probWeight: 10
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Left Forearm
          shortcode: lfraloc
          bodyPartCode: larmpart
          bleedingSusceptibility: low
          amputability: medium
          shockValue: 1
          probWeight: 20
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Left Hand
          shortcode: lhandloc
          bodyPartCode: larmpart
          bleedingSusceptibility: none
          amputability: high
          shockValue: 2
          probWeight: 10
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Thorax
          shortcode: thrxloc
          bodyPartCode: torsopart
          bleedingSusceptibility: medium
          amputability: none
          shockValue: 4
          probWeight: 40
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Abdomen
          shortcode: abdmnloc
          bodyPartCode: torsopart
          bleedingSusceptibility: high
          amputability: none
          shockValue: 4
          probWeight: 40
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Pelvis
          shortcode: plvisloc
          bodyPartCode: torsopart
          bleedingSusceptibility: medium
          amputability: none
          shockValue: 4
          probWeight: 20
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Right Thigh
          shortcode: rthghloc
          bodyPartCode: rlegpart
          bleedingSusceptibility: medium
          amputability: low
          shockValue: 3
          probWeight: 40
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Right Knee
          shortcode: rkneeloc
          bodyPartCode: rlegpart
          bleedingSusceptibility: low
          amputability: medium
          shockValue: 2
          probWeight: 10
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Right Calf
          shortcode: rcalfloc
          bodyPartCode: rlegpart
          bleedingSusceptibility: low
          amputability: medium
          shockValue: 1
          probWeight: 30
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Right Foot
          shortcode: rfootloc
          bodyPartCode: rlegpart
          bleedingSusceptibility: none
          amputability: medium
          shockValue: 2
          probWeight: 20
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Left Thigh
          shortcode: lthghloc
          bodyPartCode: llegpart
          bleedingSusceptibility: medium
          amputability: low
          shockValue: 3
          probWeight: 40
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Left Knee
          shortcode: lkneeloc
          bodyPartCode: llegpart
          bleedingSusceptibility: low
          amputability: medium
          shockValue: 2
          probWeight: 10
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Left Calf
          shortcode: lcalfloc
          bodyPartCode: llegpart
          bleedingSusceptibility: low
          amputability: medium
          shockValue: 1
          probWeight: 30
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
        - name: Left Foot
          shortcode: lfootloc
          bodyPartCode: llegpart
          bleedingSusceptibility: none
          amputability: medium
          shockValue: 2
          probWeight: 20
          protectionBase:
            blunt: 0
            edged: 0
            piercing: 0
            fire: 0
    weight:
      base: null
      calc: (9 * str) + 50
    reachBase: 0
    bodyScaleBase: 1
    personalFatigue: enc + 5
  currentMoveMedium: terrestrial
  movementProfiles:
    - medium: terrestrial
      feetPerRound: 50
      leaguesPerWatch: 5
      encumbrance: floor(wt/4)
      strMod: -5 * floor((str - 10) / 2)
      disabled: false
  defaultCombatGroup: null
  items:
    - { shortcode: str, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: end, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: dex, type: attribute, system: { scoreBase: 18 } }
    - { shortcode: agl, type: attribute, system: { scoreBase: 16 } }
    - { shortcode: per, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: snt, type: attribute, system: { scoreBase: 9 } }
    - { shortcode: cml, type: attribute, system: { scoreBase: 9 } }
    - { shortcode: aur, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: wil, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: rea, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: cre, type: attribute, system: { scoreBase: 5 } }
    - { shortcode: emp, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: elo, type: attribute, system: { scoreBase: 8 } }
    - { shortcode: mor, type: attribute, system: { scoreBase: 9 } }
    - { shortcode: voi, type: attribute, system: { scoreBase: 5 } }
    - { shortcode: archery, type: skill, name: Shortbow (Bow), system: { masteryLevelBase: 112 } }
    - { shortcode: awar, type: skill, system: { masteryLevelBase: 60 } }
    - { shortcode: chrm, type: skill }
    - { shortcode: clmb, type: skill, system: { masteryLevelBase: 75 } }
    - { shortcode: cmd, type: skill }
    - { shortcode: cook, type: skill }
    - { shortcode: dnce, type: skill }
    - { shortcode: dscr, type: skill }
    - { shortcode: draw, type: skill }
    - { shortcode: folklr, type: skill }
    - { shortcode: guil, type: skill }
    - { shortcode: init, type: skill, system: { masteryLevelBase: 112 } }
    - { shortcode: shok, type: skill }
    - { shortcode: intr, type: skill, system: { masteryLevelBase: 39 } }
    - { shortcode: jump, type: skill, system: { masteryLevelBase: 68 } }
    - { shortcode: melee, type: skill, system: { masteryLevelBase: 109 } }
    - { shortcode: dge, type: skill }
    - { shortcode: pysn, type: skill, system: { masteryLevelBase: 45 } }
    - { shortcode: ridg, type: skill }
    - { shortcode: sing, type: skill, system: { masteryLevelBase: 24 } }
    - { shortcode: stlth, type: skill, system: { masteryLevelBase: 60 } }
    - { shortcode: srvl, type: skill, system: { masteryLevelBase: 70 } }
    - { shortcode: spirit, type: skill }
    - { shortcode: swim, type: skill }
    - { shortcode: thtcs, type: skill }
    - { shortcode: thro, type: skill, system: { masteryLevelBase: 80 } }
    - { shortcode: bflkbite, type: skill }
    - { shortcode: bflkgrab, type: skill }
    - { shortcode: bflkheadbutt, type: skill }
    - { shortcode: bflkkick, type: skill }
    - { shortcode: limbblock, type: skill }
    - { shortcode: press, type: skill }
    - { shortcode: bflkpunch, type: skill }
    - { shortcode: trip, type: skill }
    - { shortcode: sprt, type: mysticalability }
    - { shortcode: lang, type: skill, name: "Language, Serf", system: { masteryLevelBase: 80 } }
    - { shortcode: hrld, type: skill, system: { masteryLevelBase: 45 } }
    - { shortcode: wpnc, type: skill, system: { masteryLevelBase: 42 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 1270 } }
    - { shortcode: pouchbuckram, type: containergear }
    - { shortcode: RByr, type: armorgear }
    - { shortcode: CvCloak, type: armorgear }
    - { shortcode: KHlfHelm, type: armorgear }
    - { shortcode: LtTrsr, type: armorgear }
    - { shortcode: LLeg, type: armorgear }
    - { shortcode: CShoe, type: armorgear }
    - { shortcode: LTunic, type: armorgear }
    - { shortcode: Dgr, type: weapongear }
    - { shortcode: Kni, type: weapongear }
    - { shortcode: bgsmcvs, type: containergear }
    - { shortcode: tndrbx, type: miscgear }
    - { shortcode: pipesmokin, type: miscgear }
    - { shortcode: quiverlgsh, type: containergear }
    - { shortcode: tankardpew, type: miscgear }
---

# Appearance {#appearance}

**Height**: 5' 6"
**Frame**: Scant
**Weight**: 116
**Size**: 5
**Comeliness**: Average
**Complexion**: Medium
**Hair Color**: Auburn
**Eye Color**: Blue
**Voice**: Unpleasant

# Dossier {#dossier}

**Age**: 38
**Birthday**: 16 Agrazhar 682
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: 3rd child of 4
**Siblings**: FFFM
**Parentage**: Offspring
**Offspring**: Both parents alive and living together
**Estrangement**: Outcast
**Clanhead**: Aunt/Uncle
**Medical**: Ambidexterous

## Notes

Modifier to Frame of -3 (from 6) {Sex=Female, Species=Human}

Modifier to AttributesAGL of +2 (from 12) {Frame=Scant}

Modifier to AttributesAUR of +2 (from 12) {Sex=Female, Species=Human}

Ambidexterous mod to Dexterity: +3

116lbs weight resulted in -2 strength mod.

Scant frame resulted in +2 agility mod.

Modifier to StartingEquipment of +100 (from 11) {SocialClass=Serf}
