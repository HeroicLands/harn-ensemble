---
aliases:
  - Shaelis of Matlim
tags: []
name:
  full: Shaelis of Matlim
  title: ""
  given: Shaelis
  clan: Matlim
  aliases: []
id: 36u73wEEgAViJw66
folder: GNynVWgIrKPK50Ca
shortcode: shaelisofmatlim
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
social:
  occupation: Harper/Skald
  class: unguilded
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: human
  gender: female
  age: 31
  birthday: 689/5/25
  height:
    m: 1.6
  weight:
    kg: 112.49
  build:
    frame: scant
  appearance:
    eye_color: green
    hair_color: red
    skin_color: dark
    complexion: plain
    extra_features:
      - Ambidexterous
hm3:
  species: human
  sunsign: angberelius
  attributes:
    str: 8
    sta: 13
    dex: 17
    agl: 19
    int: 10
    aur: 12
    wil: 11
    eye: 13
    hrg: 9
    sml: 6
    voi: 12
    cml: 8
    mor: 11
  move: 17
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 50 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 39 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 33 } }
    - shortcode: language
      type: skill
      name: Language, Unguilded
      system:
        masteryLevel: 61
    - { shortcode: musician, type: skill, name: Gittern (Musician), system: { masteryLevel: 84 } }
    - { shortcode: musician, type: skill, name: Lute (Musician), system: { masteryLevel: 60 } }
    - { shortcode: musician, type: skill, name: Recorder (Musician), system: { masteryLevel: 84 } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 40 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 33 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 66 } }
    - { shortcode: script, type: skill, name: Script(Lakaise), system: { masteryLevel: 96 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 65 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: folklore, type: skill, system: { masteryLevel: 40 } }
    - { shortcode: woodcraft, type: skill, system: { masteryLevel: 45 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 223 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: LtCBoot, type: armorgear }
    - { shortcode: SgClk, type: armorgear }
    - { shortcode: CHood, type: armorgear }
    - { shortcode: SgLeg, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: SgTunic, type: armorgear }
    - { shortcode: Kni, type: weapongear }
    - { shortcode: backbagsmcanvas, type: containergear }
    - { shortcode: tndrbx, type: miscgear }
    - name: Gittern
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        value: 150
        weight: 5
    - { shortcode: lute, type: miscgear }
    - name: Recorder
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        value: 4
        weight: 0.5
    - { shortcode: woodcarvingkitportable, type: miscgear }
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
    - { shortcode: str, type: attribute, system: { scoreBase: 8 } }
    - { shortcode: end, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: dex, type: attribute, system: { scoreBase: 17 } }
    - { shortcode: agl, type: attribute, system: { scoreBase: 18 } }
    - { shortcode: per, type: attribute, system: { scoreBase: 8 } }
    - { shortcode: snt, type: attribute, system: { scoreBase: 6 } }
    - { shortcode: cml, type: attribute, system: { scoreBase: 8 } }
    - { shortcode: aur, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: wil, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: rea, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: cre, type: attribute, system: { scoreBase: 9 } }
    - { shortcode: emp, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: elo, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: mor, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: voi, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: archery, type: skill }
    - { shortcode: awar, type: skill, system: { masteryLevelBase: 36 } }
    - { shortcode: chrm, type: skill }
    - { shortcode: clmb, type: skill, system: { masteryLevelBase: 56 } }
    - { shortcode: cmd, type: skill }
    - { shortcode: cook, type: skill }
    - { shortcode: dnce, type: skill }
    - { shortcode: dscr, type: skill }
    - { shortcode: draw, type: skill }
    - { shortcode: folklr, type: skill, system: { masteryLevelBase: 40 } }
    - { shortcode: guil, type: skill }
    - { shortcode: init, type: skill, system: { masteryLevelBase: 65 } }
    - { shortcode: shok, type: skill }
    - { shortcode: intr, type: skill, system: { masteryLevelBase: 33 } }
    - { shortcode: jump, type: skill, system: { masteryLevelBase: 60 } }
    - { shortcode: melee, type: skill }
    - { shortcode: dge, type: skill }
    - { shortcode: pysn, type: skill }
    - { shortcode: ridg, type: skill }
    - { shortcode: sing, type: skill, system: { masteryLevelBase: 66 } }
    - { shortcode: stlth, type: skill, system: { masteryLevelBase: 39 } }
    - { shortcode: srvl, type: skill }
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
    - shortcode: lang
      type: skill
      name: Language, Unguilded
      system:
        masteryLevelBase: 61
    - { shortcode: musc, type: skill, name: Recorder (Musician), system: { masteryLevelBase: 84 } }
    - { shortcode: script, type: skill, name: Script(Lakaise), system: { masteryLevelBase: 96 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 223 } }
    - { shortcode: pouchbuckram, type: containergear }
    - { shortcode: LtCBoot, type: armorgear }
    - { shortcode: SgClk, type: armorgear }
    - { shortcode: CHood, type: armorgear }
    - { shortcode: SgLeg, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: SgTunic, type: armorgear }
    - { shortcode: Kni, type: weapongear }
    - { shortcode: bgsmcvs, type: containergear }
    - { shortcode: tndrbx, type: miscgear }
    - { shortcode: lute, type: miscgear }
    - { shortcode: woodwrkkit, type: miscgear }
---

# Appearance {#appearance}

**Height**: 5' 3"
**Frame**: Scant
**Weight**: 248
**Size**: 9
**Comeliness**: Plain
**Complexion**: Dark
**Hair Color**: Red
**Eye Color**: Green
**Voice**: Average

# Dossier {#dossier}

**Age**: 31
**Birthday**: 25 Larane 689
**Culture**: Feudal
**Social Class**: Unguilded
**Sibling Rank**: 5th child of 5
**Siblings**: ffMmF
**Parentage**: Offspring
**Offspring**: Both parents alive and living together
**Estrangement**: Unpopular
**Clanhead**: Cousin
**Medical**: Ambidexterous

## Notes

Modifier to Frame of -3 (from 6) {Sex=Female, Species=Human}

Modifier to AttributesAGL of +2 (from 15) {Frame=Scant}

Modifier to AttributesAUR of +2 (from 10) {Sex=Female, Species=Human}

Modifier to HairColor of -25 (from 91) {Complexion=Dark, Species=Human}

Modifier to EyeColor of +25 (from 30) {Complexion=Dark, Species=Human}

Ambidexterous mod to Dexterity: +2

106lbs weight resulted in -3 strength mod.

Scant frame resulted in +2 agility mod.

Modifier to StartingEquipment of +200 (from 56) {SocialClass=Unguilded}
