---
aliases:
  - Cyzor of Bor
tags: []
name:
  full: Cyzor of Bor
  title: ""
  given: Cyzor
  clan: Bor
  aliases: []
id: dMLDWhKhVojzVYlB
folder: wYO4XEaOHdLCVUM0
shortcode: cyzorofbor
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
package: harnensemble
social:
  occupation: Patrician
  class: serf
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: human
  gender: male
  age: 42
  birthday: 678/8/20
  height:
    m: 1.73
  weight:
    kg: 129.27
  build:
    frame: medium
  appearance:
    eye_color: blue
    hair_color: brown
    skin_color: dark
    complexion: plain
    extra_features: []
hm3:
  species: human
  sunsign: tarael
  attributes:
    str: 14
    sta: 12
    dex: 10
    agl: 11
    int: 16
    aur: 17
    wil: 16
    eye: 9
    hrg: 7
    sml: 12
    voi: 11
    cml: 8
    mor: 14
    end: 14
  move: 15
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
        masteryLevel: 98
    - shortcode: dancing
      type: skill
      system:
        masteryLevel: 36
    - shortcode: jumping
      type: skill
      system:
        masteryLevel: 60
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
        masteryLevel: 55
    - shortcode: intrigue
      type: skill
      system:
        masteryLevel: 51
    - shortcode: language
      type: skill
      name: Language, Serf
      system:
        masteryLevel: 64
    - shortcode: oratory
      type: skill
      system:
        masteryLevel: 36
    - shortcode: rhetoric
      type: skill
      system:
        masteryLevel: 45
    - shortcode: singing
      type: skill
      system:
        masteryLevel: 27
    - shortcode: axe
      type: skill
      name: Handaxe (Axe)
      system:
        masteryLevel: 72
    - shortcode: dagger
      type: skill
      system:
        masteryLevel: 45
    - shortcode: initiative
      type: skill
      system:
        masteryLevel: 84
    - shortcode: polearm
      type: skill
      name: Lance (Polearm)
      system:
        masteryLevel: 108
    - shortcode: riding
      type: skill
      system:
        masteryLevel: 96
    - shortcode: shield
      type: skill
      system:
        masteryLevel: 77
    - shortcode: sword
      type: skill
      name: Broadsword (Sword)
      system:
        masteryLevel: 99
    - shortcode: unarmed
      type: skill
      system:
        masteryLevel: 66
    - shortcode: foraging
      type: skill
      system:
        masteryLevel: 60
    - shortcode: heraldry
      type: skill
      system:
        masteryLevel: 33
    - shortcode: physician
      type: skill
      system:
        masteryLevel: 33
    - shortcode: survival
      type: skill
      system:
        masteryLevel: 52
    - shortcode: weaponcraft
      type: skill
      system:
        masteryLevel: 39
    - shortcode: pence
      type: miscgear
      system:
        quantity: 4586
    - shortcode: pursebuckram
      type: containergear
    - shortcode: PlBreast
      type: armorgear
    - shortcode: CvCloak
      type: armorgear
    - shortcode: LLeg
      type: armorgear
    - shortcode: CShoe
      type: armorgear
    - shortcode: LTunic
      type: armorgear
    - shortcode: Kni
      type: weapongear
    - shortcode: BrdSwd
      type: weapongear
    - shortcode: backbagsmcanvas
      type: containergear
    - shortcode: beltpouchl3
      type: containergear
    - shortcode: tndrbx
      type: miscgear
    - shortcode: pipesmokin
      type: miscgear
    - name: Ring, Bone/Horn
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        value: 1
        weight: 0.03
    - shortcode: tankardwooden
      type: miscgear
sohl:
  kbcat: archetype
  archetype: 1
  attributes:
    str: 14
    end: 12
    dex: 10
    agl: 11
    per: 8
    snt: 12
    cml: 8
    aur: 17
    wil: 16
    rea: 16
    cre: 12
    emp: 13
    elo: 12
    mor: 14
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
    - shortcode: awar
      type: skill
      system:
        masteryLevelBase: 55
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
      system:
        masteryLevelBase: 36
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
        masteryLevelBase: 84
    - shortcode: shok
      type: skill
    - shortcode: intr
      type: skill
      system:
        masteryLevelBase: 51
    - shortcode: jump
      type: skill
      system:
        masteryLevelBase: 60
    - shortcode: melee
      type: skill
      system:
        masteryLevelBase: 80
    - shortcode: dge
      type: skill
    - shortcode: pysn
      type: skill
      system:
        masteryLevelBase: 33
    - shortcode: ridg
      type: skill
      system:
        masteryLevelBase: 96
    - shortcode: sing
      type: skill
      system:
        masteryLevelBase: 27
    - shortcode: stlth
      type: skill
      system:
        masteryLevelBase: 39
    - shortcode: srvl
      type: skill
      system:
        masteryLevelBase: 52
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
        masteryLevelBase: 64
    - shortcode: hrld
      type: skill
      system:
        masteryLevelBase: 33
    - shortcode: wpnc
      type: skill
      system:
        masteryLevelBase: 39
    - shortcode: pence
      type: miscgear
      system:
        quantity: 4586
    - shortcode: pouchbuckram
      type: containergear
    - shortcode: PlBreast
      type: armorgear
    - shortcode: CvCloak
      type: armorgear
    - shortcode: LLeg
      type: armorgear
    - shortcode: CShoe
      type: armorgear
    - shortcode: LTunic
      type: armorgear
    - shortcode: Kni
      type: weapongear
    - shortcode: BrdSwd
      type: weapongear
    - shortcode: bgsmcvs
      type: containergear
    - shortcode: beltpouchl3
      type: containergear
    - shortcode: tndrbx
      type: miscgear
    - shortcode: pipesmokin
      type: miscgear
    - shortcode: ringbone
      type: miscgear
    - shortcode: tankardpew
      type: miscgear
---

# Appearance {#appearance}

**Height**: 5' 8"
**Frame**: Medium
**Weight**: 285
**Size**: 9
**Comeliness**: Plain
**Complexion**: Dark
**Hair Color**: Brown
**Eye Color**: Blue
**Voice**: Average

# Dossier {#dossier}

**Age**: 42
**Birthday**: 20 Halane 678
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: Eldest of 10
**Siblings**: MMmFFMfMfm
**Parentage**: Offspring
**Offspring**: Both parents alive and living together
**Estrangement**: Average
**Clanhead**: Great Grandfather's Father/Mother

## Notes

Eldest gets +5 on estrangement roll.

Modifier to HairColor of -25 (from 44) {Complexion=Dark, Species=Human}

Modifier to EyeColor of +25 (from 7) {Complexion=Dark, Species=Human}

Modifier to StartingEquipment of +100 (from 54) {SocialClass=Serf}
