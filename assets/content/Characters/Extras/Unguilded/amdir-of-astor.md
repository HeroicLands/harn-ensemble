---
aliases:
  - Amdir of Astor
tags: []
name:
  full: Amdir of Astor
  title: ""
  given: Amdir
  clan: Astor
  aliases: []
id: WjWzufK1Q9JB7LCQ
folder: wqZxeSsm1ABX2AGx
shortcode: amdirofastor
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
social:
  occupation: Sindarin Horsebow
  class: serf
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: sindarin
  gender: female
  age: 171
  birthday: 549/9/6
  height:
    m: 1.75
  weight:
    kg: 63.96
  build:
    frame: light
  appearance:
    eye_color: hazel
    hair_color: brown
    skin_color: fair
    complexion: average
    extra_features:
      - Sterile
hm3:
  species: sindarin
  sunsign: tai
  attributes:
    str: 17
    sta: 11
    dex: 13
    agl: 13
    int: 6
    aur: 13
    wil: 15
    eye: 14
    hrg: 6
    sml: 18
    voi: 11
    cml: 12
    mor: 14
  move: 14
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 70 } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 112 } }
    - { shortcode: dancing, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: language, type: skill, name: "Language, Serf", system: { masteryLevel: 61 } }
    - { shortcode: musician, type: skill, system: { masteryLevel: 24 } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 18 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 33 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 27 } }
    - { shortcode: bow, type: skill, name: Heartbow (Bow), system: { masteryLevel: 84 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 84 } }
    - { shortcode: polearm, type: skill, name: Lance (Polearm), system: { masteryLevel: 105 } }
    - { shortcode: riding, type: skill, system: { masteryLevel: 91 } }
    - { shortcode: shield, type: skill, system: { masteryLevel: 98 } }
    - { shortcode: sword, type: skill, name: Longknife (Sword), system: { masteryLevel: 84 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 84 } }
    - { shortcode: foraging, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: heraldry, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 24 } }
    - { shortcode: survival, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: weaponcraft, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 1658 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: SHaub, type: armorgear }
    - { shortcode: SgLeg, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: SgTunic, type: armorgear }
    - { shortcode: Dgr, type: weapongear }
    - name: Bow(Heartbow)
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        weight: 1
    - { shortcode: tndrbx, type: miscgear }
    - { shortcode: LtLeg, type: armorgear }
    - { shortcode: quiverlgsh, type: miscgear }
    - { shortcode: KnSh, type: weapongear }
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
    - { shortcode: str, type: attribute, system: { scoreBase: 17 } }
    - { shortcode: end, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: dex, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: agl, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: per, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: snt, type: attribute, system: { scoreBase: 18 } }
    - { shortcode: cml, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: aur, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: wil, type: attribute, system: { scoreBase: 15 } }
    - { shortcode: rea, type: attribute, system: { scoreBase: 6 } }
    - { shortcode: cre, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: emp, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: elo, type: attribute, system: { scoreBase: 18 } }
    - { shortcode: mor, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: voi, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: archery, type: skill, name: Heartbow (Bow), system: { masteryLevelBase: 84 } }
    - { shortcode: awar, type: skill, system: { masteryLevelBase: 60 } }
    - { shortcode: chrm, type: skill }
    - { shortcode: clmb, type: skill, system: { masteryLevelBase: 70 } }
    - { shortcode: cmd, type: skill }
    - { shortcode: cook, type: skill }
    - { shortcode: dnce, type: skill, system: { masteryLevelBase: 56 } }
    - { shortcode: dscr, type: skill }
    - { shortcode: draw, type: skill }
    - { shortcode: folklr, type: skill }
    - { shortcode: guil, type: skill }
    - { shortcode: init, type: skill, system: { masteryLevelBase: 84 } }
    - { shortcode: shok, type: skill }
    - { shortcode: intr, type: skill, system: { masteryLevelBase: 36 } }
    - { shortcode: jump, type: skill, system: { masteryLevelBase: 56 } }
    - { shortcode: melee, type: skill, system: { masteryLevelBase: 96 } }
    - { shortcode: dge, type: skill }
    - { shortcode: pysn, type: skill, system: { masteryLevelBase: 24 } }
    - { shortcode: ridg, type: skill, system: { masteryLevelBase: 91 } }
    - { shortcode: sing, type: skill, system: { masteryLevelBase: 27 } }
    - { shortcode: stlth, type: skill, system: { masteryLevelBase: 52 } }
    - { shortcode: srvl, type: skill, system: { masteryLevelBase: 48 } }
    - { shortcode: spirit, type: skill }
    - { shortcode: swim, type: skill }
    - { shortcode: thtcs, type: skill }
    - { shortcode: thro, type: skill, system: { masteryLevelBase: 56 } }
    - { shortcode: bflkbite, type: skill }
    - { shortcode: bflkgrab, type: skill }
    - { shortcode: bflkheadbutt, type: skill }
    - { shortcode: bflkkick, type: skill }
    - { shortcode: limbblock, type: skill }
    - { shortcode: press, type: skill }
    - { shortcode: bflkpunch, type: skill }
    - { shortcode: trip, type: skill }
    - { shortcode: sprt, type: mysticalability }
    - { shortcode: lang, type: skill, name: "Language, Serf", system: { masteryLevelBase: 61 } }
    - { shortcode: musc, type: skill, system: { masteryLevelBase: 24 } }
    - { shortcode: hrld, type: skill, system: { masteryLevelBase: 30 } }
    - { shortcode: wpnc, type: skill, system: { masteryLevelBase: 30 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 1658 } }
    - { shortcode: pouchbuckram, type: containergear }
    - { shortcode: SHaub, type: armorgear }
    - { shortcode: SgLeg, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: SgTunic, type: armorgear }
    - { shortcode: Dgr, type: weapongear }
    - { shortcode: tndrbx, type: miscgear }
    - { shortcode: LtTrsr, type: armorgear }
    - { shortcode: quiverlgsh, type: containergear }
    - { shortcode: KnSh, type: weapongear }
    - { shortcode: spoonpewte, type: miscgear }
    - { shortcode: tankardpew, type: miscgear }
---

# Appearance {#appearance}

**Height**: 5' 9"
**Frame**: Light
**Weight**: 141
**Size**: 6
**Comeliness**: Average
**Complexion**: Fair
**Hair Color**: Brown
**Eye Color**: Hazel
**Voice**: Average

# Dossier {#dossier}

**Age**: 171
**Birthday**: 6 Savor 549
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: 2nd child of 2
**Siblings**: FF
**Parentage**: Offspring
**Offspring**: Mother dead, father remarried
**Estrangement**: Popular
**Clanhead**: Father/Mother
**Medical**: Sterile

## Notes

Modifier to Frame of -2 (from 9) {Species=Sindarin}

Modifier to AttributesSTR of +1 (from 17) {Species=Sindarin}

Modifier to AttributesSTA of +1 (from 10) {Species=Sindarin}

Modifier to AttributesDEX of +2 (from 10) {Species=Sindarin}

Modifier to AttributesAGL of +2 (from 10) {Species=Sindarin}

Modifier to AttributesEYE of +2 (from 12) {Species=Sindarin}

Modifier to AttributesHGR of +2 (from 4) {Species=Sindarin}

Modifier to AttributesSML of +3 (from 15) {Species=Sindarin}

Modifier to AttributesVOI of +2 (from 9) {Species=Sindarin}

Modifier to AttributesCOM of +1 (from 11) {Species=Sindarin}

Modifier to AttributesAUR of +4 (from 9) {Species=Sindarin}

Modifier to AttributesMOR of +3 (from 11) {Species=Sindarin}

Modifier to SiblingRank of -20 (from 58) {Species=Sindarin}

Ambidexterous mod to Dexterity: +1

141lbs weight resulted in -1 strength mod.

Light frame resulted in +1 agility mod.

Modifier to StartingEquipment of +100 (from 44) {SocialClass=Serf}
