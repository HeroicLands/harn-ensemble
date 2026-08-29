---
aliases:
  - Zorna of Chatil
tags: []
name:
  full: Zorna of Chatil
  title: ""
  given: Zorna
  clan: Chatil
  aliases: []
id: GtQoPm6rAr13dzuN
folder: GNynVWgIrKPK50Ca
shortcode: zornaofchatil
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
package: harnensemble
social:
  occupation: Mercantyler
  class: guilded
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: human
  gender: female
  age: 39
  birthday: 681/5/1
  height:
    m: 1.73
  weight:
    kg: 62.14
  build:
    frame: light
  appearance:
    eye_color: brown
    hair_color: black
    skin_color: dark
    complexion: average
    extra_features:
      - One Eye Missing/Blind
hm3:
  species: human
  sunsign: ahnu
  attributes:
    str: 9
    sta: 3
    dex: 11
    agl: 16
    int: 13
    aur: 9
    wil: 14
    eye: 7
    hrg: 9
    sml: 11
    voi: 15
    cml: 12
    mor: 9
    end: 9
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
        masteryLevel: 48
    - shortcode: condition
      type: skill
      system:
        masteryLevel: 40
    - shortcode: jumping
      type: skill
      system:
        masteryLevel: 78
    - shortcode: stealth
      type: skill
      system:
        masteryLevel: 78
    - shortcode: throwing
      type: skill
      system:
        masteryLevel: 36
    - shortcode: awareness
      type: skill
      system:
        masteryLevel: 54
    - shortcode: intrigue
      type: skill
      system:
        masteryLevel: 108
    - shortcode: language
      type: skill
      name: Language(Old Jarinese)
      system:
        masteryLevel: 56
    - shortcode: language
      type: skill
      name: Language, Guilded
      system:
        masteryLevel: 102
    - shortcode: oratory
      type: skill
      system:
        masteryLevel: 52
    - shortcode: rhetoric
      type: skill
      system:
        masteryLevel: 112
    - shortcode: singing
      type: skill
      system:
        masteryLevel: 39
    - shortcode: script
      type: skill
      name: Script(Lakaise)
      system:
        masteryLevel: 80
    - shortcode: dagger
      type: skill
      system:
        masteryLevel: 27
    - shortcode: initiative
      type: skill
      system:
        masteryLevel: 84
    - shortcode: unarmed
      type: skill
      system:
        masteryLevel: 60
    - shortcode: law
      type: skill
      system:
        masteryLevel: 28
    - shortcode: mathematics
      type: skill
      system:
        masteryLevel: 65
    - shortcode: pence
      type: miscgear
      system:
        quantity: 2597
    - shortcode: pursebuckram
      type: containergear
    - shortcode: RClk
      type: armorgear
    - shortcode: CHood
      type: armorgear
    - shortcode: BLeg
      type: armorgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: CTunic
      type: armorgear
    - shortcode: Dgr
      type: weapongear
    - shortcode: beltpouchl3
      type: containergear
    - shortcode: RCap
      type: armorgear
    - shortcode: WCap
      type: armorgear
    - shortcode: tndrbx
      type: miscgear
    - shortcode: waterskinsm
      type: miscgear
sohl:
  kbcat: archetype
  archetype: 1
  attributes:
    str: 9
    end: 3
    dex: 11
    agl: 16
    per: 7
    snt: 11
    cml: 12
    aur: 9
    wil: 14
    rea: 13
    cre: 12
    emp: 9
    elo: 15
    mor: 9
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
        masteryLevelBase: 54
    - shortcode: chrm
      type: skill
    - shortcode: clmb
      type: skill
      system:
        masteryLevelBase: 48
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
        masteryLevelBase: 84
    - shortcode: shok
      type: skill
    - shortcode: intr
      type: skill
      system:
        masteryLevelBase: 108
    - shortcode: jump
      type: skill
      system:
        masteryLevelBase: 78
    - shortcode: melee
      type: skill
      system:
        masteryLevelBase: 27
    - shortcode: dge
      type: skill
    - shortcode: pysn
      type: skill
    - shortcode: ridg
      type: skill
    - shortcode: sing
      type: skill
      system:
        masteryLevelBase: 39
    - shortcode: stlth
      type: skill
      system:
        masteryLevelBase: 78
    - shortcode: srvl
      type: skill
    - shortcode: spirit
      type: skill
    - shortcode: swim
      type: skill
    - shortcode: thtcs
      type: skill
    - shortcode: thro
      type: skill
      system:
        masteryLevelBase: 36
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
      name: Language, Guilded
      system:
        masteryLevelBase: 102
    - shortcode: script
      type: skill
      name: Script(Lakaise)
      system:
        masteryLevelBase: 80
    - shortcode: law
      type: skill
      system:
        masteryLevelBase: 28
    - shortcode: math
      type: skill
      system:
        masteryLevelBase: 65
    - shortcode: pence
      type: miscgear
      system:
        quantity: 2597
    - shortcode: pouchbuckram
      type: containergear
    - shortcode: RClk
      type: armorgear
    - shortcode: CHood
      type: armorgear
    - shortcode: BLeg
      type: armorgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: CTunic
      type: armorgear
    - shortcode: Dgr
      type: weapongear
    - shortcode: beltpouchl3
      type: containergear
    - shortcode: RCap
      type: armorgear
    - shortcode: WCap
      type: armorgear
    - shortcode: tndrbx
      type: miscgear
    - shortcode: wtrskin
      type: containergear
---

# Appearance {#appearance}

**Height**: 5' 8"
**Frame**: Light
**Weight**: 137
**Size**: 6
**Comeliness**: Average
**Complexion**: Dark
**Hair Color**: Black
**Eye Color**: Brown
**Voice**: Pleasant

# Dossier {#dossier}

**Age**: 39
**Birthday**: 1 Larane 681
**Culture**: Feudal
**Social Class**: Guilded
**Sibling Rank**: Eldest of 6
**Siblings**: FfffFM
**Parentage**: Bastard
**Estrangement**: Average
**Clanhead**: Father/Mother
**Medical**: One Eye Missing/Blind

## Notes

Modifier to Frame of -3 (from 11) {Sex=Female, Species=Human}

Modifier to AttributesAGL of +1 (from 14) {Frame=Light}

Modifier to AttributesAUR of +2 (from 7) {Sex=Female, Species=Human}

Eldest gets +5 on estrangement roll.

Modifier to HairColor of -25 (from 2) {Complexion=Dark, Species=Human}

Modifier to EyeColor of +25 (from 78) {Complexion=Dark, Species=Human}

One Eye Missing/Blind mod to Eyssight: -3

137lbs weight resulted in -1 strength mod.

Light frame resulted in +1 agility mod.

Modifier to StartingEquipment of +300 (from 20) {SocialClass=Guilded}
