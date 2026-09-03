---
aliases:
  - Vadir of Arasaner
tags: []
name:
  full: Vadir of Arasaner
  title: ""
  given: Vadir
  clan: Arasaner
  aliases: []
id: deFkCGYRScXZWIcR
folder: wYO4XEaOHdLCVUM0
shortcode: vadirofarasaner
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
social:
  occupation: Patrician
  class: serf
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: human
  gender: male
  age: 39
  birthday: 681/7/7
  height:
    m: 1.75
  weight:
    kg: 123.83
  build:
    frame: light
  appearance:
    eye_color: brown
    hair_color: black
    skin_color: dark
    complexion: plain
    extra_features:
      - Obesity
hm3:
  species: human
  sunsign: hirin-nadai
  attributes:
    str: 11
    sta: 13
    dex: 7
    agl: 9
    int: 16
    aur: 10
    wil: 17
    eye: 13
    hrg: 13
    sml: 6
    voi: 8
    cml: 8
    mor: 9
  move: 9
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 54 } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 78 } }
    - { shortcode: dancing, type: skill, system: { masteryLevel: 45 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 44 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 44 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 98 } }
    - { shortcode: language, type: skill, name: "Language, Serf", system: { masteryLevel: 63 } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 39 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 27 } }
    - { shortcode: axe, type: skill, name: Handaxe (Axe), system: { masteryLevel: 72 } }
    - { shortcode: dagger, type: skill, system: { masteryLevel: 55 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 98 } }
    - { shortcode: polearm, type: skill, name: Lance (Polearm), system: { masteryLevel: 72 } }
    - { shortcode: riding, type: skill, system: { masteryLevel: 88 } }
    - { shortcode: shield, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: sword, type: skill, name: Broadsword (Sword), system: { masteryLevel: 54 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 45 } }
    - { shortcode: foraging, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: heraldry, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 24 } }
    - { shortcode: survival, type: skill, system: { masteryLevel: 77 } }
    - { shortcode: weaponcraft, type: skill, system: { masteryLevel: 22 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 5822 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: CHood, type: armorgear }
    - { shortcode: MHbk, type: armorgear }
    - { shortcode: LLeg, type: armorgear }
    - { shortcode: CShoe, type: armorgear }
    - { shortcode: LTunic, type: armorgear }
    - { shortcode: HAxe, type: weapongear }
    - { shortcode: Kni, type: weapongear }
    - { shortcode: backbagsmcanvas, type: containergear }
    - { shortcode: beltpouchl3, type: containergear }
    - { shortcode: LtCap, type: armorgear }
    - name: Scabbard, sword
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        value: 48
        weight: 1
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
    - { shortcode: str, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: end, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: dex, type: attribute, system: { scoreBase: 7 } }
    - { shortcode: agl, type: attribute, system: { scoreBase: 9 } }
    - { shortcode: per, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: snt, type: attribute, system: { scoreBase: 6 } }
    - { shortcode: cml, type: attribute, system: { scoreBase: 8 } }
    - { shortcode: aur, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: wil, type: attribute, system: { scoreBase: 17 } }
    - { shortcode: rea, type: attribute, system: { scoreBase: 16 } }
    - { shortcode: cre, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: emp, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: elo, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: mor, type: attribute, system: { scoreBase: 9 } }
    - { shortcode: voi, type: attribute, system: { scoreBase: 8 } }
    - { shortcode: archery, type: skill }
    - { shortcode: awar, type: skill, system: { masteryLevelBase: 44 } }
    - { shortcode: chrm, type: skill }
    - { shortcode: clmb, type: skill, system: { masteryLevelBase: 54 } }
    - { shortcode: cmd, type: skill }
    - { shortcode: cook, type: skill }
    - { shortcode: dnce, type: skill, system: { masteryLevelBase: 45 } }
    - { shortcode: dscr, type: skill }
    - { shortcode: draw, type: skill }
    - { shortcode: folklr, type: skill }
    - { shortcode: guil, type: skill }
    - { shortcode: init, type: skill, system: { masteryLevelBase: 98 } }
    - { shortcode: shok, type: skill }
    - { shortcode: intr, type: skill, system: { masteryLevelBase: 98 } }
    - { shortcode: jump, type: skill, system: { masteryLevelBase: 44 } }
    - { shortcode: melee, type: skill, system: { masteryLevelBase: 62 } }
    - { shortcode: dge, type: skill }
    - { shortcode: pysn, type: skill, system: { masteryLevelBase: 24 } }
    - { shortcode: ridg, type: skill, system: { masteryLevelBase: 88 } }
    - { shortcode: sing, type: skill, system: { masteryLevelBase: 27 } }
    - { shortcode: stlth, type: skill, system: { masteryLevelBase: 60 } }
    - { shortcode: srvl, type: skill, system: { masteryLevelBase: 77 } }
    - { shortcode: spirit, type: skill }
    - { shortcode: swim, type: skill }
    - { shortcode: thtcs, type: skill }
    - { shortcode: thro, type: skill, system: { masteryLevelBase: 60 } }
    - { shortcode: bflkbite, type: skill }
    - { shortcode: bflkgrab, type: skill }
    - { shortcode: bflkheadbutt, type: skill }
    - { shortcode: bflkkick, type: skill }
    - { shortcode: limbblock, type: skill }
    - { shortcode: press, type: skill }
    - { shortcode: bflkpunch, type: skill }
    - { shortcode: trip, type: skill }
    - { shortcode: sprt, type: mysticalability }
    - { shortcode: lang, type: skill, name: "Language, Serf", system: { masteryLevelBase: 63 } }
    - { shortcode: hrld, type: skill, system: { masteryLevelBase: 48 } }
    - { shortcode: wpnc, type: skill, system: { masteryLevelBase: 22 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 5822 } }
    - { shortcode: pouchbuckram, type: containergear }
    - { shortcode: CHood, type: armorgear }
    - { shortcode: MHbk, type: armorgear }
    - { shortcode: LLeg, type: armorgear }
    - { shortcode: CShoe, type: armorgear }
    - { shortcode: LTunic, type: armorgear }
    - { shortcode: HAxe, type: weapongear }
    - { shortcode: Kni, type: weapongear }
    - { shortcode: bgsmcvs, type: containergear }
    - { shortcode: beltpouchl3, type: containergear }
    - { shortcode: LtCap, type: armorgear }
    - { shortcode: scabbard, type: miscgear }
    - { shortcode: tankardpew, type: miscgear }
---

# Appearance {#appearance}

**Height**: 5' 9"
**Frame**: Light
**Weight**: 273
**Size**: 9
**Comeliness**: Plain
**Complexion**: Dark
**Hair Color**: Black
**Eye Color**: Brown
**Voice**: Unpleasant

# Dossier {#dossier}

**Age**: 39
**Birthday**: 7 Azura 681
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: 2nd child of 4
**Siblings**: FMfM
**Parentage**: Offspring
**Offspring**: Mother dead
**Estrangement**: Average
**Clanhead**: Father/Mother
**Medical**: Obesity

## Notes

Modifier to AttributesAGL of +1 (from 8) {Frame=Light}

Modifier to HairColor of -25 (from 33) {Complexion=Dark, Species=Human}

Modifier to EyeColor of +25 (from 71) {Complexion=Dark, Species=Human}

Obesity mod to Agility: -1

141lbs weight resulted in -1 strength mod.

Light frame resulted in +1 agility mod.

Modifier to StartingEquipment of +100 (from 60) {SocialClass=Serf}
