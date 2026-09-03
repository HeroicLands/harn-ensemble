---
aliases:
  - Lam of Provin
tags: []
name:
  full: Lam of Provin
  title: ""
  given: Lam
  clan: Provin
  aliases: []
id: DkuFwjjxc2gNVku6
folder: wqZxeSsm1ABX2AGx
shortcode: lamofprovin
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
social:
  occupation: Imperial Legionnaire, Shortbow
  class: serf
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: human
  gender: male
  age: 20
  birthday: 700/3/2
  height:
    m: 1.75
  weight:
    kg: 107.5
  build:
    frame: scant
  appearance:
    eye_color: violet
    hair_color: brown
    skin_color: fair
    complexion: attractive
    extra_features:
      - Deformed/Missing Arm
hm3:
  species: human
  sunsign: aralius-feniri
  attributes:
    str: 12
    sta: 10
    dex: 14
    agl: 17
    int: 7
    aur: 10
    wil: 12
    eye: 11
    hrg: 11
    sml: 12
    voi: 10
    cml: 14
    mor: 12
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 64 } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 55 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 39 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 44 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 27 } }
    - { shortcode: language, type: skill, name: "Language, Serf", system: { masteryLevel: 59 } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 27 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: bow, type: skill, name: Shortbow (Bow), system: { masteryLevel: 72 } }
    - { shortcode: dagger, type: skill, system: { masteryLevel: 65 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 78 } }
    - { shortcode: shield, type: skill, system: { masteryLevel: 65 } }
    - { shortcode: sword, type: skill, name: Shortsword (Sword), system: { masteryLevel: 65 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: foraging, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: heraldry, type: skill, system: { masteryLevel: 24 } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 20 } }
    - { shortcode: survival, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: weaponcraft, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 0 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: CvCloak, type: armorgear }
    - { shortcode: QGmb, type: armorgear }
    - { shortcode: LtLeg, type: armorgear }
    - { shortcode: LLeg, type: armorgear }
    - { shortcode: CShoe, type: armorgear }
    - { shortcode: LTunic, type: armorgear }
    - { shortcode: Kni, type: weapongear }
    - { shortcode: SBw, type: weapongear }
    - name: Arrow, dozen
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        weight: 1
    - { shortcode: backbagsmcanvas, type: containergear }
    - { shortcode: beltpouchl3, type: containergear }
    - name: "Debt to Money Lender: Dickon of Charadas for 133d"
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        weight: 1
    - { shortcode: tndrbx, type: miscgear }
    - { shortcode: LtCap, type: armorgear }
    - { shortcode: quiverlgsh, type: miscgear }
    - { shortcode: Bklr, type: weapongear }
    - { shortcode: spoonwooden, type: miscgear }
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
    - { shortcode: str, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: end, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: dex, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: agl, type: attribute, system: { scoreBase: 17 } }
    - { shortcode: per, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: snt, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: cml, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: aur, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: wil, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: rea, type: attribute, system: { scoreBase: 7 } }
    - { shortcode: cre, type: attribute, system: { scoreBase: 9 } }
    - { shortcode: emp, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: elo, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: mor, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: voi, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: archery, type: skill, name: Shortbow (Bow), system: { masteryLevelBase: 72 } }
    - { shortcode: awar, type: skill, system: { masteryLevelBase: 44 } }
    - { shortcode: chrm, type: skill }
    - { shortcode: clmb, type: skill, system: { masteryLevelBase: 64 } }
    - { shortcode: cmd, type: skill }
    - { shortcode: cook, type: skill }
    - { shortcode: dnce, type: skill }
    - { shortcode: dscr, type: skill }
    - { shortcode: draw, type: skill }
    - { shortcode: folklr, type: skill }
    - { shortcode: guil, type: skill }
    - { shortcode: init, type: skill, system: { masteryLevelBase: 78 } }
    - { shortcode: shok, type: skill }
    - { shortcode: intr, type: skill, system: { masteryLevelBase: 27 } }
    - { shortcode: jump, type: skill, system: { masteryLevelBase: 60 } }
    - { shortcode: melee, type: skill, system: { masteryLevelBase: 65 } }
    - { shortcode: dge, type: skill }
    - { shortcode: pysn, type: skill, system: { masteryLevelBase: 20 } }
    - { shortcode: ridg, type: skill }
    - { shortcode: sing, type: skill, system: { masteryLevelBase: 30 } }
    - { shortcode: stlth, type: skill, system: { masteryLevelBase: 39 } }
    - { shortcode: srvl, type: skill, system: { masteryLevelBase: 48 } }
    - { shortcode: spirit, type: skill }
    - { shortcode: swim, type: skill }
    - { shortcode: thtcs, type: skill }
    - { shortcode: thro, type: skill, system: { masteryLevelBase: 48 } }
    - { shortcode: bflkbite, type: skill }
    - { shortcode: bflkgrab, type: skill }
    - { shortcode: bflkheadbutt, type: skill }
    - { shortcode: bflkkick, type: skill }
    - { shortcode: limbblock, type: skill }
    - { shortcode: press, type: skill }
    - { shortcode: bflkpunch, type: skill }
    - { shortcode: trip, type: skill }
    - { shortcode: sprt, type: mysticalability }
    - { shortcode: lang, type: skill, name: "Language, Serf", system: { masteryLevelBase: 59 } }
    - { shortcode: hrld, type: skill, system: { masteryLevelBase: 24 } }
    - { shortcode: wpnc, type: skill, system: { masteryLevelBase: 30 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 0 } }
    - { shortcode: pouchbuckram, type: containergear }
    - { shortcode: CvCloak, type: armorgear }
    - { shortcode: GTnc, type: armorgear }
    - { shortcode: LtTrsr, type: armorgear }
    - { shortcode: LLeg, type: armorgear }
    - { shortcode: CShoe, type: armorgear }
    - { shortcode: LTunic, type: armorgear }
    - { shortcode: Kni, type: weapongear }
    - { shortcode: ArwStd, type: projectilegear, system: { quantity: 12 } }
    - { shortcode: bgsmcvs, type: containergear }
    - { shortcode: beltpouchl3, type: containergear }
    - { shortcode: tndrbx, type: miscgear }
    - { shortcode: LtCap, type: armorgear }
    - { shortcode: quiverlgsh, type: containergear }
    - { shortcode: Bklr, type: weapongear }
    - { shortcode: spoonpewte, type: miscgear }
    - { shortcode: tankardpew, type: miscgear }
---

# Appearance {#appearance}

**Height**: 5' 9"
**Frame**: Scant
**Weight**: 237
**Size**: 8
**Comeliness**: Attractive
**Complexion**: Fair
**Hair Color**: Brown
**Eye Color**: Violet
**Voice**: Average

# Dossier {#dossier}

**Age**: 20
**Birthday**: 2 Kelen 700
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: Eldest of 5
**Siblings**: MMMfM
**Parentage**: Fostered
**Estrangement**: Unpopular
**Clanhead**: Father's Aunt/Uncle
**Medical**: Deformed/Missing Arm

## Notes

Modifier to AttributesAGL of +2 (from 13) {Frame=Scant}

Eldest gets +5 on estrangement roll.

Modifier to HairColor of +25 (from 9) {Complexion=Fair, Species=Human}

Modifier to EyeColor of -10 (from 7) {Complexion=Fair, Species=Human}

Deformed/Missing Arm mod to Dexterity: -2

125lbs weight resulted in -2 strength mod.

Scant frame resulted in +2 agility mod.

Modifier to StartingEquipment of +100 (from 29) {SocialClass=Serf}
