---
aliases:
  - Gerrick Asarn
  - 599-2 Dilettante
tags: []
name:
  full: Gerrick Asarn
  title: ""
  given: Gerrick
  clan: Asarn
  aliases: []
id: zRHCVBVaIN8CG7Z6
folder: lu83pb6NNFEwAs5L
shortcode: gerrickasarn
img: images/fffv1/token/FFF_599-2_Dilettante.png
portrait: images/fffv1/FFF_599-2_Dilettante.jpg
tokenImg: images/fffv1/token/FFF_599-2_Dilettante.png
type: being
social:
  occupation: Patrician
  class: noble
  society: imperial
  organizations: []
harnworld:
  realm: ""
  ritual:
    - halea
traits:
  species: human
  gender: male
  age: 30
  birthday: 689/8/5
  height:
    m: 1.91
  weight:
    kg: 79.38
  build:
    frame: medium
  appearance:
    eye_color: hazel
    hair_color: black
    skin_color: medium
    complexion: average
    extra_features: []
hm3:
  species: human
  sunsign: hirin-tarael
  attributes:
    str: 12
    sta: 10
    dex: 12
    agl: 10
    int: 16
    aur: 14
    wil: 14
    eye: 11
    hrg: 14
    sml: 12
    voi: 13
    cml: 13
    mor: 8
  move: 10
  items:
    - { shortcode: skull, type: armorlocation }
    - { shortcode: face, type: armorlocation }
    - { shortcode: neck, type: armorlocation }
    - { shortcode: lshoulder, type: armorlocation }
    - { shortcode: rshoulder, type: armorlocation }
    - { shortcode: luparm, type: armorlocation }
    - { shortcode: ruparm, type: armorlocation }
    - { shortcode: lelb, type: armorlocation }
    - { shortcode: relb, type: armorlocation }
    - { shortcode: lhand, type: armorlocation }
    - { shortcode: rhand, type: armorlocation }
    - { shortcode: thorax, type: armorlocation }
    - { shortcode: abdm, type: armorlocation }
    - { shortcode: groin, type: armorlocation }
    - { shortcode: lhip, type: armorlocation }
    - { shortcode: rhip, type: armorlocation }
    - { shortcode: lthigh, type: armorlocation }
    - { shortcode: rthigh, type: armorlocation }
    - { shortcode: lknee, type: armorlocation }
    - { shortcode: rknee, type: armorlocation }
    - { shortcode: lcalf, type: armorlocation }
    - { shortcode: rcalf, type: armorlocation }
    - { shortcode: lfoot, type: armorlocation }
    - { shortcode: rfoot, type: armorlocation }
    - { shortcode: climbing, type: skill, system: { masteryLevel: 44, skillBase: { value: 11 } } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 55, skillBase: { value: 12 } } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 52, skillBase: { value: 13 } } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 48, skillBase: { value: 15 } } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 60, skillBase: { value: 14 } } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 70, skillBase: { value: 14 } } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 98, skillBase: { value: 17 } } }
    - { shortcode: lovecraft, type: skill, system: { masteryLevel: 65, skillBase: { value: 12 } } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 28, skillBase: { value: 15 } } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 65, skillBase: { value: 15 } } }
    - shortcode: rhetoric
      type: skill
      name: Negotiation (Rhetoric)
      system:
        masteryLevel: 90
        skillBase:
          value: 15
    - { shortcode: singing, type: skill, system: { masteryLevel: 52, skillBase: { value: 13 } } }
    - shortcode: language
      type: skill
      name: "Language: Harnic"
      system:
        masteryLevel: 84
        skillBase:
          value: 14
    - shortcode: script
      type: skill
      name: "Script: Lakise"
      system:
        masteryLevel: 84
        skillBase:
          value: 14
    - { shortcode: halea, type: skill, system: { masteryLevel: 20, skillBase: { value: 16 } } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 72, skillBase: { value: 13 } } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 33, skillBase: { value: 11 } } }
    - { shortcode: dodge, type: skill, system: { masteryLevel: 65, skillBase: { value: 10 } } }
    - { shortcode: riding, type: skill, system: { masteryLevel: 32, skillBase: { value: 12 } } }
    - { shortcode: dagger, type: skill, system: { masteryLevel: 66, skillBase: { value: 12 } } }
    - shortcode: mathematics
      type: skill
      system:
        masteryLevel: 68
        skillBase:
          value: 16
    - { shortcode: Dgr, type: weapongear }
    - { shortcode: RRobe, type: armorgear }
    - { shortcode: RLeg, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: pence, type: miscgear, system: { quantity: 100 } }
    - { shortcode: gldcrwn, type: miscgear, system: { quantity: 5 } }
sohl:
  kbcat: archetype
  archetype: 1
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
    - { shortcode: str, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: end, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: dex, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: agl, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: per, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: snt, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: cml, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: aur, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: wil, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: rea, type: attribute, system: { scoreBase: 16 } }
    - { shortcode: cre, type: attribute, system: { scoreBase: 15 } }
    - { shortcode: emp, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: elo, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: mor, type: attribute, system: { scoreBase: 8 } }
    - { shortcode: voi, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: archery, type: skill }
    - { shortcode: awar, type: skill, system: { masteryLevelBase: 70 } }
    - { shortcode: chrm, type: skill }
    - { shortcode: clmb, type: skill, system: { masteryLevelBase: 44 } }
    - { shortcode: cmd, type: skill }
    - { shortcode: cook, type: skill }
    - { shortcode: dnce, type: skill }
    - { shortcode: dscr, type: skill }
    - { shortcode: draw, type: skill }
    - { shortcode: folklr, type: skill }
    - { shortcode: guil, type: skill }
    - { shortcode: init, type: skill, system: { masteryLevelBase: 72 } }
    - { shortcode: shok, type: skill }
    - { shortcode: intr, type: skill, system: { masteryLevelBase: 98 } }
    - { shortcode: jump, type: skill, system: { masteryLevelBase: 52 } }
    - { shortcode: melee, type: skill, system: { masteryLevelBase: 66 } }
    - { shortcode: dge, type: skill, system: { masteryLevelBase: 65 } }
    - { shortcode: pysn, type: skill }
    - { shortcode: ridg, type: skill, system: { masteryLevelBase: 32 } }
    - { shortcode: sing, type: skill, system: { masteryLevelBase: 52 } }
    - { shortcode: stlth, type: skill, system: { masteryLevelBase: 48 } }
    - { shortcode: srvl, type: skill }
    - { shortcode: spirit, type: skill }
    - { shortcode: swim, type: skill }
    - { shortcode: thtcs, type: skill }
    - { shortcode: thro, type: skill, system: { masteryLevelBase: 60 } }
    - { shortcode: bflkbite, type: skill }
    - { shortcode: bflkgrab, type: skill }
    - { shortcode: bflkheadbutt, type: skill }
    - { shortcode: bflkkick, type: skill }
    - { shortcode: limbblock, type: skill }
    - { shortcode: press, type: skill }
    - { shortcode: bflkpunch, type: skill }
    - { shortcode: trip, type: skill }
    - { shortcode: sprt, type: mysticalability }
    - { shortcode: lang, type: skill, name: "Language: Harnic", system: { masteryLevelBase: 84 } }
    - { shortcode: script, type: skill, name: "Script: Lakise", system: { masteryLevelBase: 84 } }
    - { shortcode: math, type: skill, system: { masteryLevelBase: 68 } }
    - { shortcode: Dgr, type: weapongear }
    - { shortcode: RRobe, type: armorgear }
    - { shortcode: RLeg, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: pence, type: miscgear, system: { quantity: 100 } }
    - { shortcode: gldcrwn, type: miscgear, system: { quantity: 5 } }
    - { name: Halea, type: affiliation, system: { shortcode: halea, subType: divine } }
    - name: Halea
      type: skill
      system:
        subType: mystical
        shortcode: halea
        skillBaseFormula: sb(attr.wil, attr.rea)
        masteryLevelBase: 20
---

# Appearance {#appearance}

**Apparent Age**: Middle aged
**Culture**: Imperial
**Social Class**: Noble
**Height**: 6 ft 3 in
**Frame**: Medium
**Weight**: 175 lb
**Appearance**: Average
**Hair Colour**: Black
**Eye Colour**: Hazel
**Voice**: Average
**Obvious Medical Traits**: None
**Apparent Occupation**: Dilettante
**Apparent Wealth**: Wealthy
**Weapons**: None
**Armour**: None
**Companions**: Bodyguards
**Other obvious features**: None

# Dossier {#dossier}

**Title**: FFF 599-2 Dilettante
**Birthday**: 5 Halane 689
**Appearance**: Age 30, height 6' 3", medium frame, weight 175 lb, average appearance, medium complexion, black hair, hazel eyes.
**Medical/Psyche**: None
**Size**: 7
**Armor**: Fine cloth robe and leggings, leather shoes
**Other Equipment**: Coin purse
**Valuables**: 100d in silver, L5 in gold coin, gold ring (250d)
**Notes**:

## Biography

Gerrick is the eldest son and heir to Senator Asarn of Tharda. The Asarn family is one of the main landholding families of the Coranan District. Gerrick has rarely been outside the city of Coranan, preferring its diverse entertainment options to the "boredom of the countryside". Four family manors provide him with a modest income.

A devout worshipper of Halea, Gerrick is a hedonist with tastes that others would describe as odd, if they could adequately describe them at all. A regular attendant to services at the temple, he has made sufficient donations to have the services of a priestess living at his residence.

Gerrick maintains a stable of pleasure slaves at a townhouse owned through an intermediary; he purchases a new slave two or three times a year. He allows his bodyguards use of the slaves as well, increasing their loyalty. Slaves that no longer please him are sold, usually with their tongues cut out.

Gerrick is a skilled manipulator, negotiator, blackmailer, and money manager. He has an extensive network of contacts throughout Coranan, almost all of which owe him favours. These contacts are used first for the betterment of Gerrick, and then for the betterment of the family, a policy that has not endeared him to the rest of the Asarns.

Gerrick fully believes that he will become Senator Gerrick after the passing of his father, an event for which Gerrick is becoming impatient. He is aware that not all of the extended family would support him in an election, and is working on gathering the information and resources he needs to ensure his succession. Blackmail, extortion, and assassination are just methods of negotiation as far as Gerrick is concerned.

## Adventure Hooks

A Favour for a Favour: The PCs are in a bit of trouble; Gerrick helps them, either financially or by influence. But the cost will be a favour in return.

Abduction: Gerrick has had an NPC (or a PC) abducted to be used as one of his pleasure slaves. PCs investigate and either have to rescue them, buy them, or negotiate a release.

Information Gathering: In order to further his goals, Gerrick needs some sensitive information on someone. He hires or blackmails the PCs to get it, but will disavow and eventually silence them if they are caught.

Bodyguards: Gerrick has learned that another family member has contracted for his death, he needs additional bodyguards, and the PCs fit the bill as an expendable resource.

## Credits

This character is taken from "Friends, Foes, and Followers, Vol. 1" on Lythia.com (https://www.lythia.com/game_aides/friends-foes-followers-volume-1/), by Kerry Mould, with illustrations by Richard Luscheck and Juha Makkonen, and is "fanon", a derivative work of copyrighted material by Columbia Games Inc. and N. Robin Crossby.
