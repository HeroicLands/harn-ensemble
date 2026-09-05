---
tags: []
name:
  full: Merelyn of Paseraleh
  title: ""
  given: Merelyn
  clan: Paseraleh
  aliases: []
id: Dl79q0xCaljTQZX3
folder: lJ4R58L7PULmhYxr
shortcode: merelynofpaseraleh
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
social:
  occupation: "Shek-Pvar/Fyvria****"
  class: serf
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: human
  gender: female
  age: 23
  birthday: 697/12/9
  height:
    m: 1.65
  weight:
    kg: 57.15
  build:
    frame: light
  appearance:
    eye_color: hazel
    hair_color: brown
    skin_color: medium
    complexion: attractive
    extra_features: []
hm3:
  species: human
  sunsign: lado
  attributes:
    str: 11
    sta: 13
    dex: 14
    agl: 18
    int: 12
    aur: 16
    wil: 14
    eye: 11
    hrg: 6
    sml: 6
    voi: 9
    cml: 14
    mor: 5
  move: 17
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 65 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 75 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 28 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 42 } }
    - { shortcode: language, type: skill, name: "Language, Serf", system: { masteryLevel: 72 } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 22 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 33 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 24 } }
    - { shortcode: script, type: skill, name: Script(Lakaise), system: { masteryLevel: 94 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 64 } }
    - { shortcode: agriculture, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: animalcraft, type: skill, system: { masteryLevel: 39 } }
    - { shortcode: embalming, type: skill, system: { masteryLevel: 20 } }
    - { shortcode: folklore, type: skill, system: { masteryLevel: 44 } }
    - { shortcode: foraging, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: herblore, type: skill, system: { masteryLevel: 27 } }
    - { shortcode: mathematics, type: skill, system: { masteryLevel: 24 } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 24 } }
    - { shortcode: survival, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: tracking, type: skill, system: { masteryLevel: 20 } }
    - { shortcode: fyvria, type: skill, system: { masteryLevel: 42 } }
    - { shortcode: neutral, type: skill, system: { masteryLevel: 45 } }
    - { shortcode: dispell, type: spell }
    - { shortcode: focus, type: spell }
    - { shortcode: balmofgresan, type: spell }
    - { shortcode: figureofaestras, type: spell }
    - { shortcode: verdanthand, type: spell }
    - { shortcode: handofiliam, type: spell }
    - { shortcode: favrinsbar, type: spell }
    - { shortcode: powerofsharadorn, type: spell }
    - { shortcode: dreamofgalega, type: spell }
    - { shortcode: dispell, type: spell }
    - { shortcode: pence, type: miscgear, system: { quantity: 11 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: CvCloak, type: armorgear }
    - { shortcode: LLeg, type: armorgear }
    - { shortcode: CShoe, type: armorgear }
    - { shortcode: LTunic, type: armorgear }
    - { shortcode: Kni, type: weapongear }
    - { shortcode: beltpouchl3, type: containergear }
    - { shortcode: tndrbx, type: miscgear }
    - { shortcode: firstaidbagwinstruments, type: miscgear }
    - { shortcode: writingkitportable, type: miscgear }
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
    - { shortcode: end, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: dex, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: agl, type: attribute, system: { scoreBase: 18 } }
    - { shortcode: per, type: attribute, system: { scoreBase: 5 } }
    - { shortcode: snt, type: attribute, system: { scoreBase: 6 } }
    - { shortcode: cml, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: aur, type: attribute, system: { scoreBase: 16 } }
    - { shortcode: wil, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: rea, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: cre, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: emp, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: elo, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: mor, type: attribute, system: { scoreBase: 5 } }
    - { shortcode: voi, type: attribute, system: { scoreBase: 9 } }
    - { shortcode: archery, type: skill }
    - { shortcode: awar, type: skill, system: { masteryLevelBase: 28 } }
    - { shortcode: chrm, type: skill }
    - { shortcode: clmb, type: skill, system: { masteryLevelBase: 56 } }
    - { shortcode: cmd, type: skill }
    - { shortcode: cook, type: skill }
    - { shortcode: dnce, type: skill }
    - { shortcode: dscr, type: skill }
    - { shortcode: draw, type: skill }
    - { shortcode: folklr, type: skill, system: { masteryLevelBase: 44 } }
    - { shortcode: guil, type: skill }
    - { shortcode: init, type: skill, system: { masteryLevelBase: 60 } }
    - { shortcode: shok, type: skill }
    - { shortcode: intr, type: skill, system: { masteryLevelBase: 42 } }
    - { shortcode: jump, type: skill, system: { masteryLevelBase: 75 } }
    - { shortcode: melee, type: skill }
    - { shortcode: dge, type: skill }
    - { shortcode: pysn, type: skill, system: { masteryLevelBase: 24 } }
    - { shortcode: ridg, type: skill }
    - { shortcode: sing, type: skill, system: { masteryLevelBase: 24 } }
    - { shortcode: stlth, type: skill, system: { masteryLevelBase: 36 } }
    - { shortcode: srvl, type: skill, system: { masteryLevelBase: 36 } }
    - { shortcode: spirit, type: skill }
    - { shortcode: swim, type: skill }
    - { shortcode: thtcs, type: skill }
    - { shortcode: thro, type: skill, system: { masteryLevelBase: 48 } }
    - { shortcode: bflkbite, type: skill }
    - { shortcode: bflkgrab, type: skill }
    - { shortcode: bflkheadbutt, type: skill }
    - { shortcode: bflkkick, type: skill }
    - { shortcode: limbblock, type: skill }
    - { shortcode: press, type: skill }
    - { shortcode: bflkpunch, type: skill }
    - { shortcode: trip, type: skill }
    - { shortcode: sprt, type: mysticalability }
    - { shortcode: lang, type: skill, name: "Language, Serf", system: { masteryLevelBase: 72 } }
    - { shortcode: script, type: skill, name: Script(Lakaise), system: { masteryLevelBase: 94 } }
    - { shortcode: agri, type: skill, system: { masteryLevelBase: 48 } }
    - { shortcode: anmcft, type: skill, system: { masteryLevelBase: 39 } }
    - { shortcode: embl, type: skill, system: { masteryLevelBase: 20 } }
    - { shortcode: herb, type: skill, system: { masteryLevelBase: 27 } }
    - { shortcode: math, type: skill, system: { masteryLevelBase: 24 } }
    - { shortcode: trak, type: skill, system: { masteryLevelBase: 20 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 11 } }
    - { shortcode: pouchbuckram, type: containergear }
    - { shortcode: CvCloak, type: armorgear }
    - { shortcode: LLeg, type: armorgear }
    - { shortcode: CShoe, type: armorgear }
    - { shortcode: LTunic, type: armorgear }
    - { shortcode: Kni, type: weapongear }
    - { shortcode: beltpouchl3, type: containergear }
    - { shortcode: tndrbx, type: miscgear }
    - { shortcode: medsupil, type: miscgear }
    - { shortcode: scribekit, type: miscgear }
    - { name: Fyvria, type: affiliation, system: { shortcode: fyvria, subType: arcane } }
    - { name: Neutral, type: affiliation, system: { shortcode: neutral, subType: arcane } }
    - name: Fyvria
      type: skill
      system:
        subType: mystical
        shortcode: fyvria
        skillBaseFormula: sb(attr.aur, attr.rea)
        masteryLevelBase: 42
    - name: Neutral
      type: skill
      system:
        subType: mystical
        shortcode: neutral
        skillBaseFormula: sb(attr.aur, attr.rea)
        masteryLevelBase: 45
    - name: Dispell
      type: mysticalability
      system:
        subType: arcaneincantation
        assocSkillCode: neutral
        assocAffiliationCode: neutral
        levelBase: 1
    - name: Focus
      type: mysticalability
      system:
        subType: arcaneincantation
        assocSkillCode: neutral
        assocAffiliationCode: neutral
        levelBase: 3
    - name: Balm of Gresan
      type: mysticalability
      system:
        subType: arcaneincantation
        assocSkillCode: fyvria
        assocAffiliationCode: fyvria
        levelBase: 1
    - name: Figure of Aestras
      type: mysticalability
      system:
        subType: arcaneincantation
        assocSkillCode: fyvria
        assocAffiliationCode: fyvria
        levelBase: 1
    - name: Verdant Hand
      type: mysticalability
      system:
        subType: arcaneincantation
        assocSkillCode: fyvria
        assocAffiliationCode: fyvria
        levelBase: 2
    - name: Hand of Iliam
      type: mysticalability
      system:
        subType: arcaneincantation
        assocSkillCode: fyvria
        assocAffiliationCode: fyvria
        levelBase: 2
    - name: Favrin's Bar
      type: mysticalability
      system:
        subType: arcaneincantation
        assocSkillCode: fyvria
        assocAffiliationCode: fyvria
        levelBase: 3
    - name: Power of Sharadorn
      type: mysticalability
      system:
        subType: arcaneincantation
        assocSkillCode: fyvria
        assocAffiliationCode: fyvria
        levelBase: 3
    - name: Dream of Galega
      type: mysticalability
      system:
        subType: arcaneincantation
        assocSkillCode: fyvria
        assocAffiliationCode: fyvria
        levelBase: 4
---

# Appearance {#appearance}

**Height**: 5' 5"
**Frame**: Light
**Weight**: 126
**Size**: 5
**Comeliness**: Attractive
**Complexion**: Medium
**Hair Color**: Brown
**Eye Color**: Hazel
**Voice**: Average

# Dossier {#dossier}

**Age**: 23
**Birthday**: 9 Morgat 697
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: 3rd child of 10
**Siblings**: mmFffFMFMF
**Parentage**: Offspring
**Offspring**: Both parents alive and living together
**Estrangement**: Unpopular
**Clanhead**: Aunt/Uncle

## Notes

Modifier to Frame of -3 (from 11) {Sex=Female, Species=Human}

Modifier to AttributesAGL of +1 (from 16) {Frame=Light}

Modifier to AttributesAUR of +2 (from 14) {Sex=Female, Species=Human}

126lbs weight resulted in -2 strength mod.

Light frame resulted in +1 agility mod.

Modifier to StartingEquipment of +100 (from 59) {SocialClass=Serf}
