---
aliases:
  - Cirben of Balchadhod
tags: []
name:
  full: Cirben of Balchadhod
  title: ""
  given: Cirben
  clan: Balchadhod
  aliases: []
id: 4uPsPhgKl3M0J9vC
folder: wYO4XEaOHdLCVUM0
shortcode: cirbenofbalchadhod
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
package: harnensemble
social:
  occupation: Sindarin Knight
  class: guilded
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: sindarin
  gender: female
  age: 208
  birthday: 512/7/23
  height:
    m: 1.68
  weight:
    kg: 52.62
  build:
    frame: scant
  appearance:
    eye_color: hazel
    hair_color: blonde
    skin_color: pale
    complexion: average
    extra_features: []
hm3:
  species: sindarin
  sunsign: hirin
  attributes:
    str: 13
    sta: 14
    dex: 7
    agl: 16
    int: 10
    aur: 15
    wil: 13
    eye: 13
    hrg: 19
    sml: 13
    voi: 12
    cml: 10
    mor: 12
    end: 13
  move: 13
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
        masteryLevel: 48
    - shortcode: condition
      type: skill
      system:
        masteryLevel: 91
    - shortcode: dancing
      type: skill
      system:
        masteryLevel: 70
    - shortcode: jumping
      type: skill
      system:
        masteryLevel: 85
    - shortcode: stealth
      type: skill
      system:
        masteryLevel: 54
    - shortcode: throwing
      type: skill
      system:
        masteryLevel: 65
    - shortcode: awareness
      type: skill
      system:
        masteryLevel: 64
    - shortcode: intrigue
      type: skill
      system:
        masteryLevel: 60
    - shortcode: language
      type: skill
      name: Language, Guilded
      system:
        masteryLevel: 82
    - shortcode: musician
      type: skill
      system:
        masteryLevel: 75
    - shortcode: oratory
      type: skill
      system:
        masteryLevel: 40
    - shortcode: rhetoric
      type: skill
      system:
        masteryLevel: 33
    - shortcode: singing
      type: skill
      system:
        masteryLevel: 42
    - shortcode: initiative
      type: skill
      system:
        masteryLevel: 112
    - shortcode: polearm
      type: skill
      name: Lance (Polearm)
      system:
        masteryLevel: 99
    - shortcode: riding
      type: skill
      system:
        masteryLevel: 108
    - shortcode: shield
      type: skill
      system:
        masteryLevel: 81
    - shortcode: sword
      type: skill
      name: Longknife (Sword)
      system:
        masteryLevel: 63
    - shortcode: unarmed
      type: skill
      system:
        masteryLevel: 96
    - shortcode: foraging
      type: skill
      system:
        masteryLevel: 60
    - shortcode: heraldry
      type: skill
      system:
        masteryLevel: 22
    - shortcode: physician
      type: skill
      system:
        masteryLevel: 20
    - shortcode: survival
      type: skill
      system:
        masteryLevel: 40
    - shortcode: weaponcraft
      type: skill
      system:
        masteryLevel: 22
    - shortcode: pence
      type: miscgear
      system:
        quantity: 8946
    - shortcode: pursebuckram
      type: containergear
    - shortcode: LtCBoot
      type: armorgear
    - shortcode: BLeg
      type: armorgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: CTunic
      type: armorgear
    - shortcode: Dgr
      type: weapongear
    - shortcode: LKni
      type: weapongear
    - shortcode: backbagmed
      type: containergear
    - shortcode: tndrbx
      type: miscgear
    - shortcode: pipesmokin
      type: miscgear
    - shortcode: KnSh
      type: weapongear
    - shortcode: spoonpewte
      type: miscgear
    - shortcode: tndrbx
      type: miscgear
    - name: Comb, wood
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        value: 2
        weight: 0.1
sohl:
  kbcat: archetype
  archetype: 1
  attributes:
    str: 13
    end: 14
    dex: 7
    agl: 16
    per: 18
    snt: 13
    cml: 10
    aur: 15
    wil: 13
    rea: 10
    cre: 15
    emp: 10
    elo: 14
    mor: 12
    voi: 12
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
        masteryLevelBase: 64
    - shortcode: chrm
      type: skill
    - shortcode: clmb
      type: skill
      system:
        masteryLevelBase: 48
    - shortcode: cmd
      type: skill
    - shortcode: cook
      type: skill
    - shortcode: dnce
      type: skill
      system:
        masteryLevelBase: 70
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
        masteryLevelBase: 112
    - shortcode: shok
      type: skill
    - shortcode: intr
      type: skill
      system:
        masteryLevelBase: 60
    - shortcode: jump
      type: skill
      system:
        masteryLevelBase: 85
    - shortcode: melee
      type: skill
      system:
        masteryLevelBase: 81
    - shortcode: dge
      type: skill
    - shortcode: pysn
      type: skill
      system:
        masteryLevelBase: 20
    - shortcode: ridg
      type: skill
      system:
        masteryLevelBase: 108
    - shortcode: sing
      type: skill
      system:
        masteryLevelBase: 42
    - shortcode: stlth
      type: skill
      system:
        masteryLevelBase: 54
    - shortcode: srvl
      type: skill
      system:
        masteryLevelBase: 40
    - shortcode: spirit
      type: skill
    - shortcode: swim
      type: skill
    - shortcode: thtcs
      type: skill
    - shortcode: thro
      type: skill
      system:
        masteryLevelBase: 65
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
      name: Language, Guilded
      system:
        masteryLevelBase: 82
    - shortcode: musc
      type: skill
      system:
        masteryLevelBase: 75
    - shortcode: hrld
      type: skill
      system:
        masteryLevelBase: 22
    - shortcode: wpnc
      type: skill
      system:
        masteryLevelBase: 22
    - shortcode: pence
      type: miscgear
      system:
        quantity: 8946
    - shortcode: pouchbuckram
      type: containergear
    - shortcode: LtCBoot
      type: armorgear
    - shortcode: BLeg
      type: armorgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: CTunic
      type: armorgear
    - shortcode: Dgr
      type: weapongear
    - shortcode: LKni
      type: weapongear
    - shortcode: backbagmed
      type: containergear
    - shortcode: tndrbx
      type: miscgear
    - shortcode: pipesmokin
      type: miscgear
    - shortcode: KnSh
      type: weapongear
    - shortcode: spoonpewte
      type: miscgear
    - shortcode: groomkitcom
      type: miscgear
---

# Appearance {#appearance}

**Height**: 5' 6"
**Frame**: Scant
**Weight**: 116
**Size**: 5
**Comeliness**: Average
**Complexion**: Pale
**Hair Color**: Blond
**Eye Color**: Hazel
**Voice**: Average

# Dossier {#dossier}

**Age**: 208
**Birthday**: 23 Azura 512
**Culture**: Feudal
**Social Class**: Guilded
**Sibling Rank**: Eldest of 3
**Siblings**: FmF
**Parentage**: Offspring
**Offspring**: Both parents alive and living together
**Estrangement**: Favorite
**Clanhead**: Aunt/Uncle

## Notes

Modifier to Frame of -2 (from 6) {Species=Sindarin}

Modifier to AttributesSTR of +1 (from 14) {Species=Sindarin}

Modifier to AttributesSTA of +1 (from 13) {Species=Sindarin}

Modifier to AttributesDEX of +2 (from 5) {Species=Sindarin}

Modifier to AttributesAGL of +2 (from 12) {Species=Sindarin}

Modifier to AttributesEYE of +2 (from 11) {Species=Sindarin}

Modifier to AttributesHGR of +2 (from 17) {Species=Sindarin}

Modifier to AttributesSML of +3 (from 10) {Species=Sindarin}

Modifier to AttributesVOI of +2 (from 10) {Species=Sindarin}

Modifier to AttributesCOM of +1 (from 9) {Species=Sindarin}

Modifier to AttributesAUR of +4 (from 11) {Species=Sindarin}

Modifier to AttributesMOR of +3 (from 9) {Species=Sindarin}

Modifier to SiblingRank of -20 (from 14) {Species=Sindarin}

Eldest gets +5 on estrangement roll.

116lbs weight resulted in -2 strength mod.

Scant frame resulted in +2 agility mod.

Modifier to StartingEquipment of +300 (from 10) {SocialClass=Guilded}
