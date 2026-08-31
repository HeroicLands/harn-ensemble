---
aliases:
  - Zuldagmek of Agarin
tags: []
name:
  full: Zuldagmek of Agarin
  title: ""
  given: Zuldagmek
  clan: Agarin
  aliases: []
id: f8SoAHVkq8I3dupm
folder: wqZxeSsm1ABX2AGx
shortcode: zuldagmekofagarin
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
social:
  occupation: Khuzdul Clansman
  class: noble
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: khuzdul
  gender: female
  age: 98
  birthday: 622/4/10
  height:
    m: 1.4
  weight:
    kg: 109.32
  build:
    frame: massive
  appearance:
    eye_color: blue
    hair_color: brown
    skin_color: fair
    complexion: average
    extra_features:
      - Obesity
hm3:
  species: khuzdul
  sunsign: ahnu
  attributes:
    str: 17
    sta: 15
    dex: 11
    agl: 11
    int: 11
    aur: 7
    wil: 14
    eye: 13
    hrg: 11
    sml: 8
    voi: 9
    cml: 11
    mor: 11
  move: 0
  items:
    - shortcode: skull
      type: armorlocation
    - shortcode: face
      type: armorlocation
    - shortcode: neck
      type: armorlocation
    - shortcode: lshoulder
      type: armorlocation
    - shortcode: rshoulder
      type: armorlocation
    - shortcode: luparm
      type: armorlocation
    - shortcode: ruparm
      type: armorlocation
    - shortcode: lelb
      type: armorlocation
    - shortcode: relb
      type: armorlocation
    - shortcode: lhand
      type: armorlocation
    - shortcode: rhand
      type: armorlocation
    - shortcode: thorax
      type: armorlocation
    - shortcode: abdm
      type: armorlocation
    - shortcode: groin
      type: armorlocation
    - shortcode: lhip
      type: armorlocation
    - shortcode: rhip
      type: armorlocation
    - shortcode: lthigh
      type: armorlocation
    - shortcode: rthigh
      type: armorlocation
    - shortcode: lknee
      type: armorlocation
    - shortcode: rknee
      type: armorlocation
    - shortcode: lcalf
      type: armorlocation
    - shortcode: rcalf
      type: armorlocation
    - shortcode: lfoot
      type: armorlocation
    - shortcode: rfoot
      type: armorlocation
    - shortcode: climbing
      type: skill
      system:
        masteryLevel: 36
    - shortcode: condition
      type: skill
      system:
        masteryLevel: 75
    - shortcode: jumping
      type: skill
      system:
        masteryLevel: 20
    - shortcode: stealth
      type: skill
      system:
        masteryLevel: 24
    - shortcode: throwing
      type: skill
      system:
        masteryLevel: 56
    - shortcode: awareness
      type: skill
      system:
        masteryLevel: 40
    - shortcode: intrigue
      type: skill
      system:
        masteryLevel: 44
    - shortcode: language
      type: skill
      name: Language, Noble
      system:
        masteryLevel: 82
    - shortcode: oratory
      type: skill
      system:
        masteryLevel: 33
    - shortcode: rhetoric
      type: skill
      system:
        masteryLevel: 36
    - shortcode: singing
      type: skill
      system:
        masteryLevel: 27
    - shortcode: axe
      type: skill
      name: Handaxe (Axe)
      system:
        masteryLevel: 80
    - shortcode: initiative
      type: skill
      system:
        masteryLevel: 54
    - shortcode: shield
      type: skill
      system:
        masteryLevel: 65
    - shortcode: spear
      type: skill
      system:
        masteryLevel: 105
    - shortcode: unarmed
      type: skill
      system:
        masteryLevel: 63
    - shortcode: foraging
      type: skill
      system:
        masteryLevel: 55
    - shortcode: heraldry
      type: skill
      system:
        masteryLevel: 26
    - shortcode: physician
      type: skill
      system:
        masteryLevel: 24
    - shortcode: survival
      type: skill
      system:
        masteryLevel: 56
    - shortcode: weaponcraft
      type: skill
      system:
        masteryLevel: 30
    - shortcode: pence
      type: miscgear
      system:
        quantity: 813
    - shortcode: pursebuckram
      type: containergear
    - shortcode: CHood
      type: armorgear
    - shortcode: MHbk
      type: armorgear
    - shortcode: WLeg
      type: armorgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: WTunic
      type: armorgear
    - shortcode: HAxe
      type: weapongear
    - shortcode: Dgr
      type: weapongear
    - name: Earing, Gold with gem
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        value: 425
        weight: 0.01
    - shortcode: WCap
      type: armorgear
    - shortcode: pipesmokin
      type: miscgear
    - shortcode: tankardpew
      type: miscgear
sohl:
  kbcat: archetype
  archetype: 1
  attributes:
    str: 17
    end: 15
    dex: 11
    agl: 11
    per: 10
    snt: 8
    cml: 11
    aur: 7
    wil: 14
    rea: 11
    cre: 11
    emp: 9
    elo: 11
    mor: 11
    voi: 9
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
    - shortcode: archery
      type: skill
    - shortcode: awar
      type: skill
      system:
        masteryLevelBase: 40
    - shortcode: chrm
      type: skill
    - shortcode: clmb
      type: skill
      system:
        masteryLevelBase: 36
    - shortcode: cmd
      type: skill
    - shortcode: cook
      type: skill
    - shortcode: dnce
      type: skill
    - shortcode: dscr
      type: skill
    - shortcode: draw
      type: skill
    - shortcode: folklr
      type: skill
    - shortcode: guil
      type: skill
    - shortcode: init
      type: skill
      system:
        masteryLevelBase: 54
    - shortcode: shok
      type: skill
    - shortcode: intr
      type: skill
      system:
        masteryLevelBase: 44
    - shortcode: jump
      type: skill
      system:
        masteryLevelBase: 20
    - shortcode: melee
      type: skill
      system:
        masteryLevelBase: 83
    - shortcode: dge
      type: skill
    - shortcode: pysn
      type: skill
      system:
        masteryLevelBase: 24
    - shortcode: ridg
      type: skill
    - shortcode: sing
      type: skill
      system:
        masteryLevelBase: 27
    - shortcode: stlth
      type: skill
      system:
        masteryLevelBase: 24
    - shortcode: srvl
      type: skill
      system:
        masteryLevelBase: 56
    - shortcode: spirit
      type: skill
    - shortcode: swim
      type: skill
    - shortcode: thtcs
      type: skill
    - shortcode: thro
      type: skill
      system:
        masteryLevelBase: 56
    - shortcode: bflkbite
      type: skill
    - shortcode: bflkgrab
      type: skill
    - shortcode: bflkheadbutt
      type: skill
    - shortcode: bflkkick
      type: skill
    - shortcode: limbblock
      type: skill
    - shortcode: press
      type: skill
    - shortcode: bflkpunch
      type: skill
    - shortcode: trip
      type: skill
    - shortcode: sprt
      type: mysticalability
    - shortcode: lang
      type: skill
      name: Language, Noble
      system:
        masteryLevelBase: 82
    - shortcode: hrld
      type: skill
      system:
        masteryLevelBase: 26
    - shortcode: wpnc
      type: skill
      system:
        masteryLevelBase: 30
    - shortcode: pence
      type: miscgear
      system:
        quantity: 813
    - shortcode: pouchbuckram
      type: containergear
    - shortcode: CHood
      type: armorgear
    - shortcode: MHbk
      type: armorgear
    - shortcode: WLeg
      type: armorgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: WTunic
      type: armorgear
    - shortcode: HAxe
      type: weapongear
    - shortcode: Dgr
      type: weapongear
    - shortcode: earringsgold
      type: miscgear
    - shortcode: WCap
      type: armorgear
    - shortcode: pipesmokin
      type: miscgear
    - shortcode: tankardpew
      type: miscgear
---

# Appearance {#appearance}

**Height**: 4' 7"
**Frame**: Massive
**Weight**: 241
**Size**: 9
**Comeliness**: Average
**Complexion**: Fair
**Hair Color**: Brown
**Eye Color**: Blue
**Voice**: Average

# Dossier {#dossier}

**Age**: 98
**Birthday**: 10 Nolus 622
**Culture**: Feudal
**Social Class**: Noble
**Sibling Rank**: Eldest of 4
**Siblings**: FfmM
**Parentage**: Offspring
**Offspring**: Both parents alive and living together
**Estrangement**: Favorite
**Clanhead**: Great Grandfather's Father/Mother
**Medical**: Obesity

## Notes

Modifier to Frame of +3 (from 14) {Species=Khuzdul}

Modifier to AttributesSTR of +4 (from 15) {Species=Khuzdul}

Modifier to AttributesSTA of +2 (from 13) {Species=Khuzdul}

Modifier to AttributesDEX of +1 (from 11) {Species=Khuzdul}

Modifier to AttributesAGL of -2 (from 6) {Frame=Massive}

Modifier to AttributesEYE of +1 (from 12) {Species=Khuzdul}

Modifier to AttributesHGR of +2 (from 9) {Species=Khuzdul}

Modifier to AttributesSML of +2 (from 6) {Species=Khuzdul}

Modifier to AttributesCOM of +4 (from 7) {Species=Khuzdul}

Modifier to AttributesAUR of -1 (from 8) {Species=Khuzdul}

Modifier to AttributesWIL of +3 (from 11) {Species=Khuzdul}

Modifier to SiblingRank of -20 (from 27) {Species=Khuzdul}

Eldest gets +5 on estrangement roll.

Noble Blood results in +2 inches in height.

Obesity mod to Agility: -2

130lbs weight resulted in -2 strength mod.

Massive frame resulted in -2 agility mod.

Modifier to StartingEquipment of +400 (from 74) {SocialClass=Noble}
