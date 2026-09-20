---
tags:
  - character
name:
  full: Corfyn of Barsel
  title: ""
  given: Corfyn
  clan: Barsel
  aliases: []
id: GAUXS2PWxQI9IdVT
packFolder: extrasclergy
shortcode: corfynofbarsel
type: being
social:
  occupation: Cleric/Agrik
  class: serf
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual:
    - agrik
data:
  templatePriority: 1
  gender: male
  species: human
  age: 27
  birthday: 693/10/17
  height: 1.7
  weight: 67.59
  frame: medium
  appearance:
    eye_color: brown
    hair_color: brown
    skin_color: dark
    complexion: average
    extra_features:
      - Allergy
hm3:
  type: character
  attributes:
    str: 14
    sta: 10
    dex: 15
    agl: 7
    int: 15
    aur: 8
    wil: 14
    eye: 12
    hrg: 13
    sml: 7
    voi: 16
    cml: 9
    mor: 8
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 33 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 40 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: language, type: skill, name: Language(Azeryani), system: { masteryLevel: 45 } }
    - shortcode: language
      type: skill
      name: Language(Surikal)
      system:
        shortcode: languagesurikal
        masteryLevel: 60
    - shortcode: language
      type: skill
      name: Language, Serf
      system:
        shortcode: languageserf
        masteryLevel: 80
    - { shortcode: mentalconflict, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 64 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 45 } }
    - { shortcode: script, type: skill, name: Script(Lakaise), system: { masteryLevel: 98 } }
    - shortcode: script
      type: skill
      name: Script(Zerin)
      system:
        shortcode: scriptzerin
        masteryLevel: 84
    - { shortcode: axe, type: skill, name: Sickle (Axe), system: { masteryLevel: 70 } }
    - { shortcode: club, type: skill, name: Mace (Club), system: { masteryLevel: 56 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 66 } }
    - { shortcode: shield, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: drawing, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: embalming, type: skill, system: { masteryLevel: 26 } }
    - { shortcode: folklore, type: skill, system: { masteryLevel: 45 } }
    - { shortcode: heraldry, type: skill, system: { masteryLevel: 42 } }
    - { shortcode: law, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: agrik, type: skill, system: { masteryLevel: 90 } }
    - { shortcode: agrikbaptism, type: invocation }
    - { shortcode: agrikblessing, type: invocation }
    - { shortcode: agrikcommune, type: invocation }
    - { shortcode: agrikliturgy, type: invocation }
    - { shortcode: agrikmarriage, type: invocation }
    - { shortcode: agrikpassageofthesoul, type: invocation }
    - { shortcode: agriksrespite, type: invocation }
    - { shortcode: searinghand, type: invocation }
    - { shortcode: emynscut, type: invocation }
    - { shortcode: torturersinsight, type: invocation }
    - { shortcode: shieldofamana, type: invocation }
    - { shortcode: agrikawe, type: invocation }
    - { shortcode: agrikendure, type: invocation }
    - { shortcode: agriktongues, type: invocation }
    - { shortcode: aksytspeace, type: invocation }
    - { shortcode: pence, type: miscgear, system: { quantity: 328 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: LLeg, type: armorgear }
    - { shortcode: CShoe, type: armorgear }
    - { shortcode: LTunic, type: armorgear }
    - { shortcode: Kni, type: weapongear }
  system:
    sunsign: skorus
    move: 10
sohl:
  kbcat: archetype
  items:
    - { model: attribute-str, system: { scoreBase: 14 } }
    - { model: attribute-end, system: { scoreBase: 10 } }
    - { model: attribute-dex, system: { scoreBase: 15 } }
    - { model: attribute-agl, system: { scoreBase: 7 } }
    - { model: attribute-per, system: { scoreBase: 10 } }
    - { model: attribute-snt, system: { scoreBase: 7 } }
    - { model: attribute-cml, system: { scoreBase: 9 } }
    - { model: attribute-aur, system: { scoreBase: 8 } }
    - { model: attribute-wil, system: { scoreBase: 14 } }
    - { model: attribute-rea, system: { scoreBase: 15 } }
    - { model: attribute-cre, system: { scoreBase: 14 } }
    - { model: attribute-emp, system: { scoreBase: 9 } }
    - { model: attribute-elo, system: { scoreBase: 15 } }
    - { model: attribute-mor, system: { scoreBase: 8 } }
    - { model: attribute-voi, system: { scoreBase: 16 } }
    - { model: skill-archery }
    - { model: skill-awar, system: { masteryLevelBase: 40 } }
    - { model: skill-chrm }
    - { model: skill-clmb, system: { masteryLevelBase: 48 } }
    - { model: skill-cmd }
    - { model: skill-cook }
    - { model: skill-dnce }
    - { model: skill-dscr }
    - { model: skill-draw, system: { masteryLevelBase: 30 } }
    - { model: skill-folklr, system: { masteryLevelBase: 45 } }
    - { model: skill-guil }
    - { model: skill-init, system: { masteryLevelBase: 66 } }
    - { model: skill-shok }
    - { model: skill-intr, system: { masteryLevelBase: 52 } }
    - { model: skill-jump, system: { masteryLevelBase: 36 } }
    - { model: skill-melee, system: { masteryLevelBase: 61 } }
    - { model: skill-dge }
    - { model: skill-pysn, system: { masteryLevelBase: 30 } }
    - { model: skill-ridg }
    - { model: skill-sing, system: { masteryLevelBase: 45 } }
    - { model: skill-stlth, system: { masteryLevelBase: 33 } }
    - { model: skill-srvl }
    - { model: skill-spirit }
    - { model: skill-swim }
    - { model: skill-thtcs }
    - { model: skill-thro, system: { masteryLevelBase: 52 } }
    - { model: skill-bflkbite }
    - { model: skill-bflkgrab }
    - { model: skill-bflkheadbutt }
    - { model: skill-bflkkick }
    - { model: skill-limbblock }
    - { model: skill-press }
    - { model: skill-bflkpunch }
    - { model: skill-trip }
    - { model: mysticalability-sprt }
    - { model: skill-lang, name: "Language, Serf", system: { masteryLevelBase: 80 } }
    - { model: skill-script, name: Script(Zerin), system: { masteryLevelBase: 84 } }
    - { model: skill-embl, system: { masteryLevelBase: 26 } }
    - { model: skill-hrld, system: { masteryLevelBase: 42 } }
    - { model: skill-law, system: { masteryLevelBase: 30 } }
    - { model: miscgear-pence, system: { quantity: 328 } }
    - { model: containergear-pouchbuckram }
    - { model: armorgear-LLeg }
    - { model: armorgear-CShoe }
    - { model: armorgear-LTunic }
    - { model: weapongear-Kni }
    - { name: Agrik, type: affiliation, system: { shortcode: agrik, subType: divine } }
    - name: Agrik
      type: skill
      system:
        subType: mystical
        shortcode: agrik
        skillBaseFormula: sb(attr.wil, attr.rea)
        masteryLevelBase: 90
    - name: Baptism
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 2
    - name: Blessing
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 2
    - name: Commune
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 2
    - name: Liturgy
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 2
    - name: Marriage
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 2
    - name: Passage of the Soul
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 2
    - name: Agrik's Respite
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 4
    - name: Searing Hand
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 3
    - name: Emyn's Cut
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 2
    - name: Torturer's Insight
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 3
    - name: Shield of Amana
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 2
    - name: Awe
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 3
    - name: Endure
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 3
    - name: Tongues
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 3
    - name: Ak-Syt's Peace
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
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

**Height**: 5' 7"
**Frame**: Medium
**Weight**: 149
**Size**: 6
**Comeliness**: Average
**Complexion**: Dark
**Hair Color**: Brown
**Eye Color**: Brown
**Voice**: Excellent

# Dossier {#dossier}

**Age**: 27
**Birthday**: 17 Ilvin 693
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: 5th child of 5
**Siblings**: MmffM
**Parentage**: Fostered
**Estrangement**: Popular
**Clanhead**: Father's Father/Mother
**Medical**: Allergy

## Notes

Modifier to HairColor of -25 (from 52) {Complexion=Dark, Species=Human}

Modifier to EyeColor of +25 (from 58) {Complexion=Dark, Species=Human}

Modifier to StartingEquipment of +100 (from 78) {SocialClass=Serf}
