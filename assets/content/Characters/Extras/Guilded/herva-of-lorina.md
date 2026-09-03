---
aliases:
  - Herva of Lorina
tags: []
name:
  full: Herva of Lorina
  title: ""
  given: Herva
  clan: Lorina
  aliases: []
id: 0zF4JKcQEvY27zhV
folder: GNynVWgIrKPK50Ca
shortcode: hervaoflorina
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
social:
  occupation: Courtesan
  class: serf
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: human
  gender: female
  age: 37
  birthday: 683/7/30
  height:
    m: 1.63
  weight:
    kg: 55.79
  build:
    frame: light
  appearance:
    eye_color: violet
    hair_color: black
    skin_color: pale
    complexion: average
    extra_features:
      - Left-Handed
hm3:
  species: human
  sunsign: hirin
  attributes:
    str: 11
    sta: 15
    dex: 13
    agl: 15
    int: 8
    aur: 10
    wil: 15
    eye: 12
    hrg: 9
    sml: 11
    voi: 13
    cml: 12
    mor: 8
  move: 12
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 65 } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 65 } }
    - { shortcode: dancing, type: skill, system: { masteryLevel: 45 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 70 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 55 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 110 } }
    - { shortcode: language, type: skill, name: "Language, Serf", system: { masteryLevel: 62 } }
    - { shortcode: lovecraft, type: skill, system: { masteryLevel: 104 } }
    - { shortcode: musician, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 22 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 77 } }
    - { shortcode: script, type: skill, name: Script(Lakaise), system: { masteryLevel: 81 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 1619 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: CvCloak, type: armorgear }
    - { shortcode: LLeg, type: armorgear }
    - { shortcode: SlkRobe, type: armorgear }
    - { shortcode: CShoe, type: armorgear }
    - { shortcode: LTunic, type: armorgear }
    - { shortcode: Kni, type: weapongear }
    - { shortcode: backbagsmcanvas, type: containergear }
    - { shortcode: beltpouchl3, type: containergear }
    - { shortcode: brushhair, type: miscgear }
    - name: Elprequir, 1 dose
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        value: 18
        weight: 0.1
    - name: Necklace, Copper
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        value: 8
        weight: 0.25
    - { shortcode: pursesilk, type: miscgear }
    - { shortcode: spoonwooden, type: miscgear }
    - { shortcode: tankardwooden, type: miscgear }
    - name: Comb, wood
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        value: 2
        weight: 0.1
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
    - { shortcode: str, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: end, type: attribute, system: { scoreBase: 15 } }
    - { shortcode: dex, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: agl, type: attribute, system: { scoreBase: 15 } }
    - { shortcode: per, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: snt, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: cml, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: aur, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: wil, type: attribute, system: { scoreBase: 15 } }
    - { shortcode: rea, type: attribute, system: { scoreBase: 8 } }
    - { shortcode: cre, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: emp, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: elo, type: attribute, system: { scoreBase: 16 } }
    - { shortcode: mor, type: attribute, system: { scoreBase: 8 } }
    - { shortcode: voi, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: archery, type: skill }
    - { shortcode: awar, type: skill, system: { masteryLevelBase: 55 } }
    - { shortcode: chrm, type: skill }
    - { shortcode: clmb, type: skill, system: { masteryLevelBase: 65 } }
    - { shortcode: cmd, type: skill }
    - { shortcode: cook, type: skill }
    - { shortcode: dnce, type: skill, system: { masteryLevelBase: 45 } }
    - { shortcode: dscr, type: skill }
    - { shortcode: draw, type: skill }
    - { shortcode: folklr, type: skill }
    - { shortcode: guil, type: skill }
    - { shortcode: init, type: skill, system: { masteryLevelBase: 60 } }
    - { shortcode: shok, type: skill }
    - { shortcode: intr, type: skill, system: { masteryLevelBase: 110 } }
    - { shortcode: jump, type: skill, system: { masteryLevelBase: 60 } }
    - { shortcode: melee, type: skill }
    - { shortcode: dge, type: skill }
    - { shortcode: pysn, type: skill }
    - { shortcode: ridg, type: skill }
    - { shortcode: sing, type: skill, system: { masteryLevelBase: 77 } }
    - { shortcode: stlth, type: skill, system: { masteryLevelBase: 60 } }
    - { shortcode: srvl, type: skill }
    - { shortcode: spirit, type: skill }
    - { shortcode: swim, type: skill }
    - { shortcode: thtcs, type: skill }
    - { shortcode: thro, type: skill, system: { masteryLevelBase: 70 } }
    - { shortcode: bflkbite, type: skill }
    - { shortcode: bflkgrab, type: skill }
    - { shortcode: bflkheadbutt, type: skill }
    - { shortcode: bflkkick, type: skill }
    - { shortcode: limbblock, type: skill }
    - { shortcode: press, type: skill }
    - { shortcode: bflkpunch, type: skill }
    - { shortcode: trip, type: skill }
    - { shortcode: sprt, type: mysticalability }
    - { shortcode: lang, type: skill, name: "Language, Serf", system: { masteryLevelBase: 62 } }
    - { shortcode: musc, type: skill, system: { masteryLevelBase: 30 } }
    - { shortcode: script, type: skill, name: Script(Lakaise), system: { masteryLevelBase: 81 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 1619 } }
    - { shortcode: pouchbuckram, type: containergear }
    - { shortcode: CvCloak, type: armorgear }
    - { shortcode: LLeg, type: armorgear }
    - { shortcode: SlkRobe, type: armorgear }
    - { shortcode: CShoe, type: armorgear }
    - { shortcode: LTunic, type: armorgear }
    - { shortcode: Kni, type: weapongear }
    - { shortcode: bgsmcvs, type: containergear }
    - { shortcode: beltpouchl3, type: containergear }
    - { shortcode: groomkit, type: miscgear }
    - name: Elprequir
      type: concoctiongear
      system:
        subType: mundane
        value: 12
        weight: 0.0625
        potency: mild
        docHtml: |
          <p>A common plant growing in pastures, dried and
          crushed into a fine blue powder and taken orally;
          an aphrodisiac, often slipped into food.</p>
    - { shortcode: necklacecopper, type: miscgear }
    - { shortcode: spoonpewte, type: miscgear }
    - { shortcode: tankardpew, type: miscgear }
    - { shortcode: groomkitcom, type: miscgear }
---

# Appearance {#appearance}

**Height**: 5' 4"
**Frame**: Light
**Weight**: 123
**Size**: 5
**Comeliness**: Average
**Complexion**: Pale
**Hair Color**: Black
**Eye Color**: Violet
**Voice**: Pleasant

# Dossier {#dossier}

**Age**: 37
**Birthday**: 30 Azura 683
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: 2nd child of 4
**Siblings**: FFfF
**Parentage**: Offspring
**Offspring**: Both parents alive and living together
**Estrangement**: Unpopular
**Clanhead**: Father's Aunt/Uncle
**Medical**: Left-Handed

## Notes

Modifier to Frame of -3 (from 10) {Sex=Female, Species=Human}

Modifier to AttributesAGL of +1 (from 13) {Frame=Light}

Modifier to AttributesAUR of +2 (from 8) {Sex=Female, Species=Human}

Modifier to EyeColor of -25 (from 24) {Complexion=Pale, Species=Human}

Left-Handed mod to Dexterity: +2

123lbs weight resulted in -2 strength mod.

Light frame resulted in +1 agility mod.

Modifier to StartingEquipment of +100 (from 65) {SocialClass=Serf}
