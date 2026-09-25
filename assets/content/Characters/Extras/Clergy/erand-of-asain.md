---
tags:
  - character
name:
  full: Erand of Asain
  title: ""
  given: Erand
  clan: Asain
  aliases: []
id: SgsoOSCF3UlbrkqO
packFolder: extrasclergy
shortcode: erandofasain
type: being
social:
  occupation: Cleric/Sarajin
  class: unguilded
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual:
    - sarajin
data:
  templatePriority: 1
  gender: male
  species: humanflk
  age: 30
  born: 690/2/22
  height: 1.83
  weight: 77.11
  frame: medium
  appearance:
    eye_color: green
    hair_color: brown
    skin_color: pale
    complexion: attractive
    extra_features:
      - Deformed/Missing Arm
hm3:
  type: character
  attributes:
    str: 15
    sta: 15
    dex: 8
    agl: 12
    int: 13
    aur: 3
    wil: 8
    eye: 13
    hrg: 13
    sml: 9
    voi: 13
    cml: 13
    mor: 16
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 65 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 55 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 44 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 32 } }
    - { shortcode: language, type: skill, name: Language(Ivinian), system: { masteryLevel: 55 } }
    - shortcode: language
      type: skill
      name: Language, Unguilded
      system:
        shortcode: languageunguilded
        masteryLevel: 61
    - { shortcode: mentalconflict, type: skill, system: { masteryLevel: 24 } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 39 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 44 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: script, type: skill, name: Script(Lakaise), system: { masteryLevel: 81 } }
    - shortcode: script
      type: skill
      name: Script(Runic)
      system:
        shortcode: scriptrunic
        masteryLevel: 81
    - { shortcode: axe, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: dagger, type: skill, system: { masteryLevel: 45 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 63 } }
    - { shortcode: shield, type: skill, system: { masteryLevel: 40 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 44 } }
    - { shortcode: drawing, type: skill, system: { masteryLevel: 22 } }
    - { shortcode: embalming, type: skill, system: { masteryLevel: 20 } }
    - { shortcode: folklore, type: skill, system: { masteryLevel: 39 } }
    - { shortcode: heraldry, type: skill, system: { masteryLevel: 18 } }
    - { shortcode: law, type: skill, system: { masteryLevel: 22 } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 22 } }
    - { shortcode: runecraft, type: skill, system: { masteryLevel: 18 } }
    - { shortcode: seamanship, type: skill, system: { masteryLevel: 33 } }
    - { shortcode: sarajin, type: skill, system: { masteryLevel: 98 } }
    - { shortcode: sarajinbaptism, type: invocation }
    - { shortcode: sarajinblessing, type: invocation }
    - { shortcode: sarajincommune, type: invocation }
    - { shortcode: sarajinliturgy, type: invocation }
    - { shortcode: sarajinmarriage, type: invocation }
    - { shortcode: sarajinpassageofthesoul, type: invocation }
    - { shortcode: talagaadshonor, type: invocation }
    - { shortcode: jarlakslope, type: invocation }
    - { shortcode: usnarlshug, type: invocation }
    - { shortcode: spiritofshalka, type: invocation }
    - { shortcode: sarajinawe, type: invocation }
    - { shortcode: prayertoelkyri, type: invocation }
    - { shortcode: sarajinendure, type: invocation }
    - { shortcode: sarajintongues, type: invocation }
    - { shortcode: suerljisdefense, type: invocation }
    - { shortcode: njehusdive, type: invocation }
    - { shortcode: pence, type: miscgear, system: { quantity: 239 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: SgLeg, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: SgTunic, type: armorgear }
    - { shortcode: Kni, type: weapongear }
    - { shortcode: RndSh, type: weapongear }
  system:
    species: human
    sunsign: aralius
    move: 12
sohl:
  kbcat: archetype
  items:
    - { model: sohl-sohl-attribute-str, system: { scoreBase: 15 } }
    - { model: sohl-sohl-attribute-end, system: { scoreBase: 15 } }
    - { model: sohl-sohl-attribute-dex, system: { scoreBase: 8 } }
    - { model: sohl-sohl-attribute-agl, system: { scoreBase: 12 } }
    - { model: sohl-sohl-attribute-per, system: { scoreBase: 12 } }
    - { model: sohl-sohl-attribute-snt, system: { scoreBase: 9 } }
    - { model: sohl-sohl-attribute-cml, system: { scoreBase: 13 } }
    - { model: sohl-sohl-attribute-aur, system: { scoreBase: 3 } }
    - { model: sohl-sohl-attribute-wil, system: { scoreBase: 8 } }
    - { model: sohl-sohl-attribute-rea, system: { scoreBase: 13 } }
    - { model: sohl-sohl-attribute-cre, system: { scoreBase: 14 } }
    - { model: sohl-sohl-attribute-emp, system: { scoreBase: 3 } }
    - { model: sohl-sohl-attribute-elo, system: { scoreBase: 9 } }
    - { model: sohl-sohl-attribute-mor, system: { scoreBase: 16 } }
    - { model: sohl-sohl-attribute-voi, system: { scoreBase: 13 } }
    - { model: sohl-sohl-skill-archery }
    - { model: sohl-sohl-skill-awar, system: { masteryLevelBase: 44 } }
    - { model: sohl-sohl-skill-chrm }
    - { model: sohl-sohl-skill-clmb, system: { masteryLevelBase: 52 } }
    - { model: sohl-sohl-skill-cmd }
    - { model: sohl-sohl-skill-cook }
    - { model: sohl-sohl-skill-dnce }
    - { model: sohl-sohl-skill-dscr }
    - { model: sohl-sohl-skill-draw, system: { masteryLevelBase: 22 } }
    - { model: sohl-sohl-skill-folklr, system: { masteryLevelBase: 39 } }
    - { model: sohl-sohl-skill-guil }
    - { model: sohl-sohl-skill-init, system: { masteryLevelBase: 63 } }
    - { model: sohl-sohl-skill-shok }
    - { model: sohl-sohl-skill-intr, system: { masteryLevelBase: 32 } }
    - { model: sohl-sohl-skill-jump, system: { masteryLevelBase: 65 } }
    - { model: sohl-sohl-skill-melee, system: { masteryLevelBase: 44 } }
    - { model: sohl-sohl-skill-dge }
    - { model: sohl-sohl-skill-pysn, system: { masteryLevelBase: 22 } }
    - { model: sohl-sohl-skill-ridg }
    - { model: sohl-sohl-skill-sing, system: { masteryLevelBase: 52 } }
    - { model: sohl-sohl-skill-stlth, system: { masteryLevelBase: 55 } }
    - { model: sohl-sohl-skill-srvl }
    - { model: sohl-sohl-skill-spirit }
    - { model: sohl-sohl-skill-swim }
    - { model: sohl-sohl-skill-thtcs }
    - { model: sohl-sohl-skill-thro, system: { masteryLevelBase: 48 } }
    - { model: sohl-sohl-skill-bflkbite }
    - { model: sohl-sohl-skill-bflkgrab }
    - { model: sohl-sohl-skill-bflkheadbutt }
    - { model: sohl-sohl-skill-bflkkick }
    - { model: sohl-sohl-skill-limbblock }
    - { model: sohl-sohl-skill-press }
    - { model: sohl-sohl-skill-bflkpunch }
    - { model: sohl-sohl-skill-trip }
    - { model: sohl-sohl-mysticalability-sprt }
    - model: sohl-sohl-skill-lang
      name: Language, Unguilded
      system:
        masteryLevelBase: 61
    - { model: sohl-sohl-skill-script, name: Script(Runic), system: { masteryLevelBase: 81 } }
    - { model: sohl-sohl-skill-embl, system: { masteryLevelBase: 20 } }
    - { model: sohl-sohl-skill-hrld, system: { masteryLevelBase: 18 } }
    - { model: sohl-sohl-skill-law, system: { masteryLevelBase: 22 } }
    - { model: sohl-sohl-mysticalability-runecft, system: { masteryLevelBase: 18 } }
    - { model: sohl-sohl-skill-smsh, system: { masteryLevelBase: 33 } }
    - { model: sohl-sohl-miscgear-pence, system: { quantity: 239 } }
    - { model: sohl-sohl-containergear-pouchbuckram }
    - { model: sohl-sohl-armorgear-SgLeg }
    - { model: sohl-sohl-armorgear-LtShoe }
    - { model: sohl-sohl-armorgear-SgTunic }
    - { model: sohl-sohl-weapongear-Kni }
    - { model: sohl-sohl-weapongear-RndSh }
    - { name: Sarajin, type: affiliation, system: { shortcode: sarajin, subType: divine } }
    - name: Sarajin
      type: skill
      system:
        subType: mystical
        shortcode: sarajin
        skillBaseFormula: sb(attr.wil, attr.rea)
        masteryLevelBase: 98
    - name: Baptism
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: sarajin
        assocAffiliationCode: sarajin
        levelBase: 2
    - name: Blessing
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: sarajin
        assocAffiliationCode: sarajin
        levelBase: 2
    - name: Commune
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: sarajin
        assocAffiliationCode: sarajin
        levelBase: 2
    - name: Liturgy
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: sarajin
        assocAffiliationCode: sarajin
        levelBase: 2
    - name: Marriage
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: sarajin
        assocAffiliationCode: sarajin
        levelBase: 2
    - name: Passage of the Soul
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: sarajin
        assocAffiliationCode: sarajin
        levelBase: 2
    - name: Talagaad's Honor
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: sarajin
        assocAffiliationCode: sarajin
        levelBase: 4
    - name: Jarlak's Lope
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: sarajin
        assocAffiliationCode: sarajin
        levelBase: 3
    - name: Usnarl's Hug
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: sarajin
        assocAffiliationCode: sarajin
        levelBase: 2
    - name: Spirit of Shalka
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: sarajin
        assocAffiliationCode: sarajin
        levelBase: 3
    - name: Awe
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: sarajin
        assocAffiliationCode: sarajin
        levelBase: 3
    - name: Prayer to Elkyri
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: sarajin
        assocAffiliationCode: sarajin
        levelBase: 2
    - name: Endure
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: sarajin
        assocAffiliationCode: sarajin
        levelBase: 3
    - name: Tongues
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: sarajin
        assocAffiliationCode: sarajin
        levelBase: 3
    - name: Suerlji's Defense
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: sarajin
        assocAffiliationCode: sarajin
        levelBase: 3
    - name: Njehu's Dive
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: sarajin
        assocAffiliationCode: sarajin
        levelBase: 4
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

**Height**: 6' 0"
**Frame**: Medium
**Weight**: 170
**Size**: 7
**Comeliness**: Attractive
**Complexion**: Pale
**Hair Color**: Brown
**Eye Color**: Green
**Voice**: Pleasant

# Dossier {#dossier}

**Age**: 30
**Birthday**: 22 Peonu 690
**Culture**: Feudal
**Social Class**: Unguilded
**Sibling Rank**: 3rd child of 8
**Siblings**: fFMffMmm
**Parentage**: Offspring
**Offspring**: Both parents alive and living together
**Estrangement**: Unpopular
**Clanhead**: Father/Mother
**Medical**: Deformed/Missing Arm

## Notes

Modifier to EyeColor of -25 (from 79) {Complexion=Pale, Species=Human}

Deformed/Missing Arm mod to Dexterity: -1

170lbs weight resulted in +1 strength mod.

Modifier to StartingEquipment of +200 (from 99) {SocialClass=Unguilded}
