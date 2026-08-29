---
aliases:
  - Keldarith of Kal
tags: []
name:
  full: Keldarith of Kal
  title: ""
  given: Keldarith
  clan: Kal
  aliases: []
id: 4a9DphGgsTZwMxMv
folder: wqZxeSsm1ABX2AGx
shortcode: keldarithofkal
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
package: harnensemble
social:
  occupation: Khuzdul Clansman
  class: unguilded
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: khuzdul
  gender: male
  age: 98
  birthday: 622/10/24
  height:
    m: 1.3
  weight:
    kg: 91.63
  build:
    frame: medium
  appearance:
    eye_color: hazel
    hair_color: auburn
    skin_color: fair
    complexion: beautiful
    extra_features:
      - Addiction
hm3:
  species: khuzdul
  sunsign: skorus
  attributes:
    str: 17
    sta: 10
    dex: 9
    agl: 8
    int: 7
    aur: 13
    wil: 10
    eye: 8
    hrg: 15
    sml: 18
    voi: 10
    cml: 17
    mor: 13
    end: 12
  move: 11
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
        masteryLevel: 55
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
        masteryLevel: 33
    - shortcode: throwing
      type: skill
      system:
        masteryLevel: 44
    - shortcode: awareness
      type: skill
      system:
        masteryLevel: 65
    - shortcode: intrigue
      type: skill
      system:
        masteryLevel: 33
    - shortcode: language
      type: skill
      name: Language, Unguilded
      system:
        masteryLevel: 59
    - shortcode: oratory
      type: skill
      system:
        masteryLevel: 33
    - shortcode: rhetoric
      type: skill
      system:
        masteryLevel: 30
    - shortcode: singing
      type: skill
      system:
        masteryLevel: 33
    - shortcode: axe
      type: skill
      name: Handaxe (Axe)
      system:
        masteryLevel: 84
    - shortcode: initiative
      type: skill
      system:
        masteryLevel: 54
    - shortcode: shield
      type: skill
      system:
        masteryLevel: 55
    - shortcode: spear
      type: skill
      system:
        masteryLevel: 98
    - shortcode: unarmed
      type: skill
      system:
        masteryLevel: 66
    - shortcode: foraging
      type: skill
      system:
        masteryLevel: 44
    - shortcode: heraldry
      type: skill
      system:
        masteryLevel: 20
    - shortcode: physician
      type: skill
      system:
        masteryLevel: 18
    - shortcode: survival
      type: skill
      system:
        masteryLevel: 55
    - shortcode: weaponcraft
      type: skill
      system:
        masteryLevel: 36
    - shortcode: pence
      type: miscgear
      system:
        quantity: 0
    - shortcode: pursebuckram
      type: containergear
    - shortcode: LtCBoot
      type: armorgear
    - shortcode: SgClk
      type: armorgear
    - shortcode: QGmb
      type: armorgear
    - shortcode: LtLeg
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
    - shortcode: backbagsmcanvas
      type: containergear
    - name: "Debt to Money Lender: Kodarith of Haclean for 40d"
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        weight: 1
    - shortcode: tankardwooden
      type: miscgear
sohl:
  kbcat: archetype
  archetype: 1
  attributes:
    str: 17
    end: 10
    dex: 9
    agl: 8
    per: 15
    snt: 18
    cml: 17
    aur: 13
    wil: 10
    rea: 7
    cre: 15
    emp: 13
    elo: 11
    mor: 13
    voi: 10
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
        masteryLevelBase: 65
    - shortcode: chrm
      type: skill
    - shortcode: clmb
      type: skill
      system:
        masteryLevelBase: 55
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
        masteryLevelBase: 33
    - shortcode: jump
      type: skill
      system:
        masteryLevelBase: 44
    - shortcode: melee
      type: skill
      system:
        masteryLevelBase: 79
    - shortcode: dge
      type: skill
    - shortcode: pysn
      type: skill
      system:
        masteryLevelBase: 18
    - shortcode: ridg
      type: skill
    - shortcode: sing
      type: skill
      system:
        masteryLevelBase: 33
    - shortcode: stlth
      type: skill
      system:
        masteryLevelBase: 33
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
      name: Language, Unguilded
      system:
        masteryLevelBase: 59
    - shortcode: hrld
      type: skill
      system:
        masteryLevelBase: 20
    - shortcode: wpnc
      type: skill
      system:
        masteryLevelBase: 36
    - shortcode: pence
      type: miscgear
      system:
        quantity: 0
    - shortcode: pouchbuckram
      type: containergear
    - shortcode: LtCBoot
      type: armorgear
    - shortcode: SgClk
      type: armorgear
    - shortcode: GTnc
      type: armorgear
    - shortcode: LtTrsr
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
    - shortcode: bgsmcvs
      type: containergear
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
**Hair Color**: Auburn
**Eye Color**: Hazel
**Voice**: Average

# Dossier {#dossier}

**Age**: 98
**Birthday**: 24 Ilvin 622
**Culture**: Feudal
**Social Class**: Unguilded
**Sibling Rank**: 4th child of 4
**Siblings**: MmMM
**Parentage**: Bastard
**Estrangement**: Average
**Clanhead**: Grandfather's Father/Mother
**Medical**: Addiction

## Notes

Modifier to Frame of +3 (from 9) {Species=Khuzdul}

Modifier to AttributesSTR of +4 (from 16) {Species=Khuzdul}

Modifier to AttributesSTA of +2 (from 8) {Species=Khuzdul}

Modifier to AttributesDEX of +1 (from 8) {Species=Khuzdul}

Modifier to AttributesEYE of +1 (from 7) {Species=Khuzdul}

Modifier to AttributesHGR of +2 (from 13) {Species=Khuzdul}

Modifier to AttributesSML of +2 (from 16) {Species=Khuzdul}

Modifier to AttributesCOM of +4 (from 13) {Species=Khuzdul}

Modifier to AttributesAUR of -1 (from 14) {Species=Khuzdul}

Modifier to AttributesWIL of +3 (from 7) {Species=Khuzdul}

Modifier to SiblingRank of -20 (from 99) {Species=Khuzdul}

91lbs weight resulted in -3 strength mod.

Modifier to StartingEquipment of +200 (from 10) {SocialClass=Unguilded}
