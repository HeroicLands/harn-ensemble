---
aliases:
  - Arthel of Balliar
tags: []
name:
  full: Arthel of Balliar
  title: ""
  given: Arthel
  clan: Balliar
  aliases: []
id: JGFDiEmahtpO1PbL
folder: wqZxeSsm1ABX2AGx
shortcode: arthelofballiar
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
package: harnensemble
social:
  occupation: Sindarin Ranger, Light
  class: guilded
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: sindarin
  gender: female
  age: 235
  birthday: 485/5/5
  height:
    m: 1.57
  weight:
    kg: 58.97
  build:
    frame: medium
  appearance:
    eye_color: blue
    hair_color: blonde
    skin_color: pale
    complexion: average
    extra_features:
      - Sterile
hm3:
  species: sindarin
  sunsign: angberelius-ahnu
  attributes:
    str: 11
    sta: 14
    dex: 11
    agl: 11
    int: 8
    aur: 15
    wil: 12
    eye: 12
    hrg: 8
    sml: 14
    voi: 15
    cml: 12
    mor: 15
    end: 12
  move: 8
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
        masteryLevel: 44
    - shortcode: condition
      type: skill
      system:
        masteryLevel: 60
    - shortcode: jumping
      type: skill
      system:
        masteryLevel: 44
    - shortcode: stealth
      type: skill
      system:
        masteryLevel: 30
    - shortcode: throwing
      type: skill
      system:
        masteryLevel: 44
    - shortcode: awareness
      type: skill
      system:
        masteryLevel: 44
    - shortcode: intrigue
      type: skill
      system:
        masteryLevel: 33
    - shortcode: language
      type: skill
      name: Language, Guilded
      system:
        masteryLevel: 71
    - shortcode: oratory
      type: skill
      system:
        masteryLevel: 33
    - shortcode: rhetoric
      type: skill
      system:
        masteryLevel: 33
    - shortcode: singing
      type: skill
      system:
        masteryLevel: 36
    - shortcode: bow
      type: skill
      name: Heartbow (Bow)
      system:
        masteryLevel: 66
    - shortcode: dagger
      type: skill
      system:
        masteryLevel: 60
    - shortcode: initiative
      type: skill
      system:
        masteryLevel: 66
    - shortcode: shield
      type: skill
      system:
        masteryLevel: 66
    - shortcode: sword
      type: skill
      name: Longknife (Sword)
      system:
        masteryLevel: 84
    - shortcode: unarmed
      type: skill
      system:
        masteryLevel: 44
    - shortcode: foraging
      type: skill
      system:
        masteryLevel: 44
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
        masteryLevel: 24
    - shortcode: pence
      type: miscgear
      system:
        quantity: 36
    - shortcode: pursebuckram
      type: containergear
    - shortcode: RClk
      type: armorgear
    - shortcode: RCowl
      type: armorgear
    - shortcode: BLeg
      type: armorgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: CTunic
      type: armorgear
    - shortcode: LtTunic
      type: armorgear
    - shortcode: Dgr
      type: weapongear
    - shortcode: LKni
      type: weapongear
    - shortcode: backbagmed
      type: containergear
    - shortcode: RCap
      type: armorgear
    - shortcode: LtLeg
      type: armorgear
    - shortcode: pipesmokin
      type: miscgear
    - shortcode: spoonpewte
      type: miscgear
    - shortcode: tankardpew
      type: miscgear
sohl:
  kbcat: archetype
  archetype: 1
  attributes:
    str: 11
    end: 14
    dex: 11
    agl: 11
    per: 11
    snt: 14
    cml: 12
    aur: 15
    wil: 12
    rea: 8
    cre: 11
    emp: 14
    elo: 16
    mor: 15
    voi: 15
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
        masteryLevelBase: 66
    - shortcode: awar
      type: skill
      system:
        masteryLevelBase: 44
    - shortcode: chrm
      type: skill
    - shortcode: clmb
      type: skill
      system:
        masteryLevelBase: 44
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
        masteryLevelBase: 33
    - shortcode: jump
      type: skill
      system:
        masteryLevelBase: 44
    - shortcode: melee
      type: skill
      system:
        masteryLevelBase: 70
    - shortcode: dge
      type: skill
    - shortcode: pysn
      type: skill
      system:
        masteryLevelBase: 20
    - shortcode: ridg
      type: skill
    - shortcode: sing
      type: skill
      system:
        masteryLevelBase: 36
    - shortcode: stlth
      type: skill
      system:
        masteryLevelBase: 30
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
        masteryLevelBase: 44
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
        masteryLevelBase: 71
    - shortcode: hrld
      type: skill
      system:
        masteryLevelBase: 22
    - shortcode: wpnc
      type: skill
      system:
        masteryLevelBase: 24
    - shortcode: pence
      type: miscgear
      system:
        quantity: 36
    - shortcode: pouchbuckram
      type: containergear
    - shortcode: RClk
      type: armorgear
    - shortcode: RCowl
      type: armorgear
    - shortcode: BLeg
      type: armorgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: CTunic
      type: armorgear
    - shortcode: LtTunic
      type: armorgear
    - shortcode: Dgr
      type: weapongear
    - shortcode: LKni
      type: weapongear
    - shortcode: backbagmed
      type: containergear
    - shortcode: RCap
      type: armorgear
    - shortcode: LtTrsr
      type: armorgear
    - shortcode: pipesmokin
      type: miscgear
    - shortcode: spoonpewte
      type: miscgear
    - shortcode: tankardpew
      type: miscgear
---

# Appearance {#appearance}

**Height**: 5' 2"
**Frame**: Medium
**Weight**: 130
**Size**: 5
**Comeliness**: Average
**Complexion**: Pale
**Hair Color**: Blond
**Eye Color**: Blue
**Voice**: Pleasant

# Dossier {#dossier}

**Age**: 235
**Birthday**: 5 Larane 485
**Culture**: Feudal
**Social Class**: Guilded
**Sibling Rank**: 3rd child of 3
**Siblings**: FmF
**Parentage**: Offspring
**Offspring**: Both parents alive and living together
**Estrangement**: Popular
**Clanhead**: Father/Mother
**Medical**: Sterile

## Notes

Modifier to Frame of -2 (from 11) {Species=Sindarin}

Modifier to AttributesSTR of +1 (from 12) {Species=Sindarin}

Modifier to AttributesSTA of +1 (from 13) {Species=Sindarin}

Modifier to AttributesDEX of +2 (from 9) {Species=Sindarin}

Modifier to AttributesAGL of +2 (from 9) {Species=Sindarin}

Modifier to AttributesEYE of +2 (from 10) {Species=Sindarin}

Modifier to AttributesHGR of +2 (from 6) {Species=Sindarin}

Modifier to AttributesSML of +3 (from 11) {Species=Sindarin}

Modifier to AttributesVOI of +2 (from 13) {Species=Sindarin}

Modifier to AttributesCOM of +1 (from 11) {Species=Sindarin}

Modifier to AttributesAUR of +4 (from 11) {Species=Sindarin}

Modifier to AttributesMOR of +3 (from 12) {Species=Sindarin}

Modifier to SiblingRank of -20 (from 86) {Species=Sindarin}

130lbs weight resulted in -2 strength mod.

Modifier to StartingEquipment of +300 (from 54) {SocialClass=Guilded}
