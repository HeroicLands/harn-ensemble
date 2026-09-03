---
aliases:
  - Lasyn of Ael
tags: []
name:
  full: Lasyn of Ael
  title: ""
  given: Lasyn
  clan: Ael
  aliases: []
id: 6smpeAorEzZ8ARiu
folder: wqZxeSsm1ABX2AGx
shortcode: lasynofael
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
social:
  occupation: Sage/Tutor
  class: noble
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: human
  gender: female
  age: 31
  birthday: 689/1/20
  height:
    m: 1.68
  weight:
    kg: 65.77
  build:
    frame: medium
  appearance:
    eye_color: blue
    hair_color: brown
    skin_color: swarthy
    complexion: average
    extra_features:
      - Left-Handed
hm3:
  species: human
  sunsign: ulandus
  attributes:
    str: 12
    sta: 12
    dex: 14
    agl: 8
    int: 14
    aur: 17
    wil: 7
    eye: 12
    hrg: 11
    sml: 9
    voi: 16
    cml: 9
    mor: 14
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 88 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 24 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 50 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: language, type: skill, name: Language(Ivinian), system: { masteryLevel: 36 } }
    - { shortcode: language, type: skill, name: "Language, Noble", system: { masteryLevel: 94 } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 39 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 42 } }
    - { shortcode: script, type: skill, name: Script(Lakaise), system: { masteryLevel: 96 } }
    - { shortcode: script, type: skill, name: Script(Script(Runic)), system: { masteryLevel: 109 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 35 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: folklore, type: skill, system: { masteryLevel: 84 } }
    - { shortcode: mathematics, type: skill, system: { masteryLevel: 55 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 1390 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: LtCBoot, type: armorgear }
    - { shortcode: WClk, type: armorgear }
    - { shortcode: CHood, type: armorgear }
    - { shortcode: WLeg, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: WTunic, type: armorgear }
    - { shortcode: Dgr, type: weapongear }
    - { shortcode: WCap, type: armorgear }
    - { shortcode: pipesmokin, type: miscgear }
    - { shortcode: writingkitportable, type: miscgear }
    - { shortcode: tankardpew, type: miscgear }
    - name: Textbook
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        value: 150
        weight: 3
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
    - { shortcode: str, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: end, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: dex, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: agl, type: attribute, system: { scoreBase: 8 } }
    - { shortcode: per, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: snt, type: attribute, system: { scoreBase: 9 } }
    - { shortcode: cml, type: attribute, system: { scoreBase: 9 } }
    - { shortcode: aur, type: attribute, system: { scoreBase: 17 } }
    - { shortcode: wil, type: attribute, system: { scoreBase: 7 } }
    - { shortcode: rea, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: cre, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: emp, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: elo, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: mor, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: voi, type: attribute, system: { scoreBase: 16 } }
    - { shortcode: archery, type: skill }
    - { shortcode: awar, type: skill, system: { masteryLevelBase: 50 } }
    - { shortcode: chrm, type: skill }
    - { shortcode: clmb, type: skill, system: { masteryLevelBase: 52 } }
    - { shortcode: cmd, type: skill }
    - { shortcode: cook, type: skill }
    - { shortcode: dnce, type: skill }
    - { shortcode: dscr, type: skill }
    - { shortcode: draw, type: skill }
    - { shortcode: folklr, type: skill, system: { masteryLevelBase: 84 } }
    - { shortcode: guil, type: skill }
    - { shortcode: init, type: skill, system: { masteryLevelBase: 35 } }
    - { shortcode: shok, type: skill }
    - { shortcode: intr, type: skill, system: { masteryLevelBase: 36 } }
    - { shortcode: jump, type: skill, system: { masteryLevelBase: 36 } }
    - { shortcode: melee, type: skill }
    - { shortcode: dge, type: skill }
    - { shortcode: pysn, type: skill }
    - { shortcode: ridg, type: skill }
    - { shortcode: sing, type: skill, system: { masteryLevelBase: 42 } }
    - { shortcode: stlth, type: skill, system: { masteryLevelBase: 24 } }
    - { shortcode: srvl, type: skill }
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
    - { shortcode: lang, type: skill, name: "Language, Noble", system: { masteryLevelBase: 94 } }
    - shortcode: script
      type: skill
      name: Script(Script(Runic))
      system:
        masteryLevelBase: 109
    - { shortcode: math, type: skill, system: { masteryLevelBase: 55 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 1390 } }
    - { shortcode: pouchbuckram, type: containergear }
    - { shortcode: LtCBoot, type: armorgear }
    - { shortcode: WClk, type: armorgear }
    - { shortcode: CHood, type: armorgear }
    - { shortcode: WLeg, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: WTunic, type: armorgear }
    - { shortcode: Dgr, type: weapongear }
    - { shortcode: WCap, type: armorgear }
    - { shortcode: pipesmokin, type: miscgear }
    - { shortcode: scribekit, type: miscgear }
    - { shortcode: tankardpew, type: miscgear }
---

# Appearance {#appearance}

**Height**: 5' 6"
**Frame**: Medium
**Weight**: 145
**Size**: 6
**Comeliness**: Average
**Complexion**: Swarthy
**Hair Color**: Brown
**Eye Color**: Blue
**Voice**: Excellent

# Dossier {#dossier}

**Age**: 31
**Birthday**: 20 Nuzyael 689
**Culture**: Feudal
**Social Class**: Noble
**Sibling Rank**: 5th child of 7
**Siblings**: ffMfFFm
**Parentage**: Fostered
**Estrangement**: Average
**Clanhead**: Father's Cousin
**Medical**: Left-Handed

## Notes

Modifier to Frame of -3 (from 15) {Sex=Female, Species=Human}

Modifier to AttributesAUR of +2 (from 15) {Sex=Female, Species=Human}

Noble Blood results in +2 inches in height.

Modifier to EyeColor of +15 (from 22) {Complexion=Swarthy, Species=Human}

Left-Handed mod to Dexterity: +2

145lbs weight resulted in -1 strength mod.

Modifier to StartingEquipment of +400 (from 78) {SocialClass=Noble}
