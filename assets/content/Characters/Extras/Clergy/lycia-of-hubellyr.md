---
tags:
  - character
name:
  full: Lycia of Hubellyr
  title: ""
  given: Lycia
  clan: Hubellyr
  aliases: []
id: 8jOMig6yvG1sS4Cq
packFolder: extrasclergy
shortcode: lyciaofhubellyr
type: being
social:
  occupation: Cleric/Morgath
  class: unguilded
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual:
    - morgath
data:
  templatePriority: 1
  gender: female
  species: human
  age: 27
  birthday: 693/11/30
  height: 1.78
  weight: 129.73
  frame: medium
  appearance:
    eye_color: green
    hair_color: black
    skin_color: dark
    complexion: average
    extra_features:
      - "*Parasites"
hm3:
  type: character
  attributes:
    str: 8
    sta: 7
    dex: 14
    agl: 11
    int: 13
    aur: 16
    wil: 10
    eye: 8
    hrg: 11
    sml: 12
    voi: 13
    cml: 12
    mor: 4
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 44 } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 45 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 40 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 40 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 40 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: language, type: skill, name: Language(Azeri), system: { masteryLevel: 36 } }
    - shortcode: language
      type: skill
      name: Language(Ormauk)
      system:
        shortcode: languageormauk
        masteryLevel: 36
    - shortcode: language
      type: skill
      name: Language, Unguilded
      system:
        shortcode: languageunguilded
        masteryLevel: 62
    - { shortcode: mentalconflict, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 39 } }
    - { shortcode: script, type: skill, name: Script(Lakaise), system: { masteryLevel: 81 } }
    - shortcode: script
      type: skill
      name: Script(Nuvesarl)
      system:
        shortcode: scriptnuvesarl
        masteryLevel: 81
    - { shortcode: dagger, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 40 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: drawing, type: skill, system: { masteryLevel: 20 } }
    - { shortcode: embalming, type: skill, system: { masteryLevel: 33 } }
    - { shortcode: folklore, type: skill, system: { masteryLevel: 39 } }
    - { shortcode: heraldry, type: skill, system: { masteryLevel: 20 } }
    - shortcode: hidework
      type: skill
      name: Human Skin (Hidework)
      system:
        masteryLevel: 24
    - { shortcode: law, type: skill, system: { masteryLevel: 24 } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 26 } }
    - { shortcode: tarotry, type: skill, system: { masteryLevel: 26 } }
    - { shortcode: woodcraft, type: skill, name: Masks (Woodcraft), system: { masteryLevel: 26 } }
    - { shortcode: morgath, type: skill, system: { masteryLevel: 64 } }
    - { shortcode: morgathbaptism, type: invocation }
    - { shortcode: morgathblessing, type: invocation }
    - { shortcode: morgathcommune, type: invocation }
    - { shortcode: morgathliturgy, type: invocation }
    - { shortcode: morgathmarriage, type: invocation }
    - { shortcode: morgathpassageofthesoul, type: invocation }
    - { shortcode: myvriaskiss, type: invocation }
    - { shortcode: klysscommand, type: invocation }
    - { shortcode: heartofdarkness, type: invocation }
    - { shortcode: throatofklyss, type: invocation }
    - { shortcode: necrosy, type: invocation }
    - { shortcode: speakwithdead, type: invocation }
    - { shortcode: pence, type: miscgear, system: { quantity: 120 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: SgLeg, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: SgTunic, type: armorgear }
    - { shortcode: Kni, type: weapongear }
  system:
    sunsign: masara-lado
    move: 9
sohl:
  kbcat: archetype
  items:
    - { model: attribute-str, system: { scoreBase: 8 } }
    - { model: attribute-end, system: { scoreBase: 7 } }
    - { model: attribute-dex, system: { scoreBase: 14 } }
    - { model: attribute-agl, system: { scoreBase: 11 } }
    - { model: attribute-per, system: { scoreBase: 9 } }
    - { model: attribute-snt, system: { scoreBase: 12 } }
    - { model: attribute-cml, system: { scoreBase: 12 } }
    - { model: attribute-aur, system: { scoreBase: 16 } }
    - { model: attribute-wil, system: { scoreBase: 10 } }
    - { model: attribute-rea, system: { scoreBase: 13 } }
    - { model: attribute-cre, system: { scoreBase: 9 } }
    - { model: attribute-emp, system: { scoreBase: 11 } }
    - { model: attribute-elo, system: { scoreBase: 11 } }
    - { model: attribute-mor, system: { scoreBase: 4 } }
    - { model: attribute-voi, system: { scoreBase: 13 } }
    - { model: skill-archery }
    - { model: skill-awar, system: { masteryLevelBase: 40 } }
    - { model: skill-chrm }
    - { model: skill-clmb, system: { masteryLevelBase: 44 } }
    - { model: skill-cmd }
    - { model: skill-cook }
    - { model: skill-dnce }
    - { model: skill-dscr }
    - { model: skill-draw, system: { masteryLevelBase: 20 } }
    - { model: skill-folklr, system: { masteryLevelBase: 39 } }
    - { model: skill-guil }
    - { model: skill-init, system: { masteryLevelBase: 40 } }
    - { model: skill-shok }
    - { model: skill-intr, system: { masteryLevelBase: 52 } }
    - { model: skill-jump, system: { masteryLevelBase: 40 } }
    - { model: skill-melee, system: { masteryLevelBase: 48 } }
    - { model: skill-dge }
    - { model: skill-pysn, system: { masteryLevelBase: 26 } }
    - { model: skill-ridg }
    - { model: skill-sing, system: { masteryLevelBase: 39 } }
    - { model: skill-stlth, system: { masteryLevelBase: 30 } }
    - { model: skill-srvl }
    - { model: skill-spirit }
    - { model: skill-swim }
    - { model: skill-thtcs }
    - { model: skill-thro, system: { masteryLevelBase: 40 } }
    - { model: skill-bflkbite }
    - { model: skill-bflkgrab }
    - { model: skill-bflkheadbutt }
    - { model: skill-bflkkick }
    - { model: skill-limbblock }
    - { model: skill-press }
    - { model: skill-bflkpunch }
    - { model: skill-trip }
    - { model: mysticalability-sprt }
    - model: skill-lang
      name: Language, Unguilded
      system:
        masteryLevelBase: 62
    - { model: skill-script, name: Script(Nuvesarl), system: { masteryLevelBase: 81 } }
    - { model: skill-embl, system: { masteryLevelBase: 33 } }
    - { model: skill-hrld, system: { masteryLevelBase: 20 } }
    - model: skill-hide
      name: Human Skin (Hidework)
      system:
        masteryLevelBase: 24
    - { model: skill-law, system: { masteryLevelBase: 24 } }
    - { model: mysticalability-tarot, system: { masteryLevelBase: 26 } }
    - { model: miscgear-pence, system: { quantity: 120 } }
    - { model: containergear-pouchbuckram }
    - { model: armorgear-SgLeg }
    - { model: armorgear-LtShoe }
    - { model: armorgear-SgTunic }
    - { model: weapongear-Kni }
    - { name: Morgath, type: affiliation, system: { shortcode: morgath, subType: divine } }
    - name: Morgath
      type: skill
      system:
        subType: mystical
        shortcode: morgath
        skillBaseFormula: sb(attr.wil, attr.rea)
        masteryLevelBase: 64
    - name: Baptism
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 2
    - name: Blessing
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 2
    - name: Commune
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 2
    - name: Liturgy
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 2
    - name: Marriage
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 2
    - name: Passage of the Soul
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 2
    - name: Myvria's Kiss
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 4
    - name: Klyss' Command
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 3
    - name: Heart of Darkness
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 2
    - name: Throat of Klyss
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 3
    - name: Necrosy
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 2
    - name: Speak with Dead
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 2
  system:
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
---

# Appearance {#appearance}

**Height**: 5' 10"
**Frame**: Medium
**Weight**: 286
**Size**: 10
**Comeliness**: Average
**Complexion**: Dark
**Hair Color**: Black
**Eye Color**: Green
**Voice**: Pleasant

# Dossier {#dossier}

**Age**: 27
**Birthday**: 30 Navek 693
**Culture**: Feudal
**Social Class**: Unguilded
**Sibling Rank**: 3rd child of 8
**Siblings**: fFFmMMFm
**Parentage**: Offspring
**Offspring**: Both parents alive and living together
**Estrangement**: Favorite
**Clanhead**: Father's Father/Mother
**Medical**: *Parasites

## Notes

Modifier to Frame of -3 (from 12) {Sex=Female, Species=Human}

Modifier to AttributesAUR of +2 (from 14) {Sex=Female, Species=Human}

Modifier to HairColor of -25 (from 36) {Complexion=Dark, Species=Human}

Modifier to EyeColor of +25 (from 30) {Complexion=Dark, Species=Human}

Parastites cause special penalty to Rhetoric and Lovecraft until cured.

160lbs weight resulted in +1 strength mod.

Modifier to StartingEquipment of +200 (from 19) {SocialClass=Unguilded}
