---
aliases:
  - Captain Gorin of Merlis
tags: []
name:
  full: Captain Gorin of Merlis
  title: Captain
  given: Gorin
  clan: Merlis
  aliases: []
id: pDZvr3qdmafIvNCp
folder: ZMLVnTuUb85MUQMD
shortcode: captaingorinofmerlis
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
social:
  occupation: Feudal Guardsman, Heavy
  class: unguilded
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: human
  gender: male
  age: 36
  birthday: 684/11/12
  height:
    m: 1.91
  weight:
    kg: 92.08
  build:
    frame: heavy
  appearance:
    eye_color: blue
    hair_color: strawberry blond
    skin_color: fair
    complexion: attractive
    extra_features:
      - Left-Handed
hm3:
  species: human
  sunsign: masara
  attributes:
    str: 14
    sta: 12
    dex: 19
    agl: 7
    int: 14
    aur: 8
    wil: 12
    eye: 14
    hrg: 18
    sml: 17
    voi: 15
    cml: 13
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 90 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 64 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 44 } }
    - shortcode: language
      type: skill
      name: Language, Unguilded
      system:
        masteryLevel: 89
    - { shortcode: oratory, type: skill, system: { masteryLevel: 42 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 68 } }
    - { shortcode: dagger, type: skill, system: { masteryLevel: 102 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 90 } }
    - { shortcode: shield, type: skill, system: { masteryLevel: 108 } }
    - { shortcode: spear, type: skill, system: { masteryLevel: 105 } }
    - { shortcode: sword, type: skill, name: Falchion (Sword), system: { masteryLevel: 102 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 75 } }
    - { shortcode: foraging, type: skill, system: { masteryLevel: 80 } }
    - { shortcode: heraldry, type: skill, system: { masteryLevel: 45 } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 51 } }
    - { shortcode: survival, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: weaponcraft, type: skill, system: { masteryLevel: 45 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 1782 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: LtCBoot, type: armorgear }
    - { shortcode: PlHHelm, type: armorgear }
    - { shortcode: LtLeg, type: armorgear }
    - { shortcode: SgLeg, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: SgTunic, type: armorgear }
    - { shortcode: Dgr, type: weapongear }
    - { shortcode: Kni, type: weapongear }
    - { shortcode: backbagsmcanvas, type: containergear }
    - { shortcode: beltpouchl3, type: containergear }
    - { shortcode: RHbk, type: armorgear }
    - { shortcode: pipesmokin, type: miscgear }
    - { shortcode: RndSh, type: weapongear }
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
    - { shortcode: str, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: end, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: dex, type: attribute, system: { scoreBase: 18 } }
    - { shortcode: agl, type: attribute, system: { scoreBase: 7 } }
    - { shortcode: per, type: attribute, system: { scoreBase: 18 } }
    - { shortcode: snt, type: attribute, system: { scoreBase: 17 } }
    - { shortcode: cml, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: aur, type: attribute, system: { scoreBase: 8 } }
    - { shortcode: wil, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: rea, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: cre, type: attribute, system: { scoreBase: 18 } }
    - { shortcode: emp, type: attribute, system: { scoreBase: 6 } }
    - { shortcode: elo, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: mor, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: voi, type: attribute, system: { scoreBase: 15 } }
    - { shortcode: archery, type: skill }
    - { shortcode: awar, type: skill, system: { masteryLevelBase: 64 } }
    - { shortcode: chrm, type: skill }
    - { shortcode: clmb, type: skill, system: { masteryLevelBase: 52 } }
    - { shortcode: cmd, type: skill }
    - { shortcode: cook, type: skill }
    - { shortcode: dnce, type: skill }
    - { shortcode: dscr, type: skill }
    - { shortcode: draw, type: skill }
    - { shortcode: folklr, type: skill }
    - { shortcode: guil, type: skill }
    - { shortcode: init, type: skill, system: { masteryLevelBase: 90 } }
    - { shortcode: shok, type: skill }
    - { shortcode: intr, type: skill, system: { masteryLevelBase: 44 } }
    - { shortcode: jump, type: skill, system: { masteryLevelBase: 36 } }
    - { shortcode: melee, type: skill, system: { masteryLevelBase: 104 } }
    - { shortcode: dge, type: skill }
    - { shortcode: pysn, type: skill, system: { masteryLevelBase: 51 } }
    - { shortcode: ridg, type: skill }
    - { shortcode: sing, type: skill, system: { masteryLevelBase: 68 } }
    - { shortcode: stlth, type: skill, system: { masteryLevelBase: 48 } }
    - { shortcode: srvl, type: skill, system: { masteryLevelBase: 60 } }
    - { shortcode: spirit, type: skill }
    - { shortcode: swim, type: skill }
    - { shortcode: thtcs, type: skill }
    - { shortcode: thro, type: skill, system: { masteryLevelBase: 90 } }
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
        masteryLevelBase: 89
    - { shortcode: hrld, type: skill, system: { masteryLevelBase: 45 } }
    - { shortcode: wpnc, type: skill, system: { masteryLevelBase: 45 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 1782 } }
    - { shortcode: pouchbuckram, type: containergear }
    - { shortcode: LtCBoot, type: armorgear }
    - { shortcode: PlHHelm, type: armorgear }
    - { shortcode: LtTrsr, type: armorgear }
    - { shortcode: SgLeg, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: SgTunic, type: armorgear }
    - { shortcode: Dgr, type: weapongear }
    - { shortcode: Kni, type: weapongear }
    - { shortcode: bgsmcvs, type: containergear }
    - { shortcode: beltpouchl3, type: containergear }
    - { shortcode: RHbk, type: armorgear }
    - { shortcode: pipesmokin, type: miscgear }
    - { shortcode: RndSh, type: weapongear }
---

# Appearance {#appearance}

**Height**: 6' 3"
**Frame**: Heavy
**Weight**: 203
**Size**: 8
**Comeliness**: Attractive
**Complexion**: Fair
**Hair Color**: Strawberry Blond
**Eye Color**: Blue
**Voice**: Pleasant

# Dossier {#dossier}

**Age**: 36
**Birthday**: 12 Navek 684
**Culture**: Feudal
**Social Class**: Unguilded
**Sibling Rank**: 4th child of 6
**Siblings**: fMfMFF
**Parentage**: Offspring
**Offspring**: Both parents alive and living together
**Estrangement**: Unpopular
**Clanhead**: Cousin
**Medical**: Left-Handed

## Notes

Modifier to AttributesAGL of -1 (from 9) {Frame=Heavy}

Modifier to HairColor of +25 (from 54) {Complexion=Fair, Species=Human}

Modifier to EyeColor of -10 (from 30) {Complexion=Fair, Species=Human}

Left-Handed mod to Dexterity: +2

203lbs weight resulted in +3 strength mod.

Heavy frame resulted in -1 agility mod.

Modifier to StartingEquipment of +200 (from 22) {SocialClass=Unguilded}
