---
tags:
  - character
name:
  full: Worin of Kesten
  title: ""
  given: Worin
  clan: Kesten
  aliases: []
id: vLZajD1ySS1AoUHR
packFolder: fffunguilded
shortcode: worinofkesten
type: being
social:
  occupation: Servant
  class: freeman
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual:
    - peoni
data:
  icon: fff4173tok
  templatePriority: 1
  gender: male
  species: human
  age: 33
  born: 686/11/25
  height: 1.83
  weight: 77.11
  frame: medium
  appearance:
    eye_color: green
    hair_color: red
    skin_color: fair
    complexion: average
    extra_features: []
hm3:
  type: character
  attributes:
    str: 15
    sta: 13
    dex: 13
    agl: 17
    int: 6
    aur: 9
    wil: 12
    eye: 14
    hrg: 17
    sml: 13
    voi: 10
    cml: 10
    mor: 9
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 70, skillBase: { value: 15 } } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 70, skillBase: { value: 13 } } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 70, skillBase: { value: 16 } } }
    - { shortcode: riding, type: skill, system: { masteryLevel: 61, skillBase: { value: 14 } } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 51, skillBase: { value: 15 } } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 63, skillBase: { value: 14 } } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 66, skillBase: { value: 15 } } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 41, skillBase: { value: 9 } } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 18, skillBase: { value: 9 } } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 38, skillBase: { value: 9 } } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 42, skillBase: { value: 13 } } }
    - shortcode: language
      type: skill
      name: "Languages: Harnic"
      system:
        masteryLevel: 49
        skillBase:
          value: 9
    - { shortcode: peoni, type: skill, system: { masteryLevel: 10, skillBase: { value: 10 } } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 56, skillBase: { value: 14 } } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 76, skillBase: { value: 17 } } }
    - { shortcode: dodge, type: skill, system: { masteryLevel: 85, skillBase: { value: 17 } } }
    - { shortcode: club, type: skill, system: { masteryLevel: 63, skillBase: { value: 14 } } }
    - { shortcode: dagger, type: skill, system: { masteryLevel: 66, skillBase: { value: 13 } } }
    - { shortcode: whip, type: skill, system: { masteryLevel: 44, skillBase: { value: 13 } } }
    - shortcode: whip
      type: skill
      name: Horsewhip (Whip)
      system:
        shortcode: horsewhipwhip
        masteryLevel: 48
        skillBase:
          value: 13
    - { shortcode: cookery, type: skill, system: { masteryLevel: 57, skillBase: { value: 13 } } }
    - { shortcode: herblore, type: skill, system: { masteryLevel: 25, skillBase: { value: 11 } } }
    - { shortcode: hidework, type: skill, system: { masteryLevel: 42, skillBase: { value: 13 } } }
    - shortcode: animalcraft
      type: skill
      name: Horsecraft (Animalcraft)
      system:
        masteryLevel: 56
        skillBase:
          value: 13
    - { shortcode: survival, type: skill, system: { masteryLevel: 47, skillBase: { value: 11 } } }
    - shortcode: textilecraft
      type: skill
      system:
        masteryLevel: 50
        skillBase:
          value: 13
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: Dgr, type: weapongear }
    - { shortcode: Clb, type: weapongear }
    - { shortcode: Whp, type: weapongear }
    - { shortcode: beltpouchl3, type: containergear }
    - { shortcode: LTunic, type: armorgear }
    - { shortcode: LLeg, type: armorgear }
    - { shortcode: LtVest, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: pence, type: miscgear, system: { quantity: 15 } }
  system:
    sunsign: masara
    move: 17
sohl:
  kbcat: archetype
  items:
    - { model: attribute-str, system: { scoreBase: 15 } }
    - { model: attribute-end, system: { scoreBase: 13 } }
    - { model: attribute-dex, system: { scoreBase: 13 } }
    - { model: attribute-agl, system: { scoreBase: 17 } }
    - { model: attribute-per, system: { scoreBase: 17 } }
    - { model: attribute-snt, system: { scoreBase: 13 } }
    - { model: attribute-cml, system: { scoreBase: 10 } }
    - { model: attribute-aur, system: { scoreBase: 9 } }
    - { model: attribute-wil, system: { scoreBase: 12 } }
    - { model: attribute-rea, system: { scoreBase: 6 } }
    - { model: attribute-cre, system: { scoreBase: 18 } }
    - { model: attribute-emp, system: { scoreBase: 10 } }
    - { model: attribute-elo, system: { scoreBase: 12 } }
    - { model: attribute-mor, system: { scoreBase: 9 } }
    - { model: attribute-voi, system: { scoreBase: 10 } }
    - { model: skill-archery }
    - { model: skill-awar, system: { masteryLevelBase: 66 } }
    - { model: skill-chrm }
    - { model: skill-clmb, system: { masteryLevelBase: 70 } }
    - { model: skill-cmd }
    - { model: skill-cook, system: { masteryLevelBase: 57 } }
    - { model: skill-dnce }
    - { model: skill-dscr }
    - { model: skill-draw }
    - { model: skill-folklr }
    - { model: skill-guil }
    - { model: skill-init, system: { masteryLevelBase: 56 } }
    - { model: skill-shok }
    - { model: skill-intr, system: { masteryLevelBase: 41 } }
    - { model: skill-jump, system: { masteryLevelBase: 70 } }
    - { model: skill-melee, system: { masteryLevelBase: 55 } }
    - { model: skill-dge, system: { masteryLevelBase: 85 } }
    - { model: skill-pysn }
    - { model: skill-ridg, system: { masteryLevelBase: 61 } }
    - { model: skill-sing, system: { masteryLevelBase: 42 } }
    - { model: skill-stlth, system: { masteryLevelBase: 51 } }
    - { model: skill-srvl, system: { masteryLevelBase: 47 } }
    - { model: skill-spirit }
    - { model: skill-swim }
    - { model: skill-thtcs }
    - { model: skill-thro, system: { masteryLevelBase: 63 } }
    - { model: skill-bflkbite }
    - { model: skill-bflkgrab }
    - { model: skill-bflkheadbutt }
    - { model: skill-bflkkick }
    - { model: skill-limbblock }
    - { model: skill-press }
    - { model: skill-bflkpunch }
    - { model: skill-trip }
    - { model: mysticalability-sprt }
    - { model: skill-lang, name: "Languages: Harnic", system: { masteryLevelBase: 49 } }
    - { model: skill-herb, system: { masteryLevelBase: 25 } }
    - { model: skill-hide, system: { masteryLevelBase: 42 } }
    - model: skill-anmcft
      name: Horsecraft (Animalcraft)
      system:
        masteryLevelBase: 56
    - { model: skill-txtl, system: { masteryLevelBase: 50 } }
    - { model: containergear-pouchbuckram }
    - { model: weapongear-Dgr }
    - { model: weapongear-Clb }
    - { model: weapongear-Whp }
    - { model: containergear-beltpouchl3 }
    - { model: armorgear-LTunic }
    - { model: armorgear-LLeg }
    - { model: armorgear-LtVest }
    - { model: armorgear-LtShoe }
    - { model: miscgear-pence, system: { quantity: 15 } }
    - { name: Peoni, type: affiliation, system: { shortcode: peoni, subType: divine } }
    - name: Peoni
      type: skill
      system:
        subType: mystical
        shortcode: peoni
        skillBaseFormula: sb(attr.wil, attr.rea)
        masteryLevelBase: 10
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

![[fff4173|Worin of Kesten]]{float: top-left}

**Apparent Age**: Middle aged
**Culture**: Feudal
**Social Class**: Freeman (unguilded)
**Height**: 6 ft
**Frame**: Medium
**Weight**: 170 lb
**Appearance**: Average
**Hair Colour**: Red
**Eye Colour**: Green
**Voice**: Average
**Obvious Medical Traits**: None
**Apparent Occupation**: Groomsman
**Apparent Wealth**: Little
**Weapons**: Heavy dagger, club
**Armour**: Leather vest
**Companions**: Romont the teamster
**Other obvious features**: None

# Dossier {#dossier}

**Title**: FFF 417-3 Servant
**Birthday**: 25 Navek 686
**Appearance**: Age 33, height 6', medium frame, weight 170 lb, average appearance, fair complexion, red hair, green eyes
**Medical/Psyche**: Parasites (lice)
**Size**: 7
**Armor**: Simple cloth tunic and leggings, leather vest and shoes. Heavy dagger, club and whip.
**Other Equipment**: Belt pouch
**Valuables**: 15d in silver in a money pouch
**Notes**:

## Biography

Both Worin's mother and father are servants. When he was old enough, he began to help out, fetching water and firewood, cleaning and doing small tasks. As he grew, he was given more responsibility. For the last ten years he has been a full time groom. He is responsible for taking care of his master's horses, including mucking-out (cleaning) the stables and feeding, exercising and grooming the horses under the direction of the ostler. His ambition is to join the ostler's guild and oversee the stable on day. Unfortunately, he is not the brightest fellow.

Easily identified by his bright red hair, Worin is well known by the chamberlain and other servants. He is not very intelligent and easily tricked. Inevitably, when he discovers he has been duped, he will to lash out with his fists. Despite tending towards the "flailing arms and blind luck" school of unarmed combat, he is actually a good fighter. He usually loses only when he is outnumbered.

Deep down, Worin is a good person and wants to be liked. For those who discover this, such as Romont [FFF 419-1], he can be a fiercely loyal friend. Because of his loyalty, Worin is rarely alone, which can be helpful when his big mouth gets him into a bar fight. Older, wiser and more mature, Romont acts as a check on Worin's wilder urges. The Chamberlain has noted this and assigned the two to work together. They now spend most of their work and leisure time together. Worin has a limited vocabulary. When he runs out of words, he tends to use the phrase "I will fong you!" to express his frustration.

Worin spends most of his working day with the horses. He feeds them and grooms them in the morning; then he saddles or harnesses them for the day's activities. At each stop, he checks the horse's hoofs for stones and their legs for injuries. He leads them to water and prepares their feed. At the end of the day, he removes the saddles and harnesses, rubs them down and sets up the picket line for them to graze. Despite the care he lavishes on the horses, he only gets to ride when he is exercising a horse, otherwise he walks with the rest of the servants. In the evening, he also helps with camp security. Since he is equipped only with a dagger and club, his job is to patrol the camp and call for help if he spots intruders.

## Adventure Hooks

I Will Fong You. Worin has been gambling. He has made the mistake of winning too much and the local toughs decide to take their losses back.

Buying Supplies. As a horse specialist, Worin is sent out to purchase feed and tack for the horses. The PCs are buying something and he offers his opinion.

## Credits

This character is taken from "Friends, Foes, and Followers, Vol. 1" on Lythia.com (<https://www.lythia.com/game_aides/friends-foes-followers-volume-1/>), by Kerry Mould, with illustrations by Richard Luscheck and Juha Makkonen, and is "fanon", a derivative work of copyrighted material by Columbia Games Inc. and N. Robin Crossby.
