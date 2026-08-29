---
aliases:
  - Veteran Karithan of Wesin
tags: []
name:
  full: Veteran Karithan of Wesin
  title: Veteran
  given: Karithan
  clan: Wesin
  aliases: []
id: xFcSIgThvrp5paiB
folder: ZMLVnTuUb85MUQMD
shortcode: veterankarithanofwesin
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
package: harnensemble
social:
  occupation: Feudal Guardsman, Light
  class: unguilded
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: human
  gender: male
  age: 31
  birthday: 689/2/5
  height:
    m: 1.85
  weight:
    kg: 141.07
  build:
    frame: massive
  appearance:
    eye_color: blue
    hair_color: silver
    skin_color: fair
    complexion: average
    extra_features:
      - "*Epilepsy"
hm3:
  species: human
  sunsign: aralius-ulandus
  attributes:
    str: 13
    sta: 16
    dex: 13
    agl: 8
    int: 19
    aur: 9
    wil: 11
    eye: 11
    hrg: 9
    sml: 13
    voi: 15
    cml: 11
    mor: 14
    end: 13
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
        masteryLevel: 65
    - shortcode: condition
      type: skill
      system:
        masteryLevel: 84
    - shortcode: jumping
      type: skill
      system:
        masteryLevel: 36
    - shortcode: stealth
      type: skill
      system:
        masteryLevel: 27
    - shortcode: throwing
      type: skill
      system:
        masteryLevel: 48
    - shortcode: awareness
      type: skill
      system:
        masteryLevel: 55
    - shortcode: intrigue
      type: skill
      system:
        masteryLevel: 39
    - shortcode: language
      type: skill
      name: Language, Unguilded
      system:
        masteryLevel: 65
    - shortcode: oratory
      type: skill
      system:
        masteryLevel: 45
    - shortcode: rhetoric
      type: skill
      system:
        masteryLevel: 45
    - shortcode: singing
      type: skill
      system:
        masteryLevel: 65
    - shortcode: dagger
      type: skill
      system:
        masteryLevel: 84
    - shortcode: initiative
      type: skill
      system:
        masteryLevel: 90
    - shortcode: shield
      type: skill
      system:
        masteryLevel: 70
    - shortcode: spear
      type: skill
      system:
        masteryLevel: 84
    - shortcode: sword
      type: skill
      name: Shortsword (Sword)
      system:
        masteryLevel: 65
    - shortcode: unarmed
      type: skill
      system:
        masteryLevel: 52
    - shortcode: foraging
      type: skill
      system:
        masteryLevel: 68
    - shortcode: heraldry
      type: skill
      system:
        masteryLevel: 22
    - shortcode: physician
      type: skill
      system:
        masteryLevel: 28
    - shortcode: survival
      type: skill
      system:
        masteryLevel: 68
    - shortcode: weaponcraft
      type: skill
      system:
        masteryLevel: 24
    - shortcode: pence
      type: miscgear
      system:
        quantity: 0
    - shortcode: pursebuckram
      type: containergear
    - shortcode: RByr
      type: armorgear
    - shortcode: SgClk
      type: armorgear
    - shortcode: CHood
      type: armorgear
    - shortcode: KHlfHelm
      type: armorgear
    - shortcode: LtLeg
      type: armorgear
    - shortcode: SgLeg
      type: armorgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: SgTunic
      type: armorgear
    - shortcode: Dgr
      type: weapongear
    - shortcode: Kni
      type: weapongear
    - shortcode: backbagsmcanvas
      type: containergear
    - name: "Debt to Money Lender: Terlinen of Chatil for 24d"
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        weight: 1
    - shortcode: tndrbx
      type: miscgear
    - shortcode: LtCap
      type: armorgear
    - shortcode: RndSh
      type: weapongear
    - shortcode: tankardwooden
      type: miscgear
sohl:
  kbcat: archetype
  archetype: 1
  attributes:
    str: 13
    end: 16
    dex: 13
    agl: 8
    per: 11
    snt: 13
    cml: 11
    aur: 9
    wil: 11
    rea: 18
    cre: 11
    emp: 5
    elo: 11
    mor: 14
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
    - shortcode: awar
      type: skill
      system:
        masteryLevelBase: 55
    - shortcode: chrm
      type: skill
    - shortcode: clmb
      type: skill
      system:
        masteryLevelBase: 65
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
        masteryLevelBase: 90
    - shortcode: shok
      type: skill
    - shortcode: intr
      type: skill
      system:
        masteryLevelBase: 39
    - shortcode: jump
      type: skill
      system:
        masteryLevelBase: 36
    - shortcode: melee
      type: skill
      system:
        masteryLevelBase: 76
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
        masteryLevelBase: 65
    - shortcode: stlth
      type: skill
      system:
        masteryLevelBase: 27
    - shortcode: srvl
      type: skill
      system:
        masteryLevelBase: 68
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
        masteryLevelBase: 65
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
        quantity: 0
    - shortcode: pouchbuckram
      type: containergear
    - shortcode: RByr
      type: armorgear
    - shortcode: SgClk
      type: armorgear
    - shortcode: CHood
      type: armorgear
    - shortcode: KHlfHelm
      type: armorgear
    - shortcode: LtTrsr
      type: armorgear
    - shortcode: SgLeg
      type: armorgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: SgTunic
      type: armorgear
    - shortcode: Dgr
      type: weapongear
    - shortcode: Kni
      type: weapongear
    - shortcode: bgsmcvs
      type: containergear
    - shortcode: tndrbx
      type: miscgear
    - shortcode: LtCap
      type: armorgear
    - shortcode: RndSh
      type: weapongear
    - shortcode: tankardpew
      type: miscgear
---

# Appearance {#appearance}

**Height**: 6' 1"
**Frame**: Massive
**Weight**: 311
**Size**: 10
**Comeliness**: Average
**Complexion**: Fair
**Hair Color**: Silver
**Eye Color**: Blue
**Voice**: Pleasant

# Dossier {#dossier}

**Age**: 31
**Birthday**: 5 Peonu 689
**Culture**: Feudal
**Social Class**: Unguilded
**Sibling Rank**: 2nd child of 3
**Siblings**: FMf
**Parentage**: Bastard
**Estrangement**: Average
**Clanhead**: Grandfather's Cousin
**Medical**: *Epilepsy

## Notes

Modifier to AttributesAGL of -2 (from 12) {Frame=Massive}

Modifier to HairColor of +25 (from 92) {Complexion=Fair, Species=Human}

Modifier to EyeColor of -10 (from 25) {Complexion=Fair, Species=Human}

Epilepsy mod to Intelligence: +2

210lbs weight resulted in +3 strength mod.

Massive frame resulted in -2 agility mod.

Modifier to StartingEquipment of +200 (from 20) {SocialClass=Unguilded}
