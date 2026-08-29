---
aliases:
  - Amarth of Cuilos
tags: []
name:
  full: Amarth of Cuilos
  title: ""
  given: Amarth
  clan: Cuilos
  aliases: []
id: YSnPgG6pE6HQahg6
folder: wqZxeSsm1ABX2AGx
shortcode: amarthofcuilos
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
package: harnensemble
social:
  occupation: Sindarin Ranger, Light
  class: serf
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: sindarin
  gender: male
  age: 292
  birthday: 428/5/5
  height:
    m: 1.7
  weight:
    kg: 67.59
  build:
    frame: medium
  appearance:
    eye_color: blue
    hair_color: brown
    skin_color: fair
    complexion: average
    extra_features:
      - Birthmarks
hm3:
  species: sindarin
  sunsign: angberelius-ahnu
  attributes:
    str: 18
    sta: 16
    dex: 15
    agl: 7
    int: 16
    aur: 16
    wil: 13
    eye: 12
    hrg: 14
    sml: 15
    voi: 11
    cml: 11
    mor: 17
    end: 16
  move: 4
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
        masteryLevel: 52
    - shortcode: condition
      type: skill
      system:
        masteryLevel: 90
    - shortcode: jumping
      type: skill
      system:
        masteryLevel: 50
    - shortcode: stealth
      type: skill
      system:
        masteryLevel: 44
    - shortcode: throwing
      type: skill
      system:
        masteryLevel: 75
    - shortcode: awareness
      type: skill
      system:
        masteryLevel: 52
    - shortcode: intrigue
      type: skill
      system:
        masteryLevel: 45
    - shortcode: language
      type: skill
      name: Language, Serf
      system:
        masteryLevel: 63
    - shortcode: oratory
      type: skill
      system:
        masteryLevel: 24
    - shortcode: rhetoric
      type: skill
      system:
        masteryLevel: 39
    - shortcode: singing
      type: skill
      system:
        masteryLevel: 36
    - shortcode: bow
      type: skill
      name: Heartbow (Bow)
      system:
        masteryLevel: 105
    - shortcode: dagger
      type: skill
      system:
        masteryLevel: 105
    - shortcode: initiative
      type: skill
      system:
        masteryLevel: 66
    - shortcode: shield
      type: skill
      system:
        masteryLevel: 96
    - shortcode: sword
      type: skill
      name: Longknife (Sword)
      system:
        masteryLevel: 95
    - shortcode: unarmed
      type: skill
      system:
        masteryLevel: 52
    - shortcode: foraging
      type: skill
      system:
        masteryLevel: 60
    - shortcode: heraldry
      type: skill
      system:
        masteryLevel: 39
    - shortcode: physician
      type: skill
      system:
        masteryLevel: 28
    - shortcode: survival
      type: skill
      system:
        masteryLevel: 80
    - shortcode: weaponcraft
      type: skill
      system:
        masteryLevel: 48
    - shortcode: pence
      type: miscgear
      system:
        quantity: 483
    - shortcode: pursebuckram
      type: containergear
    - shortcode: LtCBoot
      type: armorgear
    - shortcode: RClk
      type: armorgear
    - shortcode: CHood
      type: armorgear
    - shortcode: SgLeg
      type: armorgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: LtTunic
      type: armorgear
    - shortcode: SgTunic
      type: armorgear
    - shortcode: Dgr
      type: weapongear
    - shortcode: HBw
      type: weapongear
    - shortcode: backbagsmcanvas
      type: containergear
    - shortcode: beltpouchl3
      type: containergear
    - shortcode: tndrbx
      type: miscgear
    - shortcode: LtCap
      type: armorgear
    - shortcode: LtLeg
      type: armorgear
    - shortcode: spoonwooden
      type: miscgear
    - shortcode: tankardwooden
      type: miscgear
    - shortcode: tndrbx
      type: miscgear
sohl:
  kbcat: archetype
  archetype: 1
  attributes:
    str: 18
    end: 16
    dex: 15
    agl: 7
    per: 15
    snt: 15
    cml: 11
    aur: 16
    wil: 13
    rea: 16
    cre: 13
    emp: 12
    elo: 10
    mor: 17
    voi: 11
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
      name: Heartbow (Bow)
      system:
        masteryLevelBase: 105
    - shortcode: awar
      type: skill
      system:
        masteryLevelBase: 52
    - shortcode: chrm
      type: skill
    - shortcode: clmb
      type: skill
      system:
        masteryLevelBase: 52
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
        masteryLevelBase: 66
    - shortcode: shok
      type: skill
    - shortcode: intr
      type: skill
      system:
        masteryLevelBase: 45
    - shortcode: jump
      type: skill
      system:
        masteryLevelBase: 50
    - shortcode: melee
      type: skill
      system:
        masteryLevelBase: 99
    - shortcode: dge
      type: skill
    - shortcode: pysn
      type: skill
      system:
        masteryLevelBase: 28
    - shortcode: ridg
      type: skill
    - shortcode: sing
      type: skill
      system:
        masteryLevelBase: 36
    - shortcode: stlth
      type: skill
      system:
        masteryLevelBase: 44
    - shortcode: srvl
      type: skill
      system:
        masteryLevelBase: 80
    - shortcode: spirit
      type: skill
    - shortcode: swim
      type: skill
    - shortcode: thtcs
      type: skill
    - shortcode: thro
      type: skill
      system:
        masteryLevelBase: 75
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
      name: Language, Serf
      system:
        masteryLevelBase: 63
    - shortcode: hrld
      type: skill
      system:
        masteryLevelBase: 39
    - shortcode: wpnc
      type: skill
      system:
        masteryLevelBase: 48
    - shortcode: pence
      type: miscgear
      system:
        quantity: 483
    - shortcode: pouchbuckram
      type: containergear
    - shortcode: LtCBoot
      type: armorgear
    - shortcode: RClk
      type: armorgear
    - shortcode: CHood
      type: armorgear
    - shortcode: SgLeg
      type: armorgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: LtTunic
      type: armorgear
    - shortcode: SgTunic
      type: armorgear
    - shortcode: Dgr
      type: weapongear
    - shortcode: bgsmcvs
      type: containergear
    - shortcode: beltpouchl3
      type: containergear
    - shortcode: tndrbx
      type: miscgear
    - shortcode: LtCap
      type: armorgear
    - shortcode: LtTrsr
      type: armorgear
    - shortcode: spoonpewte
      type: miscgear
    - shortcode: tankardpew
      type: miscgear
---

# Appearance {#appearance}

**Height**: 5' 7"
**Frame**: Medium
**Weight**: 149
**Size**: 6
**Comeliness**: Average
**Complexion**: Fair
**Hair Color**: Brown
**Eye Color**: Blue
**Voice**: Average

# Dossier {#dossier}

**Age**: 292
**Birthday**: 5 Larane 428
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: 3rd child of 3
**Siblings**: MFM
**Parentage**: Offspring
**Offspring**: Both parents alive and living together
**Estrangement**: Unpopular
**Clanhead**: Grandfather's Cousin
**Medical**: Birthmarks

## Notes

Modifier to Frame of -2 (from 11) {Species=Sindarin}

Modifier to AttributesSTR of +1 (from 17) {Species=Sindarin}

Modifier to AttributesSTA of +1 (from 15) {Species=Sindarin}

Modifier to AttributesDEX of +2 (from 13) {Species=Sindarin}

Modifier to AttributesAGL of +2 (from 5) {Species=Sindarin}

Modifier to AttributesEYE of +2 (from 10) {Species=Sindarin}

Modifier to AttributesHGR of +2 (from 12) {Species=Sindarin}

Modifier to AttributesSML of +3 (from 12) {Species=Sindarin}

Modifier to AttributesVOI of +2 (from 9) {Species=Sindarin}

Modifier to AttributesCOM of +1 (from 10) {Species=Sindarin}

Modifier to AttributesAUR of +4 (from 12) {Species=Sindarin}

Modifier to AttributesMOR of +3 (from 14) {Species=Sindarin}

Modifier to SiblingRank of -20 (from 73) {Species=Sindarin}

Modifier to StartingEquipment of +100 (from 45) {SocialClass=Serf}
