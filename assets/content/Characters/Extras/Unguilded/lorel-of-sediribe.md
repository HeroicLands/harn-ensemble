---
aliases:
  - Lorel of Sediribe
tags: []
name:
  full: Lorel of Sediribe
  title: ""
  given: Lorel
  clan: Sediribe
  aliases: []
id: mIjuMuBqGOhoJBZX
folder: wqZxeSsm1ABX2AGx
shortcode: lorelofsediribe
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
package: harnensemble
social:
  occupation: Feudal Yeoman, Longbow
  class: serf
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: human
  gender: male
  age: 36
  birthday: 684/10/10
  height:
    m: 1.65
  weight:
    kg: 63.96
  build:
    frame: medium
  appearance:
    eye_color: green
    hair_color: auburn
    skin_color: medium
    complexion: plain
    extra_features:
      - Allergy
hm3:
  species: human
  sunsign: skorus
  attributes:
    str: 13
    sta: 16
    dex: 17
    agl: 9
    int: 6
    aur: 12
    wil: 15
    eye: 13
    hrg: 11
    sml: 10
    voi: 10
    cml: 8
    mor: 15
    end: 15
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
        masteryLevel: 52
    - shortcode: condition
      type: skill
      system:
        masteryLevel: 112
    - shortcode: jumping
      type: skill
      system:
        masteryLevel: 60
    - shortcode: stealth
      type: skill
      system:
        masteryLevel: 33
    - shortcode: throwing
      type: skill
      system:
        masteryLevel: 56
    - shortcode: awareness
      type: skill
      system:
        masteryLevel: 55
    - shortcode: intrigue
      type: skill
      system:
        masteryLevel: 72
    - shortcode: language
      type: skill
      name: Language, Serf
      system:
        masteryLevel: 70
    - shortcode: oratory
      type: skill
      system:
        masteryLevel: 16
    - shortcode: rhetoric
      type: skill
      system:
        masteryLevel: 44
    - shortcode: singing
      type: skill
      system:
        masteryLevel: 50
    - shortcode: bow
      type: skill
      name: Longbow (Bow)
      system:
        masteryLevel: 70
    - shortcode: dagger
      type: skill
      system:
        masteryLevel: 75
    - shortcode: initiative
      type: skill
      system:
        masteryLevel: 78
    - shortcode: shield
      type: skill
      system:
        masteryLevel: 105
    - shortcode: sword
      type: skill
      name: Falchion (Sword)
      system:
        masteryLevel: 105
    - shortcode: unarmed
      type: skill
      system:
        masteryLevel: 78
    - shortcode: foraging
      type: skill
      system:
        masteryLevel: 44
    - shortcode: heraldry
      type: skill
      system:
        masteryLevel: 48
    - shortcode: physician
      type: skill
      system:
        masteryLevel: 65
    - shortcode: survival
      type: skill
      system:
        masteryLevel: 48
    - shortcode: weaponcraft
      type: skill
      system:
        masteryLevel: 60
    - shortcode: pence
      type: miscgear
      system:
        quantity: 1893
    - shortcode: pursebuckram
      type: containergear
    - shortcode: RByr
      type: armorgear
    - shortcode: CvCloak
      type: armorgear
    - shortcode: KHlfHelm
      type: armorgear
    - shortcode: LtLeg
      type: armorgear
    - shortcode: LLeg
      type: armorgear
    - shortcode: CShoe
      type: armorgear
    - shortcode: LTunic
      type: armorgear
    - shortcode: Kni
      type: weapongear
    - shortcode: LBw
      type: weapongear
    - name: Arrow, dozen
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        weight: 1
    - shortcode: backbagsmcanvas
      type: containergear
    - shortcode: beltpouchl3
      type: containergear
    - name: Pendant, Copper
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        value: 8
        weight: 0.05
    - shortcode: tankardwooden
      type: miscgear
sohl:
  kbcat: archetype
  archetype: 1
  attributes:
    str: 13
    end: 16
    dex: 17
    agl: 9
    per: 11
    snt: 10
    cml: 8
    aur: 12
    wil: 15
    rea: 6
    cre: 9
    emp: 16
    elo: 14
    mor: 15
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
      name: Longbow (Bow)
      system:
        masteryLevelBase: 70
    - shortcode: awar
      type: skill
      system:
        masteryLevelBase: 55
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
        masteryLevelBase: 78
    - shortcode: shok
      type: skill
    - shortcode: intr
      type: skill
      system:
        masteryLevelBase: 72
    - shortcode: jump
      type: skill
      system:
        masteryLevelBase: 60
    - shortcode: melee
      type: skill
      system:
        masteryLevelBase: 95
    - shortcode: dge
      type: skill
    - shortcode: pysn
      type: skill
      system:
        masteryLevelBase: 65
    - shortcode: ridg
      type: skill
    - shortcode: sing
      type: skill
      system:
        masteryLevelBase: 50
    - shortcode: stlth
      type: skill
      system:
        masteryLevelBase: 33
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
        masteryLevelBase: 56
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
        masteryLevelBase: 70
    - shortcode: hrld
      type: skill
      system:
        masteryLevelBase: 48
    - shortcode: wpnc
      type: skill
      system:
        masteryLevelBase: 60
    - shortcode: pence
      type: miscgear
      system:
        quantity: 1893
    - shortcode: pouchbuckram
      type: containergear
    - shortcode: RByr
      type: armorgear
    - shortcode: CvCloak
      type: armorgear
    - shortcode: KHlfHelm
      type: armorgear
    - shortcode: LtTrsr
      type: armorgear
    - shortcode: LLeg
      type: armorgear
    - shortcode: CShoe
      type: armorgear
    - shortcode: LTunic
      type: armorgear
    - shortcode: Kni
      type: weapongear
    - shortcode: LBw50
      type: weapongear
    - shortcode: ArwStd
      type: projectilegear
      system:
        quantity: 12
    - shortcode: bgsmcvs
      type: containergear
    - shortcode: beltpouchl3
      type: containergear
    - shortcode: amuletcopper
      type: miscgear
    - shortcode: tankardpew
      type: miscgear
---

# Appearance {#appearance}

**Height**: 5' 5"
**Frame**: Medium
**Weight**: 141
**Size**: 6
**Comeliness**: Plain
**Complexion**: Medium
**Hair Color**: Auburn
**Eye Color**: Green
**Voice**: Average

# Dossier {#dossier}

**Age**: 36
**Birthday**: 10 Ilvin 684
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: 4th child of 6
**Siblings**: MFFMfM
**Parentage**: Offspring
**Offspring**: Both parents alive and living together
**Estrangement**: Popular
**Clanhead**: Grandfather's Cousin
**Medical**: Allergy

## Notes

141lbs weight resulted in -1 strength mod.

Modifier to StartingEquipment of +100 (from 64) {SocialClass=Serf}
