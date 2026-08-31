---
aliases:
  - Ondarn Khorild
  - 310-1 Harper
tags: []
name:
  full: Ondarn Khorild
  title: ""
  given: Ondarn
  clan: Khorild
  aliases: []
id: UHhx7MSVKR5Zszng
folder: dbDLVOgUtgVgjgnJ
shortcode: ondarnkhorild
img: images/fffv1/token/FFF_310-1_Harper.png
portrait: images/fffv1/FFF_310-1_Harper.jpg
tokenImg: images/fffv1/token/FFF_310-1_Harper.png
type: being
social:
  occupation: Harper
  class: freeman
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual:
    - halea
traits:
  species: human
  gender: male
  age: 33
  birthday: 686/3/8
  height:
    m: 1.57
  weight:
    kg: 53.07
  build:
    frame: light
  appearance:
    eye_color: grey
    hair_color: blonde
    skin_color: fair
    complexion: attractive
    extra_features:
      - Very long fingers
hm3:
  species: human
  sunsign: feniri
  attributes:
    str: 10
    sta: 13
    dex: 17
    agl: 13
    int: 17
    aur: 11
    wil: 9
    eye: 14
    hrg: 16
    sml: 12
    voi: 17
    cml: 14
    mor: 9
  move: 13
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 59, skillBase: { value: 13 } } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 63, skillBase: { value: 11 } } }
    - { shortcode: dancing, type: skill, system: { masteryLevel: 51, skillBase: { value: 14 } } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 49, skillBase: { value: 13 } } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 60, skillBase: { value: 14 } } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 63, skillBase: { value: 14 } } }
    - shortcode: musician
      type: skill
      name: Drum (Musician)
      system:
        masteryLevel: 65
        skillBase:
          value: 16
    - shortcode: musician
      type: skill
      name: Flute (Musician)
      system:
        masteryLevel: 70
        skillBase:
          value: 16
    - shortcode: musician
      type: skill
      name: Harp (Musician)
      system:
        masteryLevel: 85
        skillBase:
          value: 16
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 38, skillBase: { value: 12 } } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 70, skillBase: { value: 16 } } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 50, skillBase: { value: 14 } } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 92, skillBase: { value: 17 } } }
    - shortcode: language
      type: skill
      name: "Language: Harnic"
      system:
        masteryLevel: 74
        skillBase:
          value: 14
    - shortcode: script
      type: skill
      name: "Script: Lakise"
      system:
        masteryLevel: 86
        skillBase:
          value: 16
    - { shortcode: halea, type: skill, system: { masteryLevel: 16, skillBase: { value: 16 } } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 42, skillBase: { value: 10 } } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 40, skillBase: { value: 13 } } }
    - { shortcode: dodge, type: skill, system: { masteryLevel: 65, skillBase: { value: 13 } } }
    - { shortcode: folklore, type: skill, system: { masteryLevel: 78, skillBase: { value: 17 } } }
    - { shortcode: woodcraft, type: skill, system: { masteryLevel: 44, skillBase: { value: 14 } } }
    - { shortcode: SgTunic, type: armorgear }
    - { shortcode: SgLeg, type: armorgear }
    - { shortcode: LtCap, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: beltpouchl3, type: containergear }
    - { shortcode: pence, type: miscgear, system: { quantity: 67 } }
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
    - { shortcode: str, type: attribute, system: { scoreBase: 10 } }
    - { shortcode: end, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: dex, type: attribute, system: { scoreBase: 17 } }
    - { shortcode: agl, type: attribute, system: { scoreBase: 13 } }
    - { shortcode: per, type: attribute, system: { scoreBase: 16 } }
    - { shortcode: snt, type: attribute, system: { scoreBase: 12 } }
    - { shortcode: cml, type: attribute, system: { scoreBase: 14 } }
    - { shortcode: aur, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: wil, type: attribute, system: { scoreBase: 9 } }
    - { shortcode: rea, type: attribute, system: { scoreBase: 17 } }
    - { shortcode: cre, type: attribute, system: { scoreBase: 18 } }
    - { shortcode: emp, type: attribute, system: { scoreBase: 5 } }
    - { shortcode: elo, type: attribute, system: { scoreBase: 11 } }
    - { shortcode: mor, type: attribute, system: { scoreBase: 9 } }
    - { shortcode: voi, type: attribute, system: { scoreBase: 17 } }
    - { shortcode: archery, type: skill }
    - { shortcode: awar, type: skill, system: { masteryLevelBase: 63 } }
    - { shortcode: chrm, type: skill }
    - { shortcode: clmb, type: skill, system: { masteryLevelBase: 59 } }
    - { shortcode: cmd, type: skill }
    - { shortcode: cook, type: skill }
    - { shortcode: dnce, type: skill, system: { masteryLevelBase: 51 } }
    - { shortcode: dscr, type: skill }
    - { shortcode: draw, type: skill }
    - { shortcode: folklr, type: skill, system: { masteryLevelBase: 78 } }
    - { shortcode: guil, type: skill }
    - { shortcode: init, type: skill, system: { masteryLevelBase: 42 } }
    - { shortcode: shok, type: skill }
    - { shortcode: intr, type: skill, system: { masteryLevelBase: 38 } }
    - { shortcode: jump, type: skill }
    - { shortcode: melee, type: skill }
    - { shortcode: dge, type: skill, system: { masteryLevelBase: 65 } }
    - { shortcode: pysn, type: skill }
    - { shortcode: ridg, type: skill }
    - { shortcode: sing, type: skill, system: { masteryLevelBase: 92 } }
    - { shortcode: stlth, type: skill, system: { masteryLevelBase: 49 } }
    - { shortcode: srvl, type: skill }
    - { shortcode: spirit, type: skill }
    - { shortcode: swim, type: skill }
    - { shortcode: thtcs, type: skill }
    - { shortcode: thro, type: skill, system: { masteryLevelBase: 60 } }
    - { shortcode: bflkbite, type: skill }
    - { shortcode: bflkgrab, type: skill }
    - { shortcode: bflkheadbutt, type: skill }
    - { shortcode: bflkkick, type: skill }
    - { shortcode: limbblock, type: skill }
    - { shortcode: press, type: skill }
    - { shortcode: bflkpunch, type: skill }
    - { shortcode: trip, type: skill }
    - { shortcode: sprt, type: mysticalability }
    - { shortcode: musc, type: skill, name: Harp (Musician), system: { masteryLevelBase: 85 } }
    - { shortcode: lang, type: skill, name: "Language: Harnic", system: { masteryLevelBase: 74 } }
    - { shortcode: script, type: skill, name: "Script: Lakise", system: { masteryLevelBase: 86 } }
    - { shortcode: SgTunic, type: armorgear }
    - { shortcode: SgLeg, type: armorgear }
    - { shortcode: LtCap, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: beltpouchl3, type: containergear }
    - { shortcode: pence, type: miscgear, system: { quantity: 67 } }
    - { name: Halea, type: affiliation, system: { shortcode: halea, subType: divine } }
    - name: Halea
      type: skill
      system:
        subType: mystical
        shortcode: halea
        skillBaseFormula: sb(attr.wil, attr.rea)
        masteryLevelBase: 16
---

# Appearance {#appearance}

**Apparent Age**: Middle aged
**Culture**: Feudal
**Social Class**: Freeman (guilded)
**Height**: 5 ft 2 in
**Frame**: Light
**Weight**: 117 lb
**Appearance**: Attractive
**Hair Colour**: Blonde
**Eye Colour**: Grey
**Voice**: Excellent
**Obvious Medical Traits**: None
**Apparent Occupation**: Master Harper
**Apparent Wealth**: Moderate
**Weapons**: None
**Armour**: None
**Companions**: None
**Other obvious features**: Very long fingers

# Dossier {#dossier}

**Title**: FFF 310-1 Harper
**Birthday**: 8 Kelen 686
**Appearance**: Age 33, height 5' 2", light frame, weight 117 lb, attractive appearance, fair complexion, blonde hair, grey eyes
**Medical/Psyche**: None
**Size**: 5
**Armor**: Fine cloth tunic and leggings, leather hat and shoes
**Other Equipment**: Belt pouch
**Valuables**: 67d in silver
**Notes**:

## Biography

Ondarn's parents were harpers and travelled extensively. When he was born, they left him with his aunt and uncle in Tashal until he was old enough to travel. As a result, he has a distinctive Kaldoric accent he has never been able to shake. Blessed with a strong voice and an excellent memory, Ondarn had little trouble learning his parents' repertoire of songs and folk tales. He accompanies his songs on the harp, his most valuable possession.

After a five-year apprenticeship and a dozen years as a wandering bard, Ondarn was awarded the coveted title of Master Harper last year in Aleath, Kanday. His presentation of seven original works was well received by his assembled peers. He now intends to devote several years to roaming the isle in search of new tales. He dreams of one day visiting (or even attending) the "Silver Lute Palace of Harpers" in Elshavel, Evael.

A slight, not particularly strong man, Ondarn has a distinct aversion to violence. He shuns weapons and is the first out the door (pay or no pay) when a fight breaks out. That being the case, he is often completely ignored as a harmless fop by the rich and powerful men who hire him. They discuss the most remarkable subjects under his very nose. Although he claims "complete discretion is assured" he is not above selling a particularly juicy bit of i formation for the right price. Often resulting in him being only one step ahead of angry former employers.

Although definitely not effeminate, Ondarn is bisexual. A flirt and a tease, he has an infallible ability to pick out someone (of either sex) who is attracted to him. If he is the least bit attracted to them, he will find a time and place to seduce and bed them. This has resulted in many hasty departures with fathers, husbands and brothers in hot pursuit. As a result, Ondarn has had to continually change his identity and move, so he may be found in any city, town or village under any of a dozen pseudonyms.

## Adventure Hooks

Valuable Information: The PCs need information but can't get it themselves. A contact suggests Ondarn could do it. He does, but then wants more money or he will reveal the PCs to the noble they are spying on.

A Matter of Honour: Ondarn has taken the virginity of a prominent young man. His father is worried that if rumours of his son's "tastes" get out, his prospects for marriage will be done. He hires the PCs to silence Ondarn. The son will pay them more to help him escape.

An Old Legend: While in an inn, the PCs hear Ondarn sing about something they are looking for. He agrees to tell them more if they let him in on the job.

## Credits

This character is taken from "Friends, Foes, and Followers, Vol. 1" on Lythia.com (https://www.lythia.com/game_aides/friends-foes-followers-volume-1/), by Kerry Mould, with illustrations by Richard Luscheck and Juha Makkonen, and is "fanon", a derivative work of copyrighted material by Columbia Games Inc. and N. Robin Crossby.
