---
aliases:
  - Merelyn of Dythias
tags: []
name:
  full: Merelyn of Dythias
  title: ""
  given: Merelyn
  clan: Dythias
  aliases: []
id: i9AtrTBRjsDCWnxE
folder: GNynVWgIrKPK50Ca
shortcode: merelynofdythias
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
social:
  occupation: Alchemist
  class: unguilded
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: human
  gender: female
  age: 29
  birthday: 691/10/5
  height:
    m: 1.83
  weight:
    kg: 69.4
  build:
    frame: light
  appearance:
    eye_color: brown
    hair_color: brown
    skin_color: dark
    complexion: average
    extra_features:
      - Monochromasia
hm3:
  species: human
  sunsign: skorus
  attributes:
    str: 15
    sta: 16
    dex: 12
    agl: 9
    int: 11
    aur: 13
    wil: 7
    eye: 12
    hrg: 10
    sml: 14
    voi: 14
    cml: 9
    mor: 8
  move: 11
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 72 } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 44 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 32 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 65 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 33 } }
    - shortcode: language
      type: skill
      name: Language, Unguilded
      system:
        masteryLevel: 70
    - { shortcode: oratory, type: skill, system: { masteryLevel: 22 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 33 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: script, type: skill, name: Script(Lakaise), system: { masteryLevel: 92 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 28 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: alchemy, type: skill, system: { masteryLevel: 105 } }
    - { shortcode: herblore, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: mathematics, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: mining, type: skill, system: { masteryLevel: 24 } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 24 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 198 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: SgLeg, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: SgTunic, type: armorgear }
    - { shortcode: Kni, type: weapongear }
    - { shortcode: backbagsmcanvas, type: containergear }
    - { shortcode: tndrbx, type: miscgear }
    - name: Notebook
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        value: 50
        weight: 2
    - name: Scale/balance
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        value: 72
        weight: 5
    - { shortcode: spoonwooden, type: miscgear }
    - { shortcode: tankardwooden, type: miscgear }
    - { shortcode: tndrbx, type: miscgear }
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
    - { shortcode: str, type: attribute, system: { scoreBase: 15 } }
    - { shortcode: end, type: attribute, system: { scoreBase: 16 } }
    - { shortcode: dex, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: agl, type: attribute, system: { scoreBase: 9 } }
    - { shortcode: per, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: snt, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: cml, type: attribute, system: { scoreBase: 9 } }
    - { shortcode: aur, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: wil, type: attribute, system: { scoreBase: 7 } }
    - { shortcode: rea, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: cre, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: emp, type: attribute, system: { scoreBase: 9 } }
    - { shortcode: elo, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: mor, type: attribute, system: { scoreBase: 8 } }
    - { shortcode: voi, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: archery, type: skill }
    - { shortcode: awar, type: skill, system: { masteryLevelBase: 60 } }
    - { shortcode: chrm, type: skill }
    - { shortcode: clmb, type: skill, system: { masteryLevelBase: 72 } }
    - { shortcode: cmd, type: skill }
    - { shortcode: cook, type: skill }
    - { shortcode: dnce, type: skill }
    - { shortcode: dscr, type: skill }
    - { shortcode: draw, type: skill }
    - { shortcode: folklr, type: skill }
    - { shortcode: guil, type: skill }
    - { shortcode: init, type: skill, system: { masteryLevelBase: 28 } }
    - { shortcode: shok, type: skill }
    - { shortcode: intr, type: skill, system: { masteryLevelBase: 33 } }
    - { shortcode: jump, type: skill, system: { masteryLevelBase: 44 } }
    - { shortcode: melee, type: skill }
    - { shortcode: dge, type: skill }
    - { shortcode: pysn, type: skill, system: { masteryLevelBase: 24 } }
    - { shortcode: ridg, type: skill }
    - { shortcode: sing, type: skill, system: { masteryLevelBase: 36 } }
    - { shortcode: stlth, type: skill, system: { masteryLevelBase: 32 } }
    - { shortcode: srvl, type: skill }
    - { shortcode: spirit, type: skill }
    - { shortcode: swim, type: skill }
    - { shortcode: thtcs, type: skill }
    - { shortcode: thro, type: skill, system: { masteryLevelBase: 65 } }
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
        masteryLevelBase: 70
    - { shortcode: script, type: skill, name: Script(Lakaise), system: { masteryLevelBase: 92 } }
    - { shortcode: alch, type: mysticalability, system: { masteryLevelBase: 105 } }
    - { shortcode: herb, type: skill, system: { masteryLevelBase: 36 } }
    - { shortcode: math, type: skill, system: { masteryLevelBase: 30 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 198 } }
    - { shortcode: pouchbuckram, type: containergear }
    - { shortcode: SgLeg, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: SgTunic, type: armorgear }
    - { shortcode: Kni, type: weapongear }
    - { shortcode: bgsmcvs, type: containergear }
    - { shortcode: tndrbx, type: miscgear }
    - { shortcode: booktrvl, type: miscgear }
    - { shortcode: spoonpewte, type: miscgear }
    - { shortcode: tankardpew, type: miscgear }
    - { shortcode: wtrskin, type: containergear }
---

# Appearance {#appearance}

**Height**: 6' 0"
**Frame**: Light
**Weight**: 153
**Size**: 6
**Comeliness**: Average
**Complexion**: Dark
**Hair Color**: Brown
**Eye Color**: Brown
**Voice**: Pleasant

# Dossier {#dossier}

**Age**: 29
**Birthday**: 5 Ilvin 691
**Culture**: Feudal
**Social Class**: Unguilded
**Sibling Rank**: Eldest of 8
**Siblings**: FMmMMmMF
**Parentage**: Offspring
**Offspring**: Mother dead, father remarried
**Estrangement**: Popular
**Clanhead**: Aunt/Uncle
**Medical**: Monochromasia

## Notes

Modifier to Frame of -3 (from 9) {Sex=Female, Species=Human}

Modifier to AttributesAGL of +1 (from 7) {Frame=Light}

Modifier to AttributesAUR of +2 (from 11) {Sex=Female, Species=Human}

Eldest gets +5 on estrangement roll.

Modifier to HairColor of -25 (from 47) {Complexion=Dark, Species=Human}

Modifier to EyeColor of +25 (from 76) {Complexion=Dark, Species=Human}

Monochromasia mod to Eyesight: -1

Light frame resulted in +1 agility mod.

Modifier to StartingEquipment of +200 (from 100) {SocialClass=Unguilded}
