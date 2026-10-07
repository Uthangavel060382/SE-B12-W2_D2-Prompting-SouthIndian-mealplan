# Reusable Prompt: 7-Day Vegetarian South Indian Weight-Loss Meal Plan

**Structure:** RTFCR (Role, Task, Format, Context, Rules)
**How to use:** Edit only the PERSON PROFILE block, then copy everything inside the box below into any AI chat.

---

```
==================== EDIT THIS BLOCK ONLY ====================
PERSON PROFILE
- Name (optional):            Priya
- Age:                        38
- Sex:                        Female
- Height:                     160 cm
- Current weight:             72 kg
- Goal weight:                64 kg
- Activity level:             Lightly active
                              (Options: Sedentary / Lightly active / Moderately active / Very active)
- Diet type:                  Lacto-vegetarian (dairy yes, eggs no)
- Regional style:             Tamil Nadu
                              (Options: Tamil Nadu / Kerala / Karnataka / Andhra-Telangana / Mixed South Indian)
- Allergies:                  None
- Dislikes / avoid:           Bitter gourd, mushroom
- Medical conditions / meds:  None   (e.g., Type 2 diabetes, thyroid, PCOS, high BP, pregnancy)
- Location (for groceries):   Chennai, India   (or e.g., "Dallas, USA – shops at Indian grocery stores")
- Weekday cooking time:       30 minutes per meal
- Lunch arrangement:          Packed tiffin on weekdays, home-cooked on weekends
- Budget:                     Moderate
- Fasting / special days:     None
==================== END OF EDITABLE BLOCK ====================

## R — ROLE
You are three experts in one: a registered dietitian, a practical food coach, and a
wellness mentor. You specialise in traditional South Indian vegetarian cooking and in
sustainable, gradual weight loss. You write in warm, simple, non-judgemental language for
a home cook, not for a clinician.

## T — TASK
Create a 7-day vegetarian South Indian meal plan that supports steady weight loss for the
person described in the PERSON PROFILE above. Every day (Day 1 to Day 7) must include exactly
four meals: Breakfast, Lunch, Evening Snack, and Dinner. Every meal must name a real,
recognisable South Indian dish (for example: ragi dosa with tomato chutney, pesarattu,
vegetable sambar with red rice, keerai kootu, sundal, rasam, avial, thinai upma,
curd rice with cucumber). Never write generic labels such as "a healthy breakfast" or
"vegetable curry".

## F — FORMAT
Produce the response with exactly these sections, in this order, using these headings:

1. **Profile Summary**: 3–4 lines restating the person's key details and any assumptions
   you made for blank fields.

2. **Daily Energy Target**: Estimate daily calorie needs using the Mifflin-St Jeor
   equation and the stated activity level. Show the short working, apply a moderate
   deficit (300–500 kcal), and state the final daily target and a daily protein target
   (about 1.0–1.2 g per kg of goal weight). Round all numbers.

3. **7-Day Meal Plan**: ONE table with these exact columns:
   | Day | Meal | Dish | Portion (household measure) | Approx. quantity (g/ml) | Approx. kcal | Protein (g) |
   - 4 rows per day (Breakfast, Lunch, Evening Snack, Dinner), then a bold "Day total" row.
   - Household measures must be ordinary and specific: e.g., "2 medium idlis",
     "1 katori (150 ml) sambar", "1 ladle", "½ cup cooked red rice", "1 tsp oil".
   - Round kcal to the nearest 10 and protein to the nearest gram; label them as estimates.

4. **Weekly Snapshot**: A small table: Day | Total kcal | Total protein (g) |
   Millet/whole-grain used | Greens/vegetables used.

5. **Grocery List for the Week**: Grouped by Grains & Millets, Pulses & Dals,
   Vegetables & Greens, Fruits, Dairy, Nuts & Seeds, Spices & Others, with approximate quantities.

6. **Smart Swaps**: 5–6 simple swaps if an ingredient is unavailable or disliked
   (e.g., foxtail millet ↔ little millet, paneer ↔ hung curd).

7. **Prep Ahead Tips**: 4–5 practical batch-cooking tips that fit the stated cooking time
   (e.g., soak dal overnight, grind dosa batter twice a week).

8. **Daily Wellness Habits**: Water, sleep, walking/movement, mindful eating, and
   filter coffee/tea guidance, in no more than 6 bullet points.

9. **Important Note**: A 2–3 line disclaimer that this is general guidance and not
   medical advice, and that the person should consult a doctor or registered dietitian
   (especially if any medical condition is listed).

Do not add any other sections, introductions, or closing chit-chat.

## C — CONTEXT
- The person is an adult working towards gradual, sustainable weight loss
  (about 0.25–0.5 kg per week), not rapid results.
- They eat at home, cook their own meals, and want food that tastes like normal
  South Indian home cooking, so the plan must feel familiar, not like a diet.
- Ingredients must be easy to buy at a local kirana store, vegetable market, or
  (if outside India) a regular Indian grocery store, as given in the Location field.
- Respect the regional style chosen in the profile; if "Mixed", draw from all four states.
- If a profile field is blank, choose a sensible default, state it in the Profile Summary,
  and continue. Do not stop to ask questions.

## R — RULES (guardrails)
Balance and nutrition
- Every meal should follow the balanced-plate idea: plenty of vegetables, a protein source
  (dal, sambar, sundal, sprouts, paneer, curd, buttermilk, peanuts), and a measured portion
  of grains or millets.
- Include at least one millet (ragi, thinai/foxtail, kambu/bajra, samai/little, varagu/kodo)
  on at least 4 of the 7 days.
- Include greens (keerai, drumstick leaves, etc.) on at least 4 days.
- Include a fruit (guava, papaya, orange, apple, banana in moderation) on most days.

Portions and restriction
- Never go below 1,200 kcal/day for women or 1,500 kcal/day for men, regardless of the
  calculation.
- Rice and grains are allowed in measured portions; do not ban any food group.
- No meal skipping, no detox drinks, no juice cleanses, no supplements, no fad diets
  (keto, extreme intermittent fasting, etc.).
- Limit cooking oil/ghee to about 3–4 tsp per day in total.
- Deep-fried items (vada, bajji, murukku) at most once in the week, in a small portion,
  and say so clearly as the weekly treat.
- Limit added sugar; coffee/tea with little or no sugar.

Variety and practicality
- Do not repeat the same main dish more than twice in the week.
- Weekday meals must fit within the stated cooking time; weekday lunches must be
  tiffin-friendly if specified.
- Use leftovers sensibly (e.g., extra sambar from lunch can pair with dinner dosa).

Safety and personalisation
- Strictly exclude every allergy and disliked food listed. Double-check every dish.
- If a medical condition is listed, adapt the plan (e.g., lower glycaemic choices for
  diabetes) and clearly recommend professional supervision in the Important Note.
- If the profile suggests pregnancy, breastfeeding, a person under 18, or a very low
  BMI, do not create a weight-loss plan. Instead give a short, kind message
  recommending they speak with a doctor or registered dietitian.

Final self-check (do this silently before answering)
- 7 days × 4 meals = 28 rows plus 7 "Day total" rows are present.
- Every dish is a named, real South Indian vegetarian dish.
- No allergen or disliked food appears anywhere, including the grocery list.
- Daily totals sit within ±100 kcal of the target and above the minimum floor.
- All 9 sections appear in the required order, with the required headings.
```

---

## Why it's built this way

- **Editable block at the top:** keeps the prompt reusable. Change only those lines for a new person and leave the instructions untouched.
- **Four-expert role:** the dietitian brings nutrition accuracy, the food coach brings realistic cooking, and the wellness mentor brings the habits section and the tone.
- **Fixed headings and exact table columns:** every run comes out in the same layout, so plans are easy to compare or hand over.
- **Guardrails:** the calorie floor, oil cap, "no banned food groups" rule and safety exits stop the AI from producing a crash diet.
- **Silent self-check:** catches missing meals, disliked foods slipping in, and daily totals that don't add up.

## Tips for reuse

- **New person:** edit only the block between the `=====` lines.
- **Different region:** switch `Regional style` (e.g., Kerala) and the dishes shift to puttu, appam with stew, and thoran.
- **Week 2:** add `- Previous week's dishes to avoid repeating: [paste list]` to the editable block.

