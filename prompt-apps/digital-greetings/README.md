# 🎨 Digital Greetings - Prompt Architect

A lightweight web application that generates high-quality AI image generation prompts for creating stunning digital greeting cards.

## What It Does

Digital Greetings is an interactive prompt builder that combines your creative inputs to generate sophisticated, detailed prompts optimized for AI image generators. Instead of struggling to write the perfect prompt from scratch, users can select themes, styles, and preferences—and the app automatically generates professional-grade prompts ready for tools like Midjourney, Google Gemini, Grok, and other AI image generators.

Perfect for creating personalized greeting cards, holiday designs, and celebratory artwork.

## How It Works

### 1. **Select or Create a Theme**
   - Choose from preset themes: St. Patrick's Day, Earth Day, Diwali, Eid, Lunar New Year
   - Or enter a custom theme description (e.g., "Ethereal phoenix rising from golden flames")

### 2. **Customize the Card**
   - Add optional text that will appear on the greeting card
   - Supports any message, greeting, or date

### 3. **Choose Visual Style**
   Pick from three categories:
   - **Realism**: 8K Ultra Realistic, Cinematic, Macro Detail
   - **Artistic**: Watercolor, Oil Painting, Sketch, Art Deco
   - **Craft & 3D**: Paper Origami, Claymation, Stained Glass, Isometric 3D

### 4. **Set Aspect Ratio & Mode**
   - **Ratios**: 4:5 (portrait), 1:1 (square), 16:9 (widescreen)
   - **Mode**: Pro (detailed) or Lite (simplified)

### 5. **Generate & Copy**
   - The app generates an optimized prompt in real-time
   - Copy the prompt with one click
   - Use it in your favorite AI image generator

## Sample Prompts

### Example 1: Earth Day (Detailed Mode)
**Input:**
- Theme: "mother nature cradling a vibrant bioluminescent Earth"
- Text: "Happy Earth Day 2026"
- Style: 8K Ultra Realistic
- Ratio: 4:5
- Mode: Pro

**Generated Prompt:**
```
An astonishing, high-concept greeting card masterpiece: mother nature cradling a vibrant bioluminescent Earth. Style: 8k ultra-realistic photography, cinematic lighting. The card features the elegant, integrated typography: "Happy Earth Day 2026". The composition is ethereal with dynamic depth of field and volumetric lighting. Incorporate ultra-detailed textures like holographic foil, embossed heavy-stock paper, and magical atmospheric particles. The background is a vibrant, cinematic fusion of surreal colors and dreamlike bokeh. Professional studio lighting, 8k resolution, photorealistic macro details, hyper-vibrant color grading, symmetrical artistic composition. --v 6.0 --ar 4:5
```

---

### Example 2: Lunar New Year (Lite Mode)
**Input:**
- Theme: "ornate red silk dragon dancing through floating golden lanterns"
- Text: "新年快乐" (Happy New Year)
- Style: Watercolor
- Ratio: 1:1
- Mode: Lite

**Generated Prompt:**
```
Astonishing card: ornate red silk dragon dancing through floating golden lanterns. Style: vibrant watercolor painting, wet-on-wet technique, delicate splatters. Text: "新年快乐". Vibrant magical atmosphere, glowing accents, cinematic, hyper-realistic, 8k, --ar 1:1
```

---

### Example 3: Diwali (Art Deco Style)
**Input:**
- Theme: "grand palace courtyard filled with thousands of golden oil lamps"
- Text: (No custom text)
- Style: Art Deco Illustration
- Ratio: 16:9
- Mode: Pro

**Generated Prompt:**
```
An astonishing, high-concept greeting card masterpiece: grand palace courtyard filled with thousands of golden oil lamps. Style: art deco illustration, gold geometric lines, vintage. The composition is ethereal with dynamic depth of field and volumetric lighting. Incorporate ultra-detailed textures like holographic foil, embossed heavy-stock paper, and magical atmospheric particles. The background is a vibrant, cinematic fusion of surreal colors and dreamlike bokeh. Professional studio lighting, 8k resolution, photorealistic macro details, hyper-vibrant color grading, symmetrical artistic composition. --v 6.0 --ar 16:9
```

---

## Tested With

The generated prompts have been successfully tested with:
- **GenTube.App** - AI image generation platform
- **Grok AI** - Xai's image generation model
- **Google Gemini AI** - Google's multimodal AI
- **Shapes.inc** - Design generation tool

## Features

✨ **Real-time Generation** - Prompts update instantly as you adjust settings
📋 **One-Click Copy** - Copy prompts directly to clipboard
🎯 **Smart Presets** - Quick-select popular holidays and themes
🎨 **Professional Output** - Generated prompts include technical parameters (version, aspect ratio)
📱 **Responsive Design** - Works seamlessly on desktop and mobile
♿ **Accessible** - Clean, intuitive interface with proper labels and form controls

## Technical Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS custom properties (variables)
- **Vanilla JavaScript** - Zero dependencies, instant loading

## File Structure

```
digital-greetings/
├── index.html          # Main application
├── README.md          # This file
└── img/               # Reference images
    ├── gentube-app.jpeg
    ├── grok-ai.jpg
    ├── gemini-ai.png
    └── shapes-inc.png
```

## How to Use

1. Open `index.html` in any modern web browser
2. Select or enter a greeting card theme
3. (Optional) Add custom text to appear on the card
4. Choose your preferred visual style and aspect ratio
5. Select Pro mode for detailed prompts or Lite for simpler ones
6. Click "Copy Prompt" to copy the generated text
7. Paste into your preferred AI image generator and create your greeting card

## Tips for Best Results

- **Be Descriptive** - Specific themes generate more detailed prompts
- **Combine Styles** - Experiment with different visual styles for unique results
- **Pro Mode** - Use Pro mode for high-quality, publication-ready cards
- **Lite Mode** - Use Lite mode for quick, experimental designs
- **Text Placement** - Keep custom text concise for balanced card compositions

## Credits

Created by Gemini AI as part of the DoneByAi project.  
Inspired by the need for quick, professional prompt generation for AI-powered greeting card design.

---

**Version:** 1.0  
**Year:** 2026  
**Project:** 4AI - Digital Greetings
