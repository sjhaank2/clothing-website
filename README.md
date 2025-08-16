# clothing-website
Clothing website for semantic search


# 🔍 Semantic Search Test Questions (5 Products)

These questions test AI's ability to understand **meaning and context** rather than exact keyword matching:

## **❄️ Winter & Cold Weather**

### 1. **"clothing for freezing weather"**
- **Expected:** ProductA (jacket) + ProductB (coat)
- **Why:** No direct "freezing" keyword, but AI should understand winter/cold context
- **Keywords NOT in content:** "freezing", "clothing"

### 2. **"thermal protection apparel"** 
- **Expected:** ProductA (jacket)
- **Why:** AI should connect "thermal" with "warm" and "insulation"
- **Keywords NOT in content:** "thermal", "protection", "apparel"

### 3. **"what to wear during snowfall"**
- **Expected:** ProductA (jacket) 
- **Why:** AI should understand snowy conditions need warm clothing
- **Keywords NOT in content:** "wear", "during", "snowfall"

## **🌧️ Water & Weather Protection**

### 4. **"protection from getting wet"**
- **Expected:** ProductC (raincoat)
- **Why:** AI should connect "getting wet" with rain protection
- **Keywords NOT in content:** "getting wet", "protection"

### 5. **"monsoon season gear"**
- **Expected:** ProductC (raincoat)
- **Why:** AI should understand monsoon = heavy rain = need waterproof items
- **Keywords NOT in content:** "gear", "season"

### 6. **"waterproof clothing for storms"**
- **Expected:** ProductC (raincoat)
- **Why:** AI should connect storms with rain and need for waterproof items
- **Keywords NOT in content:** "waterproof", "storms"

## **🏢 Professional & Lifestyle**

### 7. **"office commute outerwear"**
- **Expected:** ProductB (coat)
- **Why:** AI should understand work/school commuting context
- **Keywords NOT in content:** "office", "outerwear"

### 8. **"comfortable attire for chilly mornings"**
- **Expected:** ProductB (coat)
- **Why:** AI should connect "chilly mornings" with coat's "crisp mornings" description
- **Keywords NOT in content:** "comfortable", "attire", "mornings"

## **🏔️ Adventure & Outdoor Activities**

### 9. **"mountain climbing footwear"**
- **Expected:** ProductD (hiking boot)
- **Why:** AI should understand mountain climbing needs specialized footwear
- **Keywords NOT in content:** "mountain climbing", "footwear"

### 10. **"wilderness adventure gear"**
- **Expected:** ProductD (hiking boot)
- **Why:** AI should connect wilderness adventures with hiking equipment
- **Keywords NOT in content:** "wilderness", "adventure", "gear"

### 11. **"trekking shoes for rough terrain"**
- **Expected:** ProductD (hiking boot)
- **Why:** AI should understand trekking = hiking and need for grip
- **Keywords NOT in content:** "trekking", "shoes"

## **☀️ Summer & Hot Weather**

### 12. **"beach vacation clothing"**
- **Expected:** ProductE (summer shirt)
- **Why:** AI should connect beach vacations with summer apparel
- **Keywords NOT in content:** "beach", "vacation", "clothing"

### 13. **"tropical climate apparel"**
- **Expected:** ProductE (summer shirt)
- **Why:** AI should understand tropical = hot = need cooling clothes
- **Keywords NOT in content:** "tropical", "climate", "apparel"

### 14. **"hot weather attire"**
- **Expected:** ProductE (summer shirt)
- **Why:** AI should connect hot weather with cooling clothing
- **Keywords NOT in content:** "hot weather", "attire"

### 15. **"sun protection clothing"**
- **Expected:** ProductE (summer shirt)
- **Why:** AI should understand UV protection context
- **Keywords NOT in content:** "sun protection", "clothing"

## **🔄 Cross-Category Questions**

### 16. **"outdoor equipment for hikers"**
- **Expected:** ProductD (hiking boot) + ProductC (raincoat)
- **Why:** Hikers need both footwear and weather protection
- **Keywords NOT in content:** "outdoor equipment", "hikers"

### 17. **"weather protection gear"**
- **Expected:** ProductA (jacket) + ProductC (raincoat)
- **Why:** Both provide protection from different weather conditions
- **Keywords NOT in content:** "weather protection", "gear"

### 18. **"vacation wardrobe essentials"**
- **Expected:** ProductE (summer shirt) + ProductC (raincoat)
- **Why:** Vacations need both sun protection and rain gear
- **Keywords NOT in content:** "vacation", "wardrobe", "essentials"

---

## **🧠 Why These Test Semantic Understanding:**

| **Product** | **AI Must Understand** | **Beyond Keywords** |
|-------------|------------------------|-------------------|
| **ProductA (Jacket)** | cold = winter = thermal protection | Temperature relationships |
| **ProductB (Coat)** | work = commute = professional wear | Lifestyle contexts |
| **ProductC (Raincoat)** | storms = wet = waterproof needed | Weather cause-effect |
| **ProductD (Hiking Boot)** | mountains = terrain = specialized footwear | Activity requirements |
| **ProductE (Summer Shirt)** | beach = hot = cooling fabric | Climate associations |

## **🎯 Expected Semantic AI Behavior:**

- **Word Association:** "freezing" → "cold" → "warm clothing"
- **Context Understanding:** "office commute" → "professional setting" → "coat"
- **Activity Matching:** "mountain climbing" → "hiking" → "specialized footwear"
- **Climate Logic:** "tropical" → "hot weather" → "cooling clothes"
- **Cross-Category:** "outdoor equipment" → multiple relevant products

## **📊 Success Metrics:**

✅ **Perfect:** AI returns exactly the expected products  
🔄 **Partial:** AI returns some but not all expected products  
❌ **Fail:** AI returns no results or completely wrong products  
🌟 **Bonus:** AI returns logical additional products (cross-category matches)

This comprehensive test suite validates if your GCP Vertex AI search truly understands **semantic meaning** across all product categories!
