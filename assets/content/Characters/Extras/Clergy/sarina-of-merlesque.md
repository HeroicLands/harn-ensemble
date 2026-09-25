---
tags:
  - character
name:
  full: Sarina of Merlesque
  title: ""
  given: Sarina
  clan: Merlesque
  aliases: []
id: cZRPadbgt6lterav
packFolder: extrasclergy
shortcode: sarinaofmerlesque
type: being
social:
  occupation: Cleric/Larani
  class: serf
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual:
    - larani
data:
  templatePriority: 1
  gender: female
  species: humanflk
  age: 26
  born: 694/6/6
  height: 1.7
  weight: 67.59
  frame: medium
  appearance:
    eye_color: blue
    hair_color: black
    skin_color: dark
    complexion: plain
    extra_features: []
hm3:
  type: character
  attributes:
    str: 14
    sta: 13
    dex: 8
    agl: 13
    int: 16
    aur: 11
    wil: 15
    eye: 6
    hrg: 16
    sml: 10
    voi: 14
    cml: 8
    mor: 13
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
    - { shortcode: condition, type: skill, system: { masteryLevel: 70 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 42 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 40 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 40 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: language, type: skill, name: Language(Emela), system: { masteryLevel: 45 } }
    - shortcode: language
      type: skill
      name: Language, Serf
      system:
        shortcode: languageserf
        masteryLevel: 65
    - { shortcode: mentalconflict, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 42 } }
    - { shortcode: script, type: skill, name: Script(Khruni), system: { masteryLevel: 90 } }
    - shortcode: script
      type: skill
      name: Script(Lakaise)
      system:
        shortcode: scriptlakaise
        masteryLevel: 80
    - { shortcode: dagger, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 84 } }
    - { shortcode: shield, type: skill, system: { masteryLevel: 40 } }
    - { shortcode: sword, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 44 } }
    - { shortcode: drawing, type: skill, system: { masteryLevel: 18 } }
    - { shortcode: embalming, type: skill, system: { masteryLevel: 16 } }
    - { shortcode: folklore, type: skill, system: { masteryLevel: 45 } }
    - { shortcode: heraldry, type: skill, system: { masteryLevel: 27 } }
    - { shortcode: law, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 20 } }
    - { shortcode: larani, type: skill, system: { masteryLevel: 68 } }
    - { shortcode: laranibaptism, type: invocation }
    - { shortcode: laraniblessing, type: invocation }
    - { shortcode: laranicommune, type: invocation }
    - { shortcode: laraniliturgy, type: invocation }
    - { shortcode: laranimarriage, type: invocation }
    - { shortcode: laranipassageofthesoul, type: invocation }
    - { shortcode: protectionofangcaradina, type: invocation }
    - { shortcode: bandageofstperelyne, type: invocation }
    - { shortcode: valaminsinsight, type: invocation }
    - { shortcode: blessingofthewingedlion, type: invocation }
    - { shortcode: courageofmendiz, type: invocation }
    - { shortcode: heraldoftheendoflife, type: invocation }
    - { shortcode: pence, type: miscgear, system: { quantity: 152 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: LLeg, type: armorgear }
    - { shortcode: CShoe, type: armorgear }
    - { shortcode: LTunic, type: armorgear }
    - { shortcode: Kni, type: weapongear }
  system:
    species: human
    sunsign: angberelius-nadai
    move: 12
sohl:
  kbcat: archetype
  items:
    - { model: attribute-str, system: { scoreBase: 14 } }
    - { model: attribute-end, system: { scoreBase: 13 } }
    - { model: attribute-dex, system: { scoreBase: 8 } }
    - { model: attribute-agl, system: { scoreBase: 13 } }
    - { model: attribute-per, system: { scoreBase: 10 } }
    - { model: attribute-snt, system: { scoreBase: 10 } }
    - { model: attribute-cml, system: { scoreBase: 8 } }
    - { model: attribute-aur, system: { scoreBase: 11 } }
    - { model: attribute-wil, system: { scoreBase: 15 } }
    - { model: attribute-rea, system: { scoreBase: 16 } }
    - { model: attribute-cre, system: { scoreBase: 11 } }
    - { model: attribute-emp, system: { scoreBase: 10 } }
    - { model: attribute-elo, system: { scoreBase: 14 } }
    - { model: attribute-mor, system: { scoreBase: 13 } }
    - { model: attribute-voi, system: { scoreBase: 14 } }
    - { model: skill-archery }
    - { model: skill-awar, system: { masteryLevelBase: 40 } }
    - { model: skill-chrm }
    - { model: skill-clmb, system: { masteryLevelBase: 44 } }
    - { model: skill-cmd }
    - { model: skill-cook }
    - { model: skill-dnce }
    - { model: skill-dscr }
    - { model: skill-draw, system: { masteryLevelBase: 18 } }
    - { model: skill-folklr, system: { masteryLevelBase: 45 } }
    - { model: skill-guil }
    - { model: skill-init, system: { masteryLevelBase: 84 } }
    - { model: skill-shok }
    - { model: skill-intr, system: { masteryLevelBase: 56 } }
    - { model: skill-jump, system: { masteryLevelBase: 60 } }
    - { model: skill-melee, system: { masteryLevelBase: 43 } }
    - { model: skill-dge }
    - { model: skill-pysn, system: { masteryLevelBase: 20 } }
    - { model: skill-ridg }
    - { model: skill-sing, system: { masteryLevelBase: 42 } }
    - { model: skill-stlth, system: { masteryLevelBase: 42 } }
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
    - { model: skill-lang, name: "Language, Serf", system: { masteryLevelBase: 65 } }
    - { model: skill-script, name: Script(Lakaise), system: { masteryLevelBase: 80 } }
    - { model: skill-embl, system: { masteryLevelBase: 16 } }
    - { model: skill-hrld, system: { masteryLevelBase: 27 } }
    - { model: skill-law, system: { masteryLevelBase: 30 } }
    - { model: miscgear-pence, system: { quantity: 152 } }
    - { model: containergear-pouchbuckram }
    - { model: armorgear-LLeg }
    - { model: armorgear-CShoe }
    - { model: armorgear-LTunic }
    - { model: weapongear-Kni }
    - { name: Larani, type: affiliation, system: { shortcode: larani, subType: divine } }
    - name: Larani
      type: skill
      system:
        subType: mystical
        shortcode: larani
        skillBaseFormula: sb(attr.wil, attr.rea)
        masteryLevelBase: 68
    - name: Baptism
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: larani
        assocAffiliationCode: larani
        levelBase: 2
    - name: Blessing
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: larani
        assocAffiliationCode: larani
        levelBase: 2
    - name: Commune
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: larani
        assocAffiliationCode: larani
        levelBase: 2
    - name: Liturgy
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: larani
        assocAffiliationCode: larani
        levelBase: 2
    - name: Marriage
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: larani
        assocAffiliationCode: larani
        levelBase: 2
    - name: Passage of the Soul
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: larani
        assocAffiliationCode: larani
        levelBase: 2
    - name: Protection of Angcaradina
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: larani
        assocAffiliationCode: larani
        levelBase: 4
    - name: Bandage of St. Perelyne
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: larani
        assocAffiliationCode: larani
        levelBase: 3
    - name: Valamin's Insight
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: larani
        assocAffiliationCode: larani
        levelBase: 2
    - name: Blessing of the Winged Lion
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: larani
        assocAffiliationCode: larani
        levelBase: 3
    - name: Courage of Mendiz
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: larani
        assocAffiliationCode: larani
        levelBase: 2
    - name: Herald of the End of Life
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: larani
        assocAffiliationCode: larani
        levelBase: 3
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

**Height**: 5' 7"
**Frame**: Medium
**Weight**: 149
**Size**: 6
**Comeliness**: Plain
**Complexion**: Dark
**Hair Color**: Black
**Eye Color**: Blue
**Voice**: Pleasant

# Dossier {#dossier}

**Age**: 26
**Birthday**: 6 Agrazhar 694
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: 6th child of 6
**Siblings**: FFFMMF
**Parentage**: Orphan
**Estrangement**: Unpopular
**Clanhead**: Grandfather's Aunt/Uncle

## Notes

Modifier to Frame of -3 (from 12) {Sex=Female, Species=Human}

Modifier to AttributesAUR of +2 (from 9) {Sex=Female, Species=Human}

Modifier to HairColor of -25 (from 20) {Complexion=Dark, Species=Human}

Modifier to EyeColor of +25 (from 12) {Complexion=Dark, Species=Human}

Modifier to StartingEquipment of +100 (from 11) {SocialClass=Serf}
