---
aliases:
  - Norbin of Bardrass
tags: []
name:
  full: Norbin of Bardrass
  title: ""
  given: Norbin
  clan: Bardrass
  aliases: []
id: mVzxKnCo3lJldivN
folder: wYO4XEaOHdLCVUM0
shortcode: norbinofbardrass
portrait: systems/hm3/images/svg/knight-silhouette.svg
type: being
social:
  occupation: Herald
  class: unguilded
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
traits:
  species: human
  gender: male
  age: 43
  birthday: 677/5/28
  height:
    m: 1.63
  weight:
    kg: 112.49
  build:
    frame: medium
  appearance:
    eye_color: green
    hair_color: strawberry blond
    skin_color: fair
    complexion: beautiful
    extra_features:
      - Addiction
hm3:
  species: human
  sunsign: angberelius
  attributes:
    str: 8
    sta: 11
    dex: 9
    agl: 10
    int: 11
    aur: 17
    wil: 12
    eye: 9
    hrg: 15
    sml: 12
    voi: 10
    cml: 16
    mor: 5
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 70 } }
    - { shortcode: dancing, type: skill, system: { masteryLevel: 27 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 40 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 65 } }
    - { shortcode: language, type: skill, name: Language(Ivinian), system: { masteryLevel: 11 } }
    - shortcode: language
      type: skill
      name: Language, Unguilded
      system:
        masteryLevel: 61
    - { shortcode: oratory, type: skill, system: { masteryLevel: 84 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 88 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 33 } }
    - { shortcode: script, type: skill, name: Script(Lakaise), system: { masteryLevel: 79 } }
    - { shortcode: axe, type: skill, name: Handaxe (Axe), system: { masteryLevel: 45 } }
    - { shortcode: dagger, type: skill, system: { masteryLevel: 80 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 66 } }
    - { shortcode: polearm, type: skill, name: Lance (Polearm), system: { masteryLevel: 63 } }
    - { shortcode: riding, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: shield, type: skill, system: { masteryLevel: 64 } }
    - { shortcode: sword, type: skill, name: Broadsword (Sword), system: { masteryLevel: 66 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: drawing, type: skill, system: { masteryLevel: 54 } }
    - { shortcode: foraging, type: skill, system: { masteryLevel: 40 } }
    - { shortcode: heraldry, type: skill, system: { masteryLevel: 50 } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 18 } }
    - { shortcode: survival, type: skill, system: { masteryLevel: 45 } }
    - { shortcode: weaponcraft, type: skill, system: { masteryLevel: 20 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 1104 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: LtCBoot, type: armorgear }
    - { shortcode: SgLeg, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: SgTunic, type: armorgear }
    - { shortcode: Kni, type: weapongear }
    - { shortcode: tndrbx, type: miscgear }
    - name: Pendant, Silver
      type: miscgear
      img: systems/hm3/images/icons/svg/miscgear.svg
      system:
        value: 45
        weight: 0.05
    - { shortcode: pipesmokin, type: miscgear }
    - { shortcode: writingkitportable, type: miscgear }
    - { shortcode: KnSh, type: weapongear }
    - { shortcode: spoonwooden, type: miscgear }
    - { shortcode: tndrbx, type: miscgear }
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
    - { shortcode: str, type: attribute, system: { scoreBase: 8 } }
    - { shortcode: end, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: dex, type: attribute, system: { scoreBase: 9 } }
    - { shortcode: agl, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: per, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: snt, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: cml, type: attribute, system: { scoreBase: 16 } }
    - { shortcode: aur, type: attribute, system: { scoreBase: 17 } }
    - { shortcode: wil, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: rea, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: cre, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: emp, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: elo, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: mor, type: attribute, system: { scoreBase: 5 } }
    - { shortcode: voi, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: archery, type: skill }
    - { shortcode: awar, type: skill, system: { masteryLevelBase: 60 } }
    - { shortcode: chrm, type: skill }
    - { shortcode: clmb, type: skill, system: { masteryLevelBase: 36 } }
    - { shortcode: cmd, type: skill }
    - { shortcode: cook, type: skill }
    - { shortcode: dnce, type: skill, system: { masteryLevelBase: 27 } }
    - { shortcode: dscr, type: skill }
    - { shortcode: draw, type: skill, system: { masteryLevelBase: 54 } }
    - { shortcode: folklr, type: skill }
    - { shortcode: guil, type: skill }
    - { shortcode: init, type: skill, system: { masteryLevelBase: 66 } }
    - { shortcode: shok, type: skill }
    - { shortcode: intr, type: skill, system: { masteryLevelBase: 65 } }
    - { shortcode: jump, type: skill, system: { masteryLevelBase: 36 } }
    - { shortcode: melee, type: skill, system: { masteryLevelBase: 64 } }
    - { shortcode: dge, type: skill }
    - { shortcode: pysn, type: skill, system: { masteryLevelBase: 18 } }
    - { shortcode: ridg, type: skill, system: { masteryLevelBase: 60 } }
    - { shortcode: sing, type: skill, system: { masteryLevelBase: 33 } }
    - { shortcode: stlth, type: skill, system: { masteryLevelBase: 36 } }
    - { shortcode: srvl, type: skill, system: { masteryLevelBase: 45 } }
    - { shortcode: spirit, type: skill }
    - { shortcode: swim, type: skill }
    - { shortcode: thtcs, type: skill }
    - { shortcode: thro, type: skill, system: { masteryLevelBase: 40 } }
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
      name: Language, Unguilded
      system:
        masteryLevelBase: 61
    - { shortcode: script, type: skill, name: Script(Lakaise), system: { masteryLevelBase: 79 } }
    - { shortcode: hrld, type: skill, system: { masteryLevelBase: 50 } }
    - { shortcode: wpnc, type: skill, system: { masteryLevelBase: 20 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 1104 } }
    - { shortcode: pouchbuckram, type: containergear }
    - { shortcode: LtCBoot, type: armorgear }
    - { shortcode: SgLeg, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: SgTunic, type: armorgear }
    - { shortcode: Kni, type: weapongear }
    - { shortcode: tndrbx, type: miscgear }
    - { shortcode: amuletsilver, type: miscgear }
    - { shortcode: pipesmokin, type: miscgear }
    - { shortcode: scribekit, type: miscgear }
    - { shortcode: KnSh, type: weapongear }
    - { shortcode: spoonpewte, type: miscgear }
---

# Appearance {#appearance}

**Height**: 5' 4"
**Frame**: Medium
**Weight**: 248
**Size**: 9
**Comeliness**: Beautiful
**Complexion**: Fair
**Hair Color**: Strawberry Blond
**Eye Color**: Green
**Voice**: Average

# Dossier {#dossier}

**Age**: 43
**Birthday**: 28 Larane 677
**Culture**: Feudal
**Social Class**: Unguilded
**Sibling Rank**: 2nd child of 4
**Siblings**: MMmM
**Parentage**: Offspring
**Offspring**: Both parents alive and living together
**Estrangement**: Unpopular
**Clanhead**: Father's Aunt/Uncle
**Medical**: Addiction

## Notes

Modifier to HairColor of +25 (from 55) {Complexion=Fair, Species=Human}

Modifier to EyeColor of -10 (from 64) {Complexion=Fair, Species=Human}

137lbs weight resulted in -1 strength mod.

Modifier to StartingEquipment of +200 (from 78) {SocialClass=Unguilded}
