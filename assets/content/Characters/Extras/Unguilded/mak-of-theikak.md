---
aliases:
  - Mak of Theikak
tags: []
name:
  full: Mak of Theikak
  title: ""
  given: Mak
  clan: Theikak
  aliases: []
id: Ef3xya3CCOmtK8z9
folder: wqZxeSsm1ABX2AGx
shortcode: makoftheikak
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
package: harnensemble
social:
  occupation: Khuzdul Clansman
  class: serf
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: khuzdul
  gender: male
  age: 117
  birthday: 603/3/26
  height:
    m: 1.3
  weight:
    kg: 91.63
  build:
    frame: medium
  appearance:
    eye_color: hazel
    hair_color: brown
    skin_color: fair
    complexion: beautiful
    extra_features:
      - Monochromasia
hm3:
  species: khuzdul
  sunsign: feniri
  attributes:
    str: 18
    sta: 11
    dex: 7
    agl: 10
    int: 9
    aur: 11
    wil: 13
    eye: 7
    hrg: 14
    sml: 11
    voi: 7
    cml: 18
    mor: 10
    end: 14
  move: 12
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
        masteryLevel: 66
    - shortcode: condition
      type: skill
      system:
        masteryLevel: 70
    - shortcode: jumping
      type: skill
      system:
        masteryLevel: 60
    - shortcode: stealth
      type: skill
      system:
        masteryLevel: 48
    - shortcode: throwing
      type: skill
      system:
        masteryLevel: 60
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
      name: Language, Serf
      system:
        masteryLevel: 59
    - shortcode: oratory
      type: skill
      system:
        masteryLevel: 22
    - shortcode: rhetoric
      type: skill
      system:
        masteryLevel: 45
    - shortcode: singing
      type: skill
      system:
        masteryLevel: 36
    - shortcode: axe
      type: skill
      name: Handaxe (Axe)
      system:
        masteryLevel: 75
    - shortcode: initiative
      type: skill
      system:
        masteryLevel: 72
    - shortcode: shield
      type: skill
      system:
        masteryLevel: 90
    - shortcode: spear
      type: skill
      system:
        masteryLevel: 105
    - shortcode: unarmed
      type: skill
      system:
        masteryLevel: 88
    - shortcode: foraging
      type: skill
      system:
        masteryLevel: 36
    - shortcode: heraldry
      type: skill
      system:
        masteryLevel: 27
    - shortcode: physician
      type: skill
      system:
        masteryLevel: 14
    - shortcode: survival
      type: skill
      system:
        masteryLevel: 55
    - shortcode: weaponcraft
      type: skill
      system:
        masteryLevel: 30
    - shortcode: pence
      type: miscgear
      system:
        quantity: 1633
    - shortcode: pursebuckram
      type: containergear
    - shortcode: CHood
      type: armorgear
    - shortcode: QGmb
      type: armorgear
    - shortcode: SgLeg
      type: armorgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: SgTunic
      type: armorgear
    - shortcode: HAxe
      type: weapongear
    - shortcode: Dgr
      type: weapongear
    - name: Anklet, Bone/Horn
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        value: 3
        weight: 0.125
    - shortcode: backbagsmcanvas
      type: containergear
    - shortcode: LtCap
      type: armorgear
    - shortcode: pipesmokin
      type: miscgear
    - shortcode: RndSh
      type: weapongear
    - shortcode: tankardwooden
      type: miscgear
sohl:
  kbcat: archetype
  archetype: 1
  attributes:
    str: 18
    end: 11
    dex: 7
    agl: 10
    per: 10
    snt: 11
    cml: 18
    aur: 11
    wil: 13
    rea: 9
    cre: 11
    emp: 11
    elo: 11
    mor: 10
    voi: 7
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
        masteryLevelBase: 66
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
        masteryLevelBase: 72
    - shortcode: shok
      type: skill
    - shortcode: intr
      type: skill
      system:
        masteryLevelBase: 44
    - shortcode: jump
      type: skill
      system:
        masteryLevelBase: 60
    - shortcode: melee
      type: skill
      system:
        masteryLevelBase: 90
    - shortcode: dge
      type: skill
    - shortcode: pysn
      type: skill
      system:
        masteryLevelBase: 14
    - shortcode: ridg
      type: skill
    - shortcode: sing
      type: skill
      system:
        masteryLevelBase: 36
    - shortcode: stlth
      type: skill
      system:
        masteryLevelBase: 48
    - shortcode: srvl
      type: skill
      system:
        masteryLevelBase: 55
    - shortcode: spirit
      type: skill
    - shortcode: swim
      type: skill
    - shortcode: thtcs
      type: skill
    - shortcode: thro
      type: skill
      system:
        masteryLevelBase: 60
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
        masteryLevelBase: 59
    - shortcode: hrld
      type: skill
      system:
        masteryLevelBase: 27
    - shortcode: wpnc
      type: skill
      system:
        masteryLevelBase: 30
    - shortcode: pence
      type: miscgear
      system:
        quantity: 1633
    - shortcode: pouchbuckram
      type: containergear
    - shortcode: CHood
      type: armorgear
    - shortcode: GTnc
      type: armorgear
    - shortcode: SgLeg
      type: armorgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: SgTunic
      type: armorgear
    - shortcode: HAxe
      type: weapongear
    - shortcode: Dgr
      type: weapongear
    - shortcode: ankletbone
      type: miscgear
    - shortcode: bgsmcvs
      type: containergear
    - shortcode: LtCap
      type: armorgear
    - shortcode: pipesmokin
      type: miscgear
    - shortcode: RndSh
      type: weapongear
    - shortcode: tankardpew
      type: miscgear
---

# Appearance {#appearance}

**Height**: 4' 3"
**Frame**: Medium
**Weight**: 202
**Size**: 8
**Comeliness**: Beautiful
**Complexion**: Fair
**Hair Color**: Brown
**Eye Color**: Hazel
**Voice**: Unpleasant

# Dossier {#dossier}

**Age**: 117
**Birthday**: 26 Kelen 603
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: Eldest of 3
**Siblings**: MMm
**Parentage**: Offspring
**Offspring**: Both parents alive and living together
**Estrangement**: Popular
**Clanhead**: Father's Cousin
**Medical**: Monochromasia

## Notes

Modifier to Frame of +3 (from 8) {Species=Khuzdul}

Modifier to AttributesSTR of +4 (from 17) {Species=Khuzdul}

Modifier to AttributesSTA of +2 (from 9) {Species=Khuzdul}

Modifier to AttributesDEX of +1 (from 6) {Species=Khuzdul}

Modifier to AttributesEYE of +1 (from 7) {Species=Khuzdul}

Modifier to AttributesHGR of +2 (from 12) {Species=Khuzdul}

Modifier to AttributesSML of +2 (from 9) {Species=Khuzdul}

Modifier to AttributesCOM of +4 (from 14) {Species=Khuzdul}

Modifier to AttributesAUR of -1 (from 12) {Species=Khuzdul}

Modifier to AttributesWIL of +3 (from 10) {Species=Khuzdul}

Modifier to SiblingRank of -20 (from 28) {Species=Khuzdul}

Eldest gets +5 on estrangement roll.

Monochromasia mod to Eyesight: -1

91lbs weight resulted in -3 strength mod.

Modifier to StartingEquipment of +100 (from 10) {SocialClass=Serf}
