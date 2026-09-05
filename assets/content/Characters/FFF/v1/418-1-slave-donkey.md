---
tags: []
name:
  full: Donkey
  title: ""
  given: Donkey
  clan: ""
  aliases: []
id: X9QMQDMRJ2tSGvPK
folder: i4hECpF8Vz6XJURd
shortcode: donkey
img: images/fffv1/token/FFF_418-1_Slave.png
portrait: images/fffv1/FFF_418-1_Slave.jpg
tokenImg: images/fffv1/token/FFF_418-1_Slave.png
type: being
social:
  occupation: Slave
  class: slave
  society: imperial
  organizations: []
harnworld:
  realm: ""
  ritual:
    - peoni
traits:
  species: human
  gender: male
  age: 25
  birthday: 694/9/9
  height:
    m: 1.68
  weight:
    kg: 52.62
  build:
    frame: scant
  appearance:
    eye_color: blue
    hair_color: blonde
    skin_color: fair
    complexion: average
    extra_features:
      - Scars
      - parasites
      - pox marks
      - missing both thumbs
hm3:
  species: human
  sunsign: tai
  attributes:
    str: 16
    sta: 15
    dex: 7
    agl: 15
    int: 10
    aur: 10
    wil: 14
    eye: 11
    hrg: 16
    sml: 16
    voi: 12
    cml: 11
    mor: 7
  move: 15
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 47, skillBase: { value: 10 } } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 72, skillBase: { value: 15 } } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 65, skillBase: { value: 15 } } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 57, skillBase: { value: 17 } } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 49, skillBase: { value: 11 } } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 76, skillBase: { value: 14 } } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 45, skillBase: { value: 11 } } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 29, skillBase: { value: 11 } } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 46, skillBase: { value: 13 } } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 49, skillBase: { value: 13 } } }
    - shortcode: language
      type: skill
      name: "Language: Harnic"
      system:
        masteryLevel: 63
        skillBase:
          value: 13
    - { shortcode: peoni, type: skill, system: { masteryLevel: 10, skillBase: { value: 10 } } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 72, skillBase: { value: 14 } } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 67, skillBase: { value: 13 } } }
    - { shortcode: dodge, type: skill, system: { masteryLevel: 81, skillBase: { value: 15 } } }
    - name: Shackles
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        weight: 1
    - { shortcode: CLoin, type: armorgear }
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
    - { shortcode: str, type: attribute, system: { scoreBase: 16 } }
    - { shortcode: end, type: attribute, system: { scoreBase: 15 } }
    - { shortcode: dex, type: attribute, system: { scoreBase: 7 } }
    - { shortcode: agl, type: attribute, system: { scoreBase: 15 } }
    - { shortcode: per, type: attribute, system: { scoreBase: 17 } }
    - { shortcode: snt, type: attribute, system: { scoreBase: 16 } }
    - { shortcode: cml, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: aur, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: wil, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: rea, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: cre, type: attribute, system: { scoreBase: 15 } }
    - { shortcode: emp, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: elo, type: attribute, system: { scoreBase: 16 } }
    - { shortcode: mor, type: attribute, system: { scoreBase: 7 } }
    - { shortcode: voi, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: archery, type: skill }
    - { shortcode: awar, type: skill, system: { masteryLevelBase: 76 } }
    - { shortcode: chrm, type: skill }
    - { shortcode: clmb, type: skill, system: { masteryLevelBase: 47 } }
    - { shortcode: cmd, type: skill }
    - { shortcode: cook, type: skill }
    - { shortcode: dnce, type: skill }
    - { shortcode: dscr, type: skill }
    - { shortcode: draw, type: skill }
    - { shortcode: folklr, type: skill }
    - { shortcode: guil, type: skill }
    - { shortcode: init, type: skill, system: { masteryLevelBase: 72 } }
    - { shortcode: shok, type: skill }
    - { shortcode: intr, type: skill, system: { masteryLevelBase: 45 } }
    - { shortcode: jump, type: skill, system: { masteryLevelBase: 65 } }
    - { shortcode: melee, type: skill }
    - { shortcode: dge, type: skill, system: { masteryLevelBase: 81 } }
    - { shortcode: pysn, type: skill }
    - { shortcode: ridg, type: skill }
    - { shortcode: sing, type: skill, system: { masteryLevelBase: 49 } }
    - { shortcode: stlth, type: skill, system: { masteryLevelBase: 57 } }
    - { shortcode: srvl, type: skill }
    - { shortcode: spirit, type: skill }
    - { shortcode: swim, type: skill }
    - { shortcode: thtcs, type: skill }
    - { shortcode: thro, type: skill, system: { masteryLevelBase: 49 } }
    - { shortcode: bflkbite, type: skill }
    - { shortcode: bflkgrab, type: skill }
    - { shortcode: bflkheadbutt, type: skill }
    - { shortcode: bflkkick, type: skill }
    - { shortcode: limbblock, type: skill }
    - { shortcode: press, type: skill }
    - { shortcode: bflkpunch, type: skill }
    - { shortcode: trip, type: skill }
    - { shortcode: sprt, type: mysticalability }
    - { shortcode: lang, type: skill, name: "Language: Harnic", system: { masteryLevelBase: 63 } }
    - { shortcode: CLoin, type: armorgear }
    - { name: Peoni, type: affiliation, system: { shortcode: peoni, subType: divine } }
    - name: Peoni
      type: skill
      system:
        subType: mystical
        shortcode: peoni
        skillBaseFormula: sb(attr.wil, attr.rea)
        masteryLevelBase: 10
---

# Appearance {#appearance}

**Apparent Age**: Adult
**Culture**: Imperial
**Social Class**: Slave
**Height**: 5 ft 6 in
**Frame**: Scant
**Weight**: 116 lb
**Appearance**: Average
**Hair Colour**: Blond
**Eye Colour**: Blue
**Voice**: Average
**Obvious Medical Traits**: Scars, parasites, pox marks, missing both thumbs
**Apparent Occupation**: Slave
**Apparent Wealth**: None
**Weapons**: None
**Armour**: None
**Companions**: Overseer, other slaves
**Other obvious features**: None

# Dossier {#dossier}

**Title**: FFF 418-1 Slave
**Birthday**: 9 Savor 694
**Appearance**: Age 25, height 5'6", scant frame, weight 116 lb, average appearance, fair complexion, blonde hair, blue eyes.
**Medical/Psyche**: Scars, parasites, pox marks, both thumbs removed.
**Size**: 5
**Armor**: Foul loincloth
**Other Equipment**: Shackles
**Valuables**: 0d in coin
**Notes**:

## Biography

Donkey has no idea where he was born or even how old he is. He has been a slave as long as he can remember. He does primarily grunt labour. Donkey loads and unloads ships and wagons. He also works as a porter, carrying heavy baskets of goods. A raiding party from the Order of the Octagonal Pit took Donkey from an Orbaalese colony on the north coast of Harn when he was barely more than a toddler. He was branded with their distinctive brand. He was too young to be of any sport in the ring so he was sold as a house slave. Even at the age of five he proved rebellious. He was beaten frequently but kept trying to escape. Finally, both his thumbs were hacked off with a meat cleaver and cauterized with a hot iron. That seemed to calm him down.

Donkey has passed from owner to owner in exchange or as payment of debt. He has spent most of his life along the great Thard River in Rethem and the Thardic Republic. He has never had much opportunity or time to learn. He knows little more than the route from the slave cells to the docks and back. Often, he doesn't even know what town he is in until he gets a chance to ask one of the other slaves.

As a slave, Donkey is treated like a donkey, which is where his latest master came up with his name. He is fed and watered, worked hard all day, and then put away in a cell at night. Donkey is a strong slave and uses this to dominate many of the other slaves. He is not afraid to fight them for food or a better sleeping area. Donkey is vigilant and quick to dodge out of the line of the overseer's whip.

## Adventure Hooks

New Here? The PCs get taken prisoner and thrown naked into the cells with the slaves. If the PCs are obviously tougher or stronger than him, Donkey tries to make friends.

Fight. Donkey has angered his master for the last time and has been sent to the arena to die. The PCs have been captured and are matched against him. They have a distinct advantage as they have thumbs and can grasp weapons. Do they take mercy on this unskilled slave or slaughter him?

Will a Slave Do? The PCs need pack animals but there has been a run on the market and there are none currently available. The auctioneer asks if the PCs would take this slave off his hands. He is strong and can carry a heavy pannier of goods. He is the last of a large lot and is being sold cheap.

## Credits

This character is taken from "Friends, Foes, and Followers, Vol. 1" on Lythia.com (https://www.lythia.com/game_aides/friends-foes-followers-volume-1/), by Kerry Mould, with illustrations by Richard Luscheck and Juha Makkonen, and is "fanon", a derivative work of copyrighted material by Columbia Games Inc. and N. Robin Crossby.
