---
aliases:
  - Amlugorthuiredheluin of Arannachafin
tags: []
name:
  full: Amlugorthuiredheluin of Arannachafin
  title: ""
  given: Amlugorthuiredheluin
  clan: Arannachafin
  aliases: []
id: ZMHA0ifEfrdnzwxs
folder: wqZxeSsm1ABX2AGx
shortcode: amlugorthuiredheluinofarannachafin
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
social:
  occupation: Sindarin Ranger, Light
  class: unguilded
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: sindarin
  gender: female
  age: 307
  birthday: 413/6/14
  height:
    m: 1.8
  weight:
    kg: 74.84
  build:
    frame: medium
  appearance:
    eye_color: grey
    hair_color: blonde
    skin_color: fair
    complexion: attractive
    extra_features:
      - Birthmarks
hm3:
  species: sindarin
  sunsign: nadai
  attributes:
    str: 18
    sta: 11
    dex: 12
    agl: 19
    int: 10
    aur: 16
    wil: 11
    eye: 19
    hrg: 18
    sml: 13
    voi: 15
    cml: 15
    mor: 11
  move: 15
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 112 } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 104 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 100 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 68 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 80 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 36 } }
    - shortcode: language
      type: skill
      name: Language, Unguilded
      system:
        masteryLevel: 86
    - { shortcode: oratory, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 72 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 80 } }
    - { shortcode: bow, type: skill, name: Heartbow (Bow), system: { masteryLevel: 119 } }
    - { shortcode: dagger, type: skill, system: { masteryLevel: 112 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 104 } }
    - { shortcode: shield, type: skill, system: { masteryLevel: 84 } }
    - { shortcode: sword, type: skill, name: Longknife (Sword), system: { masteryLevel: 90 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 80 } }
    - { shortcode: foraging, type: skill, system: { masteryLevel: 66 } }
    - { shortcode: heraldry, type: skill, system: { masteryLevel: 28 } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: survival, type: skill, system: { masteryLevel: 78 } }
    - { shortcode: weaponcraft, type: skill, system: { masteryLevel: 26 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 1994 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: RClk, type: armorgear }
    - { shortcode: SgClk, type: armorgear }
    - { shortcode: SgLeg, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: LtTunic, type: armorgear }
    - { shortcode: SgTunic, type: armorgear }
    - { shortcode: Dgr, type: weapongear }
    - { shortcode: HBw, type: weapongear }
    - name: Spoon of Yavari
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        weight: 1
        value: 0
    - name: Anklet, Silver
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        value: 120
        weight: 0.125
    - { shortcode: tndrbx, type: miscgear }
    - { shortcode: LtCap, type: armorgear }
    - { shortcode: LtLeg, type: armorgear }
    - { shortcode: spoonwooden, type: miscgear }
    - { shortcode: tankardwooden, type: miscgear }
    - { shortcode: waterskinsm, type: miscgear }
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
    - { shortcode: str, type: attribute, system: { scoreBase: 18 } }
    - { shortcode: end, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: dex, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: agl, type: attribute, system: { scoreBase: 18 } }
    - { shortcode: per, type: attribute, system: { scoreBase: 18 } }
    - { shortcode: snt, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: cml, type: attribute, system: { scoreBase: 15 } }
    - { shortcode: aur, type: attribute, system: { scoreBase: 16 } }
    - { shortcode: wil, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: rea, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: cre, type: attribute, system: { scoreBase: 18 } }
    - { shortcode: emp, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: elo, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: mor, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: voi, type: attribute, system: { scoreBase: 15 } }
    - { shortcode: archery, type: skill, name: Heartbow (Bow), system: { masteryLevelBase: 119 } }
    - { shortcode: awar, type: skill, system: { masteryLevelBase: 80 } }
    - { shortcode: chrm, type: skill }
    - { shortcode: clmb, type: skill, system: { masteryLevelBase: 112 } }
    - { shortcode: cmd, type: skill }
    - { shortcode: cook, type: skill }
    - { shortcode: dnce, type: skill }
    - { shortcode: dscr, type: skill }
    - { shortcode: draw, type: skill }
    - { shortcode: folklr, type: skill }
    - { shortcode: guil, type: skill }
    - { shortcode: init, type: skill, system: { masteryLevelBase: 104 } }
    - { shortcode: shok, type: skill }
    - { shortcode: intr, type: skill, system: { masteryLevelBase: 36 } }
    - { shortcode: jump, type: skill, system: { masteryLevelBase: 100 } }
    - { shortcode: melee, type: skill, system: { masteryLevelBase: 95 } }
    - { shortcode: dge, type: skill }
    - { shortcode: pysn, type: skill, system: { masteryLevelBase: 52 } }
    - { shortcode: ridg, type: skill }
    - { shortcode: sing, type: skill, system: { masteryLevelBase: 80 } }
    - { shortcode: stlth, type: skill, system: { masteryLevelBase: 48 } }
    - { shortcode: srvl, type: skill, system: { masteryLevelBase: 78 } }
    - { shortcode: spirit, type: skill }
    - { shortcode: swim, type: skill }
    - { shortcode: thtcs, type: skill }
    - { shortcode: thro, type: skill, system: { masteryLevelBase: 68 } }
    - { shortcode: bflkbite, type: skill }
    - { shortcode: bflkgrab, type: skill }
    - { shortcode: bflkheadbutt, type: skill }
    - { shortcode: bflkkick, type: skill }
    - { shortcode: limbblock, type: skill }
    - { shortcode: press, type: skill }
    - { shortcode: bflkpunch, type: skill }
    - { shortcode: trip, type: skill }
    - { shortcode: sprt, type: mysticalability }
    - shortcode: lang
      type: skill
      name: Language, Unguilded
      system:
        masteryLevelBase: 86
    - { shortcode: hrld, type: skill, system: { masteryLevelBase: 28 } }
    - { shortcode: wpnc, type: skill, system: { masteryLevelBase: 26 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 1994 } }
    - { shortcode: pouchbuckram, type: containergear }
    - { shortcode: RClk, type: armorgear }
    - { shortcode: SgClk, type: armorgear }
    - { shortcode: SgLeg, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: LtTunic, type: armorgear }
    - { shortcode: SgTunic, type: armorgear }
    - { shortcode: Dgr, type: weapongear }
    - { name: Spoon of Yavari, type: miscgear, system: { value: 0, weight: 1 } }
    - { shortcode: ankletsilver, type: miscgear }
    - { shortcode: tndrbx, type: miscgear }
    - { shortcode: LtCap, type: armorgear }
    - { shortcode: LtTrsr, type: armorgear }
    - { shortcode: spoonpewte, type: miscgear }
    - { shortcode: tankardpew, type: miscgear }
    - { shortcode: wtrskin, type: containergear }
---

# Appearance {#appearance}

**Height**: 5' 11"
**Frame**: Medium
**Weight**: 165
**Size**: 6
**Comeliness**: Attractive
**Complexion**: Fair
**Hair Color**: Blond
**Eye Color**: Grey
**Voice**: Pleasant

# Dossier {#dossier}

**Age**: 307
**Birthday**: 14 Agrazhar 413
**Culture**: Feudal
**Social Class**: Unguilded
**Sibling Rank**: 2nd child of 4
**Siblings**: MFMF
**Parentage**: Offspring
**Offspring**: Both parents alive and living together
**Estrangement**: Unpopular
**Clanhead**: Father/Mother
**Medical**: Birthmarks

## Notes

Modifier to Frame of -2 (from 11) {Species=Sindarin}

Modifier to AttributesSTR of +1 (from 16) {Species=Sindarin}

Modifier to AttributesSTA of +1 (from 10) {Species=Sindarin}

Modifier to AttributesDEX of +2 (from 10) {Species=Sindarin}

Modifier to AttributesAGL of +2 (from 17) {Species=Sindarin}

Modifier to AttributesEYE of +2 (from 17) {Species=Sindarin}

Modifier to AttributesHGR of +2 (from 16) {Species=Sindarin}

Modifier to AttributesSML of +3 (from 10) {Species=Sindarin}

Modifier to AttributesVOI of +2 (from 13) {Species=Sindarin}

Modifier to AttributesCOM of +1 (from 16) {Species=Sindarin}

Modifier to AttributesAUR of +4 (from 12) {Species=Sindarin}

Modifier to AttributesMOR of +3 (from 8) {Species=Sindarin}

Modifier to SiblingRank of -20 (from 50) {Species=Sindarin}

Birthmarks mod to Comeliness: -2

165lbs weight resulted in +1 strength mod.

Modifier to StartingEquipment of +200 (from 76) {SocialClass=Unguilded}
