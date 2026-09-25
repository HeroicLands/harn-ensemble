---
tags:
  - character
name:
  full: Tolmey of Onparsin
  title: ""
  given: Tolmey
  clan: Onparsin
  aliases: []
id: 55wgiUH0JZ1KgJqA
packFolder: extrasclergy
shortcode: tolmeyofonparsin
type: being
social:
  occupation: Cleric/Naveh
  class: serf
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual:
    - naveh
data:
  templatePriority: 1
  gender: female
  species: humanflk
  age: 33
  born: 687/11/17
  height: 1.73
  weight: 69.4
  frame: medium
  appearance:
    eye_color: brown
    hair_color: brown
    skin_color: medium
    complexion: beautiful
    extra_features:
      - Left-Handed
hm3:
  type: character
  attributes:
    str: 8
    sta: 11
    dex: 10
    agl: 13
    int: 14
    aur: 11
    wil: 13
    eye: 15
    hrg: 9
    sml: 8
    voi: 14
    cml: 18
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
    - { shortcode: acrobatics, type: skill, system: { masteryLevel: 33 } }
    - { shortcode: climbing, type: skill, system: { masteryLevel: 40 } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 50 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 55 } }
    - { shortcode: legerdemain, type: skill, system: { masteryLevel: 44 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 55 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 44 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 40 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: language, type: skill, name: Language(Besha), system: { masteryLevel: 52 } }
    - shortcode: language
      type: skill
      name: Language, Serf
      system:
        shortcode: languageserf
        masteryLevel: 63
    - { shortcode: mentalconflict, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 90 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: script, type: skill, name: Script(Lakaise), system: { masteryLevel: 83 } }
    - shortcode: script
      type: skill
      name: Script(Neramic)
      system:
        shortcode: scriptneramic
        masteryLevel: 96
    - { shortcode: dagger, type: skill, system: { masteryLevel: 44 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 91 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 84 } }
    - { shortcode: drawing, type: skill, system: { masteryLevel: 26 } }
    - { shortcode: embalming, type: skill, system: { masteryLevel: 22 } }
    - { shortcode: folklore, type: skill, system: { masteryLevel: 42 } }
    - { shortcode: heraldry, type: skill, system: { masteryLevel: 24 } }
    - { shortcode: law, type: skill, system: { masteryLevel: 39 } }
    - { shortcode: lockcraft, type: skill, system: { masteryLevel: 24 } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: naveh, type: skill, system: { masteryLevel: 75 } }
    - { shortcode: navehbaptism, type: invocation }
    - { shortcode: navehblessing, type: invocation }
    - { shortcode: navehcommune, type: invocation }
    - { shortcode: navehliturgy, type: invocation }
    - { shortcode: navehmarriage, type: invocation }
    - { shortcode: navehpassageofthesoul, type: invocation }
    - { shortcode: navehscloak, type: invocation }
    - { shortcode: krasulaswhisper, type: invocation }
    - { shortcode: gekrishssong, type: invocation }
    - { shortcode: gytevshaspassage, type: invocation }
    - { shortcode: veshastale, type: invocation }
    - { shortcode: dekejisgift, type: invocation }
    - { shortcode: agilityofdekejis, type: invocation }
    - { shortcode: eyesofdekejis, type: invocation }
    - { shortcode: navehawe, type: invocation }
    - { shortcode: flashfromkamil, type: invocation }
    - { shortcode: pence, type: miscgear, system: { quantity: 477 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: LLeg, type: armorgear }
    - { shortcode: CShoe, type: armorgear }
    - { shortcode: LTunic, type: armorgear }
    - { shortcode: Kni, type: weapongear }
    - name: Lockpick kit
      type: miscgear
      data:
        icon: sohl-none-icon-miscgear
      system:
        value: 24
        weight: 1
  system:
    species: human
    sunsign: masara
    move: 16
sohl:
  kbcat: archetype
  items:
    - { model: sohl-sohl-attribute-str, system: { scoreBase: 8 } }
    - { model: sohl-sohl-attribute-end, system: { scoreBase: 11 } }
    - { model: sohl-sohl-attribute-dex, system: { scoreBase: 10 } }
    - { model: sohl-sohl-attribute-agl, system: { scoreBase: 13 } }
    - { model: sohl-sohl-attribute-per, system: { scoreBase: 10 } }
    - { model: sohl-sohl-attribute-snt, system: { scoreBase: 8 } }
    - { model: sohl-sohl-attribute-cml, system: { scoreBase: 18 } }
    - { model: sohl-sohl-attribute-aur, system: { scoreBase: 11 } }
    - { model: sohl-sohl-attribute-wil, system: { scoreBase: 13 } }
    - { model: sohl-sohl-attribute-rea, system: { scoreBase: 14 } }
    - { model: sohl-sohl-attribute-cre, system: { scoreBase: 15 } }
    - { model: sohl-sohl-attribute-emp, system: { scoreBase: 10 } }
    - { model: sohl-sohl-attribute-elo, system: { scoreBase: 14 } }
    - { model: sohl-sohl-attribute-mor, system: { scoreBase: 4 } }
    - { model: sohl-sohl-attribute-voi, system: { scoreBase: 14 } }
    - { model: sohl-sohl-skill-archery }
    - { model: sohl-sohl-skill-awar, system: { masteryLevelBase: 40 } }
    - { model: sohl-sohl-skill-chrm }
    - { model: sohl-sohl-skill-clmb, system: { masteryLevelBase: 40 } }
    - { model: sohl-sohl-skill-cmd }
    - { model: sohl-sohl-skill-cook }
    - { model: sohl-sohl-skill-dnce }
    - { model: sohl-sohl-skill-dscr }
    - { model: sohl-sohl-skill-draw, system: { masteryLevelBase: 26 } }
    - { model: sohl-sohl-skill-folklr, system: { masteryLevelBase: 42 } }
    - { model: sohl-sohl-skill-guil }
    - { model: sohl-sohl-skill-init, system: { masteryLevelBase: 91 } }
    - { model: sohl-sohl-skill-shok }
    - { model: sohl-sohl-skill-intr, system: { masteryLevelBase: 60 } }
    - { model: sohl-sohl-skill-jump, system: { masteryLevelBase: 55 } }
    - { model: sohl-sohl-skill-melee, system: { masteryLevelBase: 44 } }
    - { model: sohl-sohl-skill-dge }
    - { model: sohl-sohl-skill-pysn, system: { masteryLevelBase: 30 } }
    - { model: sohl-sohl-skill-ridg }
    - { model: sohl-sohl-skill-sing, system: { masteryLevelBase: 52 } }
    - { model: sohl-sohl-skill-stlth, system: { masteryLevelBase: 55 } }
    - { model: sohl-sohl-skill-srvl }
    - { model: sohl-sohl-skill-spirit }
    - { model: sohl-sohl-skill-swim }
    - { model: sohl-sohl-skill-thtcs }
    - { model: sohl-sohl-skill-thro, system: { masteryLevelBase: 44 } }
    - { model: sohl-sohl-skill-bflkbite }
    - { model: sohl-sohl-skill-bflkgrab }
    - { model: sohl-sohl-skill-bflkheadbutt }
    - { model: sohl-sohl-skill-bflkkick }
    - { model: sohl-sohl-skill-limbblock }
    - { model: sohl-sohl-skill-press }
    - { model: sohl-sohl-skill-bflkpunch }
    - { model: sohl-sohl-skill-trip }
    - { model: sohl-sohl-mysticalability-sprt }
    - { model: sohl-sohl-skill-acro, system: { masteryLevelBase: 33 } }
    - { model: sohl-sohl-skill-lgdm, system: { masteryLevelBase: 44 } }
    - { model: sohl-sohl-skill-lang, name: "Language, Serf", system: { masteryLevelBase: 63 } }
    - { model: sohl-sohl-skill-script, name: Script(Neramic), system: { masteryLevelBase: 96 } }
    - { model: sohl-sohl-skill-embl, system: { masteryLevelBase: 22 } }
    - { model: sohl-sohl-skill-hrld, system: { masteryLevelBase: 24 } }
    - { model: sohl-sohl-skill-law, system: { masteryLevelBase: 39 } }
    - { model: sohl-sohl-skill-lock, system: { masteryLevelBase: 24 } }
    - { model: sohl-sohl-miscgear-pence, system: { quantity: 477 } }
    - { model: sohl-sohl-containergear-pouchbuckram }
    - { model: sohl-sohl-armorgear-LLeg }
    - { model: sohl-sohl-armorgear-CShoe }
    - { model: sohl-sohl-armorgear-LTunic }
    - { model: sohl-sohl-weapongear-Kni }
    - { model: sohl-sohl-miscgear-lkpickkit }
    - { name: Naveh, type: affiliation, system: { shortcode: naveh, subType: divine } }
    - name: Naveh
      type: skill
      system:
        subType: mystical
        shortcode: naveh
        skillBaseFormula: sb(attr.wil, attr.rea)
        masteryLevelBase: 75
    - name: Baptism
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: naveh
        assocAffiliationCode: naveh
        levelBase: 2
    - name: Blessing
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: naveh
        assocAffiliationCode: naveh
        levelBase: 2
    - name: Commune
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: naveh
        assocAffiliationCode: naveh
        levelBase: 2
    - name: Liturgy
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: naveh
        assocAffiliationCode: naveh
        levelBase: 2
    - name: Marriage
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: naveh
        assocAffiliationCode: naveh
        levelBase: 2
    - name: Passage of the Soul
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: naveh
        assocAffiliationCode: naveh
        levelBase: 2
    - name: Naveh's Cloak
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: naveh
        assocAffiliationCode: naveh
        levelBase: 4
    - name: Krasula's Whisper
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: naveh
        assocAffiliationCode: naveh
        levelBase: 3
    - name: Gekrish's Song
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: naveh
        assocAffiliationCode: naveh
        levelBase: 2
    - name: Gytevsha's Passage
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: naveh
        assocAffiliationCode: naveh
        levelBase: 3
    - name: Vesha's Tale
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: naveh
        assocAffiliationCode: naveh
        levelBase: 2
    - name: Dekejis' Gift
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: naveh
        assocAffiliationCode: naveh
        levelBase: 2
    - name: Agility of Dekejis
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: naveh
        assocAffiliationCode: naveh
        levelBase: 3
    - name: Eyes of Dekejis
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: naveh
        assocAffiliationCode: naveh
        levelBase: 3
    - name: Awe
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: naveh
        assocAffiliationCode: naveh
        levelBase: 3
    - name: Flash from Kamil
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: naveh
        assocAffiliationCode: naveh
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

**Height**: 5' 8"
**Frame**: Medium
**Weight**: 153
**Size**: 6
**Comeliness**: Beautiful
**Complexion**: Medium
**Hair Color**: Brown
**Eye Color**: Brown
**Voice**: Pleasant

# Dossier {#dossier}

**Age**: 33
**Birthday**: 17 Navek 687
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: Eldest of 3
**Siblings**: FFF
**Parentage**: Fostered
**Estrangement**: Unpopular
**Clanhead**: Cousin
**Medical**: Left-Handed

## Notes

Modifier to Frame of -3 (from 13) {Sex=Female, Species=Human}

Modifier to AttributesAUR of +2 (from 9) {Sex=Female, Species=Human}

Eldest gets +5 on estrangement roll.

Left-Handed mod to Dexterity: +1

Modifier to StartingEquipment of +100 (from 29) {SocialClass=Serf}
