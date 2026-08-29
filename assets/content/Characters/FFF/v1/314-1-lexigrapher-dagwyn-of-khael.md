---
aliases:
  - Dagwyn of Khael
  - 314-1 Lexigrapher
tags: []
name:
  full: Dagwyn of Khael
  title: ""
  given: Dagwyn
  clan: Khael
  aliases: []
id: YodiswBfSMxgPVLK
folder: dbDLVOgUtgVgjgnJ
shortcode: dagwynofkhael
img: images/fffv1/token/FFF_314-1_Lexigrapher.png
portrait: images/fffv1/FFF_314-1_Lexigrapher.jpg
tokenImg: images/fffv1/token/FFF_314-1_Lexigrapher.png
type: being
package: harnensemble
social:
  occupation: Lexigrapher
  class: freeman
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual:
    - peoni
traits:
  species: human
  gender: female
  age: 23
  birthday: 696/6/15
  height:
    m: 1.57
  weight:
    kg: 53.07
  build:
    frame: light
  appearance:
    eye_color: hazel (milky white)
    hair_color: brown
    skin_color: medium
    complexion: beautiful
    extra_features:
      - Cataracts
hm3:
  species: human
  sunsign: nadai
  attributes:
    str: 14
    sta: 15
    dex: 11
    agl: 8
    int: 13
    aur: 8
    wil: 15
    eye: 3
    hrg: 16
    sml: 17
    voi: 13
    cml: 17
    mor: 14
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
        masteryLevel: 24
        skillBase:
          value: 12
    - shortcode: condition
      type: skill
      system:
        masteryLevel: 75
        skillBase:
          value: 15
    - shortcode: jumping
      type: skill
      system:
        masteryLevel: 24
        skillBase:
          value: 12
    - shortcode: stealth
      type: skill
      system:
        masteryLevel: 26
        skillBase:
          value: 13
    - shortcode: throwing
      type: skill
      system:
        masteryLevel: 20
        skillBase:
          value: 10
    - shortcode: awareness
      type: skill
      system:
        masteryLevel: 48
        skillBase:
          value: 12
    - shortcode: intrigue
      type: skill
      system:
        masteryLevel: 36
        skillBase:
          value: 12
    - shortcode: oratory
      type: skill
      system:
        masteryLevel: 28
        skillBase:
          value: 14
    - shortcode: rhetoric
      type: skill
      system:
        masteryLevel: 42
        skillBase:
          value: 14
    - shortcode: singing
      type: skill
      system:
        masteryLevel: 72
        skillBase:
          value: 14
    - shortcode: language
      type: skill
      name: "Language: Harnic"
      system:
        masteryLevel: 74
        skillBase:
          value: 14
    - shortcode: peoni
      type: skill
      system:
        masteryLevel: 34
        skillBase:
          value: 12
    - shortcode: initiative
      type: skill
      system:
        masteryLevel: 26
        skillBase:
          value: 13
    - shortcode: unarmed
      type: skill
      system:
        masteryLevel: 22
        skillBase:
          value: 11
    - shortcode: dodge
      type: skill
      system:
        masteryLevel: 24
        skillBase:
          value: 8
    - shortcode: hidework
      type: skill
      system:
        masteryLevel: 58
        skillBase:
          value: 14
    - shortcode: hidework
      type: skill
      name: Parchment making (Hidework)
      system:
        masteryLevel: 76
        skillBase:
          value: 14
    - shortcode: alchemy
      type: skill
      system:
        masteryLevel: 26
        skillBase:
          value: 13
    - shortcode: LDress
      type: armorgear
    - shortcode: beltwaist
      type: miscgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: beltpouchl3
      type: containergear
    - shortcode: pence
      type: miscgear
      system:
        quantity: 11
sohl:
  kbcat: archetype
  archetype: 1
  attributes:
    str: 14
    end: 15
    dex: 11
    agl: 8
    per: 12
    snt: 17
    cml: 17
    aur: 8
    wil: 15
    rea: 13
    cre: 16
    emp: 9
    elo: 15
    mor: 14
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
    - shortcode: awar
      type: skill
      system:
        masteryLevelBase: 48
    - shortcode: chrm
      type: skill
    - shortcode: clmb
      type: skill
      system:
        masteryLevelBase: 24
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
        masteryLevelBase: 26
    - shortcode: shok
      type: skill
    - shortcode: intr
      type: skill
      system:
        masteryLevelBase: 36
    - shortcode: jump
      type: skill
      system:
        masteryLevelBase: 24
    - shortcode: melee
      type: skill
    - shortcode: dge
      type: skill
      system:
        masteryLevelBase: 24
    - shortcode: pysn
      type: skill
    - shortcode: ridg
      type: skill
    - shortcode: sing
      type: skill
      system:
        masteryLevelBase: 72
    - shortcode: stlth
      type: skill
      system:
        masteryLevelBase: 26
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
        masteryLevelBase: 20
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
        masteryLevelBase: 74
    - shortcode: hide
      type: skill
      name: Parchment making (Hidework)
      system:
        masteryLevelBase: 76
    - shortcode: alch
      type: mysticalability
      system:
        masteryLevelBase: 26
    - shortcode: LDress
      type: armorgear
    - shortcode: beltwaist
      type: miscgear
    - shortcode: LtShoe
      type: armorgear
    - shortcode: beltpouchl3
      type: containergear
    - shortcode: pence
      type: miscgear
      system:
        quantity: 11
    - name: Peoni
      type: affiliation
      system:
        shortcode: peoni
        subType: divine
    - name: Peoni
      type: skill
      system:
        subType: mystical
        shortcode: peoni
        skillBaseFormula: "sb(attr.wil, attr.rea)"
        masteryLevelBase: 34
---

# Appearance {#appearance}

**Apparent Age**: Adult
**Culture**: Feudal
**Social Class**: Freeman (guilded)
**Height**: 5 ft 2 in
**Frame**: Light
**Weight**: 117 lb
**Appearance**: Beautiful
**Hair Colour**: Brown
**Eye Colour**: Hazel (milky white)
**Voice**: Pleasant
**Obvious Medical Traits**: Cataracts
**Apparent Occupation**: Lexigrapher
**Apparent Wealth**: Moderate
**Weapons**: None
**Armour**: None
**Companions**: Brother and a black terrier
**Other obvious features**: None

# Dossier {#dossier}

**Title**: FFF 314-1 Lexigrapher
**Birthday**: 15 Agrazhar 696
**Appearance**: Age 23, height 5'2", light frame, weight 117 lb, beautiful appearance, medium complexion, brown hair, hazel (milky white) eyes
**Medical/Psyche**: Partially blind (cataracts, can only see light and dark)
**Size**: 5
**Armor**: Good quality cloth dress, leather belt and shoes
**Other Equipment**: Belt pouch
**Valuables**: 11d in coin
**Notes**: Dagwyn was born with cataracts. The irises of her eyes turned completely white by age 10.

## Biography

Dagwyn was born in Coranan, where her father was a lexigrapher. Her parents tried long and hard to have children and did not succeed until her mother was in her late thirties. The midwife noted the halos in Dagwyn's eyes when she was born and recommended she be left for the wolves, but her parents staunchly refused. The midwife pronounced her cursed and would have nothing more to do with the family. A year later, Dagwyn's mother bore a son. He was a breech birth and she died bearing him by caesarean section.

Dagwyn's father worked long hours raising his children and running his franchise. While she still had some vision, Dagwyn learned the layout of the shop and the city. She also became adept at recognising people and places by sound and smell. She refused to let blindness make her a burden to her father and brother and has learned many of the skills of the trade. Dagwyn assists her father with making parchment, vellum, and inks. She is unable to write or draw but has an amazing memory for fairy tales and stories from afar.

Despite her blindness, Dagwyn has become a canny businesswoman and sharp haggler. She uses a cane to feel her way and is always accompanied by her little black terrier, Bear, who is very protective of his mistress. Bear has a repertoire of more than a dozen different barks, growls, yips, and whines that mean different things. Although mostly blind, Dagwyn can see shapes and shadows, although only in daylight or in very brightly lit rooms. She can be a bit clumsy in unfamiliar circumstances. Despite this, she has travelled far and wide in her brother's company.

## Adventure Hooks

How May I Help You? The PCs are in need of some parchment or maps. They stop in at the local guildsman's shop and come face to face with this stunningly beautiful woman. She has an uncanny habit of looking straight at the person speaking with her milky white eyes.

Vengeance Is Sweet. Someone (perhaps a PC) takes advantage of Dagwyn, short-changing her on a deal. As a businesswoman, she will not let this go and hires thugs to settle the score.

I Will Recognise His Voice. The PCs are investigating a crime. The only witness is Dagwyn. She walked in on the crime in progress while on deliveries. The attacker let her live because he didn't believe she could identify him. She claims she would recognise his voice and his footfalls. She is their only lead.

## Credits

This character is taken from "Friends, Foes, and Followers, Vol. 1" on Lythia.com (https://www.lythia.com/game_aides/friends-foes-followers-volume-1/), by Kerry Mould, with illustrations by Richard Luscheck and Juha Makkonen, and is "fanon", a derivative work of copyrighted material by Columbia Games Inc. and N. Robin Crossby.
