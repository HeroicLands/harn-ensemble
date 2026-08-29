---
aliases:
  - Bornagar of Caben
tags: []
name:
  full: Bornagar of Caben
  title: ""
  given: Bornagar
  clan: Caben
  aliases: []
id: vljg5k6WXCvCvWIU
folder: wqZxeSsm1ABX2AGx
shortcode: bornagarofcaben
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
package: harnensemble
social:
  occupation: Sindarin Horsebow
  class: unguilded
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: sindarin
  gender: male
  age: 289
  birthday: 431/12/1
  height:
    m: 1.7
  weight:
    kg: 53.98
  build:
    frame: scant
  appearance:
    eye_color: green
    hair_color: silver
    skin_color: pale
    complexion: beautiful
    extra_features:
      - Sterile
hm3:
  species: sindarin
  sunsign: masara-lado
  attributes:
    str: 13
    sta: 13
    dex: 11
    agl: 16
    int: 7
    aur: 17
    wil: 11
    eye: 13
    hrg: 12
    sml: 16
    voi: 8
    cml: 18
    mor: 13
    end: 12
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
        masteryLevel: 52
    - shortcode: condition
      type: skill
      system:
        masteryLevel: 78
    - shortcode: dancing
      type: skill
      system:
        masteryLevel: 56
    - shortcode: jumping
      type: skill
      system:
        masteryLevel: 75
    - shortcode: stealth
      type: skill
      system:
        masteryLevel: 39
    - shortcode: throwing
      type: skill
      system:
        masteryLevel: 48
    - shortcode: awareness
      type: skill
      system:
        masteryLevel: 52
    - shortcode: intrigue
      type: skill
      system:
        masteryLevel: 33
    - shortcode: language
      type: skill
      name: Language, Unguilded
      system:
        masteryLevel: 58
    - shortcode: musician
      type: skill
      system:
        masteryLevel: 24
    - shortcode: oratory
      type: skill
      system:
        masteryLevel: 22
    - shortcode: rhetoric
      type: skill
      system:
        masteryLevel: 40
    - shortcode: singing
      type: skill
      system:
        masteryLevel: 30
    - shortcode: bow
      type: skill
      name: Heartbow (Bow)
      system:
        masteryLevel: 96
    - shortcode: initiative
      type: skill
      system:
        masteryLevel: 96
    - shortcode: polearm
      type: skill
      name: Lance (Polearm)
      system:
        masteryLevel: 84
    - shortcode: riding
      type: skill
      system:
        masteryLevel: 84
    - shortcode: shield
      type: skill
      system:
        masteryLevel: 84
    - shortcode: sword
      type: skill
      name: Longknife (Sword)
      system:
        masteryLevel: 55
    - shortcode: unarmed
      type: skill
      system:
        masteryLevel: 60
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
        masteryLevel: 24
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
        quantity: 1416
    - shortcode: pursebuckram
      type: containergear
    - shortcode: LtCBoot
      type: armorgear
    - shortcode: SgLeg
      type: armorgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: SgTunic
      type: armorgear
    - shortcode: Dgr
      type: weapongear
    - shortcode: HBw
      type: weapongear
    - shortcode: tndrbx
      type: miscgear
    - shortcode: LtLeg
      type: armorgear
    - shortcode: pipesmokin
      type: miscgear
    - shortcode: waterskinsm
      type: miscgear
sohl:
  kbcat: archetype
  archetype: 1
  attributes:
    str: 13
    end: 13
    dex: 11
    agl: 16
    per: 15
    snt: 16
    cml: 18
    aur: 17
    wil: 11
    rea: 7
    cre: 12
    emp: 11
    elo: 11
    mor: 13
    voi: 8
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
        masteryLevelBase: 96
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
      system:
        masteryLevelBase: 56
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
        masteryLevelBase: 96
    - shortcode: shok
      type: skill
    - shortcode: intr
      type: skill
      system:
        masteryLevelBase: 33
    - shortcode: jump
      type: skill
      system:
        masteryLevelBase: 75
    - shortcode: melee
      type: skill
      system:
        masteryLevelBase: 74
    - shortcode: dge
      type: skill
    - shortcode: pysn
      type: skill
      system:
        masteryLevelBase: 24
    - shortcode: ridg
      type: skill
      system:
        masteryLevelBase: 84
    - shortcode: sing
      type: skill
      system:
        masteryLevelBase: 30
    - shortcode: stlth
      type: skill
      system:
        masteryLevelBase: 39
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
        masteryLevelBase: 48
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
      name: Language, Unguilded
      system:
        masteryLevelBase: 58
    - shortcode: musc
      type: skill
      system:
        masteryLevelBase: 24
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
        quantity: 1416
    - shortcode: pouchbuckram
      type: containergear
    - shortcode: LtCBoot
      type: armorgear
    - shortcode: SgLeg
      type: armorgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: SgTunic
      type: armorgear
    - shortcode: Dgr
      type: weapongear
    - shortcode: tndrbx
      type: miscgear
    - shortcode: LtTrsr
      type: armorgear
    - shortcode: pipesmokin
      type: miscgear
    - shortcode: wtrskin
      type: containergear
---

# Appearance {#appearance}

**Height**: 5' 7"
**Frame**: Scant
**Weight**: 119
**Size**: 5
**Comeliness**: Beautiful
**Complexion**: Pale
**Hair Color**: Silver
**Eye Color**: Green
**Voice**: Unpleasant

# Dossier {#dossier}

**Age**: 289
**Birthday**: 1 Morgat 431
**Culture**: Feudal
**Social Class**: Unguilded
**Sibling Rank**: 3rd child of 3
**Siblings**: MMM
**Parentage**: Orphan
**Estrangement**: Unpopular
**Clanhead**: Cousin
**Medical**: Sterile

## Notes

Modifier to Frame of -2 (from 7) {Species=Sindarin}

Modifier to AttributesSTR of +1 (from 14) {Species=Sindarin}

Modifier to AttributesSTA of +1 (from 12) {Species=Sindarin}

Modifier to AttributesDEX of +2 (from 9) {Species=Sindarin}

Modifier to AttributesAGL of +2 (from 12) {Species=Sindarin}

Modifier to AttributesEYE of +2 (from 11) {Species=Sindarin}

Modifier to AttributesHGR of +2 (from 10) {Species=Sindarin}

Modifier to AttributesSML of +3 (from 13) {Species=Sindarin}

Modifier to AttributesVOI of +2 (from 6) {Species=Sindarin}

Modifier to AttributesCOM of +1 (from 17) {Species=Sindarin}

Modifier to AttributesAUR of +4 (from 13) {Species=Sindarin}

Modifier to AttributesMOR of +3 (from 10) {Species=Sindarin}

Modifier to SiblingRank of -20 (from 75) {Species=Sindarin}

119lbs weight resulted in -2 strength mod.

Scant frame resulted in +2 agility mod.

Modifier to StartingEquipment of +200 (from 89) {SocialClass=Unguilded}
