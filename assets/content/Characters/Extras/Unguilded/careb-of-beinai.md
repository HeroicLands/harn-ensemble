---
aliases:
  - Careb of Beinai
tags: []
name:
  full: Careb of Beinai
  title: ""
  given: Careb
  clan: Beinai
  aliases: []
id: Sdl9TH7jFlqvbguW
folder: wqZxeSsm1ABX2AGx
shortcode: carebofbeinai
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
social:
  occupation: Sindarin Guardian
  class: serf
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: sindarin
  gender: male
  age: 177
  birthday: 543/9/7
  height:
    m: 1.7
  weight:
    kg: 73.94
  build:
    frame: heavy
  appearance:
    eye_color: grey
    hair_color: brown
    skin_color: pale
    complexion: average
    extra_features:
      - Addiction
hm3:
  species: sindarin
  sunsign: tai
  attributes:
    str: 13
    sta: 13
    dex: 12
    agl: 8
    int: 7
    aur: 15
    wil: 11
    eye: 12
    hrg: 16
    sml: 15
    voi: 11
    cml: 9
    mor: 14
  move: 8
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 44 } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 72 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 39 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: language, type: skill, name: "Language, Serf", system: { masteryLevel: 60 } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 18 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: dagger, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: shield, type: skill, system: { masteryLevel: 96 } }
    - { shortcode: spear, type: skill, system: { masteryLevel: 108 } }
    - { shortcode: sword, type: skill, name: Longknife (Sword), system: { masteryLevel: 72 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 44 } }
    - { shortcode: foraging, type: skill, system: { masteryLevel: 44 } }
    - { shortcode: heraldry, type: skill, system: { masteryLevel: 24 } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 33 } }
    - { shortcode: survival, type: skill, system: { masteryLevel: 40 } }
    - { shortcode: weaponcraft, type: skill, system: { masteryLevel: 24 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 192 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: LtCBoot, type: armorgear }
    - { shortcode: RClk, type: armorgear }
    - { shortcode: CHood, type: armorgear }
    - { shortcode: SHaub, type: armorgear }
    - { shortcode: SgLeg, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: SgTunic, type: armorgear }
    - { shortcode: Dgr, type: weapongear }
    - { shortcode: backbagsmcanvas, type: containergear }
    - { shortcode: beltpouchl3, type: containergear }
    - { shortcode: tndrbx, type: miscgear }
    - { shortcode: pipesmokin, type: miscgear }
    - { shortcode: RndSh, type: weapongear }
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
    - { shortcode: end, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: dex, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: agl, type: attribute, system: { scoreBase: 8 } }
    - { shortcode: per, type: attribute, system: { scoreBase: 17 } }
    - { shortcode: snt, type: attribute, system: { scoreBase: 15 } }
    - { shortcode: cml, type: attribute, system: { scoreBase: 9 } }
    - { shortcode: aur, type: attribute, system: { scoreBase: 15 } }
    - { shortcode: wil, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: rea, type: attribute, system: { scoreBase: 7 } }
    - { shortcode: cre, type: attribute, system: { scoreBase: 16 } }
    - { shortcode: emp, type: attribute, system: { scoreBase: 15 } }
    - { shortcode: elo, type: attribute, system: { scoreBase: 15 } }
    - { shortcode: mor, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: voi, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: archery, type: skill }
    - { shortcode: awar, type: skill, system: { masteryLevelBase: 56 } }
    - { shortcode: chrm, type: skill }
    - { shortcode: clmb, type: skill, system: { masteryLevelBase: 44 } }
    - { shortcode: cmd, type: skill }
    - { shortcode: cook, type: skill }
    - { shortcode: dnce, type: skill }
    - { shortcode: dscr, type: skill }
    - { shortcode: draw, type: skill }
    - { shortcode: folklr, type: skill }
    - { shortcode: guil, type: skill }
    - { shortcode: init, type: skill, system: { masteryLevelBase: 60 } }
    - { shortcode: shok, type: skill }
    - { shortcode: intr, type: skill, system: { masteryLevelBase: 36 } }
    - { shortcode: jump, type: skill, system: { masteryLevelBase: 36 } }
    - { shortcode: melee, type: skill, system: { masteryLevelBase: 84 } }
    - { shortcode: dge, type: skill }
    - { shortcode: pysn, type: skill, system: { masteryLevelBase: 33 } }
    - { shortcode: ridg, type: skill }
    - { shortcode: sing, type: skill, system: { masteryLevelBase: 48 } }
    - { shortcode: stlth, type: skill, system: { masteryLevelBase: 39 } }
    - { shortcode: srvl, type: skill, system: { masteryLevelBase: 40 } }
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
    - { shortcode: lang, type: skill, name: "Language, Serf", system: { masteryLevelBase: 60 } }
    - { shortcode: hrld, type: skill, system: { masteryLevelBase: 24 } }
    - { shortcode: wpnc, type: skill, system: { masteryLevelBase: 24 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 192 } }
    - { shortcode: pouchbuckram, type: containergear }
    - { shortcode: LtCBoot, type: armorgear }
    - { shortcode: RClk, type: armorgear }
    - { shortcode: CHood, type: armorgear }
    - { shortcode: SHaub, type: armorgear }
    - { shortcode: SgLeg, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: SgTunic, type: armorgear }
    - { shortcode: Dgr, type: weapongear }
    - { shortcode: bgsmcvs, type: containergear }
    - { shortcode: beltpouchl3, type: containergear }
    - { shortcode: tndrbx, type: miscgear }
    - { shortcode: pipesmokin, type: miscgear }
    - { shortcode: RndSh, type: weapongear }
    - { shortcode: tankardpew, type: miscgear }
---

# Appearance {#appearance}

**Height**: 5' 7"
**Frame**: Heavy
**Weight**: 163
**Size**: 6
**Comeliness**: Average
**Complexion**: Pale
**Hair Color**: Brown
**Eye Color**: Grey
**Voice**: Average

# Dossier {#dossier}

**Age**: 177
**Birthday**: 7 Savor 543
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: 2nd child of 2
**Siblings**: MM
**Parentage**: Offspring
**Offspring**: Both parents alive and living together
**Estrangement**: Popular
**Clanhead**: Great Great Grandfather's Father/Mother
**Medical**: Addiction

## Notes

Modifier to Frame of -2 (from 16) {Species=Sindarin}

Modifier to AttributesSTR of +1 (from 11) {Species=Sindarin}

Modifier to AttributesSTA of +1 (from 12) {Species=Sindarin}

Modifier to AttributesDEX of +2 (from 10) {Species=Sindarin}

Modifier to AttributesAGL of +2 (from 7) {Species=Sindarin}

Modifier to AttributesEYE of +2 (from 10) {Species=Sindarin}

Modifier to AttributesHGR of +2 (from 14) {Species=Sindarin}

Modifier to AttributesSML of +3 (from 12) {Species=Sindarin}

Modifier to AttributesVOI of +2 (from 9) {Species=Sindarin}

Modifier to AttributesCOM of +1 (from 8) {Species=Sindarin}

Modifier to AttributesAUR of +4 (from 11) {Species=Sindarin}

Modifier to AttributesMOR of +3 (from 11) {Species=Sindarin}

Modifier to SiblingRank of -20 (from 60) {Species=Sindarin}

163lbs weight resulted in +1 strength mod.

Heavy frame resulted in -1 agility mod.

Modifier to StartingEquipment of +100 (from 96) {SocialClass=Serf}
