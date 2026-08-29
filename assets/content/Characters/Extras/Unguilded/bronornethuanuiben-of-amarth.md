---
aliases:
  - Bronornethuanuiben of Amarth
tags: []
name:
  full: Bronornethuanuiben of Amarth
  title: ""
  given: Bronornethuanuiben
  clan: Amarth
  aliases: []
id: DgI3TSwPIZGXrefQ
folder: wqZxeSsm1ABX2AGx
shortcode: bronornethuanuibenofamarth
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
  gender: female
  age: 163
  birthday: 557/3/14
  height:
    m: 1.32
  weight:
    kg: 49.9
  build:
    frame: heavy
  appearance:
    eye_color: grey
    hair_color: black
    skin_color: fair
    complexion: ugly
    extra_features:
      - Dwarfism
hm3:
  species: sindarin
  sunsign: feniri
  attributes:
    str: 11
    sta: 11
    dex: 13
    agl: 5
    int: 13
    aur: 16
    wil: 15
    eye: 16
    hrg: 12
    sml: 16
    voi: 13
    cml: 5
    mor: 15
    end: 12
  move: 6
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
        masteryLevel: 60
    - shortcode: jumping
      type: skill
      system:
        masteryLevel: 28
    - shortcode: stealth
      type: skill
      system:
        masteryLevel: 30
    - shortcode: throwing
      type: skill
      system:
        masteryLevel: 52
    - shortcode: awareness
      type: skill
      system:
        masteryLevel: 56
    - shortcode: intrigue
      type: skill
      system:
        masteryLevel: 42
    - shortcode: language
      type: skill
      name: Language, Serf
      system:
        masteryLevel: 63
    - shortcode: oratory
      type: skill
      system:
        masteryLevel: 20
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
        masteryLevel: 78
    - shortcode: dagger
      type: skill
      system:
        masteryLevel: 70
    - shortcode: initiative
      type: skill
      system:
        masteryLevel: 55
    - shortcode: shield
      type: skill
      system:
        masteryLevel: 72
    - shortcode: sword
      type: skill
      name: Longknife (Sword)
      system:
        masteryLevel: 60
    - shortcode: unarmed
      type: skill
      system:
        masteryLevel: 36
    - shortcode: foraging
      type: skill
      system:
        masteryLevel: 56
    - shortcode: heraldry
      type: skill
      system:
        masteryLevel: 28
    - shortcode: physician
      type: skill
      system:
        masteryLevel: 42
    - shortcode: survival
      type: skill
      system:
        masteryLevel: 48
    - shortcode: weaponcraft
      type: skill
      system:
        masteryLevel: 32
    - shortcode: pence
      type: miscgear
      system:
        quantity: 138
    - shortcode: pursebuckram
      type: containergear
    - shortcode: CvCloak
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
    - shortcode: beltpouchl3
      type: containergear
    - shortcode: LtCap
      type: armorgear
    - shortcode: LtLeg
      type: armorgear
    - shortcode: pipesmokin
      type: miscgear
    - shortcode: spoonwooden
      type: miscgear
sohl:
  kbcat: archetype
  archetype: 1
  attributes:
    str: 11
    end: 11
    dex: 13
    agl: 5
    per: 17
    snt: 16
    cml: 5
    aur: 16
    wil: 15
    rea: 13
    cre: 13
    emp: 15
    elo: 15
    mor: 15
    voi: 13
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
        masteryLevelBase: 78
    - shortcode: awar
      type: skill
      system:
        masteryLevelBase: 56
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
        masteryLevelBase: 55
    - shortcode: shok
      type: skill
    - shortcode: intr
      type: skill
      system:
        masteryLevelBase: 42
    - shortcode: jump
      type: skill
      system:
        masteryLevelBase: 28
    - shortcode: melee
      type: skill
      system:
        masteryLevelBase: 67
    - shortcode: dge
      type: skill
    - shortcode: pysn
      type: skill
      system:
        masteryLevelBase: 42
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
        masteryLevelBase: 48
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
        masteryLevelBase: 63
    - shortcode: hrld
      type: skill
      system:
        masteryLevelBase: 28
    - shortcode: wpnc
      type: skill
      system:
        masteryLevelBase: 32
    - shortcode: pence
      type: miscgear
      system:
        quantity: 138
    - shortcode: pouchbuckram
      type: containergear
    - shortcode: CvCloak
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
    - shortcode: beltpouchl3
      type: containergear
    - shortcode: LtCap
      type: armorgear
    - shortcode: LtTrsr
      type: armorgear
    - shortcode: pipesmokin
      type: miscgear
    - shortcode: spoonpewte
      type: miscgear
---

# Appearance {#appearance}

**Height**: 4' 4"
**Frame**: Heavy
**Weight**: 110
**Size**: 4
**Comeliness**: Ugly
**Complexion**: Fair
**Hair Color**: Black
**Eye Color**: Grey
**Voice**: Pleasant

# Dossier {#dossier}

**Age**: 163
**Birthday**: 14 Kelen 557
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: Eldest of 5
**Siblings**: FMfFM
**Parentage**: Fostered
**Estrangement**: Unpopular
**Clanhead**: Grandfather's Aunt/Uncle
**Medical**: Dwarfism

## Notes

Modifier to Frame of -2 (from 12) {Species=Sindarin}

Modifier to AttributesSTR of +1 (from 13) {Species=Sindarin}

Modifier to AttributesSTA of +1 (from 10) {Species=Sindarin}

Modifier to AttributesDEX of +2 (from 11) {Species=Sindarin}

Modifier to AttributesAGL of +2 (from 4) {Species=Sindarin}

Modifier to AttributesEYE of +2 (from 14) {Species=Sindarin}

Modifier to AttributesHGR of +2 (from 10) {Species=Sindarin}

Modifier to AttributesSML of +3 (from 13) {Species=Sindarin}

Modifier to AttributesVOI of +2 (from 11) {Species=Sindarin}

Modifier to AttributesCOM of +1 (from 4) {Species=Sindarin}

Modifier to AttributesAUR of +4 (from 12) {Species=Sindarin}

Modifier to AttributesMOR of +3 (from 12) {Species=Sindarin}

Modifier to SiblingRank of -20 (from 18) {Species=Sindarin}

Eldest gets +5 on estrangement roll.

110lbs weight resulted in -3 strength mod.

Heavy frame resulted in -1 agility mod.

Modifier to StartingEquipment of +100 (from 69) {SocialClass=Serf}
