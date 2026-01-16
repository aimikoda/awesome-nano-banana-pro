# Awesome Nano Banana Pro Prompts 🍌

A curated collection of Nano Banana Pro prompts with example outputs. Each prompt is grouped by theme and includes the full text for direct use. All created by [@aimikoda](https://x.com/aimikoda)

## Table of Contents

1. [Portraits & Identity](#portraits-identity)
2. [Style & Transformation](#style-transformation)
3. [Fashion & Product Imaging](#fashion-product-imaging)
4. [Advertising & Branding Concepts](#advertising-branding-concepts)
5. [Storytelling & Comics](#storytelling-comics)
6. [Cities & Architecture](#cities-architecture)
7. [Worlds & Dioramas](#worlds-dioramas)
8. [Games & Maps](#games-maps)
9. [Food & Culture](#food-culture)
10. [Holidays & Humor](#holidays-humor)

## 1. Portraits & Identity

### 1.1. Name Meaning Portrait

Turn Your Name’s Meaning Into an Iconic Portrait

**Prompt:**

```text
[NAME] = Your name
[SUBJECT] = The person shown in the uploaded reference image

Make a symbolic portrait reinterpretation for artistic editorial use, using a medium-close framing at eye level with a calm, centered composition, set within an abstract environment derived from the etymological and cultural meaning of [NAME], with [SUBJECT] placed as the sole figure in the midground, preserving the facial structure, facial proportions, expression, and overall likeness of [SUBJECT] exactly as in the reference image, allowing no alteration, stylization, or reinterpretation of the face under any circumstance, avoiding any reuse, reference, or derivation of clothing, accessories, or styling from the reference image, and instead designing a new outfit that supports the mood and symbolism of [NAME] without echoing the original wardrobe, translating the meaning of [NAME] into visual elements such as light behavior, color palette, atmosphere, natural forces, or metaphoric forms surrounding [SUBJECT], reflecting the name’s meaning through mood and symbolism rather than literal text, letters, or icons, using lighting direction, intensity, and color temperature to reinforce the emotional essence of [NAME], integrating symbolic elements so they feel physically and spatially connected to [SUBJECT] rather than decorative, keeping the background restrained and uncluttered with no readable text, and ensuring strong visual impact, coherence, and stylistic integrity throughout the composition.
```

####Example Outputs:

---

<img width="400" alt="Name Meaning Portrait" src="images/name-meaning-portrait-01.jpg" />
<img width="400" alt="Name Meaning Portrait" src="images/name-meaning-portrait-02.jpg" />
<img width="400" alt="Name Meaning Portrait" src="images/name-meaning-portrait-03.jpg" />
---
### 1.2. Fragmented Identity Prints

This prompt enforces a strict physical illusion: multiple instant-photo prints, one subject.
You can use it with your own photos. Change the variables as you want and generate.

**Prompt:**

```text
[SUBJECT] = the person shown in the uploaded reference image (identity anchor only)
[FRAME_COUNT] = 4
[SCENE_BG] = neutral textured studio wall

DO:
  Create [FRAME_COUNT] instant-photo prints in a tight scattered-but-coherent cluster.
  Reconstruct one continuous [SUBJECT] across all prints as fragments of one newly imagined single photograph.
  Use the uploaded reference image only as an identity anchor for [SUBJECT]’s face.
  Avoid copying the reference pose, clothing, framing, background, or lighting.
  Keep all fragments from the same frozen moment with identical camera viewpoint, scale, perspective, distance, and lens behavior.
  Set background to [SCENE_BG], empty and non-narrative, with clean studio separation.

  Define every print as real photographic paper.
  Render each print with a flat, opaque white border.
  Keep the photographic image strictly inside the inner image rectangle of each print.

  Assign one print as the dominant face frame and make it the primary visual anchor.
  Maintain seamless anatomical continuity at neighboring fragment edges so the cluster reads as one body.
  Maintain one consistent soft studio light direction, softness, color temperature, and shadow density across every print.

  Include exactly two hands total, both belonging to [SUBJECT].
  Place [SUBJECT]'s left hand originating fully inside its own print image area, then crossing the inner image edge and gripping the dominant face print.
  Place [SUBJECT]'s right hand originating fully inside a different print image area, then crossing the inner image edge and gripping a different print.
  Enforce wrist rule for both hands: keep wrist joint inside its origin print image area; allow only fingers, palm, and distal forearm to exit.
  Make both grasps unambiguous, physically plausible, and visibly compressing or overlapping print edges.
  Confine all other [SUBJECT] pixels strictly inside print image areas with zero leakage outside.

STYLE: high-resolution photographic realism, full color, natural skin tones, unified wardrobe palette, controlled surreal illusion with physical plausibility
CAMERA: single fixed viewpoint, consistent perspective across all prints, no angle changes, no lens changes
MOOD: clean studio, subtly uncanny

RULES:
  There are exactly [FRAME_COUNT] prints total.
  Print borders are opaque paper only.
  Borders contain no image data, no translucency, no cutouts, and no depth.
  No [SUBJECT] texture, silhouette, shadow, relief, embossing, or deformation may appear inside borders.
  All [SUBJECT] content must exist either inside image areas or as allowed hand crossings.

AVOID: [SUBJECT] pixels outside image areas except distal hand or forearm, wrist outside image areas, face outside image areas, hair outside image areas, torso or legs or clothing outside image areas, elbows or upper arms outside image areas, extra hands, extra arms, duplicated limbs, independent-photo framing, editorial detail shots, watermarks, signatures, text
```

## ####Example Outputs:

<img width="400" alt="Fragmented Identity Prints" src="images/fragmented-identity-prints-01.jpg" />
<img width="400" alt="Fragmented Identity Prints" src="images/fragmented-identity-prints-02.jpg" />
<img width="400" alt="Fragmented Identity Prints" src="images/fragmented-identity-prints-03.jpg" />
<img width="400" alt="Fragmented Identity Prints" src="images/fragmented-identity-prints-04.jpg" />
<img width="400" alt="Fragmented Identity Prints" src="images/fragmented-identity-prints-05.jpg" />
---
### 1.3. Zipped Lips Portrait

**Prompt:**

```text
prompt:
Make a photorealistic studio head portrait of the person from the provided reference photo, used strictly as identity anchor, captured at eye level with natural facial perspective, framed as a clean studio photograph with only the head and upper shoulders visible, set against a professional studio background with soft neutral tones, showing the subject centered and facing forward with a calm direct gaze, with a single hand gently closing a metal zipper over the lips, ensuring the lips and zipper merge naturally and convincingly without distortion, rendered with realistic skin texture and fine detail, lit with soft controlled studio lighting to create an elegant, cinematic, and emotionally restrained image.
```

## ###Example Output:

## <img width="400" alt="Zipped Lips Portrait" src="images/zipped-lips-portrait-01.jpg" />

### 1.4. Primal Archetype Portrait

Upload your picture and reveal its darker, ancient, or sacred forms.
**Prompt:**

```text
[SUBJECT] = use the uploaded reference image as the sole subject and identity anchor
[SHOT_TYPE] = head_portrait | bust_portrait | half_body | full_body
[UNIFIED_MOOD] = primal_dark | primal_sacred | primal_feral | primal_earthbound | refined_dark | refined_sacred | refined_mystic | refined_celestial | ascetic_ritual | shamanic_ancient | monolithic_icon | forgotten_deity
[COLOR_THEME] = obsidian_ash | bone_ochre | rust_clay | moss_stone | ivory_gold | charcoal_crimson | indigo_smoke | jade_sand | alabaster_silver | umber_shadow

Make a high-resolution portrait intended for artistic and editorial use.
Set the camera framing and crop strictly according to [SHOT_TYPE].
Use the uploaded reference image as the sole identity source.
Preserve facial identity and likeness so the subject is clearly recognizable as the same person.
Allow transformation only through paint, texture, adornment, lighting, and mood.
Use a neutral, unobtrusive background with subtle texture.
Render the subject as a symbolic, ceremonial figure shaped by [UNIFIED_MOOD].
Apply ritualistic markings, glyphs, and surface textures consistent with [UNIFIED_MOOD].
Maintain realistic human anatomy and natural proportions.
Use lighting and contrast to reinforce [UNIFIED_MOOD].
Apply [COLOR_THEME] consistently across the entire image.
Compose the frame so the subject remains the dominant focal presence.
Ensure the final image feels iconic, timeless, and cinematically powerful.
Avoid facial distortion, identity drift, modern fashion elements, sci-fi aesthetics, text overlays, watermarks.
```

## ####Example Outputs:

<img width="400" alt="Primal Archetype Portrait" src="images/primal-archetype-portrait-01.jpg" />
<img width="400" alt="Primal Archetype Portrait" src="images/primal-archetype-portrait-02.jpg" />
<img width="400" alt="Primal Archetype Portrait" src="images/primal-archetype-portrait-03.jpg" />
<img width="400" alt="Primal Archetype Portrait" src="images/primal-archetype-portrait-04.jpg" />
---
### 1.5. Anime Eyes Through Phone

**Prompt:**

Upload your photo or type the name of the celeb you want to use.

Set the mood and you’re ready to go. You can even change the phone.

This prompt keeps the real face untouched and lets emotion live only on the phone screen.

```text


You are a cinematic portrait composer that generates a single-frame photorealistic plus anime-hybrid image driven by contrast between reality and emotion.

VARIABLES
SUBJECT: person from provided reference image
DEVICE: iPhone 15
MOOD: sad | happy | angry | calm | mysterious | hopeful | cute | kawaii | dreamy | melancholic | confident | anxious

INSTRUCTIONS

1. Generate one high-resolution cinematic portrait image.

2. Use SUBJECT exactly as seen in the reference image.
   - Do not alter real facial features, proportions, skin texture, realism, or the original facial expression.
   - The real face expression must remain identical to the reference and must not be influenced by MOOD.

3. Frame a single real human centered in the composition.
   - Show head and upper torso only.
   - Render the real person fully realistic with natural skin detail and physically accurate lighting.

4. Phone interaction and positioning:
   - Subject extends one arm toward the camera holding DEVICE with a single hand.
   - Hold the phone in landscape orientation.
   - Preserve the original DEVICE screen aspect ratio.
   - Align the phone parallel to the camera lens.
   - Position the phone directly in front of the face.
   - The phone physically covers only the eye region.
   - All other facial regions remain visible and fully realistic.

5. Phone screen logic and masking:
   - Treat the phone screen as a transparent window revealing an alternate rendering of the same full-scale head.
   - The phone screen must display ONLY the anime-rendered eyes.
   - Do NOT render nose, mouth, cheeks, forehead, jaw, or any other facial features on the phone screen.
   - Any facial area outside the eye region must be absent, cropped out, or visually empty on the screen.
   - The anime eyes must align perfectly in position and scale with the real eyes behind the phone.
   - Set anime eye expression strictly according to MOOD.
   - Do not complete or imply the rest of the anime face on the screen.

6. Lighting:
   - Use the phone screen as the primary light source.
   - Adjust screen light intensity and color temperature according to MOOD.
   - Cast soft screen light onto the hand and the visible facial edges only.
   - Do not alter the real face expression or proportions through lighting.

7. Background:
   - Transform the background into a realistic environment that emotionally matches MOOD.
   - Use color palette, lighting, atmosphere, and depth of field to support the selected mood.

8. Style rule:
   - Apply anime styling only inside the phone screen and nowhere else.

OUTPUT
Produce exactly one final image following these instructions.
```

## ####Example Outputs:

<img width="400" alt="Anime Eyes Through Phone" src="images/anime-eyes-through-phone-01.jpg" />
<img width="400" alt="Anime Eyes Through Phone" src="images/anime-eyes-through-phone-02.jpg" />
<img width="400" alt="Anime Eyes Through Phone" src="images/anime-eyes-through-phone-03.jpg" />
<img width="400" alt="Anime Eyes Through Phone" src="images/anime-eyes-through-phone-04.jpg" />
---
### 1.6. Mixed Media Portrait Trio

Change the variables and you are ready to go!
(Subject, Accesories and Painting)
**Prompt:**

```text
VARIABLES
LEFT_SUBJECT = Dua Lipa
CENTER_SUBJECT = Anya Taylor-Joy
RIGHT_SUBJECT = Sydney Sweeney

LEFT_ACCESSORY = a purple hair bow positioned on the head
CENTER_ACCESSORY = bunny ears attached to a simple headband with a small decorative accent
RIGHT_ACCESSORY = a straw hat

PAINTING_REFERENCE = "The Starry Night by Vincent van Gogh"

Set a mixed-media image where illustrated elements are fully hand-painted and human subjects are rendered as ultra-realistic photographic figures.

Use PAINTING_REFERENCE directly as the exact visual source for all painted elements, faithfully preserving its original composition, color palette, brushwork, movement, and spatial rhythm.

Use a lightly textured off-white painted surface as the background behind the human subjects, with subtle paper grain visible and no additional figurative or decorative elements.

Ensure the area directly behind the women remains clean, bright, and predominantly white-toned, clearly separated from the painterly foreground layer.

Create a painterly foreground layer taken directly from PAINTING_REFERENCE that partially obscures the lower frame, functioning as a visual barrier rather than a literal object.

Place three adult women aligned horizontally, positioned behind this painted foreground layer.

Use real, photorealistic depictions of LEFT_SUBJECT as the left subject, CENTER_SUBJECT as the center subject, and RIGHT_SUBJECT as the right subject.

Render all three women with true-to-life skin texture, natural pores, realistic hair strands, photographic sharpness, and accurate light interaction.

Apply realistic studio lighting to the women with soft shadows and natural highlights that intentionally do not match the lighting logic of the painted elements.

Maintain a clear physical and stylistic separation where the painted elements exist as an illustrated layer and the women exist in photographic space, without interaction or texture blending.

Place the hands of each subject resting on an unseen real surface behind the painted foreground layer, with the painted forms partially obscuring the wrists.

Ensure the hands and arms appear fully photographic and unaffected by painterly texture or brushstrokes.

Apply LEFT_ACCESSORY to the left subject.
Apply CENTER_ACCESSORY to the center subject.
Apply RIGHT_ACCESSORY to the right subject.

Align all three heads upright with minimal tilt and gazes directed straight toward the viewer.

Show only the upper portions of the bodies above the painted foreground layer while the lower bodies remain fully hidden.

Keep all illustrated elements strictly painterly with visible brush texture and no photorealistic detail.

Ensure a strong visual contrast where the women appear clearly photographic and separate from the illustrated environment.

Avoid any artist signature, watermark, embedded text, or illustrative stylization on the human subjects.
```

## ####Example Outputs:

---

<img width="400" alt="Mixed Media Portrait Trio" src="images/mixed-media-portrait-trio-01.jpg" />
<img width="400" alt="Mixed Media Portrait Trio" src="images/mixed-media-portrait-trio-02.jpg" />
---
### 1.7. Orange Cat Eye Cover

**Prompt:**

```text
Make a single-frame professional studio photo output; set high resolution.

Use the person from the uploaded reference photo as the subject; preserve facial structure, body proportions, and realism.

Set a controlled studio environment dominated by a monochromatic orange tonal world.

Place the subject facing directly toward the camera, wearing a fully orange outfit that integrates naturally with the environment while keeping skin tones neutral and realistic.

Place exactly one realistic orange cat positioned directly above and centered over the subject’s head, fully inside the frame with comfortable headroom.

Show the cat’s two front paws symmetrically reaching forward to fully cover both of the subject’s eyes while the cat’s head and gaze are oriented directly toward the camera, as if posing knowingly for the portrait.

Use a clean studio portrait framing with centered composition, straight-on camera axis, and frozen moment timing.

Use soft professional studio lighting that bathes the environment, clothing, and cat in orange tones while keeping the human subject’s skin tones natural and unaltered.

Preserve photographic realism, believable scale between cat and human, clear eye coverage with paws, and intentional eye contact from the cat toward the camera.

Do not add a second cat, do not angle the cat’s head away from the camera, do not crop or cut off any part of the cat or paws, do not cover only one eye, do not alter the subject’s identity, do not stylize the human figure, do not apply orange color grading to skin, do not add text, logos, UI elements, surreal distortion, cartoon style, or fantasy aesthetics.
```

####Example Output:

---

<img width="400" alt="Orange Cat Eye Cover" src="images/orange-cat-eye-cover-01.jpg" />

---

## 2. Style & Transformation

### 2.1. Make Anything Bloom

Make Anything Bloom 🪻🌺

Transform any image by letting flowers, grass, and greenery bloom naturally from realistic surfaces, while preserving the original scene and composition.

_HOW TO USE — IMAGE PROMPT_

1. Upload an image
   You can upload anything.
   Examples:

- a keyboard
- a camera
- a perfume bottle
- a shoe
- a person
- an animal
- a random object

2. Paste the prompt
   Use the visual prompt that adds natural vegetation to the uploaded image.

3. What the prompt does

- Keeps the original camera angle, position, and background.
- Adds grass, flowers, and moss naturally.
- Plants grow only from realistic gaps, seams, and surfaces.
- The subject stays fully recognizable.

4. Example use cases

- Product photo → flowers growing between details.
- Portrait → subtle plants emerging from clothing seams or accessories.
- Object → nature gently reclaiming it.
- Minimal scene → organic, cinematic enhancement.

5. Run and adjust if needed
   If the result feels too strong or too subtle, regenerate.
   The prompt is designed to work safely without breaking composition.

Tip:
Best results come from clean, well-lit images with clear subject separation.

**Prompt:**

```text
VARIABLES
[MAIN_SUBJECT] = uploaded reference image
[PLANT_DENSITY] = balanced
[COLOR_PALETTE] = natural greens with subtle pastel accents
[EDIT_MODE] = additive_only | hybrid | reconstruct
[BACKGROUND] = unchanged | background description
[SEASON_HINT] = spring | summer | autumn | winter | early spring | late summer

INSTRUCTIONS
Make a high-resolution photorealistic image intended for premium conceptual visualization.
Use [MAIN_SUBJECT] as the exact visual identity and base form.
If [EDIT_MODE] is additive_only, preserve the original camera angle, framing, subject position, scale, orientation, background, lighting, and shadows exactly as provided.
If [EDIT_MODE] is hybrid, preserve camera angle, framing, and subject position while allowing subtle background enhancement consistent with [BACKGROUND].
If [EDIT_MODE] is reconstruct, rebuild the scene while preserving subject identity and integrate the subject into [BACKGROUND].
Integrate natural vegetation into the subject as a miniature living ecosystem.
Control overall vegetation presence according to [PLANT_DENSITY].

Allow vegetation to emerge only from physically plausible gaps, seams, recesses, joints, or surface transitions.
Guide vegetation growth, color nuance, density balance, and subtle environmental cues according to [SEASON_HINT].
Ensure seasonal influence affects plants only, not the subject’s material or structure.

Ensure growth follows real-world physical logic and surface geometry.
Prevent vegetation from obscuring primary functional areas, faces, logos, or focal features.
Render plants with believable scale, natural variation, and physical grounding.

Apply [COLOR_PALETTE] as a base while allowing seasonal tonal shifts.
Maintain visual clarity and subject dominance.
Ensure the final image feels iconic, timeless, and cinematically powerful.
Avoid text, labels, watermarks, excessive fantasy elements.
```

####Example Outputs:

---

<img width="400" alt="Make Anything Bloom" src="images/make-anything-bloom-01.jpg" />
<img width="400" alt="Make Anything Bloom" src="images/make-anything-bloom-02.jpg" />
<img width="400" alt="Make Anything Bloom" src="images/make-anything-bloom-03.jpg" />
<img width="400" alt="Make Anything Bloom" src="images/make-anything-bloom-04.jpg" />
---
### 2.2. Frozen Moment in Ice

People, animals, iconic characters or products.
All frozen inside a single moment, trapped in ice ❄️

Just change the variables and generate.
Frozen moments. Cinematic stillness.

**Prompt:**

```text
[SUBJECT_DETAIL] = a Mountain Dew can with bold logo fully visible, partially opened, aggressive aluminum deformation
[ICE_FORM] = massive crystal-clear ice block
[STATE_OF_SUBJECT] = frozen mid-explosion with extreme energy
[BACKGROUND] = pure matte black studio void

INSTRUCTIONS
Make a hyper-realistic cinematic image intended for premium advertising visualization.
Frame the scene so the entire [ICE_FORM] is fully visible from top to bottom with clear separation from the background.
Place a single [ICE_FORM] centered in the frame with balanced negative space on all sides.
Render the ice as a dense translucent frozen mass with layered internal depth, sharp pressure fractures, and suspended ice shards.
Encapsulate [SUBJECT_DETAIL] completely inside the ice, fully enclosed and not touching the outer surface.
Freeze the can in [STATE_OF_SUBJECT], with frozen liquid splash arcs and carbonation bursts suspended in place.
Preserve explosive motion through bent aluminum edges and outward force geometry.
Apply strong optical refraction and magnification effects through the ice over the logo and liquid.
Use an intense cold color palette dominated by electric greens, deep blues, and icy whites.
Set the background to [BACKGROUND] with no visible texture or horizon.
Light the scene with high-contrast directional lighting to define the ice silhouette and illuminate the subject within.
Ensure the final image feels iconic, timeless, and cinematically powerful.
Avoid text overlays, watermarks, unbranded cans, cartoon style, low-detail rendering.
```

####Example Outputs:

---

<img width="400" alt="Frozen Moment in Ice" src="images/frozen-moment-in-ice-01.jpg" />
<img width="400" alt="Frozen Moment in Ice" src="images/frozen-moment-in-ice-02.jpg" />
<img width="400" alt="Frozen Moment in Ice" src="images/frozen-moment-in-ice-03.jpg" />
---

### 2.3. Cartoon Accessory Add-On

**Prompt:**

```text
Add cartoon-style objects and accessories to the uploaded image
```

####Example Outputs:

---

<img width="400" alt="Cartoon Accessory Add-On" src="images/cartoon-accessory-add-on-01.jpg" />
<img width="400" alt="Cartoon Accessory Add-On" src="images/cartoon-accessory-add-on-02.jpg" />
<img width="400" alt="Cartoon Accessory Add-On" src="images/cartoon-accessory-add-on-03.jpg" />
---
## 3. Fashion & Product Imaging

### 3.1. Life-Size Collectible Box

Turn yourself into a life-size collectible. 💖

**Prompt:**

```text
[SUBJECT] = the person shown in the uploaded reference image
[BOX_TYPE] = Barbie Box

Make a high-resolution lifestyle photograph in 9:16 aspect ratio.
Use a full-frame camera at eye level with a perfectly straight-on, front-facing perspective.
Set the scene in a studio environment designed to match the color palette and mood of [BOX_TYPE].
Place the life-size immersive [BOX_TYPE] centered in the studio, facing the camera directly with no rotation or angle.
Define the box structure, color palette, surface materials, branding style, and decorative elements according to the visual language of [BOX_TYPE].
Include the box’s own characteristic packaging texts and branding details, consistent with [BOX_TYPE].
Include visible text reading “LIMITED EDITION” integrated naturally into the box design.
Position [SUBJECT] centered inside the box as the sole focal figure.
Preserve realistic human body proportions, scale, and anatomy for [SUBJECT] with no stylization or exaggeration.
Show a playful, confident full-body pose that fits naturally within the spatial limits of the box.
Keep the torso open, posture expressive, and facial expression joyful and relaxed.
Style wardrobe, accessories, and footwear to harmonize with the aesthetic implied by [BOX_TYPE].
Use soft, even studio lighting consistent with the box tone and materials.
Maintain clean edges, clear separation between subject, box, and background.
Ensure the final image feels iconic, immersive, and immediately recognizable as a themed display box concept.
```

####Example Outputs:

---

<img width="400" alt="Life-Size Collectible Box" src="images/life-size-collectible-box-01.jpg" />
<img width="400" alt="Life-Size Collectible Box" src="images/life-size-collectible-box-02.jpg" />
<img width="400" alt="Life-Size Collectible Box" src="images/life-size-collectible-box-03.jpg" />
<img width="400" alt="Life-Size Collectible Box" src="images/life-size-collectible-box-04.jpg" />
---
### 3.2. Flat-Lay Outfit Builder

Generates anatomy-free flat-lay outfit visuals with precise control over style, layout, surface, and accessories.

_HOW TO USE PARAMETERS_

OUTFIT_STYLE
Either use the outfit from the reference image, or select a single predefined style.
If you’re using a reference image, "use the outfit from the reference image."
You may also try a different style.

COMPOSITION_SCHEME
Choose only one layout scheme.
This controls spatial arrangement.

SURFACE
Choose only one surface.
You may switch to a different surface, but use only one per prompt.

ACCESSORY_MODE
Choose only one mode.
Decide whether accessories are part of the outfit, decorative elements, or fully excluded.
Do not mix modes in the same prompt.

**Prompt:**

```text
[OUTFIT_STYLE] = Use the outfit from the reference image | casual utilitarian womenswear | casual mens streetwear
[COMPOSITION_SCHEME] = seated-inspired angular layout | standing-inspired vertical layout | walking-inspired offset layout | dynamic diagonal layout | balance-inspired asymmetric layout | editorial flat-lay grid break | sculptural negative-space layout | yoga-inspired angular balance layout | athletic-inspired directional layout
[SURFACE] = clean matte studio backdrop | soft neutral paper surface | cool tone matte backdrop
[ACCESSORY_MODE] = outfit_integrated | decorative | none

Make a high resolution flat lay fashion image for editorial and catalog use.
Use a strict top down camera angle with a natural 50mm equivalent perspective and perfectly parallel framing.
Set the scene on [SURFACE] with no visible texture seams or edge shadows.

Show only clothing items and approved accessories placed on the surface.
Do not depict or imply any human body, body parts, limbs, skin, joints, or anatomy.
Do not include legs, hips, feet, knees, or any biological structure.

Arrange garments as a flat, uninhabited composition following [COMPOSITION_SCHEME].
Interpret [COMPOSITION_SCHEME] purely as a geometric layout logic, never as a body configuration.
Use angles, spacing, and directional alignment only to suggest balance and posture.

Keep every garment fully flat with zero internal volume.
Force all bottom garments including pants or leggings to remain collapsed, empty, and tension-free.
Do not stretch, contour, wrap, or compress fabric.
Represent bends only through sharp planar folds and angular breaks.
Prohibit smooth curves, rounded forms, seated volume, or body-fit deformation.

Allow folds and wrinkles only as gravity-driven surface creases.
Ensure clothing reads strictly as laid fabric, not worn, inhabited, or shaped by a body.

Select garments and accessories based on [OUTFIT_STYLE].
If [ACCESSORY_MODE] is outfit_integrated, include only functionally worn items.
If [ACCESSORY_MODE] is decorative, allow accessories as independent flat objects.
If [ACCESSORY_MODE] is none, exclude all accessories entirely.

Use soft diffused daylight from above with gentle shadows directly beneath each item.
Keep spacing balanced with visible negative space around the composition.
Avoid mannequins, models, body silhouettes, stuffing, air filled shapes, extra items, text, logos, or branding.
Ensure clarity, accurate fabric texture, and a calm contemporary aesthetic.
```

####Example Outputs:

---

<img width="400" alt="Flat-Lay Outfit Builder" src="images/flat-lay-outfit-builder-01.jpg" />
<img width="400" alt="Flat-Lay Outfit Builder" src="images/flat-lay-outfit-builder-02.jpg" />
<img width="400" alt="Flat-Lay Outfit Builder" src="images/flat-lay-outfit-builder-03.jpg" />
<img width="400" alt="Flat-Lay Outfit Builder" src="images/flat-lay-outfit-builder-04.jpg" />
---

### 3.3. ClearShell Product Transformation

**Prompt:**

```text
Make a photorealistic product image using the uploaded reference product.
Keep the original shape, scale, and details exactly the same.
Replace the outer casing with fully transparent clear plastic.
Render a glossy surface with slight reflections and subtle refraction.
Keep all branding and internal details clearly visible.
Avoid color tinting, distortion, or opaque materials.
Ensure clarity and professional finish.
```

####Example Outputs:

---

<img width="400" alt="ClearShell Product Transformation" src="images/clearshell-product-transformation-01.jpg" />
<img width="400" alt="ClearShell Product Transformation" src="images/clearshell-product-transformation-02.jpg" />
<img width="400" alt="ClearShell Product Transformation" src="images/clearshell-product-transformation-03.jpg" />
<img width="400" alt="ClearShell Product Transformation" src="images/clearshell-product-transformation-04.jpg" />
---
## 4. Advertising & Branding Concepts

### 4.1. Impact Splash Ad

Example Variables:

SUBJECT:

- A human adult figure
- A Nike performance sneaker
- A rubber duck
- A cluster of granola pieces
- A sausage

LIQUID TYPE:

- Water
- Milk
- Oat milk
- Muddy water
- Sand (fluidized, fine-grain)
- Black ink
- Mustard

IMPACT DISTANCE:

- Zero
- Very close
- Medium
- Far

SPLASH INTENSITY:

- Low
- Medium
- High
- Extreme

COLOR THEME:

- Clean whites and soft creamy tones
- Cool blues and aqua highlights
- Natural sand tones with warm beige
- High-contrast black and white
- Brand color palette from reference image

  **Prompt:**

```text
You are an intelligent commercial image composition model.

SUBJECT: A human adult figure
LIQUID TYPE: Water
IMPACT DISTANCE: Very Close
SPLASH INTENSITY: Mediumx
COLOR THEME: Cool blues and aqua highlights

TEXT: {TEXT}
TEXT_LANG: {TEXT_LANG}
Examples:
- TEXT empty, TEXT_LANG English
- TEXT "JUST DO IT", TEXT_LANG English

Create a single cohesive commercial-grade visual scene where:

- The subject is suspended mid-air as if falling, fully visible in its entirety, with no cropping or occlusion.
- The liquid exists below the subject at the moment of impact or just before impact, depending on the specified impact distance.
- The interaction between subject and liquid feels physically believable, visually expressive, and clearly readable.
- Composition, framing, perspective, and lighting are intelligently determined by the model to maximize clarity, balance, and visual impact.
- The color theme unifies the subject, liquid, lighting, and background into a coherent, brand-ready palette.

TEXT & TYPOGRAPHY RULES:
- If TEXT is empty, generate a very short headline and one very short subline in TEXT_LANG.
- Automatically select a clean, modern, advertisement-appropriate font optimized for readability.
- Adjust font size, weight, spacing, and placement intelligently using negative space.
- Typography must enhance the composition without dominating it.

STYLE & QUALITY RULES:
- Premium commercial advertising quality.
- Hyper-realistic materials and fluid or granular simulation.
- Studio-grade lighting with a high-speed photography aesthetic.
- Crisp focus on the subject and primary splash or impact details.
- The scene must feel intentional, polished, and campaign-ready.
- No fantasy elements.
- No illustration or painterly effects.
- No UI elements, watermarks, or logos unless naturally part of the subject.

The final image should feel like a hero visual from a global advertising campaign.
```

####Example Outputs:

---

<img width="400" alt="Impact Splash Ad" src="images/impact-splash-ad-01.jpg" />
<img width="400" alt="Impact Splash Ad" src="images/impact-splash-ad-02.jpg" />
<img width="400" alt="Impact Splash Ad" src="images/impact-splash-ad-03.jpg" />
<img width="400" alt="Impact Splash Ad" src="images/impact-splash-ad-04.jpg" />
<img width="400" alt="Impact Splash Ad" src="images/impact-splash-ad-05.jpg" />
---
### 4.2. Mood Poster Generator

This prompt is designed for anyone who wants to create a strong visual from a single emotion.

It is mood-driven.
Style-flexible.
You can write the text yourself, or let it generate one for you.
Photography, illustration, anime, 3D, or minimal graphics.
Everything stays coherent within the same clean structure.

**Prompt:**

```text
You are a minimalist visual mood composer that generates a single-frame artistic image driven primarily by emotional tone.

VARIABLES
MOOD: <string describing the emotional atmosphere, e.g. calm, melancholic, hopeful, ironic, tense, dreamy>
STYLE: <rendering language + medium, e.g. anime illustration, hand-drawn sketch, cinematic photography, 3D render, abstract painting>
TEXT: <optional short sentence or phrase; if empty, generates a fitting line inspired by MOOD>
BACKGROUND: <optional background hint; if empty, generates a background that best expresses MOOD>

INSTRUCTIONS
1. Create a single square composition with a clean, uncluttered layout.
2. Treat MOOD as the core driver for all visual and textual decisions.
3. Interpret STYLE as a combined rendering language and medium, and apply it consistently across the entire image.
4. Ensure style, typography, and background do not visually or conceptually conflict with each other.
5. Design the background based on MOOD and STYLE.
   - If BACKGROUND is provided, interpret it loosely and artistically.
   - If BACKGROUND is empty, invent a background that emotionally reinforces MOOD.
6. Use a restrained color palette that clearly reflects MOOD, avoiding visual noise.
7. Place the text thoughtfully within the composition.
   - If TEXT is provided, use it exactly as given.
   - If TEXT is empty, write a short poetic line that matches MOOD.
8. Apply a very subtle text shadow to improve readability without becoming a focal point.
9. Ensure typography feels integrated with the image, subtle and balanced.
10. Maintain generous negative space and visual breathing room.
11. Avoid narrative complexity, characters, or multiple scenes.
12. The final result should feel like a quiet mood poster or artistic still.
13. Do not add any extra elements beyond what serves MOOD directly.
14. Ensure the image reads as intentional, calm, and aesthetically cohesive.
```

####Example Outputs:

---

<img width="400" alt="Mood Poster Generator" src="images/mood-poster-generator-01.jpg" />
<img width="400" alt="Mood Poster Generator" src="images/mood-poster-generator-02.jpg" />
---
### 4.3. Chat Bubble Cinematic

Turn quotes, jokes, ideas, or iconic moments into cinematic visuals.
Use it for ads, memes, concepts, or just pure imagination.

Example Variables:
(You can ask ChatGPT or Gemini to fill these variables for your concept)

VARIABLES
OUTPUT_TYPE: commercial illustration
BACKGROUND_STYLE: light beige background filled edge-to-edge with faint, repeating line-art icons related to chaos, comedy, masks, cards, weapons, and pop-culture symbols, very low contrast
COLOR_THEME: light neutral base with bold character-driven accents
PRIMARY_TEXT_COLOR: near-black
SECONDARY_TEXT_COLOR: light gray for timestamps and UI details

ACCENT_COLORS:

- Joker: glossy acid green with a subtle yellow tint
- Deadpool: glossy deep red with a slight dark gradient

BUBBLE_COUNT: 4
BUBBLE_LAYOUT: stacked vertically with generous spacing
BUBBLE_STYLE:

- SHAPE: oversized horizontal rounded chat bubbles
- FINISH: glossy with soft inner gradient
- SHADOW: subtle realistic drop shadow
- OUTLINE: none

TYPOGRAPHY:

- FONT_FAMILY: modern sans-serif
- WEIGHT: medium
- ALIGNMENT: left

TIMESTAMP_TEXT: 9:41 PM
MESSAGE_ICON_STYLE: small blue double-check icons placed before timestamp

PARTICIPANTS:

- NAME: Joker
  DESCRIPTION: Joker from Batman universe
  SIDE: left
- NAME: Deadpool
  DESCRIPTION: Deadpool from Marvel universe
  SIDE: right

MESSAGES:

1. SENDER: Joker
   TEXT: “Why so serious?”
   REACTION: unsettling calm smile, head slightly tilted, confident stillness
2. SENDER: Deadpool
   TEXT: “Trademark issue, buddy.”
   REACTION: playful sarcasm, casual posture, slight shoulder shrug as if breaking the fourth wall
3. SENDER: Joker
   TEXT: “You’re ruining the mood.”
   REACTION: irritated smirk, narrowed eyes, subtle forward lean
4. SENDER: Deadpool
   TEXT: “That’s literally my job.”
   REACTION: smug confidence, relaxed stance, humorous body language

CHARACTER_STYLE: fully photorealistic humans and costumes, realistic materials and textures, natural lighting response, no illustration, no anime
LIGHTING_STYLE: soft cinematic studio lighting with controlled contrast and gentle highlights
COLOR_MOOD: chaotic, humorous, cinematic, self-aware
SIGNATURE: Aimi Koda, bottom-right in muted gray

**Prompt:**

```text
SYSTEM ROLE
You are a visual scene composer and commercial illustration designer that generates clean, high-resolution advertising-ready illustrations with photorealistic human characters and glossy chat-bubble UI elements.

VARIABLES
OUTPUT_TYPE: <commercial illustration | digital banner | landing page visual>
BACKGROUND_STYLE: <background color, texture, pattern description>
COLOR_THEME: <light | dark | brand-aligned>
PRIMARY_TEXT_COLOR: <color>
SECONDARY_TEXT_COLOR: <color>
ACCENT_COLORS:
- PARTICIPANT_A: <color>
- PARTICIPANT_B: <color>
- OPTIONAL_PARTICIPANT_C: <color>

BUBBLE_COUNT: <number>
BUBBLE_LAYOUT: <stacked vertically | stacked horizontally | custom flow>
BUBBLE_STYLE:
- SHAPE: <rounded | pill | custom>
- FINISH: <glossy | matte | glassy>
- SHADOW: <subtle | soft | none>
- OUTLINE: <none | thin | custom>

TYPOGRAPHY:
- FONT_FAMILY: <modern sans-serif | custom>
- WEIGHT: <regular | medium | bold>
- ALIGNMENT: <left | center | right>

TIMESTAMP_TEXT: <string or empty>
MESSAGE_ICON_STYLE: <description or none>

PARTICIPANTS:
- NAME: <string>
  DESCRIPTION: <photorealistic human description including age range, skin tone, hair, clothing>
  SIDE: <left | right>
- NAME: <string>
  DESCRIPTION: <photorealistic human description including age range, skin tone, hair, clothing>
  SIDE: <left | right>
- OPTIONAL:
  NAME: <string>
  DESCRIPTION: <photorealistic human description>
  SIDE: <left | right>

MESSAGES:
1. SENDER: <participant name>
   TEXT: <string>
   REACTION: <facial expression, gaze direction, body posture>
2. SENDER: <participant name>
   TEXT: <string>
   REACTION: <facial expression, gaze direction, body posture>
3. SENDER: <participant name>
   TEXT: <string>
   REACTION: <facial expression, gaze direction, body posture>
<add more messages as needed>

CHARACTER_STYLE: <photorealistic humans, natural skin texture, realistic proportions, realistic hair and fabric detail, no illustration, no anime>
LIGHTING_STYLE: <soft studio | cinematic | flat UI-style>
COLOR_MOOD: <friendly | premium | playful | serious | cinematic>
SIGNATURE: <optional text and placement>

INSTRUCTIONS
1. Create a high-resolution illustration suitable for advertising and digital use.
2. Do not include phone frames, device borders, or app mockup chrome unless explicitly specified.
3. Fill the entire background using BACKGROUND_STYLE with controlled contrast.
4. Place chat bubbles according to BUBBLE_LAYOUT with clear reading order.
5. Assign a distinct bubble color to each participant using ACCENT_COLORS.
6. Render chat bubbles using BUBBLE_STYLE consistently.
7. Insert message TEXT using TYPOGRAPHY with high readability.
8. Display sender NAME subtly near each bubble using SECONDARY_TEXT_COLOR.
9. Place TIMESTAMP_TEXT and MESSAGE_ICON_STYLE consistently where applicable.
10. Position each bubble on the SIDE assigned to its sender.
11. Render each participant adjacent only to their own messages.
12. Apply the specified REACTION accurately for each message.
13. Never mix message ownership, participant sides, or bubble colors.
14. Maintain strict character identity and visual consistency throughout.
15. Keep composition clean, balanced, and free of visual noise.
16. Use PRIMARY_TEXT_COLOR for dialogue and SECONDARY_TEXT_COLOR for metadata.
17. Place SIGNATURE subtly without distracting from the main content.
18. Ensure the final image feels realistic, premium, and commercially polished.
```

####Example Outputs:

---

<img width="400" alt="Chat Bubble Cinematic" src="images/chat-bubble-cinematic-01.jpg" />
<img width="400" alt="Chat Bubble Cinematic" src="images/chat-bubble-cinematic-02.jpg" />
<img width="400" alt="Chat Bubble Cinematic" src="images/chat-bubble-cinematic-03.jpg" />
<img width="400" alt="Chat Bubble Cinematic" src="images/chat-bubble-cinematic-04.jpg" />
<img width="400" alt="Chat Bubble Cinematic" src="images/chat-bubble-cinematic-05.jpg" />
---
### 4.4. Sand-Form Beauty Ad

**Prompt:**

```text
Create a high-resolution vertical advertising-style studio photo featuring {PERSON_NAME}.
Show a single adult female subject in a chest-up portrait that fills the frame with no cropping of the head, hair, neck, shoulders, or upper chest.
Pose the subject in a polished campaign stance: shoulders slightly angled, head subtly tilted, chin gently lifted, and the gaze locked straight into camera.
Include one visible hand near the collarbone or jawline in an elegant beauty-ad pose, with the hand also made of sand.
Keep a confident, premium, composed expression suitable for a luxury ad shoot.
Make ONLY the eyes organic and lifelike, with realistic irises, pupils, sclera, wet reflections, and natural catchlights.
Construct the entire rest of the visible subject from countless sand grains with crisp granular micro-detail and believable shadowing between grains.
Make everything except the eyes sand: forehead, temples, eyebrows, eyelashes, eyelids and under-eye area, nose, cheeks, lips, teeth, tongue and inside of the mouth, chin and jawline, ears, hair, neck, shoulders, collarbones, upper chest, the visible hand and fingers, plus any visible clothing, accessories, and jewelry.
Use a high-end studio lighting setup with softbox key, subtle fill, and clean rim lights to carve the form while preserving sharp sand texture and gentle sparkle.
Set a minimal seamless studio background with a smooth gradient and no environment details.
Add restrained premium post-processing: high dynamic range, crisp micro-contrast, and soft bloom only on the brightest sand glints.
Avoid text, logos, borders, extra objects, and any additional people.
```

####Example Outputs:

---

<img width="400" alt="Sand-Form Beauty Ad" src="images/sand-form-beauty-ad-01.jpg" />
<img width="400" alt="Sand-Form Beauty Ad" src="images/sand-form-beauty-ad-02.jpg" />
---
### 4.5. Ingredient Breakdown Reveal

Upload Any Product. See What’s Really Inside!
Turn Any Food Photo Into a Truthful Ingredient Breakdown with Nano Banana Pro
Turn any food image into a clear, eye-opening ingredient breakdown.
**Prompt:**

```text
Using the provided reference image, create a bold, startup-style social media visual that highlights the overwhelming presence of harmful ingredients in the product.

The composition shows a side-by-side comparison of the same product:

On the left:
The product exactly as shown in the reference image, intact, clean, and familiar in appearance.

On the right:
The same product at the exact same size, proportions, and perspective, but sliced or cut open to expose its internal composition as clearly separated horizontal layers.

The internal layers should visually emphasize imbalance:
the largest and most dominant layers represent harmful or low-quality ingredients, while beneficial ingredients appear noticeably smaller and minimal.

Use thin, sharp arrows pointing to each layer.
Next to each arrow, include clear, modern text labels stating:

the ingredient name

the approximate percentage or proportion

Design the visual hierarchy so that high-sugar and high-fat components feel visually heavy and excessive, creating an immediate sense of concern and contrast.

Design style:
Minimal, high-contrast startup infographic aesthetic.
Clean sans-serif typography, bold spacing, strong contrast.
Crisp studio lighting, exaggerated layer separation for clarity and impact.
Flat or softly graded background inspired by modern tech and startup visuals.
```

####Example Outputs:

---

<img width="400" alt="Ingredient Breakdown Reveal" src="images/ingredient-breakdown-reveal-01.jpg" />
<img width="400" alt="Ingredient Breakdown Reveal" src="images/ingredient-breakdown-reveal-02.jpg" />
<img width="400" alt="Ingredient Breakdown Reveal" src="images/ingredient-breakdown-reveal-03.jpg" />
<img width="400" alt="Ingredient Breakdown Reveal" src="images/ingredient-breakdown-reveal-04.jpg" />
---
## 5. Movie Making & Storytelling & Comics

### 5.1. Parallel Storyboard Grid

Branching one image into three different storylines, with selectable time spans and director style (e.g. Nolan, Tarantino) guiding each sequence.
**Prompt:**

```text


Here’s the prompt. Feel free to use it and adjust it to your needs.

[DIRECTOR] = director name
[DURATION] = a brief continuous moment | a short uninterrupted action | a compact continuous span | a fleeting but coherent moment | a single sustained cinematic beat | a continuous dramatic beat | a tightly paced cinematic moment | a short real-time progression | a continuous real-time fragment | a seamless micro-sequence | a moment long enough for a clear change to occur | a short span where an action clearly evolves

Create a 3x3 cinematic storyboard grid from the uploaded reference image.
Arrange the grid as three vertical columns and three horizontal rows.
Treat each column as a separate, self-contained storyline.
Within each column, the three panels form a top-to-bottom narrative sequence.
Ensure all nine panels fit on a single continuous canvas with no borders, gaps, or spacing.
Ensure every panel is a true 16:9 frame with no cropping or distortion.

Use the uploaded reference image strictly as an environment, lighting, character, material, and atmosphere reference.
Do not recreate, replicate, or directly derive any panel composition from the reference image.
Do not treat the reference image as the starting frame for any panel or storyline.

Preserve the original visual medium, realism level, color science, texture fidelity, sharpness, grain, and noise characteristics of the reference image.
Keep lighting conditions, weather, materials, and atmosphere continuous across all panels.

Use cinematic camera language in the exact visual style of [DIRECTOR].

For each column, assign clear narrative roles:
- Top panel establishes an initial situation that is compositionally distinct from the reference image.
- Middle panel introduces a clear change through action, interaction, or reaction.
- Bottom panel presents an irreversible outcome that cannot visually or narratively resemble the top panel.

Ensure each panel within a column represents a later moment than the one above it, unfolding within [DURATION].
Ensure camera framing and distance progress forward within each column and never return to an earlier composition.
Ensure visible story progression comes from changes in action, behavior, orientation, or spatial relationship, not from zoom alone.
Ensure the final panel in each column does not visually echo or reset to the first panel.

Ensure the three columns depict three different storylines, decisions, or outcomes, not variations of the same sequence.
Prevent visual or narrative repetition across columns.

Lock the identity of all primary subjects and environments to remain consistent with the reference image.
Preserve all visually distinctive attributes that contribute to the identity of any subject, object, or environment when they appear in the reference image.

Maintain strict continuity in materials, surfaces, clothing, accessories, and physical details.
Avoid text, captions, labels, UI elements, frames, borders, graphic overlays, and including [DIRECTOR] as a character.
Ensure the final image reads clearly as three parallel cinematic micro-stories and feels iconic, coherent, and cinematically powerful
```

####Example Outputs:

---

<img width="400" alt="Parallel Storyboard Grid" src="images/parallel-storyboard-grid-01.jpg" />
<img width="400" alt="Parallel Storyboard Grid" src="images/parallel-storyboard-grid-02.jpg" />
<img width="400" alt="Parallel Storyboard Grid" src="images/parallel-storyboard-grid-03.jpg" />
<img width="400" alt="Parallel Storyboard Grid" src="images/parallel-storyboard-grid-04.jpg" />
---
### 5.2. Bullet Dodge Kitchen

**Prompt:**

```text
[THROWER] = an adult woman in casual everyday clothing
[DODGING_SUBJECT] = a young person wearing a loose sweatshirt and jeans
[LOCATION] = wooden cabinets and a centered back window
[THROWN_OBJECT] = a light blue rubber clog mid-air
[ASPECT_RATIO] = 9:16

Make a photorealistic lifestyle photograph in [ASPECT_RATIO] aspect ratio.
Use a wide-angle lens positioned slightly behind the dodging subject at waist height with deep depth of field.
Set the scene in a narrow home kitchen with [KITCHEN_DESIGN].

Place [THROWN_OBJECT] in the immediate foreground closest to the camera, frozen mid-air.
Place [DODGING_SUBJECT] behind the object, viewed strictly from behind, occupying the lower half of the frame.
Place [THROWER] in the midground behind [DODGING_SUBJECT], facing the camera.

Show [DODGING_SUBJECT] performing an extreme backward Neo-style bullet dodge using only natural human motion, with the spine deeply arched so the torso folds far enough back to fully expose the face upside down, the head hanging inverted with facial features and eyes clearly visible to the camera, and the neck fully extended with the chin lifted backward to maximize facial visibility.
Show [THROWER] stepping forward with one arm fully extended in a throwing motion.
Include [THROWN_OBJECT] positioned slightly past the head and upper torso plane of [DODGING_SUBJECT] to indicate it has narrowly missed and already passed.

Use soft natural daylight from the rear window with subtle indoor ambient fill.
Ensure the image feels candid, humorous, and convincingly real.
Avoid visual effects, motion trails, stylization, cinematic grading, or slow-motion cues.
```

####Example Outputs:

---

<img width="400" alt="Bullet Dodge Kitchen" src="images/bullet-dodge-kitchen-01.jpg" />
<img width="400" alt="Bullet Dodge Kitchen" src="images/bullet-dodge-kitchen-02.jpg" />
<img width="400" alt="Bullet Dodge Kitchen" src="images/bullet-dodge-kitchen-03.jpg" />
---
### 5.3. Parametric Comic Scenes

**Prompt:**

variable-based system for auto generating clean, consistent comic scenes.

There are already many social media accounts built entirely around this kind of content.
With this prompt, you could easily create one of your own too, and the stories write themselves.

Example Prompt Variables:

TOPIC: Laughing at a small personal failure that feels tragic for exactly five seconds
CHARACTERS: A single person sitting alone at a kitchen table, messy hair, neutral face slowly shifting to dry amusement
GRID_SIZE: 4
GRID_LAYOUT: 2x2
COLOR_PALETTE: Muted grays and dull greens with a single harsh white light source
STYLE: Hand-drawn minimalist illustration with rough pencil lines and slightly imperfect proportions
MOOD: Darkly humorous, ironic
NARRATION_MODE: visual+text
SIGNATURE: Aimi Koda, bottom-right

TOPIC: Losing track of time while working late at night
CHARACTERS: A single person at a desk with a laptop, wearing casual home clothes, slightly hunched posture, focused but tired expression
GRID_SIZE: 4
GRID_LAYOUT: 2x2
COLOR_PALETTE: Dark midnight blues and soft purples with warm screen light highlights
STYLE: Hand-drawn cinematic illustration with subtle grain and soft brush texture
MOOD: Quietly exhausted, introspective
NARRATION_MODE: visual+text
SIGNATURE: Aimi Koda, bottom-right

If you want to use a product as a Character you can define it in the Characters Variable.

Example;

CHARACTERS: The product shown in the uploaded reference image, treated as the main character

```text
SYSTEM ROLE
You are a visual scene composer and caption writer that generates a clean, coherent comic-style illustration based on parametric inputs.

VARIABLES
TOPIC: <string describing the core idea or situation of the comic>
CHARACTERS: <optional string describing character(s); if empty, invent suitable character(s) based on TOPIC>
GRID_SIZE: <number of panels, e.g. 4, 6, 9>
GRID_LAYOUT: <layout format, e.g. 2x2, 3x2, 3x3>
COLOR_PALETTE: <brief description of dominant colors and mood, e.g. muted pastels, monochrome, warm tones>
STYLE: <illustration style, e.g. hand-drawn, painterly, storybook, flat graphic>
MOOD: <overall emotional tone, e.g. happy, calm, sad, nostalgic, ironic>
NARRATION_MODE: <visual | visual+text | text-led>
SIGNATURE: <optional signature text and placement, e.g. "Aimi Koda, bottom-right"; if empty, do not add a signature>

INSTRUCTIONS
1. Create a square comic-style illustration using GRID_LAYOUT with equal spacing and clean borders.
2. Interpret TOPIC as the narrative anchor and invent a short story that unfolds across the panels.
3. If CHARACTERS is provided, strictly follow it; otherwise invent character(s) that naturally fit TOPIC.
4. Keep character identity, proportions, and visual traits consistent across all panels.
5. Decide the camera progression yourself in a way that best serves the invented story.
6. Decide the background behavior yourself, keeping visual coherence across panels.
7. Decide the lighting approach yourself, choosing what best fits MOOD and STYLE.
8. Decide the overall detail level yourself and keep it consistent across all panels.
9. Apply COLOR_PALETTE consistently, allowing subtle variation when narratively useful.
10. Let MOOD influence composition, pacing, expressions, and visual rhythm across panels.
11. Follow NARRATION_MODE strictly:
    - If visual: include no text inside panels and rely entirely on imagery.
    - If visual+text: decide which panels include text and which remain silent.
    - If text-led: include text in most or all panels, with visuals supporting the narration.
12. When text is used, place it inside panels in a comic-appropriate way, such as captions, thought text, or minimal dialogue.
13. Write short, natural, story-driven text that advances the narrative implied by TOPIC and MOOD.
14. Do not force text into every panel unless NARRATION_MODE is text-led.
15. Ensure the sequence forms a clear beginning, middle, and end through visuals, text, or both.
16. If SIGNATURE is provided, add it exactly as specified, placed discreetly without distracting from the illustration.
17. Avoid unnecessary elements and visual noise.
18. Ensure the final output reads clearly as a single cohesive multi-panel comic illustration.
```

####Example Outputs:

---

<img width="400" alt="Parametric Comic Scenes" src="images/parametric-comic-scenes-01.jpg" />
<img width="400" alt="Parametric Comic Scenes" src="images/parametric-comic-scenes-02.jpg" />
<img width="400" alt="Parametric Comic Scenes" src="images/parametric-comic-scenes-03.jpg" />
<img width="400" alt="Parametric Comic Scenes" src="images/parametric-comic-scenes-04.jpg" />
---
## 6. Cities & Architecture

### 6.1. Stacked Megacity Sculpture

Generate 3D miniature city dioramas in the form of a sculptural, stacked megacity, using Nano Banana Pro.

**Prompt:**

```text
[CITY] = city name here

Make a stylized 3D miniature city diarama illustration.
Use an isometric camera angle with slight perspective and ensure full subject visibility.
Set the scene as a sculptural city stack inspired by [CITY].
Define spatial behavior as vertical accumulation with compact upward growth.
Show only the most iconic and culturally recognizable elements of [CITY].
Construct the city as a single fused megastructure rather than separate buildings.
Arrange architectural volumes, towers, and pathways into a balanced vertical silhouette.
Wrap the structure with a central ascending route that visually leads upward.
Place the entire city mass on a solid ground base.
Render the city name at the base as monumental stone-like letterforms.
Render each letter as a massive architectural block integrated into the structure.
Treat letters as load-bearing foundations with stairs, windows, doors, and passages.
Allow buildings, pathways, and landmarks to physically rise from the tops of the letters.
Integrate the ground base visually with the letter structures as one cohesive mass.
Render architecture with region-appropriate forms, proportions, and material logic.
Integrate natural elements seamlessly into the structure as part of the mass.
Use smooth shaded materials with a soft illustrated texture and no outlines.
Apply warm daylight with soft global illumination and gentle ambient shadows.
Keep the background minimal with a bright sky gradient and soft clouds.
Ensure visual impact, coherence, and stylistic integrity.
```

####Example Outputs:

---

<img width="400" alt="Stacked Megacity Sculpture" src="images/stacked-megacity-sculpture-01.jpg" />
<img width="400" alt="Stacked Megacity Sculpture" src="images/stacked-megacity-sculpture-02.jpg" />
<img width="400" alt="Stacked Megacity Sculpture" src="images/stacked-megacity-sculpture-03.jpg" />
<img width="400" alt="Stacked Megacity Sculpture" src="images/stacked-megacity-sculpture-04.jpg" />
---
### 6.2. Landmark Re-Designed

What If Landmarks Had a Different Designer?
**Prompt:**

```text
[LANDMARK] = Eiffel Tower
[DESIGNER] = Leonardo da Vinci

A hyper-realistic photograph of [LANDMARK] designed by [DESIGNER].
Capture it at its real-world site and structurally plausible architecture consistent with [DESIGNER]’s design language.
Render it as an authentic modern on-location photo with realistic lighting, atmosphere, perspective, and surrounding context, indistinguishable from a real photograph.
```

####Example Outputs:

---

<img width="400" alt="Landmark Re-Designed" src="images/landmark-re-designed-01.jpg" />
<img width="400" alt="Landmark Re-Designed" src="images/landmark-re-designed-02.jpg" />
---
### 6.3. City Tree Monument

This prompt imagines world cities as living monuments carved into colossal ancient trees.
Just change the variables and you’re ready to go.
**Prompt:**

```text
VARIABLES
[CITY]: Name of the city
[TIME_OF_DAY]: sunrise | early morning | midday | afternoon | golden hour | sunset | blue hour | night
[COLORED]: true | false

Create a hyper-detailed artistic visualization of a colossal ancient tree whose massive trunk is entirely transformed through wood carving into the city of [CITY].

Show the tree as a single monumental sculpture, fully visible from roots to crown, centered in the frame.

Carve [CITY] directly into the living wood, allowing its well-known historical landmarks, skyline, domes, towers, bridges, and districts to emerge organically from the trunk and roots without explicit labeling.

Integrate architectural forms at multiple scales and depths, with rooftops, arches, stairways, and silhouettes following the natural flow of the wood grain.

Use the roots to form coastlines, hills, and ancient neighborhoods, while upper branches subtly echo the city’s iconic skyline shapes.

Extend one major branch from the upper-left side of the tree and organically shape this branch and its offshoots into the readable text “[CITY]”, as if the lettering grew naturally as part of the tree rather than being carved or arranged.

Ensure the branch-formed lettering is continuous with the tree structure, sharing the same bark texture, growth rings, knots, and imperfections, with slight moss and lichen growth reinforcing its living origin.

Cover parts of the tree with organic greenery, including mold-like moss growth, soft lichen patches, hanging moss, and small clusters of mushrooms growing naturally from cracks, roots, and shaded carved areas.

Ensure the greenery feels damp, aged, and biologically plausible, integrated into the carving without obscuring key architectural details.

If [COLORED] is true, apply subtle natural pigments and mineral-based coloration selectively to architectural details, roofs, domes, and city accents while preserving the dominance of natural wood tones.

If [COLORED] is false, render the entire sculpture in natural wood tones only, without added pigments or color accents.

Light the scene according to [TIME_OF_DAY], using appropriate atmospheric depth to emphasize scale, texture, and craftsmanship.

Apply a realistic wood-carving aesthetic with visible chisel marks, aged textures, natural cracks, and selectively polished surfaces consistent with authentic craftsmanship.

Keep the composition cinematic, timeless, and awe-inspiring, with no modern elements, no people, and no fantasy creatures.

Render in ultra-high resolution with sharp focus, realistic shadows, and museum-grade artistic quality.
```

####Example Outputs:

---

<img width="400" alt="City Tree Monument" src="images/city-tree-monument-01.jpg" />
<img width="400" alt="City Tree Monument" src="images/city-tree-monument-02.jpg" />
<img width="400" alt="City Tree Monument" src="images/city-tree-monument-03.jpg" />
<img width="400" alt="City Tree Monument" src="images/city-tree-monument-04.jpg" />
---
## 7. Worlds & Dioramas

### 7.1. Flag Myth Diorama

This Is What Flag Meanings Look Like
This prompt turns flag meanings into 3D Dioramas

**Prompt:**

```text
[COUNTRY] = Country Name

Create a 3D miniature diorama scene that visualizes a poetic and culturally rooted interpretation of the flag of [COUNTRY].
Present the scene as a handcrafted symbolic world frozen in a single legendary moment.
Build the entire diorama on a base shaped precisely like the geographic outline of [COUNTRY], as if the land itself forms the foundation.
Do not rely on official or textbook meanings.
Assume the meaning emerges from cultural memory, myth, and traditional storytelling instincts of the nation.
Translate flag colors and symbols into a single connected physical event occurring across the land-shaped base, such as reflection, sacrifice, witnessing, or remembrance.
Let cultural perception shape the internal logic of the scene rather than literal symbolism.
Avoid turning symbols into decorative objects.
Integrate the actual flag of [COUNTRY] subtly into the scene, such as engraved, carved, or embossed along the edge or surface of the land-shaped base.
Include the country name as visible text, cleanly typeset and physically embedded into the base like a museum label or cartographic marking.
Avoid floating text or billboard-style typography.
Render the diorama with clear scale, depth, and sculptural detail, viewed slightly from above to clearly read the geographic silhouette.
Compose the scene as a visual legend that could be passed down through generations.
Ensure the final image feels iconic, timeless, and cinematically powerful.
```

####Example Outputs:

---

<img width="400" alt="Flag Myth Diorama" src="images/flag-myth-diorama-01.jpg" />
<img width="400" alt="Flag Myth Diorama" src="images/flag-myth-diorama-02.jpg" />
<img width="400" alt="Flag Myth Diorama" src="images/flag-myth-diorama-03.jpg" />
<img width="400" alt="Flag Myth Diorama" src="images/flag-myth-diorama-04.jpg" />
---
### 7.2. Time Capsule City Orb

Enter a city, pick a year, and explore cities across time.

This prompt generates a time capsule with a city locked to a single moment in time.
**Prompt:**

```text
[CITY_NAME] = city name
[YEAR] = year

Make a cinematic 3D miniature city diorama for temporal visualization in 1:1 aspect ratio.
Use a virtual cinematic camera with a slight top-down angle and realistic depth of field.
Set the scene as a suspended time capsule environment isolated from the present.
Enclose the entire miniature city inside a perfectly complete transparent spherical glass orb.
Ensure the sphere is fully closed with no cut, base, stand, pedestal, wood, or external support.
Keep the spherical form perfectly centered and visually dominant in the frame.
Show the city floating freely inside the sphere as a single cohesive landmass.
Show the city frozen exactly as it exists in [YEAR] with no elements from other time periods.
Render [CITY_NAME] with architecture, streets, landmarks, and urban density accurate to that year.
Adapt materials, construction techniques, technology level, and city layout to the specified time.
Show terrain, coastline, rivers, vegetation, and infrastructure as they would appear in that year.
Include subtle signs of life appropriate to the time such as people, vehicles, animals, or vessels when contextually plausible.
Use physically based rendering with realistic stone, wood, metal, glass, earth, and fabric textures suited to the era.
Apply soft global illumination with a cinematic light matching the temporal atmosphere.
Add a gentle rim light around the outer edge of the sphere to clearly define its silhouette.
Preserve subtle reflections and refractions on the spherical surface with minimal visual distortion.
Place all title text directly on the surface of the sphere as an overlay, not floating above or outside it.
Align the text to follow the curvature of the sphere while remaining legible.
Write the city’s name exactly as it was used in [YEAR] as the main title text on the sphere surface.
If [YEAR] refers to a past year, write the modern official city name in parentheses directly beneath the historical name on the sphere surface.
If [YEAR] refers to a future year, display only the primary city name with no secondary name.
Place the year text directly beneath the city name or names as part of the same curved title block on the sphere.
Ensure the final image feels iconic, timeless, and cinematically powerful.
```

####Example Outputs:

---

<img width="400" alt="Time Capsule City Orb" src="images/time-capsule-city-orb-01.jpg" />
<img width="400" alt="Time Capsule City Orb" src="images/time-capsule-city-orb-02.jpg" />
<img width="400" alt="Time Capsule City Orb" src="images/time-capsule-city-orb-03.jpg" />
<img width="400" alt="Time Capsule City Orb" src="images/time-capsule-city-orb-04.jpg" />
---
### 7.3. IMAX Aerial Creature Shot

This prompt turns any creature into an IMAX-level, ultra-photoreal aerial shot.

Drop in a subject, pick a view, and let it look like it was actually filmed from the sky.

Perfect for posters, key visuals, and high-impact concept shots.

Variable Examples:

[SUBJECT] options
red dragon
white dragon
golden phoenix
giant eagle
peregrine falcon
snowy owl
albatross
flying manta ray
ancient griffin
mythical thunderbird

[TIME_OF_DAY] options
sunrise
early morning
midday
afternoon
golden hour
sunset
blue hour
night
moonlit night
stormy daylight

[FLYING_OVER] options
dense emerald forest canopy
snow-covered mountain range
vast desert dunes
ancient jungle with towering trees
ocean surface with breaking waves
cloud sea above the mountains
volcanic landscape with lava veins
rolling green hills
arctic ice fields
modern megacity skyline
ancient stone city ruins
futuristic cyberpunk city
coastal Mediterranean city
old European medieval city
desert city with sandstone architecture
neon-lit night metropolis
fog-covered industrial city
mountain city carved into cliffs

[CAMERA_VIEW] options
strict top-down aerial view, camera looking directly downward
perfect bird’s-eye view, zero perspective tilt
eye-level frontal view, subject facing the camera
three-quarter front view, slight cinematic angle
side profile view, camera perpendicular to subject
low-angle view, camera looking upward
high-angle view, camera looking down

**Prompt:**

```text
[SUBJECT] = white dragon
[TIME_OF_DAY] = night
[FLYING_OVER] = dense emerald forest canopy
[CAMERA_VIEW] = strict top-down aerial view, camera looking directly downward

Make an ultra-photorealistic aerial photograph intended to look indistinguishable from a real-world camera capture.
Capture the scene as if shot on a real IMAX large-format camera.
Use large-format IMAX lens characteristics with extreme clarity and minimal distortion.
Set the camera view according to [CAMERA_VIEW].
Frame the scene so the entire [SUBJECT] including full wingspan or full body is fully visible within the frame.
Ensure generous safety margins between all extremities and the frame edges.
Scale the subject down if necessary to guarantee complete visibility without cropping.
Use poster-perfect framing with balanced negative space on all sides.
Place a vast continuous landscape of [FLYING_OVER] filling the entire background.
Show a single majestic [SUBJECT] above the environment.
If the specified subject is not naturally capable of flight, place it riding or seated on an early open-frame glider with exposed wooden structure, fabric-covered wings, and an open cockpit, inspired by early 20th-century aviation, realistically integrated.
Define surface texture, anatomy, and physical behavior realistically for the specified subject.
Ensure the head, neck, and spine remain aligned in a natural forward-facing posture with realistic anatomical limits.
Keep the body, wings or glider structure, spine, and overall form arranged in a clean, readable silhouette from the selected camera view.
Set lighting to [TIME_OF_DAY] with natural real-world light behavior and physically accurate shadows.
Preserve realistic scale, atmospheric falloff, and optical behavior.
Ensure the final image feels iconic, timeless, and cinematically powerful.
Avoid illustration, digital art, stylization, text, logos, borders, watermarks, extra creatures.
```

####Example Outputs:

---

<img width="400" alt="IMAX Aerial Creature Shot" src="images/imax-aerial-creature-shot-01.jpg" />
<img width="400" alt="IMAX Aerial Creature Shot" src="images/imax-aerial-creature-shot-02.jpg" />
<img width="400" alt="IMAX Aerial Creature Shot" src="images/imax-aerial-creature-shot-03.jpg" />
<img width="400" alt="IMAX Aerial Creature Shot" src="images/imax-aerial-creature-shot-04.jpg" />
<img width="400" alt="IMAX Aerial Creature Shot" src="images/imax-aerial-creature-shot-05.jpg" />
---
### 7.4. Totem Builder

Build your own totem.
**Prompt:**

```text
[HEAD_1] = Spider-Man
[HEAD_2] = Captain America
[HEAD_3] = Black Widow
[HEAD_4] = Deadpool
[HEAD_5] = Use the provided reference image as a strict facial identity guide. Preserve the exact facial proportions, structure, and recognizable features from the reference image.

Make a high-resolution photorealistic image for artistic and cultural visualization.
Set the camera slightly farther back and higher than eye level with a gentle elevated perspective.
Use a subtle upward angle that captures the full height and wingspan of the subject.
Show a tall vertical wooden totem fully visible from base to top.
Place the totem outdoors in a lush green natural environment.
Carve the totem from a single continuous natural wooden trunk.
Form the totem exclusively from five stacked human heads.
Arrange the heads vertically from bottom to top as [HEAD_1], [HEAD_2], [HEAD_3], [HEAD_4], [HEAD_5].
Use the provided reference image as a strict facial identity guide for each head.
Preserve exact facial proportions, structure, and recognizable features from the reference.
Translate each face into a realistic hand-carved wooden form without exaggeration or stylization.
Apply a unified Indigenous-inspired carving style across all heads.
Render realistic human proportions with defined brows, deep-set eyes, prominent noses, carved lips, and clear cheekbones.
Set all expressions to neutral with open eyes, closed mouths, and relaxed facial tension.
Orient all faces forward with slight individual head tilts.
Attach large symmetrical carved wings to the upper section of the totem.
Carve the wings from the same wood with layered feather patterns.
Paint all heads and wings with vivid traditional colors including turquoise blue, red, black, white, yellow, and earthy brown.
Apply bold geometric patterns while preserving visible wood grain, chisel marks, minor cracks, and natural weathering.
Light the scene with clear daylight and even natural sunlight.
Ensure surrounding greenery is visible to reinforce scale and context.
Ensure the final image feels iconic, timeless, and cinematically powerful.
Avoid fantasy elements, abstraction, modern materials, watermarks, text overlays, unpainted heads.
```

####Example Outputs:

---

<img width="400" alt="Totem Builder" src="images/totem-builder-01.jpg" />
<img width="400" alt="Totem Builder" src="images/totem-builder-02.jpg" />
---

## 8. Games & Maps

### 8.1. Match-3 City Diorama

**Prompt:**

```text
You are a visual generation system that creates a 3D miniature city diorama that looks like a physical, three-dimensional match-3 puzzle game world map.

VARIABLES
CITY: [City Name]
LANGUAGE: [Language]
TITLE: [CITY] Saga

INSTRUCTIONS

Depict [CITY] as a fully 3D miniature city diorama viewed from a slightly elevated, isometric perspective.
The city should feel like a tangible tabletop model inspired by the visual language of modern match-3 games.

Construct a single winding level path that travels across the diorama from start to finish.
The path must resemble a classic match-3 level route: chunky, segmented, colorful, and clearly readable as a progression line.

Represent iconic landmarks of [CITY] as individual 3D game levels placed along the path.
Each landmark should be simplified into a toy-like 3D model and labeled with its real, correct place name written in [LANGUAGE].

Replace traditional match-3 gems with chunky 3D icons inspired by [CITY]'s famous foods and drinks.
Position these icons directly on the path, spaced rhythmically like match-3 collectibles.
They should feel glossy, candy-like, slightly oversized, and designed for touch interaction.

Ensure the entire scene follows a bright, casual, polished match-3 art style:
– rounded geometry
– saturated, cheerful colors
– soft lighting
– subtle plastic, clay, or candy-like materials

Avoid realism, photorealistic textures, weathering, dirt, or cinematic grit.

Do not include any UI elements, menus, buttons, score indicators, HUDs, icons, or interface overlays.

Display only a single title at the very top of the image reading exactly: “[TITLE]”.

Avoid watermarks, logos, borders, or decorative text beyond landmark labels and the title.

The final image should feel like a premium 3D match-3 game world map frozen in time, presented as a collectible miniature city.
```

####Example Outputs:

---

<img width="400" alt="Match-3 City Diorama" src="images/match-3-city-diorama-01.jpg" />
<img width="400" alt="Match-3 City Diorama" src="images/match-3-city-diorama-02.jpg" />
---
### 8.2. Candy Crush City Map

Turning real cities into colorful Candy Crush like match-3 game world maps 🍬🍭

Iconic landmarks become levels, local flavors guide the path.

Just change the variables.
**Prompt:**

```text
You are a visual generation system that creates a colorful match-3 puzzle game world map depicting a real city as a playful, candy-like game environment, optimized for clarity, charm, and geographic storytelling.

VARIABLES
CITY: New York
LANGUAGE: English
TITLE: New York Saga

INSTRUCTIONS

Depict [CITY] as a colorful match-3 puzzle game world map viewed from a slightly elevated, illustrative perspective.

Construct a single winding level path that travels across the city, clearly guiding progression from start to finish.

Represent iconic landmarks of [CITY] as individual game levels placed along the path, and label each level with the landmark’s real, correct place name written in [LANGUAGE].

Replace standard match-3 gems with stylized icons inspired by [CITY]'s famous foods and drinks.
Position these food and drink icons directly on the winding level path as collectible or decorative elements that visually follow the route.
Ensure the icons are playful, readable, culturally recognizable, and clearly integrated into the path flow rather than scattered randomly across the map.

Ensure all visual elements follow a cohesive, bright, casual puzzle-game art style with soft shapes, vibrant colors, and a friendly tone.
Avoid realism, photorealistic textures, or gritty detail.

Do not include any UI elements, menus, buttons, score indicators, icons, or interface overlays of any kind.

Display only a single title at the very top of the image reading exactly: “[TITLE]”.

Avoid watermarks, logos, borders, or decorative text beyond landmark labels and the title.
```

####Example Outputs:

---

<img width="400" alt="Candy Crush City Map" src="images/candy-crush-city-map-01.jpg" />
<img width="400" alt="Candy Crush City Map" src="images/candy-crush-city-map-02.jpg" />
<img width="400" alt="Candy Crush City Map" src="images/candy-crush-city-map-03.jpg" />
---
## 9. Food & Culture

### 9.1. Dish-As-World Scene

**Prompt:**

```text
You are an intelligent image composition model.

Dish: {DISH_NAME}
Cuisine Country: {COUNTRY}
Visual Style: {STYLE}
(Examples for visual style:
- miniature diorama with cinematic studio lighting
- whimsical handcrafted miniature
- cinematic stylized realism
- hyperreal food photography
- soft 3D illustration
- watercolor storybook illustration
- paper-cut layered illustration
- claymation-inspired miniature
- painterly cinematic realism
- surreal-but-coherent food landscape)

Create a single cohesive visual scene where:
- The ingredients of the dish are implicitly inferred and visually represented through natural gathering, harvesting, or transformation into elements of the scene.
- The dish itself becomes the core “world” or stage of the composition, not a separate object.
- The environment, props, materials, colors, and atmosphere reflect the culture, geography, and everyday life of the specified country.
- Ingredients may form landscapes, vehicles, tools, or structures if it suits the chosen style, while remaining recognizable through context.
- The overall composition feels intentional, cinematic, and story-driven rather than a collage.

STYLE & QUALITY RULES
- Fully apply the requested Visual Style to lighting, materials, scale, and mood.
- Use depth of field, perspective, and lighting consistent with the chosen style.
- Miniature figures may be included only if they fit culturally and stylistically.
- The scene should feel handcrafted or carefully composed, not chaotic or surreal.
- No text, labels, UI elements, logos, or watermarks.
- The final image should visually explain how the dish and its cultural origin naturally come together.
```

####Example Outputs:

---

<img width="400" alt="Dish-As-World Scene" src="images/dish-as-world-scene-01.jpg" />
<img width="400" alt="Dish-As-World Scene" src="images/dish-as-world-scene-02.jpg" />
<img width="400" alt="Dish-As-World Scene" src="images/dish-as-world-scene-03.jpg" />
<img width="400" alt="Dish-As-World Scene" src="images/dish-as-world-scene-04.jpg" />
---
## 10. Holidays & Humor

### 10.1. New Year Photo Booth Strip

**Prompt:**
New Year Photo Booth Print

```text
Make a single-frame ultra-photorealistic photo at high resolution.

Use the person from the uploaded reference photo exclusively inside the photo booth prints and preserve strict facial identity.

Set the capture in front of a shopping mall photo booth with the booth clearly visible in the background.
Set the moment as entering the year 2026 using only visual New Year cues without any visible text or numbers.
Avoid showing the person anywhere outside the printed photos.

Place exactly one physical 2x4 photo booth print strip centered in the frame and make the print filling most of the frame for close inspection.
Show the strip containing eight small frames of the same person wearing New Year-themed outfits and accessories, including variations with a festive 2026 crown, a party hat, a party accessory, a clean normal pose, hand gestures and playful goofy expressions.
Place a single hand holding the enlarged print strip clearly and naturally.

Set very close framing consistent with a phone-captured photo perspective and add slight handheld imperfection with shallow, natural depth behavior.

Use soft indoor lighting with gentle holiday warmth consistent with photo booth flash behavior and ambient mall lighting.

Preserve photographic realism with accurate paper texture, believable enlarged print scale, crisp ink detail, and mild smartphone-style compression.

Avoid all text, logos, UI elements, watermarks, overlays, phones, visible numbers, showing the person outside the prints, and any artificial effects.
```

####Example Outputs:

---

<img width="400" alt="New Year Photo Booth Strip" src="images/new-year-photo-booth-strip-01.jpg" />
<img width="400" alt="New Year Photo Booth Strip" src="images/new-year-photo-booth-strip-02.jpg" />
---
### 10.2. Wrapped Chair Prank Gift

To generate viral surprise gift images, use this prompt.
**Prompt:**

```text
Use a standard household chair as the central subject, placed prominently in the room and wrapped as a Christmas gift while clearly preserving its recognizable chair silhouette.

Wrap the chair tightly with colorful Christmas-themed wrapping paper that follows the contours of the seat, backrest, and legs so the object is instantly identifiable from its shape, and secure it with a large decorative ribbon and oversized bow.

Set the scene inside a living room with a slightly unconventional, asymmetrical layout that feels lived-in rather than staged.

Place the wrapped chair on a textured area rug that partially overlaps wooden parquet flooring, grounding the object visually.

Arrange a decorated Christmas tree slightly off-center to the right near a corner or window, lit with warm lights and adorned with ornaments and golden flowers.

Place a television on a low console along an angled wall or recessed alcove in the left background, turned on and showing a woman presenting a TV program or news broadcast.

Include subtle architectural variation such as a visible doorway, hallway opening, or partial wall edge to break the room’s symmetry.

Scatter several real gift bags and wrapped packages in red and black casually around the rug, near the base of the chair and beneath the Christmas tree.

Set the camera at a slight diagonal angle at standing eye level, as if the photo was taken spontaneously upon entering the room.

Use warm indoor lighting combined with Christmas tree lights to create a cozy, cheerful holiday atmosphere.

Preserve a deliberately absurd, humorous, and prank-like tone by presenting an obviously recognizable chair as a serious Christmas gift.

Do not add any text, captions, logos, or UI elements.
```

####Example Outputs:

---

<img width="400" alt="Wrapped Chair Prank Gift" src="images/wrapped-chair-prank-gift-01.jpg" />
<img width="400" alt="Wrapped Chair Prank Gift" src="images/wrapped-chair-prank-gift-02.jpg" />
---
## License

Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
