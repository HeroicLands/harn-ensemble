---
tags: []
name:
  full: Barton of Gelram
  title: ""
  given: Barton
  clan: Gelram
  aliases: []
id: sJ8YQArkYr9NyWD7
folder: dbDLVOgUtgVgjgnJ
shortcode: bartonofgelram
img: images/fffv1/token/FFF_312-1_Innkeeper.png
portrait: images/fffv1/FFF_312-1_Innkeeper.jpg
tokenImg: images/fffv1/token/FFF_312-1_Innkeeper.png
type: being
social:
  occupation: Innkeeper
  class: freeman
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual:
    - peoni
traits:
  species: human
  gender: male
  age: 24
  birthday: 695/11/23
  height:
    m: 1.68
  weight:
    kg: 65.77
  build:
    frame: medium
  appearance:
    eye_color: brown
    hair_color: brown
    skin_color: medium
    complexion: attractive
    extra_features: []
hm3:
  species: human
  sunsign: masara
  attributes:
    str: 9
    sta: 12
    dex: 16
    agl: 14
    int: 14
    aur: 10
    wil: 10
    eye: 14
    hrg: 13
    sml: 12
    voi: 11
    cml: 13
    mor: 8
  move: 14
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 52, skillBase: { value: 13 } } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 50, skillBase: { value: 10 } } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 48, skillBase: { value: 12 } } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 36, skillBase: { value: 12 } } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 52, skillBase: { value: 13 } } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 65, skillBase: { value: 13 } } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 75, skillBase: { value: 11 } } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 26, skillBase: { value: 13 } } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 75, skillBase: { value: 12 } } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 39, skillBase: { value: 13 } } }
    - shortcode: language
      type: skill
      name: "Language: Harnic"
      system:
        masteryLevel: 72
        skillBase:
          value: 12
    - shortcode: language
      type: skill
      name: "Language: Orbaalese"
      system:
        masteryLevel: 72
        skillBase:
          value: 12
    - shortcode: script
      type: skill
      name: "Script: Lakise"
      system:
        masteryLevel: 85
        skillBase:
          value: 15
    - { shortcode: peoni, type: skill, system: { masteryLevel: 14, skillBase: { value: 14 } } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 78, skillBase: { value: 11 } } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 45, skillBase: { value: 15 } } }
    - { shortcode: dodge, type: skill, system: { masteryLevel: 75, skillBase: { value: 14 } } }
    - { shortcode: axe, type: skill, system: { masteryLevel: 33, skillBase: { value: 11 } } }
    - { shortcode: club, type: skill, system: { masteryLevel: 60, skillBase: { value: 11 } } }
    - { shortcode: dagger, type: skill, system: { masteryLevel: 45, skillBase: { value: 15 } } }
    - { shortcode: brewing, type: skill, system: { masteryLevel: 60, skillBase: { value: 15 } } }
    - { shortcode: cookery, type: skill, system: { masteryLevel: 65, skillBase: { value: 13 } } }
    - { shortcode: beltpouchl3, type: containergear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: LtApn, type: armorgear }
    - { shortcode: LLeg, type: armorgear }
    - { shortcode: LTunic, type: armorgear }
    - { shortcode: Dgr, type: weapongear }
    - { shortcode: Clb, type: weapongear }
    - name: Cleaver
      type: weapongear
      img: systems/hm3/images/icons/svg/axe.svg
      system:
        value: 72
        weight: 3
        assocSkill: Axe
        blunt: 2
        edged: 3
        piercing: 2
    - { shortcode: pence, type: miscgear, system: { quantity: 13 } }
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
    - { shortcode: str, type: attribute, system: { scoreBase: 9 } }
    - { shortcode: end, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: dex, type: attribute, system: { scoreBase: 16 } }
    - { shortcode: agl, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: per, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: snt, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: cml, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: aur, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: wil, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: rea, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: cre, type: attribute, system: { scoreBase: 16 } }
    - { shortcode: emp, type: attribute, system: { scoreBase: 6 } }
    - { shortcode: elo, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: mor, type: attribute, system: { scoreBase: 8 } }
    - { shortcode: voi, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: archery, type: skill }
    - { shortcode: awar, type: skill, system: { masteryLevelBase: 65 } }
    - { shortcode: chrm, type: skill }
    - { shortcode: clmb, type: skill, system: { masteryLevelBase: 52 } }
    - { shortcode: cmd, type: skill }
    - { shortcode: cook, type: skill, system: { masteryLevelBase: 65 } }
    - { shortcode: dnce, type: skill }
    - { shortcode: dscr, type: skill }
    - { shortcode: draw, type: skill }
    - { shortcode: folklr, type: skill }
    - { shortcode: guil, type: skill }
    - { shortcode: init, type: skill, system: { masteryLevelBase: 78 } }
    - { shortcode: shok, type: skill }
    - { shortcode: intr, type: skill, system: { masteryLevelBase: 75 } }
    - { shortcode: jump, type: skill, system: { masteryLevelBase: 48 } }
    - { shortcode: melee, type: skill, system: { masteryLevelBase: 46 } }
    - { shortcode: dge, type: skill, system: { masteryLevelBase: 75 } }
    - { shortcode: pysn, type: skill }
    - { shortcode: ridg, type: skill }
    - { shortcode: sing, type: skill, system: { masteryLevelBase: 39 } }
    - { shortcode: stlth, type: skill, system: { masteryLevelBase: 36 } }
    - { shortcode: srvl, type: skill }
    - { shortcode: spirit, type: skill }
    - { shortcode: swim, type: skill }
    - { shortcode: thtcs, type: skill }
    - { shortcode: thro, type: skill, system: { masteryLevelBase: 52 } }
    - { shortcode: bflkbite, type: skill }
    - { shortcode: bflkgrab, type: skill }
    - { shortcode: bflkheadbutt, type: skill }
    - { shortcode: bflkkick, type: skill }
    - { shortcode: limbblock, type: skill }
    - { shortcode: press, type: skill }
    - { shortcode: bflkpunch, type: skill }
    - { shortcode: trip, type: skill }
    - { shortcode: sprt, type: mysticalability }
    - shortcode: lang
      type: skill
      name: "Language: Orbaalese"
      system:
        masteryLevelBase: 72
    - { shortcode: script, type: skill, name: "Script: Lakise", system: { masteryLevelBase: 85 } }
    - { shortcode: brew, type: skill, system: { masteryLevelBase: 60 } }
    - { shortcode: beltpouchl3, type: containergear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: LtApn, type: armorgear }
    - { shortcode: LLeg, type: armorgear }
    - { shortcode: LTunic, type: armorgear }
    - { shortcode: Dgr, type: weapongear }
    - { shortcode: Clb, type: weapongear }
    - { shortcode: pence, type: miscgear, system: { quantity: 13 } }
    - { name: Peoni, type: affiliation, system: { shortcode: peoni, subType: divine } }
    - name: Peoni
      type: skill
      system:
        subType: mystical
        shortcode: peoni
        skillBaseFormula: sb(attr.wil, attr.rea)
        masteryLevelBase: 14
---

# Appearance {#appearance}

**Apparent Age**: Adult
**Culture**: Feudal
**Social Class**: Freeman (guilded)
**Height**: 5 ft 6 in
**Frame**: Medium
**Weight**: 145 lb
**Appearance**: Attractive
**Hair Colour**: Brown
**Eye Colour**: Brown
**Voice**: Average
**Obvious Medical Traits**: None
**Apparent Occupation**: Journeyman Innkeeper
**Apparent Wealth**: Little
**Weapons**: Dagger
**Armour**: None
**Companions**: Local patrons
**Other obvious features**: None

# Dossier {#dossier}

**Title**: FFF 312-1 Innkeeper
**Birthday**: 23 Navek 695
**Appearance**: Age 24, height 5' 6", medium frame, weight 145 lb, size 6, attractive appearance, medium complexion, brown hair, brown eyes
**Medical/Psyche**: None
**Size**: 6
**Armor**: Leather shoes & apron, cloth leggings & tunic. Carries a dagger, keeps a club handy behind the bar of the Inn
**Other Equipment**: Belt pouch
**Valuables**: 13d silver in a coin purse
**Notes**:

## Biography

Barton of Gelram can be described in one word - Lazy. He never wanted to be an innkeeper, but then he never wanted to be much of anything. It is only by luck, or perhaps a desire to get rid of him, that his master signed his papers making him a journeyman of the trade. Since then, Barton has moved from Inn to Inn looking for easy money, never staying long enough to be kicked out or receive an official guild reprimand.

The quality of inns Barton has been able to gain employment with has steadily gone down as word of his work ethic, or lack thereof has gotten around. He recently started at an inn that is little better than a flophouse - which suits him just fine. In fact, the Master Innkeeper is actually the head of the local Lia-Kavair. He leaves most of the day-to-day operation of the inn to Barton. Barton does just enough to keep the place open, and otherwise spends his time drinking, gambling, and spending time with the prostitutes.

Despite being kept away from the operations of the Lia-Kavair, Barton is a good observer and while lazy, he is not stupid. If the innkeeper knew just how much Barton had figured out about his illicit operations, Barton would be in for a bad time. As it is, Barton is keeping his true level of knowledge secret, waiting until a good opportunity presents itself.

## Adventure Hooks

A time of need: Desperate for a place to stay, PCs are forced to take a room at Barton's inn. He overcharges them, but otherwise leaves them alone.

Turncoat: PCs are trying to get information on the operations of the Lia-Kavair. Barton is a good source, but an expensive one. If caught by the Lia-Kavair, he will turn on the PCs, claiming they threatened his life for the information.

The Loser: Barton is gambling, and looses big to one of the PCs. Not all of the losses are Barton's own money. He talks to the Lia-Kavair and they try to get the funds back from the PC.

The Winner: Barton is gambling, and one of the PCs loose heavily to him. Barton offers them the opportunity to earn their money back. He intends to take over the LiaKavair by having the PCs take out the current leadership.

The Mercantyler: Barton has failed to pay a local mercantyler for the ale and other supplies required by the Inn. The merchant hires the PCs to get his money back. Barton used the money given to him by the innkeeper for gambling, and lost. He will claim that he paid the bill, and that the merchant is lying.

## Credits

This character is taken from "Friends, Foes, and Followers, Vol. 1" on Lythia.com (https://www.lythia.com/game_aides/friends-foes-followers-volume-1/), by Kerry Mould, with illustrations by Richard Luscheck and Juha Makkonen, and is "fanon", a derivative work of copyrighted material by Columbia Games Inc. and N. Robin Crossby.
