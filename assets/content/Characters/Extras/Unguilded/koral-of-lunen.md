---
aliases:
  - Koral of Lunen
tags: []
name:
  full: Koral of Lunen
  title: ""
  given: Koral
  clan: Lunen
  aliases: []
id: iul5JmYiaA6dYs2M
folder: wqZxeSsm1ABX2AGx
shortcode: koraloflunen
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
social:
  occupation: Shaman
  class: noble
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual:
    - "custom|Tribal"
traits:
  species: human
  gender: male
  age: 28
  birthday: 692/11/21
  height:
    m: 1.78
  weight:
    kg: 79.83
  build:
    frame: heavy
  appearance:
    eye_color: blue
    hair_color: black
    skin_color: medium
    complexion: attractive
    extra_features:
      - "*Parasites"
hm3:
  species: human
  sunsign: masara
  attributes:
    str: 15
    sta: 9
    dex: 12
    agl: 8
    int: 11
    aur: 12
    wil: 9
    eye: 12
    hrg: 15
    sml: 12
    voi: 10
    cml: 15
    mor: 8
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
        masteryLevel: 44
    - shortcode: condition
      type: skill
      system:
        masteryLevel: 55
    - shortcode: dancing
      type: skill
      system:
        masteryLevel: 36
    - shortcode: jumping
      type: skill
      system:
        masteryLevel: 40
    - shortcode: stealth
      type: skill
      system:
        masteryLevel: 30
    - shortcode: throwing
      type: skill
      system:
        masteryLevel: 65
    - shortcode: awareness
      type: skill
      system:
        masteryLevel: 52
    - shortcode: intrigue
      type: skill
      system:
        masteryLevel: 40
    - shortcode: language
      type: skill
      name: Language, Noble
      system:
        masteryLevel: 80
    - shortcode: mentalconflict
      type: skill
      system:
        masteryLevel: 40
    - shortcode: oratory
      type: skill
      system:
        masteryLevel: 36
    - shortcode: rhetoric
      type: skill
      system:
        masteryLevel: 40
    - shortcode: singing
      type: skill
      system:
        masteryLevel: 36
    - shortcode: initiative
      type: skill
      system:
        masteryLevel: 32
    - shortcode: spear
      type: skill
      system:
        masteryLevel: 28
    - shortcode: unarmed
      type: skill
      system:
        masteryLevel: 52
    - shortcode: embalming
      type: skill
      system:
        masteryLevel: 24
    - shortcode: folklore
      type: skill
      system:
        masteryLevel: 50
    - shortcode: foraging
      type: skill
      system:
        masteryLevel: 33
    - shortcode: herblore
      type: skill
      system:
        masteryLevel: 66
    - shortcode: physician
      type: skill
      system:
        masteryLevel: 39
    - shortcode: survival
      type: skill
      system:
        masteryLevel: 48
    - shortcode: tracking
      type: skill
      system:
        masteryLevel: 22
    - shortcode: weatherlore
      type: skill
      system:
        masteryLevel: 48
    - name: Tribal
      type: skill
      img: systems/hm3/images/icons/svg/circle.svg
      system:
        type: Ritual
        skillBase.value: 12
        masteryLevel: 72
        ritual.piety: 19
    - shortcode: pence
      type: miscgear
      system:
        quantity: 804
    - shortcode: pursebuckram
      type: containergear
    - shortcode: LtCBoot
      type: armorgear
    - shortcode: LtCloak
      type: armorgear
    - shortcode: WClk
      type: armorgear
    - shortcode: WLeg
      type: armorgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: WTunic
      type: armorgear
    - shortcode: Dgr
      type: weapongear
    - shortcode: Spr
      type: weapongear
      system:
        quantity: 0
    - shortcode: SprThr
      type: missilegear
      name: Spear (thrown)
    - shortcode: beltpouchl3
      type: containergear
    - shortcode: quiverlgsh
      type: miscgear
    - shortcode: spoonpewte
      type: miscgear
    - shortcode: tankardpew
      type: miscgear
sohl:
  kbcat: archetype
  archetype: 1
  attributes:
    str: 15
    end: 9
    dex: 12
    agl: 8
    per: 14
    snt: 12
    cml: 15
    aur: 12
    wil: 9
    rea: 11
    cre: 13
    emp: 9
    elo: 9
    mor: 8
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
        masteryLevelBase: 52
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
      system:
        masteryLevelBase: 36
    - shortcode: dscr
      type: skill
    - shortcode: draw
      type: skill
    - shortcode: folklr
      type: skill
      system:
        masteryLevelBase: 50
    - shortcode: guil
      type: skill
    - shortcode: init
      type: skill
      system:
        masteryLevelBase: 32
    - shortcode: shok
      type: skill
    - shortcode: intr
      type: skill
      system:
        masteryLevelBase: 40
    - shortcode: jump
      type: skill
      system:
        masteryLevelBase: 40
    - shortcode: melee
      type: skill
      system:
        masteryLevelBase: 28
    - shortcode: dge
      type: skill
    - shortcode: pysn
      type: skill
      system:
        masteryLevelBase: 39
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
        masteryLevelBase: 65
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
      name: Language, Noble
      system:
        masteryLevelBase: 80
    - shortcode: embl
      type: skill
      system:
        masteryLevelBase: 24
    - shortcode: herb
      type: skill
      system:
        masteryLevelBase: 66
    - shortcode: trak
      type: skill
      system:
        masteryLevelBase: 22
    - shortcode: pence
      type: miscgear
      system:
        quantity: 804
    - shortcode: pouchbuckram
      type: containergear
    - shortcode: LtCBoot
      type: armorgear
    - shortcode: LtCloak
      type: armorgear
    - shortcode: WClk
      type: armorgear
    - shortcode: WLeg
      type: armorgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: WTunic
      type: armorgear
    - shortcode: Dgr
      type: weapongear
    - shortcode: Spr
      type: weapongear
      system:
        quantity: 0
    - shortcode: beltpouchl3
      type: containergear
    - shortcode: quiverlgsh
      type: containergear
    - shortcode: spoonpewte
      type: miscgear
    - shortcode: tankardpew
      type: miscgear
---

# Appearance {#appearance}

**Height**: 5' 10"
**Frame**: Heavy
**Weight**: 176
**Size**: 7
**Comeliness**: Attractive
**Complexion**: Medium
**Hair Color**: Black
**Eye Color**: Blue
**Voice**: Average

# Dossier {#dossier}

**Age**: 28
**Birthday**: 21 Navek 692
**Culture**: Feudal
**Social Class**: Noble
**Sibling Rank**: 2nd child of 6
**Siblings**: MMMMff
**Parentage**: Offspring
**Offspring**: Both parents alive and living together
**Estrangement**: Favorite
**Clanhead**: Great Great Grandfather's Distant Relation
**Medical**: *Parasites

## Notes

Modifier to AttributesAGL of -1 (from 10) {Frame=Heavy}

Noble Blood results in +2 inches in height.

Parastites cause special penalty to Rhetoric and Lovecraft until cured.

176lbs weight resulted in +2 strength mod.

Heavy frame resulted in -1 agility mod.

Modifier to StartingEquipment of +400 (from 49) {SocialClass=Noble}
