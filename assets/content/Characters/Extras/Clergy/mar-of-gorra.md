---
tags:
  - character
name:
  full: Mar of Gorra
  title: ""
  given: Mar
  clan: Gorra
  aliases: []
id: Knn4lL0jrmlDopWw
packFolder: extrasclergy
shortcode: marofgorra
type: being
social:
  occupation: Cleric/Halea
  class: serf
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual:
    - halea
data:
  templatePriority: 1
  gender: male
  species: human
  age: 26
  born: 694/7/27
  height: 1.7
  weight: 135.17
  frame: medium
  appearance:
    eye_color: green
    hair_color: brown
    skin_color: dark
    complexion: attractive
    extra_features:
      - Allergy
hm3:
  type: character
  attributes:
    str: 11
    sta: 8
    dex: 7
    agl: 10
    int: 14
    aur: 13
    wil: 14
    eye: 10
    hrg: 10
    sml: 11
    voi: 14
    cml: 15
    mor: 7
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
    - { shortcode: condition, type: skill, system: { masteryLevel: 55 } }
    - { shortcode: dancing, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 39 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 44 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 55 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: language, type: skill, name: Language(Karuia), system: { masteryLevel: 70 } }
    - shortcode: language
      type: skill
      name: Language(Old Jarinese)
      system:
        shortcode: languageoldjarinese
        masteryLevel: 56
    - shortcode: language
      type: skill
      name: Language, Serf
      system:
        shortcode: languageserf
        masteryLevel: 64
    - { shortcode: lovecraft, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: mentalconflict, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: musician, type: skill, system: { masteryLevel: 18 } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 42 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: script, type: skill, name: Script(Lakaise), system: { masteryLevel: 80 } }
    - shortcode: script
      type: skill
      name: Script(Script(Runic))
      system:
        shortcode: scriptrunic
        masteryLevel: 80
    - shortcode: script
      type: skill
      name: Script(Zerin)
      system:
        shortcode: scriptzerin
        masteryLevel: 80
    - { shortcode: initiative, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: drawing, type: skill, system: { masteryLevel: 18 } }
    - { shortcode: embalming, type: skill, system: { masteryLevel: 18 } }
    - { shortcode: folklore, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: heraldry, type: skill, system: { masteryLevel: 20 } }
    - { shortcode: law, type: skill, system: { masteryLevel: 42 } }
    - { shortcode: mathematics, type: skill, system: { masteryLevel: 28 } }
    - { shortcode: perfumery, type: skill, system: { masteryLevel: 26 } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: halea, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: haleabaptism, type: invocation }
    - { shortcode: haleablessing, type: invocation }
    - { shortcode: haleacommune, type: invocation }
    - { shortcode: halealiturgy, type: invocation }
    - { shortcode: haleamarriage, type: invocation }
    - { shortcode: haleapassageofthesoul, type: invocation }
    - { shortcode: haleasapple, type: invocation }
    - { shortcode: curedisease, type: invocation }
    - { shortcode: dulciassong, type: invocation }
    - { shortcode: kilnaswhip, type: invocation }
    - { shortcode: sardurasvision, type: invocation }
    - { shortcode: ecstacy, type: invocation }
    - { shortcode: pence, type: miscgear, system: { quantity: 261 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: LLeg, type: armorgear }
    - { shortcode: CShoe, type: armorgear }
    - { shortcode: LTunic, type: armorgear }
    - { shortcode: Kni, type: weapongear }
  system:
    sunsign: hirin
    move: 9
sohl:
  kbcat: archetype
  items:
    - { model: attribute-str, system: { scoreBase: 11 } }
    - { model: attribute-end, system: { scoreBase: 8 } }
    - { model: attribute-dex, system: { scoreBase: 7 } }
    - { model: attribute-agl, system: { scoreBase: 10 } }
    - { model: attribute-per, system: { scoreBase: 9 } }
    - { model: attribute-snt, system: { scoreBase: 11 } }
    - { model: attribute-cml, system: { scoreBase: 15 } }
    - { model: attribute-aur, system: { scoreBase: 13 } }
    - { model: attribute-wil, system: { scoreBase: 14 } }
    - { model: attribute-rea, system: { scoreBase: 14 } }
    - { model: attribute-cre, system: { scoreBase: 12 } }
    - { model: attribute-emp, system: { scoreBase: 12 } }
    - { model: attribute-elo, system: { scoreBase: 14 } }
    - { model: attribute-mor, system: { scoreBase: 7 } }
    - { model: attribute-voi, system: { scoreBase: 14 } }
    - { model: skill-archery }
    - { model: skill-awar, system: { masteryLevelBase: 55 } }
    - { model: skill-chrm }
    - { model: skill-clmb, system: { masteryLevelBase: 36 } }
    - { model: skill-cmd }
    - { model: skill-cook }
    - { model: skill-dnce, system: { masteryLevelBase: 30 } }
    - { model: skill-dscr }
    - { model: skill-draw, system: { masteryLevelBase: 18 } }
    - { model: skill-folklr, system: { masteryLevelBase: 56 } }
    - { model: skill-guil }
    - { model: skill-init, system: { masteryLevelBase: 48 } }
    - { model: skill-shok }
    - { model: skill-intr, system: { masteryLevelBase: 52 } }
    - { model: skill-jump, system: { masteryLevelBase: 48 } }
    - { model: skill-melee }
    - { model: skill-dge }
    - { model: skill-pysn, system: { masteryLevelBase: 30 } }
    - { model: skill-ridg }
    - { model: skill-sing, system: { masteryLevelBase: 36 } }
    - { model: skill-stlth, system: { masteryLevelBase: 39 } }
    - { model: skill-srvl }
    - { model: skill-spirit }
    - { model: skill-swim }
    - { model: skill-thtcs }
    - { model: skill-thro, system: { masteryLevelBase: 44 } }
    - { model: skill-bflkbite }
    - { model: skill-bflkgrab }
    - { model: skill-bflkheadbutt }
    - { model: skill-bflkkick }
    - { model: skill-limbblock }
    - { model: skill-press }
    - { model: skill-bflkpunch }
    - { model: skill-trip }
    - { model: mysticalability-sprt }
    - { model: skill-lang, name: "Language, Serf", system: { masteryLevelBase: 64 } }
    - { model: skill-musc, system: { masteryLevelBase: 18 } }
    - { model: skill-script, name: Script(Zerin), system: { masteryLevelBase: 80 } }
    - { model: skill-embl, system: { masteryLevelBase: 18 } }
    - { model: skill-hrld, system: { masteryLevelBase: 20 } }
    - { model: skill-law, system: { masteryLevelBase: 42 } }
    - { model: skill-math, system: { masteryLevelBase: 28 } }
    - { model: skill-pfmy, system: { masteryLevelBase: 26 } }
    - { model: miscgear-pence, system: { quantity: 261 } }
    - { model: containergear-pouchbuckram }
    - { model: armorgear-LLeg }
    - { model: armorgear-CShoe }
    - { model: armorgear-LTunic }
    - { model: weapongear-Kni }
    - { name: Halea, type: affiliation, system: { shortcode: halea, subType: divine } }
    - name: Halea
      type: skill
      system:
        subType: mystical
        shortcode: halea
        skillBaseFormula: sb(attr.wil, attr.rea)
        masteryLevelBase: 60
    - name: Baptism
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: halea
        assocAffiliationCode: halea
        levelBase: 2
    - name: Blessing
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: halea
        assocAffiliationCode: halea
        levelBase: 2
    - name: Commune
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: halea
        assocAffiliationCode: halea
        levelBase: 2
    - name: Liturgy
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: halea
        assocAffiliationCode: halea
        levelBase: 2
    - name: Marriage
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: halea
        assocAffiliationCode: halea
        levelBase: 2
    - name: Passage of the Soul
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: halea
        assocAffiliationCode: halea
        levelBase: 2
    - name: Halea's Apple
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: halea
        assocAffiliationCode: halea
        levelBase: 4
    - name: Cure Disease
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: halea
        assocAffiliationCode: halea
        levelBase: 3
    - name: Dulcia's Song
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: halea
        assocAffiliationCode: halea
        levelBase: 2
    - name: Kilna's Whip
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: halea
        assocAffiliationCode: halea
        levelBase: 3
    - name: Sardura's Vision
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: halea
        assocAffiliationCode: halea
        levelBase: 2
    - name: Ecstacy
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: halea
        assocAffiliationCode: halea
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
**Weight**: 298
**Size**: 10
**Comeliness**: Attractive
**Complexion**: Dark
**Hair Color**: Brown
**Eye Color**: Green
**Voice**: Pleasant

# Dossier {#dossier}

**Age**: 26
**Birthday**: 27 Azura 694
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: 5th child of 7
**Siblings**: fffMMFM
**Parentage**: Fostered
**Estrangement**: Unpopular
**Clanhead**: Father/Mother
**Medical**: Allergy

## Notes

Modifier to HairColor of -25 (from 65) {Complexion=Dark, Species=Human}

Modifier to EyeColor of +25 (from 26) {Complexion=Dark, Species=Human}

Modifier to StartingEquipment of +100 (from 31) {SocialClass=Serf}
