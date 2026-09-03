---
aliases:
  - Karn of Aweil
tags: []
name:
  full: Karn of Aweil
  title: ""
  given: Karn
  clan: Aweil
  aliases: []
id: GiOaeO0UIW5OyLW7
folder: wYO4XEaOHdLCVUM0
shortcode: karnofaweil
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
social:
  occupation: Herald
  class: unguilded
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: human
  gender: male
  age: 54
  birthday: 666/7/8
  height:
    m: 1.85
  weight:
    kg: 95.25
  build:
    frame: massive
  appearance:
    eye_color: blue
    hair_color: black
    skin_color: swarthy
    complexion: average
    extra_features:
      - Left-Handed
hm3:
  species: human
  sunsign: hirin
  attributes:
    str: 15
    sta: 8
    dex: 11
    agl: 2
    int: 11
    aur: 14
    wil: 7
    eye: 13
    hrg: 11
    sml: 10
    voi: 11
    cml: 10
    mor: 11
  move: 0
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
    - { shortcode: condition, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: dancing, type: skill, system: { masteryLevel: 24 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 72 } }
    - { shortcode: language, type: skill, name: Language(Jarinese), system: { masteryLevel: 22 } }
    - shortcode: language
      type: skill
      name: Language, Unguilded
      system:
        masteryLevel: 72
    - { shortcode: oratory, type: skill, system: { masteryLevel: 84 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 88 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: script, type: skill, name: Script(Lakaise), system: { masteryLevel: 98 } }
    - { shortcode: axe, type: skill, name: Handaxe (Axe), system: { masteryLevel: 98 } }
    - { shortcode: dagger, type: skill, system: { masteryLevel: 91 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 35 } }
    - { shortcode: polearm, type: skill, name: Lance (Polearm), system: { masteryLevel: 98 } }
    - { shortcode: riding, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: shield, type: skill, system: { masteryLevel: 78 } }
    - { shortcode: sword, type: skill, name: Broadsword (Sword), system: { masteryLevel: 65 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 50 } }
    - { shortcode: drawing, type: skill, system: { masteryLevel: 65 } }
    - { shortcode: foraging, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: heraldry, type: skill, system: { masteryLevel: 55 } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: survival, type: skill, system: { masteryLevel: 84 } }
    - { shortcode: weaponcraft, type: skill, system: { masteryLevel: 55 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 472 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: LtCBoot, type: armorgear }
    - { shortcode: SgClk, type: armorgear }
    - { shortcode: CHood, type: armorgear }
    - { shortcode: SgLeg, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: SgTunic, type: armorgear }
    - { shortcode: HAxe, type: weapongear }
    - { shortcode: Kni, type: weapongear }
    - { shortcode: backbagsmcanvas, type: containergear }
    - { shortcode: tndrbx, type: miscgear }
    - { shortcode: papercasel, type: miscgear }
    - { shortcode: writingkitportable, type: miscgear }
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
    - { shortcode: str, type: attribute, system: { scoreBase: 15 } }
    - { shortcode: end, type: attribute, system: { scoreBase: 8 } }
    - { shortcode: dex, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: agl, type: attribute, system: { scoreBase: 3 } }
    - { shortcode: per, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: snt, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: cml, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: aur, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: wil, type: attribute, system: { scoreBase: 7 } }
    - { shortcode: rea, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: cre, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: emp, type: attribute, system: { scoreBase: 9 } }
    - { shortcode: elo, type: attribute, system: { scoreBase: 9 } }
    - { shortcode: mor, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: voi, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: archery, type: skill }
    - { shortcode: awar, type: skill, system: { masteryLevelBase: 56 } }
    - { shortcode: chrm, type: skill }
    - { shortcode: clmb, type: skill, system: { masteryLevelBase: 70 } }
    - { shortcode: cmd, type: skill }
    - { shortcode: cook, type: skill }
    - { shortcode: dnce, type: skill, system: { masteryLevelBase: 24 } }
    - { shortcode: dscr, type: skill }
    - { shortcode: draw, type: skill, system: { masteryLevelBase: 65 } }
    - { shortcode: folklr, type: skill }
    - { shortcode: guil, type: skill }
    - { shortcode: init, type: skill, system: { masteryLevelBase: 35 } }
    - { shortcode: shok, type: skill }
    - { shortcode: intr, type: skill, system: { masteryLevelBase: 72 } }
    - { shortcode: jump, type: skill, system: { masteryLevelBase: 48 } }
    - { shortcode: melee, type: skill, system: { masteryLevelBase: 86 } }
    - { shortcode: dge, type: skill }
    - { shortcode: pysn, type: skill, system: { masteryLevelBase: 56 } }
    - { shortcode: ridg, type: skill, system: { masteryLevelBase: 56 } }
    - { shortcode: sing, type: skill, system: { masteryLevelBase: 60 } }
    - { shortcode: stlth, type: skill, system: { masteryLevelBase: 30 } }
    - { shortcode: srvl, type: skill, system: { masteryLevelBase: 84 } }
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
    - shortcode: lang
      type: skill
      name: Language, Unguilded
      system:
        masteryLevelBase: 72
    - { shortcode: script, type: skill, name: Script(Lakaise), system: { masteryLevelBase: 98 } }
    - { shortcode: hrld, type: skill, system: { masteryLevelBase: 55 } }
    - { shortcode: wpnc, type: skill, system: { masteryLevelBase: 55 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 472 } }
    - { shortcode: pouchbuckram, type: containergear }
    - { shortcode: LtCBoot, type: armorgear }
    - { shortcode: SgClk, type: armorgear }
    - { shortcode: CHood, type: armorgear }
    - { shortcode: SgLeg, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: SgTunic, type: armorgear }
    - { shortcode: HAxe, type: weapongear }
    - { shortcode: Kni, type: weapongear }
    - { shortcode: bgsmcvs, type: containergear }
    - { shortcode: tndrbx, type: miscgear }
    - { shortcode: papercasel, type: containergear }
    - { shortcode: scribekit, type: miscgear }
    - { shortcode: spoonpewte, type: miscgear }
    - { shortcode: tankardpew, type: miscgear }
    - { shortcode: wtrskin, type: containergear }
---

# Appearance {#appearance}

**Height**: 6' 1"
**Frame**: Massive
**Weight**: 210
**Size**: 8
**Comeliness**: Average
**Complexion**: Swarthy
**Hair Color**: Black
**Eye Color**: Blue
**Voice**: Average

# Dossier {#dossier}

**Age**: 54
**Birthday**: 8 Azura 666
**Culture**: Feudal
**Social Class**: Unguilded
**Sibling Rank**: Eldest of 4
**Siblings**: Mffm
**Parentage**: Offspring
**Offspring**: Father dead, mother remarried
**Estrangement**: Popular
**Clanhead**: Aunt/Uncle
**Medical**: Left-Handed

## Notes

Modifier to AttributesAGL of -2 (from 6) {Frame=Massive}

Eldest gets +5 on estrangement roll.

Modifier to EyeColor of +15 (from 7) {Complexion=Swarthy, Species=Human}

Left-Handed mod to Dexterity: +2

210lbs weight resulted in +3 strength mod.

Massive frame resulted in -2 agility mod.

Modifier to StartingEquipment of +200 (from 1) {SocialClass=Unguilded}
