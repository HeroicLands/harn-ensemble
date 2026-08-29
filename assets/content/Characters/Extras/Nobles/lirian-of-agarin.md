---
aliases:
  - Lirian of Agarin
tags: []
name:
  full: Lirian of Agarin
  title: ""
  given: Lirian
  clan: Agarin
  aliases: []
id: HrqAOS60QRUkYsse
folder: wYO4XEaOHdLCVUM0
shortcode: lirianofagarin
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
social:
  occupation: Khuzdul High Guard
  class: serf
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: khuzdul
  gender: male
  age: 135
  birthday: 585/5/5
  height:
    m: 1.35
  weight:
    kg: 94.8
  build:
    frame: medium
  appearance:
    eye_color: grey
    hair_color: strawberry blond
    skin_color: pale
    complexion: attractive
    extra_features:
      - "*Leprosy"
hm3:
  species: khuzdul
  sunsign: angberelius-ahnu
  attributes:
    str: 14
    sta: 12
    dex: 17
    agl: 10
    int: 14
    aur: 12
    wil: 16
    eye: 8
    hrg: 14
    sml: 15
    voi: 15
    cml: 14
    mor: 8
    end: 14
  move: 7
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
        masteryLevel: 112
    - shortcode: jumping
      type: skill
      system:
        masteryLevel: 44
    - shortcode: stealth
      type: skill
      system:
        masteryLevel: 65
    - shortcode: throwing
      type: skill
      system:
        masteryLevel: 52
    - shortcode: awareness
      type: skill
      system:
        masteryLevel: 84
    - shortcode: intrigue
      type: skill
      system:
        masteryLevel: 56
    - shortcode: language
      type: skill
      name: Language, Serf
      system:
        masteryLevel: 80
    - shortcode: oratory
      type: skill
      system:
        masteryLevel: 42
    - shortcode: rhetoric
      type: skill
      system:
        masteryLevel: 75
    - shortcode: singing
      type: skill
      system:
        masteryLevel: 70
    - shortcode: club
      type: skill
      name: Mace (Club)
      system:
        masteryLevel: 105
    - shortcode: dagger
      type: skill
      system:
        masteryLevel: 105
    - shortcode: initiative
      type: skill
      system:
        masteryLevel: 112
    - shortcode: polearm
      type: skill
      name: Poleaxe (Polearm)
      system:
        masteryLevel: 112
    - shortcode: shield
      type: skill
      system:
        masteryLevel: 112
    - shortcode: unarmed
      type: skill
      system:
        masteryLevel: 78
    - shortcode: foraging
      type: skill
      system:
        masteryLevel: 90
    - shortcode: heraldry
      type: skill
      system:
        masteryLevel: 39
    - shortcode: physician
      type: skill
      system:
        masteryLevel: 78
    - shortcode: survival
      type: skill
      system:
        masteryLevel: 60
    - shortcode: weaponcraft
      type: skill
      system:
        masteryLevel: 64
    - shortcode: pence
      type: miscgear
      system:
        quantity: 4320
    - shortcode: pursebuckram
      type: containergear
    - shortcode: PlBreast
      type: armorgear
    - shortcode: CHood
      type: armorgear
    - shortcode: MHbk
      type: armorgear
    - shortcode: SgLeg
      type: armorgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: Pl34Hlm
      type: armorgear
    - shortcode: SgTunic
      type: armorgear
    - shortcode: Dgr
      type: weapongear
    - shortcode: PAxe
      type: weapongear
    - name: Armor Repair kit
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        value: 24
        weight: 10
    - shortcode: backbagsmcanvas
      type: containergear
    - shortcode: beltpouchl3
      type: containergear
    - name: Circlet, Silver
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        value: 300
        weight: 0.3125
    - shortcode: LtCap
      type: armorgear
    - shortcode: spoonwooden
      type: miscgear
sohl:
  kbcat: archetype
  archetype: 1
  attributes:
    str: 14
    end: 12
    dex: 17
    agl: 10
    per: 13
    snt: 15
    cml: 14
    aur: 12
    wil: 16
    rea: 14
    cre: 16
    emp: 12
    elo: 16
    mor: 8
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
        masteryLevelBase: 84
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
        masteryLevelBase: 112
    - shortcode: shok
      type: skill
    - shortcode: intr
      type: skill
      system:
        masteryLevelBase: 56
    - shortcode: jump
      type: skill
      system:
        masteryLevelBase: 44
    - shortcode: melee
      type: skill
      system:
        masteryLevelBase: 108
    - shortcode: dge
      type: skill
    - shortcode: pysn
      type: skill
      system:
        masteryLevelBase: 78
    - shortcode: ridg
      type: skill
    - shortcode: sing
      type: skill
      system:
        masteryLevelBase: 70
    - shortcode: stlth
      type: skill
      system:
        masteryLevelBase: 65
    - shortcode: srvl
      type: skill
      system:
        masteryLevelBase: 60
    - shortcode: spirit
      type: skill
    - shortcode: swim
      type: skill
    - shortcode: thtcs
      type: skill
    - shortcode: thro
      type: skill
      system:
        masteryLevelBase: 52
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
        masteryLevelBase: 80
    - shortcode: hrld
      type: skill
      system:
        masteryLevelBase: 39
    - shortcode: wpnc
      type: skill
      system:
        masteryLevelBase: 64
    - shortcode: pence
      type: miscgear
      system:
        quantity: 4320
    - shortcode: pouchbuckram
      type: containergear
    - shortcode: PlBreast
      type: armorgear
    - shortcode: CHood
      type: armorgear
    - shortcode: MHbk
      type: armorgear
    - shortcode: SgLeg
      type: armorgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: Pl34Hlm
      type: armorgear
    - shortcode: SgTunic
      type: armorgear
    - shortcode: Dgr
      type: weapongear
    - shortcode: PAxe
      type: weapongear
    - shortcode: armrsup
      type: miscgear
    - shortcode: bgsmcvs
      type: containergear
    - shortcode: beltpouchl3
      type: containergear
    - shortcode: circletsilver
      type: miscgear
    - shortcode: LtCap
      type: armorgear
    - shortcode: spoonpewte
      type: miscgear
---

# Appearance {#appearance}

**Height**: 4' 5"
**Frame**: Medium
**Weight**: 209
**Size**: 8
**Comeliness**: Attractive
**Complexion**: Pale
**Hair Color**: Strawberry Blond
**Eye Color**: Grey
**Voice**: Pleasant

# Dossier {#dossier}

**Age**: 135
**Birthday**: 5 Larane 585
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: 2nd child of 4
**Siblings**: mMFM
**Parentage**: Orphan
**Estrangement**: Unpopular
**Clanhead**: Father's Father/Mother
**Medical**: *Leprosy

## Notes

Modifier to Frame of +3 (from 9) {Species=Khuzdul}

Modifier to AttributesSTR of +4 (from 13) {Species=Khuzdul}

Modifier to AttributesSTA of +2 (from 10) {Species=Khuzdul}

Modifier to AttributesDEX of +1 (from 16) {Species=Khuzdul}

Modifier to AttributesEYE of +1 (from 7) {Species=Khuzdul}

Modifier to AttributesHGR of +2 (from 12) {Species=Khuzdul}

Modifier to AttributesSML of +2 (from 13) {Species=Khuzdul}

Modifier to AttributesCOM of +4 (from 13) {Species=Khuzdul}

Modifier to AttributesAUR of -1 (from 13) {Species=Khuzdul}

Modifier to AttributesWIL of +3 (from 13) {Species=Khuzdul}

Modifier to SiblingRank of -20 (from 63) {Species=Khuzdul}

Leprosy mod to Comeliness: -3

103lbs weight resulted in -3 strength mod.

Modifier to StartingEquipment of +100 (from 11) {SocialClass=Serf}
