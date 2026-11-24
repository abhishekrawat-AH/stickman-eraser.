# AI Prompts

## Master style block (paste at the start of EVERY prompt)
```
hand-drawn pencil sketch, rough graphite lines, off-white lined notebook paper texture, simple stickman with round head and big dot eyes, 2D cartoon, black and gray only, vertical 9:16, no text
```

## Character reference sheet
```
[STYLE BLOCK] character sheet of one stickman, front view, side view, shocked face, happy face, running pose, white background
```
Keep the best sheet as the reference image for every later generation. Reuse the same seed.

## Shot prompts (frames)
1. `[STYLE BLOCK] giant pink eraser shadow covering most of the page, tiny stickman looking up in fear`
2. `[STYLE BLOCK] stickman drawing a door on the page with a pencil, mid-sketch`
3. `[STYLE BLOCK] stickman falling into blank white void, half-erased door fading behind`
4. `[STYLE BLOCK] sketched bridge across a gap, half erased, stickman balancing`
5. `[STYLE BLOCK] two identical stickmen side by side, one fading from eraser smudges`
6. `[STYLE BLOCK] stickman bouncing on a sketched trampoline, eraser below`
7. `[STYLE BLOCK] thick sketched brick wall with a smudged hole as eraser pushes through`
8. `[STYLE BLOCK] stickman hiding in a pencil-drawn cave, huge eraser eye peeking in`
9. `[STYLE BLOCK] stickman proudly drawing a much bigger pink eraser, scribble lines`
10. `[STYLE BLOCK] big eraser chasing a tiny eraser, eraser dust puff`
11. `[STYLE BLOCK] stickman wiping forehead, giant eraser shadow sliding in again`

## Motion prompts (image-to-video)
```
subtle hand-drawn line boil, stickman moves with snappy cartoon timing, camera static, paper grain, 12 fps look, 3-4 seconds
```
- Generate 3 takes per shot; pick the best.
- Add a camera push-in for shots 1, 5, and 9 only.

## Negative prompt
```
color, 3D render, realistic, photo, shading, text, watermark, extra limbs
```

## Consistency tips
- Same seed and reference image across all shots.
- If the character drifts, regenerate from the character sheet.
- Fix small errors in an editor rather than regenerating.
