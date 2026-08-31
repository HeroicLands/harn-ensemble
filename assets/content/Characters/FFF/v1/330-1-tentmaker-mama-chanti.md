---
aliases:
  - Mama Chanti
  - 330-1 Tentmaker
tags: []
name:
  full: Mama Chanti
  title: ""
  given: Mama
  clan: Chanti
  aliases: []
id: DXII1oXhOLZBU8FB
folder: dbDLVOgUtgVgjgnJ
shortcode: mamachanti
img: images/fffv1/token/FFF_330-1_Tentmaker.png
portrait: images/fffv1/FFF_330-1_Tentmaker.jpg
tokenImg: images/fffv1/token/FFF_330-1_Tentmaker.png
type: being
social:
  occupation: Tentmaker
  class: freeman
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual:
    - halea
traits:
  species: human
  gender: female
  age: 93
  birthday: 626/5/14
  height:
    m: 1.55
  weight:
    kg: 79.38
  build:
    frame: heavy
  appearance:
    eye_color: hazel
    hair_color: grey
    skin_color: dark
    complexion: plain
    extra_features: []
hm3:
  species: human
  sunsign: angberelius
  attributes:
    str: 11
    sta: 3
    dex: 7
    agl: 4
    int: 14
    aur: 13
    wil: 17
    eye: 8
    hrg: 3
    sml: 5
    voi: 14
    cml: 6
    mor: 13
  move: 4
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
        masteryLevel: 14
        skillBase:
          value: 7
    - shortcode: condition
      type: skill
      system:
        masteryLevel: 30
        skillBase:
          value: 10
    - shortcode: jumping
      type: skill
      system:
        masteryLevel: 12
        skillBase:
          value: 6
    - shortcode: stealth
      type: skill
      system:
        masteryLevel: 16
        skillBase:
          value: 8
    - shortcode: throwing
      type: skill
      system:
        masteryLevel: 18
        skillBase:
          value: 9
    - shortcode: awareness
      type: skill
      system:
        masteryLevel: 20
        skillBase:
          value: 5
    - shortcode: intrigue
      type: skill
      system:
        masteryLevel: 77
        skillBase:
          value: 15
    - shortcode: oratory
      type: skill
      system:
        masteryLevel: 90
        skillBase:
          value: 11
    - shortcode: rhetoric
      type: skill
      system:
        masteryLevel: 76
        skillBase:
          value: 15
    - shortcode: singing
      type: skill
      system:
        masteryLevel: 30
        skillBase:
          value: 10
    - shortcode: language
      type: skill
      name: "Language: Harnic"
      system:
        masteryLevel: 75
        skillBase:
          value: 15
    - shortcode: halea
      type: skill
      system:
        masteryLevel: 18
        skillBase:
          value: 11
    - shortcode: initiative
      type: skill
      system:
        masteryLevel: 26
        skillBase:
          value: 13
    - shortcode: unarmed
      type: skill
      system:
        masteryLevel: 14
        skillBase:
          value: 7
    - shortcode: dodge
      type: skill
      system:
        masteryLevel: 20
        skillBase:
          value: 4
    - shortcode: cookery
      type: skill
      system:
        masteryLevel: 30
        skillBase:
          value: 6
    - shortcode: folklore
      type: skill
      system:
        masteryLevel: 96
        skillBase:
          value: 14
    - shortcode: hidework
      type: skill
      system:
        masteryLevel: 40
        skillBase:
          value: 10
    - shortcode: textilecraft
      type: skill
      system:
        masteryLevel: 51
        skillBase:
          value: 7
    - shortcode: textilecraft
      type: skill
      name: Needlework (Textilecraft)
      system:
        masteryLevel: 62
        skillBase:
          value: 7
    - shortcode: woodcraft
      type: skill
      system:
        masteryLevel: 20
        skillBase:
          value: 10
    - shortcode: LDress
      type: armorgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: beltpouchl3
      type: containergear
    - name: Yarn and Needles
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        weight: 1
    - shortcode: pence
      type: miscgear
      system:
        quantity: 15
sohl:
  kbcat: archetype
  archetype: 1
  attributes:
    str: 11
    end: 3
    dex: 7
    agl: 4
    per: 3
    snt: 5
    cml: 6
    aur: 13
    wil: 17
    rea: 14
    cre: 4
    emp: 14
    elo: 16
    mor: 13
    voi: 14
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
        masteryLevelBase: 20
    - shortcode: chrm
      type: skill
    - shortcode: clmb
      type: skill
      system:
        masteryLevelBase: 14
    - shortcode: cmd
      type: skill
    - shortcode: cook
      type: skill
      system:
        masteryLevelBase: 30
    - shortcode: dnce
      type: skill
    - shortcode: dscr
      type: skill
    - shortcode: draw
      type: skill
    - shortcode: folklr
      type: skill
      system:
        masteryLevelBase: 96
    - shortcode: guil
      type: skill
    - shortcode: init
      type: skill
      system:
        masteryLevelBase: 26
    - shortcode: shok
      type: skill
    - shortcode: intr
      type: skill
      system:
        masteryLevelBase: 77
    - shortcode: jump
      type: skill
      system:
        masteryLevelBase: 12
    - shortcode: melee
      type: skill
    - shortcode: dge
      type: skill
      system:
        masteryLevelBase: 20
    - shortcode: pysn
      type: skill
    - shortcode: ridg
      type: skill
    - shortcode: sing
      type: skill
      system:
        masteryLevelBase: 30
    - shortcode: stlth
      type: skill
      system:
        masteryLevelBase: 16
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
        masteryLevelBase: 18
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
      name: "Language: Harnic"
      system:
        masteryLevelBase: 75
    - shortcode: hide
      type: skill
      system:
        masteryLevelBase: 40
    - shortcode: txtl
      type: skill
      name: Needlework (Textilecraft)
      system:
        masteryLevelBase: 62
    - shortcode: LDress
      type: armorgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: beltpouchl3
      type: containergear
    - shortcode: pence
      type: miscgear
      system:
        quantity: 15
    - name: Halea
      type: affiliation
      system:
        shortcode: halea
        subType: divine
    - name: Halea
      type: skill
      system:
        subType: mystical
        shortcode: halea
        skillBaseFormula: "sb(attr.wil, attr.rea)"
        masteryLevelBase: 18
---

# Appearance {#appearance}

**Apparent Age**: Elderly
**Culture**: Feudal
**Social Class**: Freeman (guilded)
**Height**: 5 ft 1 in
**Frame**: Heavy
**Weight**: 175 lb
**Appearance**: Plain
**Hair Colour**: Grey
**Eye Colour**: Hazel
**Voice**: Pleasant
**Obvious Medical Traits**: None
**Apparent Occupation**: Tentmaker
**Apparent Wealth**: Moderate
**Weapons**: None
**Armour**: None
**Companions**: Grandson's family
**Other obvious features**: None

# Dossier {#dossier}

**Title**: FFF 330-1 Tentmaker
**Birthday**: 14 Larane 626
**Appearance**: Age 93, height 5'1", heavy frame, weight 175 lb, size 6, plain appearance, dark complexion, gray hair, hazel eyes.
**Medical/Psyche**: Eidetic memory
**Size**: 6
**Armor**: Plain cloth dress and leather shoes.
**Other Equipment**: Purse with yarn and needles.
**Valuables**: 15d in coin, silver necklace (100d)
**Notes**:

## Biography

As far as anyone knows, Mama Chanti (that is what everyone calls her) is the oldest human in the kingdom. She currently lives with her grandson, who is 54. Her own children are long dead; in fact, she often looks after her own great-great grandchildren while their parents work. Although she tires easily and can hardly hear anymore, she is still going strong. She has announced that she intends to live to be 100. Given her iron will, it is certainly possible.

The tentmaker's shop is prominently located and Mama Chanti can be seen every morning out front with a bit of sewing, rocking in her rocking chair. In her long and varied life, she has seen the births and deaths of kings, wars, plagues, famines, and all manner of things. Her memory is as sharp as ever and she can describe events from her childhood as if they happened yesterday. She has an amazing way with words and is a hypnotic storyteller. It is not uncommon to see her surrounded by children (and a few adults) telling stories from far-off lands and olden days.

Mama Chanti travelled extensively with her dearly beloved husband, Ferragus. She loves to tell stories of their travels by boat to the distant lands of the Azeryani Empire and other exotic places. Some have questioned the truthfulness of her stories but merchants from those countries who have heard her tales say that they are accurate. In a society where books and records are scarce, Mama Chanti is a rare and special resource, a human library. No patsy, she is known to charge outrageous prices to strangers with difficult questions when she knows they can't find the answer elsewhere.

## Adventure Hooks

Mama Chanti Has Been Kidnapped. The PCs know Mama from their childhood as a fixture in their town. Word comes that masked men have kidnapped the old lady right off her doorstep. Will they save her?

Your Past Will Haunt You. The PCs' patron did a few bad deeds in his youth. Fortunately, most of the people who know about them are dead. Unfortunately, Mama Chanti is still alive and your patron is afraid she will rekin dle the rumours. He wants the little old lady to have an accident.

Do You Remember When... The PCs are hot on the trail of some vital clue when they run into a dead end. As they have done since they were children, they head over to see Mama Chanti to ask her if she remembers anything about the event in question. She does indeed-she just needs a few chores done first.

## Credits

This character is taken from "Friends, Foes, and Followers, Vol. 1" on Lythia.com (https://www.lythia.com/game_aides/friends-foes-followers-volume-1/), by Kerry Mould, with illustrations by Richard Luscheck and Juha Makkonen, and is "fanon", a derivative work of copyrighted material by Columbia Games Inc. and N. Robin Crossby.
