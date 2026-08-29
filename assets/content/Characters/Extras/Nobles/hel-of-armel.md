---
aliases:
  - Hel of Armel
tags: []
name:
  full: Hel of Armel
  title: ""
  given: Hel
  clan: Armel
  aliases: []
id: PLihCqJHhc7WpWxe
folder: wYO4XEaOHdLCVUM0
shortcode: helofarmel
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
package: harnensemble
social:
  occupation: Feudal Knight, Heavy
  class: serf
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: human
  gender: female
  age: 50
  birthday: 670/1/5
  height:
    m: 1.7
  weight:
    kg: 67.59
  build:
    frame: medium
  appearance:
    eye_color: brown
    hair_color: black
    skin_color: dark
    complexion: average
    extra_features:
      - Allergy
hm3:
  species: human
  sunsign: ulandus-lado
  attributes:
    str: 13
    sta: 13
    dex: 10
    agl: 12
    int: 13
    aur: 15
    wil: 12
    eye: 13
    hrg: 10
    sml: 13
    voi: 9
    cml: 9
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
        masteryLevel: 91
    - shortcode: condition
      type: skill
      system:
        masteryLevel: 65
    - shortcode: dancing
      type: skill
      system:
        masteryLevel: 55
    - shortcode: jumping
      type: skill
      system:
        masteryLevel: 48
    - shortcode: stealth
      type: skill
      system:
        masteryLevel: 55
    - shortcode: throwing
      type: skill
      system:
        masteryLevel: 48
    - shortcode: awareness
      type: skill
      system:
        masteryLevel: 72
    - shortcode: intrigue
      type: skill
      system:
        masteryLevel: 52
    - shortcode: language
      type: skill
      name: Language, Serf
      system:
        masteryLevel: 72
    - shortcode: oratory
      type: skill
      system:
        masteryLevel: 30
    - shortcode: rhetoric
      type: skill
      system:
        masteryLevel: 33
    - shortcode: singing
      type: skill
      system:
        masteryLevel: 36
    - shortcode: axe
      type: skill
      name: Handaxe (Axe)
      system:
        masteryLevel: 72
    - shortcode: dagger
      type: skill
      system:
        masteryLevel: 88
    - shortcode: initiative
      type: skill
      system:
        masteryLevel: 108
    - shortcode: polearm
      type: skill
      name: Lance (Polearm)
      system:
        masteryLevel: 108
    - shortcode: riding
      type: skill
      system:
        masteryLevel: 108
    - shortcode: shield
      type: skill
      system:
        masteryLevel: 108
    - shortcode: sword
      type: skill
      name: Bastard Sword (Sword)
      system:
        masteryLevel: 77
    - shortcode: unarmed
      type: skill
      system:
        masteryLevel: 91
    - shortcode: foraging
      type: skill
      system:
        masteryLevel: 84
    - shortcode: heraldry
      type: skill
      system:
        masteryLevel: 22
    - shortcode: physician
      type: skill
      system:
        masteryLevel: 48
    - shortcode: survival
      type: skill
      system:
        masteryLevel: 56
    - shortcode: weaponcraft
      type: skill
      system:
        masteryLevel: 44
    - shortcode: pence
      type: miscgear
      system:
        quantity: 9273
    - shortcode: pursebuckram
      type: containergear
    - shortcode: PlBack
      type: armorgear
    - shortcode: CvCloak
      type: armorgear
    - shortcode: LLeg
      type: armorgear
    - shortcode: MLeg
      type: armorgear
    - shortcode: CShoe
      type: armorgear
    - shortcode: LTunic
      type: armorgear
    - shortcode: Dgr
      type: weapongear
    - shortcode: Kni
      type: weapongear
    - shortcode: backbagsmcanvas
      type: containergear
    - shortcode: beltpouchl3
      type: containergear
    - shortcode: LtCap
      type: armorgear
    - shortcode: KiSh
      type: weapongear
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
    str: 13
    end: 13
    dex: 10
    agl: 12
    per: 12
    snt: 13
    cml: 9
    aur: 15
    wil: 12
    rea: 13
    cre: 9
    emp: 10
    elo: 9
    mor: 14
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
        masteryLevelBase: 72
    - shortcode: chrm
      type: skill
    - shortcode: clmb
      type: skill
      system:
        masteryLevelBase: 91
    - shortcode: cmd
      type: skill
    - shortcode: cook
      type: skill
    - shortcode: dnce
      type: skill
      system:
        masteryLevelBase: 55
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
        masteryLevelBase: 108
    - shortcode: shok
      type: skill
    - shortcode: intr
      type: skill
      system:
        masteryLevelBase: 52
    - shortcode: jump
      type: skill
      system:
        masteryLevelBase: 48
    - shortcode: melee
      type: skill
      system:
        masteryLevelBase: 91
    - shortcode: dge
      type: skill
    - shortcode: pysn
      type: skill
      system:
        masteryLevelBase: 48
    - shortcode: ridg
      type: skill
      system:
        masteryLevelBase: 108
    - shortcode: sing
      type: skill
      system:
        masteryLevelBase: 36
    - shortcode: stlth
      type: skill
      system:
        masteryLevelBase: 55
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
      name: Language, Serf
      system:
        masteryLevelBase: 72
    - shortcode: hrld
      type: skill
      system:
        masteryLevelBase: 22
    - shortcode: wpnc
      type: skill
      system:
        masteryLevelBase: 44
    - shortcode: pence
      type: miscgear
      system:
        quantity: 9273
    - shortcode: pouchbuckram
      type: containergear
    - shortcode: CvCloak
      type: armorgear
    - shortcode: LLeg
      type: armorgear
    - shortcode: MLeg
      type: armorgear
    - shortcode: CShoe
      type: armorgear
    - shortcode: LTunic
      type: armorgear
    - shortcode: Dgr
      type: weapongear
    - shortcode: Kni
      type: weapongear
    - shortcode: bgsmcvs
      type: containergear
    - shortcode: beltpouchl3
      type: containergear
    - shortcode: LtCap
      type: armorgear
    - shortcode: KiSh
      type: weapongear
    - shortcode: spoonpewte
      type: miscgear
    - shortcode: tankardpew
      type: miscgear
    - shortcode: tndrbx
      type: miscgear
---

# Appearance {#appearance}

**Height**: 5' 7"
**Frame**: Medium
**Weight**: 149
**Size**: 6
**Comeliness**: Average
**Complexion**: Dark
**Hair Color**: Black
**Eye Color**: Brown
**Voice**: Average

# Dossier {#dossier}

**Age**: 50
**Birthday**: 5 Nuzyael 670
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: 3rd child of 6
**Siblings**: FmFfMf
**Parentage**: Bastard (Acknowledged)
**Estrangement**: Popular
**Clanhead**: Father's Aunt/Uncle
**Medical**: Allergy

## Notes

Modifier to Frame of -3 (from 14) {Sex=Female, Species=Human}

Modifier to AttributesAUR of +2 (from 13) {Sex=Female, Species=Human}

Modifier to HairColor of -25 (from 35) {Complexion=Dark, Species=Human}

Modifier to EyeColor of +25 (from 96) {Complexion=Dark, Species=Human}

Modifier to StartingEquipment of +100 (from 48) {SocialClass=Serf}
